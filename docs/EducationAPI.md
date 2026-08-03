# \EducationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EducationDestroyByRegistryId**](EducationAPI.md#EducationDestroyByRegistryId) | **Delete** /api/v1/registries/{registryId}/educations/{id} | Delete an education record
[**EducationIndexByRegistryId**](EducationAPI.md#EducationIndexByRegistryId) | **Get** /api/v1/educations/registries/{registryId} | Get education records by registry ID
[**EducationShowByRegistryId**](EducationAPI.md#EducationShowByRegistryId) | **Get** /api/v1/educations/{id}/registries/{registryId} | Get a specific education record by ID and registry ID
[**EducationStoreByRegistryId**](EducationAPI.md#EducationStoreByRegistryId) | **Post** /api/v1/registries/{registryId}/educations | Create a new education record for a registry
[**EducationUpdateByRegistryId**](EducationAPI.md#EducationUpdateByRegistryId) | **Put** /api/v1/registries/{registryId}/educations/{id} | Update an existing education record



## EducationDestroyByRegistryId

> EducationDestroyByRegistryId200Response EducationDestroyByRegistryId(ctx, registryId, id).Execute()

Delete an education record

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
	registryId := int32(1) // int32 | ID of the registry
	id := int32(1) // int32 | ID of the education record

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EducationAPI.EducationDestroyByRegistryId(context.Background(), registryId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EducationAPI.EducationDestroyByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EducationDestroyByRegistryId`: EducationDestroyByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `EducationAPI.EducationDestroyByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 
**id** | **int32** | ID of the education record | 

### Other Parameters

Other parameters are passed through a pointer to a apiEducationDestroyByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EducationIndexByRegistryId

> []Education EducationIndexByRegistryId(ctx, registryId).Execute()

Get education records by registry ID

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
	registryId := int32(1) // int32 | ID of the registry

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EducationAPI.EducationIndexByRegistryId(context.Background(), registryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EducationAPI.EducationIndexByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EducationIndexByRegistryId`: []Education
	fmt.Fprintf(os.Stdout, "Response from `EducationAPI.EducationIndexByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiEducationIndexByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]Education**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EducationShowByRegistryId

> Education EducationShowByRegistryId(ctx, registryId, id).Execute()

Get a specific education record by ID and registry ID

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
	registryId := int32(1) // int32 | ID of the registry
	id := int32(1) // int32 | ID of the education record

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EducationAPI.EducationShowByRegistryId(context.Background(), registryId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EducationAPI.EducationShowByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EducationShowByRegistryId`: Education
	fmt.Fprintf(os.Stdout, "Response from `EducationAPI.EducationShowByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 
**id** | **int32** | ID of the education record | 

### Other Parameters

Other parameters are passed through a pointer to a apiEducationShowByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Education**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EducationStoreByRegistryId

> AccreditationStoreByRegistryId201Response EducationStoreByRegistryId(ctx, registryId).Education(education).Execute()

Create a new education record for a registry

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
	registryId := int32(1) // int32 | ID of the registry
	education := *openapiclient.NewEducation() // Education | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EducationAPI.EducationStoreByRegistryId(context.Background(), registryId).Education(education).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EducationAPI.EducationStoreByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EducationStoreByRegistryId`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `EducationAPI.EducationStoreByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiEducationStoreByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **education** | [**Education**](Education.md) |  | 

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


## EducationUpdateByRegistryId

> Education EducationUpdateByRegistryId(ctx, registryId, id).Education(education).Execute()

Update an existing education record

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
	registryId := int32(1) // int32 | ID of the registry
	id := int32(1) // int32 | ID of the education record
	education := *openapiclient.NewEducation() // Education | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EducationAPI.EducationUpdateByRegistryId(context.Background(), registryId, id).Education(education).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EducationAPI.EducationUpdateByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EducationUpdateByRegistryId`: Education
	fmt.Fprintf(os.Stdout, "Response from `EducationAPI.EducationUpdateByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 
**id** | **int32** | ID of the education record | 

### Other Parameters

Other parameters are passed through a pointer to a apiEducationUpdateByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **education** | [**Education**](Education.md) |  | 

### Return type

[**Education**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

