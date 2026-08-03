# \ValidationLogCommentsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ValidationLogCommentsComments**](ValidationLogCommentsAPI.md#ValidationLogCommentsComments) | **Get** /api/v1/validation_logs/{id}/comments | Get all comments for a Validation Log
[**ValidationLogCommentsDestroy**](ValidationLogCommentsAPI.md#ValidationLogCommentsDestroy) | **Delete** /api/v1/validation_log_comments/{id} | Delete a validation log comment
[**ValidationLogCommentsShow**](ValidationLogCommentsAPI.md#ValidationLogCommentsShow) | **Get** /api/v1/validation_log_comments/{id} | Get a single validation log comment
[**ValidationLogCommentsStore**](ValidationLogCommentsAPI.md#ValidationLogCommentsStore) | **Post** /api/v1/validation_log_comments | Create a new validation log comment
[**ValidationLogCommentsUpdate**](ValidationLogCommentsAPI.md#ValidationLogCommentsUpdate) | **Put** /api/v1/validation_log_comments/{id} | Update a validation log comment



## ValidationLogCommentsComments

> []ValidationLog ValidationLogCommentsComments(ctx, id).Execute()

Get all comments for a Validation Log



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
	resp, r, err := apiClient.ValidationLogCommentsAPI.ValidationLogCommentsComments(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogCommentsAPI.ValidationLogCommentsComments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogCommentsComments`: []ValidationLog
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogCommentsAPI.ValidationLogCommentsComments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the validation log | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogCommentsCommentsRequest struct via the builder pattern


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


## ValidationLogCommentsDestroy

> ValidationLogCommentsDestroy200Response ValidationLogCommentsDestroy(ctx, id).Execute()

Delete a validation log comment



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
	id := int32(56) // int32 | The ID of the comment

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogCommentsAPI.ValidationLogCommentsDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogCommentsAPI.ValidationLogCommentsDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogCommentsDestroy`: ValidationLogCommentsDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogCommentsAPI.ValidationLogCommentsDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the comment | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogCommentsDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ValidationLogCommentsDestroy200Response**](ValidationLogCommentsDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogCommentsShow

> ValidationLogComment ValidationLogCommentsShow(ctx, id).Execute()

Get a single validation log comment



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
	id := int32(56) // int32 | The ID of the comment

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogCommentsAPI.ValidationLogCommentsShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogCommentsAPI.ValidationLogCommentsShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogCommentsShow`: ValidationLogComment
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogCommentsAPI.ValidationLogCommentsShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the comment | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogCommentsShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogCommentsStore

> ValidationLogComment ValidationLogCommentsStore(ctx).ValidationLogCommentsStoreRequest(validationLogCommentsStoreRequest).Execute()

Create a new validation log comment



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
	validationLogCommentsStoreRequest := *openapiclient.NewValidationLogCommentsStoreRequest(int32(123), "Comment_example") // ValidationLogCommentsStoreRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogCommentsAPI.ValidationLogCommentsStore(context.Background()).ValidationLogCommentsStoreRequest(validationLogCommentsStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogCommentsAPI.ValidationLogCommentsStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogCommentsStore`: ValidationLogComment
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogCommentsAPI.ValidationLogCommentsStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogCommentsStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **validationLogCommentsStoreRequest** | [**ValidationLogCommentsStoreRequest**](ValidationLogCommentsStoreRequest.md) |  | 

### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogCommentsUpdate

> ValidationLogComment ValidationLogCommentsUpdate(ctx, id).ValidationLogCommentsUpdateRequest(validationLogCommentsUpdateRequest).Execute()

Update a validation log comment



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
	id := int32(56) // int32 | The ID of the comment
	validationLogCommentsUpdateRequest := *openapiclient.NewValidationLogCommentsUpdateRequest("Comment_example") // ValidationLogCommentsUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogCommentsAPI.ValidationLogCommentsUpdate(context.Background(), id).ValidationLogCommentsUpdateRequest(validationLogCommentsUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogCommentsAPI.ValidationLogCommentsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogCommentsUpdate`: ValidationLogComment
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogCommentsAPI.ValidationLogCommentsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the comment | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogCommentsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **validationLogCommentsUpdateRequest** | [**ValidationLogCommentsUpdateRequest**](ValidationLogCommentsUpdateRequest.md) |  | 

### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

