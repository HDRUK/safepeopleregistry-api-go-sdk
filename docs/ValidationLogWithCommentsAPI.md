# \ValidationLogWithCommentsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ValidationLogWithCommentsIndex**](ValidationLogWithCommentsAPI.md#ValidationLogWithCommentsIndex) | **Get** /api/v1/validation_logs/{id} | Get  a Validation Log



## ValidationLogWithCommentsIndex

> []ValidationLog ValidationLogWithCommentsIndex(ctx, id).Execute()

Get  a Validation Log



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
	id := int32(56) // int32 | The ID of the validation log

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogWithCommentsAPI.ValidationLogWithCommentsIndex(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogWithCommentsAPI.ValidationLogWithCommentsIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogWithCommentsIndex`: []ValidationLog
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogWithCommentsAPI.ValidationLogWithCommentsIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the validation log | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogWithCommentsIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ValidationLog**](ValidationLog.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

