# \TrainingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TrainingIndex**](TrainingAPI.md#TrainingIndex) | **Get** /api/v1/training | Training@index
[**TrainingIndexByRegistryId**](TrainingAPI.md#TrainingIndexByRegistryId) | **Get** /api/v1/training/registry/{id} | Training@show
[**TrainingShow**](TrainingAPI.md#TrainingShow) | **Get** /api/v1/training/{id} | Training@show
[**TrainingStore**](TrainingAPI.md#TrainingStore) | **Post** /api/v1/training | Training@store
[**TrainingUpdate**](TrainingAPI.md#TrainingUpdate) | **Put** /api/v1/training/{id} | Training@update



## TrainingIndex

> TrainingShow200Response TrainingIndex(ctx).Execute()

Training@index



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
	resp, r, err := apiClient.TrainingAPI.TrainingIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingAPI.TrainingIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrainingIndex`: TrainingShow200Response
	fmt.Fprintf(os.Stdout, "Response from `TrainingAPI.TrainingIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiTrainingIndexRequest struct via the builder pattern


### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrainingIndexByRegistryId

> TrainingShow200Response TrainingIndexByRegistryId(ctx, id).Execute()

Training@show



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
	id := int32(1) // int32 | Training registry id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingAPI.TrainingIndexByRegistryId(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingAPI.TrainingIndexByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrainingIndexByRegistryId`: TrainingShow200Response
	fmt.Fprintf(os.Stdout, "Response from `TrainingAPI.TrainingIndexByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Training registry id | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrainingIndexByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrainingShow

> TrainingShow200Response TrainingShow(ctx, id).Execute()

Training@show



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
	id := int32(1) // int32 | Training id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingAPI.TrainingShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingAPI.TrainingShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrainingShow`: TrainingShow200Response
	fmt.Fprintf(os.Stdout, "Response from `TrainingAPI.TrainingShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Training id | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrainingShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrainingStore

> AccreditationStoreByRegistryId201Response TrainingStore(ctx).Training(training).Execute()

Training@store



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
	training := *openapiclient.NewTraining() // Training | Training definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingAPI.TrainingStore(context.Background()).Training(training).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingAPI.TrainingStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrainingStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `TrainingAPI.TrainingStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrainingStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **training** | [**Training**](Training.md) | Training definition | 

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrainingUpdate

> TrainingUpdate200Response TrainingUpdate(ctx, id).Training(training).Execute()

Training@update



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
	id := int32(1) // int32 | Training entry ID
	training := *openapiclient.NewTraining() // Training | Training definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingAPI.TrainingUpdate(context.Background(), id).Training(training).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingAPI.TrainingUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrainingUpdate`: TrainingUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `TrainingAPI.TrainingUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Training entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrainingUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **training** | [**Training**](Training.md) | Training definition | 

### Return type

[**TrainingUpdate200Response**](TrainingUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

