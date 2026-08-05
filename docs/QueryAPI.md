# \QueryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**QueryQuery**](QueryAPI.md#QueryQuery) | **Post** /api/v1/query | Query@query



## QueryQuery

> QueryQuery200Response QueryQuery(ctx).XClientId(xClientId).XSignature(xSignature).QueryQueryRequest(queryQueryRequest).Execute()

Query@query



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
	xClientId := "8f14e45f-ceea-467e-adc1-0000example" // string | Custodian client ID used to authenticate the requesting custodian
	xSignature := "xSignature_example" // string | HMAC signature of the raw request body, signed with the custodian's unique identifier
	queryQueryRequest := *openapiclient.NewQueryQueryRequest() // QueryQueryRequest | Query definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueryAPI.QueryQuery(context.Background()).XClientId(xClientId).XSignature(xSignature).QueryQueryRequest(queryQueryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueryAPI.QueryQuery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QueryQuery`: QueryQuery200Response
	fmt.Fprintf(os.Stdout, "Response from `QueryAPI.QueryQuery`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiQueryQueryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xClientId** | **string** | Custodian client ID used to authenticate the requesting custodian | 
 **xSignature** | **string** | HMAC signature of the raw request body, signed with the custodian&#39;s unique identifier | 
 **queryQueryRequest** | [**QueryQueryRequest**](QueryQueryRequest.md) | Query definition | 

### Return type

[**QueryQuery200Response**](QueryQuery200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

