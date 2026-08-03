# \RegistryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RegistryDestroy**](RegistryAPI.md#RegistryDestroy) | **Delete** /api/v1/registry/{id} | Registry@destroy
[**RegistryIndex**](RegistryAPI.md#RegistryIndex) | **Get** /api/v1/registry | Registry@index
[**RegistryShow**](RegistryAPI.md#RegistryShow) | **Get** /api/v1/registry/{id} | Registry@show
[**RegistryStore**](RegistryAPI.md#RegistryStore) | **Post** /api/v1/registry | Registry@store
[**RegistryUpdate**](RegistryAPI.md#RegistryUpdate) | **Put** /api/v1/registry/{id} | Registry@update



## RegistryDestroy

> AffiliationDestroy200Response RegistryDestroy(ctx, id).Execute()

Registry@destroy



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
	id := int32(1) // int32 | Registry entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistryAPI.RegistryDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistryAPI.RegistryDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegistryDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `RegistryAPI.RegistryDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Registry entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegistryDestroyRequest struct via the builder pattern


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


## RegistryIndex

> RegistryIndex200Response RegistryIndex(ctx).Execute()

Registry@index



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
	resp, r, err := apiClient.RegistryAPI.RegistryIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistryAPI.RegistryIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegistryIndex`: RegistryIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `RegistryAPI.RegistryIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegistryIndexRequest struct via the builder pattern


### Return type

[**RegistryIndex200Response**](RegistryIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegistryShow

> RegistryIndex200Response RegistryShow(ctx, id).Execute()

Registry@show



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
	id := int32(1) // int32 | Registry entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistryAPI.RegistryShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistryAPI.RegistryShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegistryShow`: RegistryIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `RegistryAPI.RegistryShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Registry entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegistryShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegistryIndex200Response**](RegistryIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegistryStore

> AccreditationStoreByRegistryId201Response RegistryStore(ctx).Registry(registry).Execute()

Registry@store



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
	registry := *openapiclient.NewRegistry() // Registry | Registry definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistryAPI.RegistryStore(context.Background()).Registry(registry).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistryAPI.RegistryStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegistryStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `RegistryAPI.RegistryStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegistryStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registry** | [**Registry**](Registry.md) | Registry definition | 

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


## RegistryUpdate

> RegistryUpdate200Response RegistryUpdate(ctx, id).Registry(registry).Execute()

Registry@update



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
	id := int32(1) // int32 | Registry entry ID
	registry := *openapiclient.NewRegistry() // Registry | Registry definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RegistryAPI.RegistryUpdate(context.Background(), id).Registry(registry).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RegistryAPI.RegistryUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegistryUpdate`: RegistryUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `RegistryAPI.RegistryUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Registry entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegistryUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **registry** | [**Registry**](Registry.md) | Registry definition | 

### Return type

[**RegistryUpdate200Response**](RegistryUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

