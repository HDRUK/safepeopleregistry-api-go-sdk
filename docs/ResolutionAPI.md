# \ResolutionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ResolutionIndexByRegistryId**](ResolutionAPI.md#ResolutionIndexByRegistryId) | **Get** /api/v1/registries/{registryId}/resolutions | Get resolutions by registry ID
[**ResolutionStoreByRegistryId**](ResolutionAPI.md#ResolutionStoreByRegistryId) | **Post** /api/v1/registries/{registryId}/resolutions | Create a new resolution for a registry



## ResolutionIndexByRegistryId

> []Resolution ResolutionIndexByRegistryId(ctx, registryId).Execute()

Get resolutions by registry ID

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
	resp, r, err := apiClient.ResolutionAPI.ResolutionIndexByRegistryId(context.Background(), registryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResolutionAPI.ResolutionIndexByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolutionIndexByRegistryId`: []Resolution
	fmt.Fprintf(os.Stdout, "Response from `ResolutionAPI.ResolutionIndexByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolutionIndexByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]Resolution**](Resolution.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolutionStoreByRegistryId

> AccreditationStoreByRegistryId201Response ResolutionStoreByRegistryId(ctx, registryId).Resolution(resolution).Execute()

Create a new resolution for a registry

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
	resolution := *openapiclient.NewResolution() // Resolution | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResolutionAPI.ResolutionStoreByRegistryId(context.Background(), registryId).Resolution(resolution).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResolutionAPI.ResolutionStoreByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolutionStoreByRegistryId`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `ResolutionAPI.ResolutionStoreByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | ID of the registry | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolutionStoreByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resolution** | [**Resolution**](Resolution.md) |  | 

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

