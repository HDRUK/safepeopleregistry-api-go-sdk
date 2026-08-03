# \ValidationChecksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ValidationChecksDestroy**](ValidationChecksAPI.md#ValidationChecksDestroy) | **Delete** /api/v1/validation_checks/{id} | Delete a validation check
[**ValidationChecksIndex**](ValidationChecksAPI.md#ValidationChecksIndex) | **Get** /api/v1/validation_checks | List all validation checks
[**ValidationChecksShow**](ValidationChecksAPI.md#ValidationChecksShow) | **Get** /api/v1/validation_checks/{id} | Get a single validation check
[**ValidationChecksStore**](ValidationChecksAPI.md#ValidationChecksStore) | **Post** /api/v1/validation_checks | Create a new validation check
[**ValidationChecksUpdate**](ValidationChecksAPI.md#ValidationChecksUpdate) | **Put** /api/v1/validation_checks/{id} | Update a validation check



## ValidationChecksDestroy

> ValidationChecksDestroy200Response ValidationChecksDestroy(ctx, id).Execute()

Delete a validation check



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
	id := int32(56) // int32 | ID of the validation check

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationChecksAPI.ValidationChecksDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationChecksAPI.ValidationChecksDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationChecksDestroy`: ValidationChecksDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationChecksAPI.ValidationChecksDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the validation check | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationChecksDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ValidationChecksDestroy200Response**](ValidationChecksDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationChecksIndex

> []ValidationCheck ValidationChecksIndex(ctx).Execute()

List all validation checks



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
	resp, r, err := apiClient.ValidationChecksAPI.ValidationChecksIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationChecksAPI.ValidationChecksIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationChecksIndex`: []ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `ValidationChecksAPI.ValidationChecksIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiValidationChecksIndexRequest struct via the builder pattern


### Return type

[**[]ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationChecksShow

> ValidationCheck ValidationChecksShow(ctx, id).Execute()

Get a single validation check



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
	id := int32(56) // int32 | ID of the validation check

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationChecksAPI.ValidationChecksShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationChecksAPI.ValidationChecksShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationChecksShow`: ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `ValidationChecksAPI.ValidationChecksShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the validation check | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationChecksShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationChecksStore

> ValidationCheck ValidationChecksStore(ctx).ValidationChecksStoreRequest(validationChecksStoreRequest).Execute()

Create a new validation check



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
	validationChecksStoreRequest := *openapiclient.NewValidationChecksStoreRequest("Name_example", "Description_example") // ValidationChecksStoreRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationChecksAPI.ValidationChecksStore(context.Background()).ValidationChecksStoreRequest(validationChecksStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationChecksAPI.ValidationChecksStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationChecksStore`: ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `ValidationChecksAPI.ValidationChecksStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidationChecksStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **validationChecksStoreRequest** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  | 

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationChecksUpdate

> ValidationCheck ValidationChecksUpdate(ctx, id).ValidationChecksStoreRequest(validationChecksStoreRequest).Execute()

Update a validation check



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
	id := int32(56) // int32 | ID of the validation check
	validationChecksStoreRequest := *openapiclient.NewValidationChecksStoreRequest("Name_example", "Description_example") // ValidationChecksStoreRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationChecksAPI.ValidationChecksUpdate(context.Background(), id).ValidationChecksStoreRequest(validationChecksStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationChecksAPI.ValidationChecksUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationChecksUpdate`: ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `ValidationChecksAPI.ValidationChecksUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the validation check | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationChecksUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **validationChecksStoreRequest** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  | 

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

