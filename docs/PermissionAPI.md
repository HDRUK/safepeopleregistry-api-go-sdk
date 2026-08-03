# \PermissionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PermissionDestroy**](PermissionAPI.md#PermissionDestroy) | **Delete** /api/v1/permissions/{id} | Permission@destroy
[**PermissionIndex**](PermissionAPI.md#PermissionIndex) | **Get** /api/v1/permissions | Permission@index
[**PermissionShow**](PermissionAPI.md#PermissionShow) | **Get** /api/v1/permissions/{id} | Permission@show
[**PermissionStore**](PermissionAPI.md#PermissionStore) | **Post** /api/v1/permissions | Permission@store
[**PermissionUpdate**](PermissionAPI.md#PermissionUpdate) | **Patch** /api/v1/permissions/{id} | Permission@update



## PermissionDestroy

> AffiliationDestroy200Response PermissionDestroy(ctx, id).Execute()

Permission@destroy



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
	id := int32(1) // int32 | Permission entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionAPI.PermissionDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionAPI.PermissionDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PermissionDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `PermissionAPI.PermissionDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Permission entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPermissionDestroyRequest struct via the builder pattern


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


## PermissionIndex

> PermissionIndex200Response PermissionIndex(ctx).Execute()

Permission@index



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
	resp, r, err := apiClient.PermissionAPI.PermissionIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionAPI.PermissionIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PermissionIndex`: PermissionIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `PermissionAPI.PermissionIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPermissionIndexRequest struct via the builder pattern


### Return type

[**PermissionIndex200Response**](PermissionIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PermissionShow

> PermissionIndex200Response PermissionShow(ctx, id).Execute()

Permission@show



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
	id := int32(1) // int32 | Permission entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionAPI.PermissionShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionAPI.PermissionShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PermissionShow`: PermissionIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `PermissionAPI.PermissionShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Permission entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPermissionShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PermissionIndex200Response**](PermissionIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PermissionStore

> AccreditationStoreByRegistryId201Response PermissionStore(ctx).PermissionStoreRequest(permissionStoreRequest).Execute()

Permission@store



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
	permissionStoreRequest := *openapiclient.NewPermissionStoreRequest() // PermissionStoreRequest | Permission definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionAPI.PermissionStore(context.Background()).PermissionStoreRequest(permissionStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionAPI.PermissionStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PermissionStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `PermissionAPI.PermissionStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPermissionStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **permissionStoreRequest** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition | 

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


## PermissionUpdate

> PermissionUpdate200Response PermissionUpdate(ctx, id).PermissionStoreRequest(permissionStoreRequest).Execute()

Permission@update



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
	id := int32(1) // int32 | Permission entry ID
	permissionStoreRequest := *openapiclient.NewPermissionStoreRequest() // PermissionStoreRequest | Permission definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionAPI.PermissionUpdate(context.Background(), id).PermissionStoreRequest(permissionStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionAPI.PermissionUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PermissionUpdate`: PermissionUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `PermissionAPI.PermissionUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Permission entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPermissionUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **permissionStoreRequest** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition | 

### Return type

[**PermissionUpdate200Response**](PermissionUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

