# \AccreditationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccreditationIndexByRegistryId**](AccreditationAPI.md#AccreditationIndexByRegistryId) | **Get** /api/v1/accreditations/{registryId} | Get accreditations by registry ID
[**AccreditationStoreByRegistryId**](AccreditationAPI.md#AccreditationStoreByRegistryId) | **Post** /api/v1/accreditations/{registryId} | Create accreditation for a registry
[**AccreditationUpdateByRegistryId**](AccreditationAPI.md#AccreditationUpdateByRegistryId) | **Put** /api/v1/accreditations/{id}/registries/{registryId} | Update accreditation for a registry



## AccreditationIndexByRegistryId

> AccreditationIndexByRegistryId200Response AccreditationIndexByRegistryId(ctx, registryId).Execute()

Get accreditations by registry ID

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
	resp, r, err := apiClient.AccreditationAPI.AccreditationIndexByRegistryId(context.Background(), registryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccreditationAPI.AccreditationIndexByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccreditationIndexByRegistryId`: AccreditationIndexByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AccreditationAPI.AccreditationIndexByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccreditationIndexByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccreditationIndexByRegistryId200Response**](AccreditationIndexByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccreditationStoreByRegistryId

> AccreditationStoreByRegistryId201Response AccreditationStoreByRegistryId(ctx, registryId).Accreditation(accreditation).Execute()

Create accreditation for a registry

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
	accreditation := *openapiclient.NewAccreditation() // Accreditation | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccreditationAPI.AccreditationStoreByRegistryId(context.Background(), registryId).Accreditation(accreditation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccreditationAPI.AccreditationStoreByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccreditationStoreByRegistryId`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `AccreditationAPI.AccreditationStoreByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccreditationStoreByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accreditation** | [**Accreditation**](Accreditation.md) |  | 

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


## AccreditationUpdateByRegistryId

> AccreditationUpdateByRegistryId200Response AccreditationUpdateByRegistryId(ctx, registryId, id).Accreditation(accreditation).Execute()

Update accreditation for a registry

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
	id := int32(1) // int32 | ID of the accreditation
	accreditation := *openapiclient.NewAccreditation() // Accreditation | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccreditationAPI.AccreditationUpdateByRegistryId(context.Background(), registryId, id).Accreditation(accreditation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccreditationAPI.AccreditationUpdateByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccreditationUpdateByRegistryId`: AccreditationUpdateByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AccreditationAPI.AccreditationUpdateByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 
**id** | **int32** | ID of the accreditation | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccreditationUpdateByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **accreditation** | [**Accreditation**](Accreditation.md) |  | 

### Return type

[**AccreditationUpdateByRegistryId200Response**](AccreditationUpdateByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

