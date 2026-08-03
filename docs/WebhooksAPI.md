# \WebhooksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**WebhooksCreateReceiver**](WebhooksAPI.md#WebhooksCreateReceiver) | **Post** /api/v1/webhooks/receivers | Create a new webhook receiver
[**WebhooksDeleteReceiver**](WebhooksAPI.md#WebhooksDeleteReceiver) | **Delete** /api/v1/webhooks/receivers/{custodianId} | Delete a webhook receiver
[**WebhooksGetAllEventTriggers**](WebhooksAPI.md#WebhooksGetAllEventTriggers) | **Get** /api/v1/webhooks/event-triggers | Get all webhook event triggers
[**WebhooksGetAllReceivers**](WebhooksAPI.md#WebhooksGetAllReceivers) | **Get** /api/v1/webhooks/receivers | Get all webhook receivers
[**WebhooksGetReceiversByCustodian**](WebhooksAPI.md#WebhooksGetReceiversByCustodian) | **Get** /api/v1/webhooks/receivers/{custodianId} | Get webhook receivers by custodian
[**WebhooksSendgrid**](WebhooksAPI.md#WebhooksSendgrid) | **Get** /api/v1/webhooks/sendgrid | Get sendgrid webhook event triggers
[**WebhooksUpdateReceiver**](WebhooksAPI.md#WebhooksUpdateReceiver) | **Put** /api/v1/webhooks/receivers/{custodianId} | Update a webhook receiver



## WebhooksCreateReceiver

> WebhooksCreateReceiver201Response WebhooksCreateReceiver(ctx).WebhooksCreateReceiverRequest(webhooksCreateReceiverRequest).Execute()

Create a new webhook receiver



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
	webhooksCreateReceiverRequest := *openapiclient.NewWebhooksCreateReceiverRequest() // WebhooksCreateReceiverRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksCreateReceiver(context.Background()).WebhooksCreateReceiverRequest(webhooksCreateReceiverRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksCreateReceiver``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksCreateReceiver`: WebhooksCreateReceiver201Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksCreateReceiver`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksCreateReceiverRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webhooksCreateReceiverRequest** | [**WebhooksCreateReceiverRequest**](WebhooksCreateReceiverRequest.md) |  | 

### Return type

[**WebhooksCreateReceiver201Response**](WebhooksCreateReceiver201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksDeleteReceiver

> EducationDestroyByRegistryId200Response WebhooksDeleteReceiver(ctx, custodianId).WebhooksDeleteReceiverRequest(webhooksDeleteReceiverRequest).Execute()

Delete a webhook receiver



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
	custodianId := int32(56) // int32 | 
	webhooksDeleteReceiverRequest := *openapiclient.NewWebhooksDeleteReceiverRequest() // WebhooksDeleteReceiverRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksDeleteReceiver(context.Background(), custodianId).WebhooksDeleteReceiverRequest(webhooksDeleteReceiverRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksDeleteReceiver``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksDeleteReceiver`: EducationDestroyByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksDeleteReceiver`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksDeleteReceiverRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **webhooksDeleteReceiverRequest** | [**WebhooksDeleteReceiverRequest**](WebhooksDeleteReceiverRequest.md) |  | 

### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksGetAllEventTriggers

> WebhooksGetAllEventTriggers200Response WebhooksGetAllEventTriggers(ctx).Execute()

Get all webhook event triggers



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksGetAllEventTriggers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksGetAllEventTriggers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksGetAllEventTriggers`: WebhooksGetAllEventTriggers200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksGetAllEventTriggers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksGetAllEventTriggersRequest struct via the builder pattern


### Return type

[**WebhooksGetAllEventTriggers200Response**](WebhooksGetAllEventTriggers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksGetAllReceivers

> WebhooksGetAllReceivers200Response WebhooksGetAllReceivers(ctx).Execute()

Get all webhook receivers



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksGetAllReceivers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksGetAllReceivers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksGetAllReceivers`: WebhooksGetAllReceivers200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksGetAllReceivers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksGetAllReceiversRequest struct via the builder pattern


### Return type

[**WebhooksGetAllReceivers200Response**](WebhooksGetAllReceivers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksGetReceiversByCustodian

> WebhooksGetAllReceivers200Response WebhooksGetReceiversByCustodian(ctx, custodianId).Execute()

Get webhook receivers by custodian



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
	custodianId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksGetReceiversByCustodian(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksGetReceiversByCustodian``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksGetReceiversByCustodian`: WebhooksGetAllReceivers200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksGetReceiversByCustodian`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksGetReceiversByCustodianRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**WebhooksGetAllReceivers200Response**](WebhooksGetAllReceivers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksSendgrid

> WebhooksSendgrid(ctx).Execute()

Get sendgrid webhook event triggers



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebhooksAPI.WebhooksSendgrid(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksSendgrid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksSendgridRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhooksUpdateReceiver

> EducationDestroyByRegistryId200Response WebhooksUpdateReceiver(ctx, custodianId).WebhooksUpdateReceiverRequest(webhooksUpdateReceiverRequest).Execute()

Update a webhook receiver



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
	custodianId := int32(56) // int32 | 
	webhooksUpdateReceiverRequest := *openapiclient.NewWebhooksUpdateReceiverRequest() // WebhooksUpdateReceiverRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.WebhooksUpdateReceiver(context.Background(), custodianId).WebhooksUpdateReceiverRequest(webhooksUpdateReceiverRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.WebhooksUpdateReceiver``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WebhooksUpdateReceiver`: EducationDestroyByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.WebhooksUpdateReceiver`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWebhooksUpdateReceiverRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **webhooksUpdateReceiverRequest** | [**WebhooksUpdateReceiverRequest**](WebhooksUpdateReceiverRequest.md) |  | 

### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

