# \ExperienceAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ExperienceDestroy**](ExperienceAPI.md#ExperienceDestroy) | **Delete** /api/v1/experiences/{id} | Experience@destroy
[**ExperienceIndex**](ExperienceAPI.md#ExperienceIndex) | **Get** /api/v1/experiences | Experience@index
[**ExperienceShow**](ExperienceAPI.md#ExperienceShow) | **Get** /api/v1/experiences/{id} | Experience@show
[**ExperienceStore**](ExperienceAPI.md#ExperienceStore) | **Post** /api/v1/experiences | Experience@store
[**ExperienceUpdate**](ExperienceAPI.md#ExperienceUpdate) | **Put** /api/v1/experiences/{id} | Experience@update



## ExperienceDestroy

> AffiliationDestroy200Response ExperienceDestroy(ctx, id).Execute()

Experience@destroy



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
	id := int32(1) // int32 | Experience entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExperienceAPI.ExperienceDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExperienceAPI.ExperienceDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExperienceDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `ExperienceAPI.ExperienceDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Experience entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiExperienceDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AffiliationDestroy200Response**](AffiliationDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExperienceIndex

> ExperienceIndex200Response ExperienceIndex(ctx).Execute()

Experience@index



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
	resp, r, err := apiClient.ExperienceAPI.ExperienceIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExperienceAPI.ExperienceIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExperienceIndex`: ExperienceIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ExperienceAPI.ExperienceIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiExperienceIndexRequest struct via the builder pattern


### Return type

[**ExperienceIndex200Response**](ExperienceIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExperienceShow

> ExperienceShow200Response ExperienceShow(ctx, id).Execute()

Experience@show



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
	id := int32(1) // int32 | Experience entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExperienceAPI.ExperienceShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExperienceAPI.ExperienceShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExperienceShow`: ExperienceShow200Response
	fmt.Fprintf(os.Stdout, "Response from `ExperienceAPI.ExperienceShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Experience entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiExperienceShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ExperienceShow200Response**](ExperienceShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExperienceStore

> ExperienceStore201Response ExperienceStore(ctx).ExperienceStoreRequest(experienceStoreRequest).Execute()

Experience@store



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
	experienceStoreRequest := *openapiclient.NewExperienceStoreRequest() // ExperienceStoreRequest | Experience definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExperienceAPI.ExperienceStore(context.Background()).ExperienceStoreRequest(experienceStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExperienceAPI.ExperienceStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExperienceStore`: ExperienceStore201Response
	fmt.Fprintf(os.Stdout, "Response from `ExperienceAPI.ExperienceStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExperienceStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **experienceStoreRequest** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition | 

### Return type

[**ExperienceStore201Response**](ExperienceStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExperienceUpdate

> ExperienceUpdate200Response ExperienceUpdate(ctx, id).ExperienceStoreRequest(experienceStoreRequest).Execute()

Experience@update



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
	id := int32(1) // int32 | Experience entry ID
	experienceStoreRequest := *openapiclient.NewExperienceStoreRequest() // ExperienceStoreRequest | Experience definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExperienceAPI.ExperienceUpdate(context.Background(), id).ExperienceStoreRequest(experienceStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExperienceAPI.ExperienceUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExperienceUpdate`: ExperienceUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ExperienceAPI.ExperienceUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Experience entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiExperienceUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **experienceStoreRequest** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition | 

### Return type

[**ExperienceUpdate200Response**](ExperienceUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

