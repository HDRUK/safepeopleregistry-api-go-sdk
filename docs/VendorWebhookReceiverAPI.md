# \VendorWebhookReceiverAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**VendorWebhookReceiverReceive**](VendorWebhookReceiverAPI.md#VendorWebhookReceiverReceive) | **Post** /api/v1/webhooks/{provider} | Receive a webhook callback from a vendor



## VendorWebhookReceiverReceive

> VendorWebhookReceiverReceive200Response VendorWebhookReceiverReceive(ctx, provider).Body(body).Execute()

Receive a webhook callback from a vendor

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/HDRUK/safepeopleregistry-api-go-sdk"
)

func main() {
	provider := "example-provider" // string | Name of the vendor providing the webhook
	body := map[string]interface{}{ ... } // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VendorWebhookReceiverAPI.VendorWebhookReceiverReceive(context.Background(), provider).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VendorWebhookReceiverAPI.VendorWebhookReceiverReceive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VendorWebhookReceiverReceive`: VendorWebhookReceiverReceive200Response
	fmt.Fprintf(os.Stdout, "Response from `VendorWebhookReceiverAPI.VendorWebhookReceiverReceive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** | Name of the vendor providing the webhook | 

### Other Parameters

Other parameters are passed through a pointer to a apiVendorWebhookReceiverReceiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  | 

### Return type

[**VendorWebhookReceiverReceive200Response**](VendorWebhookReceiverReceive200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

