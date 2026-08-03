# \IdentityAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IdentityDestroy**](IdentityAPI.md#IdentityDestroy) | **Delete** /api/v1/identities/{id} | Identity@destroy
[**IdentityIndex**](IdentityAPI.md#IdentityIndex) | **Get** /api/v1/identities | Identity@index
[**IdentityShow**](IdentityAPI.md#IdentityShow) | **Get** /api/v1/identities/{id} | Identity@show
[**IdentityStore**](IdentityAPI.md#IdentityStore) | **Post** /api/v1/identities | Identity@store
[**IdentityUpdate**](IdentityAPI.md#IdentityUpdate) | **Put** /api/v1/identities/{id} | Identity@update



## IdentityDestroy

> AffiliationDestroy200Response IdentityDestroy(ctx, id).Execute()

Identity@destroy



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
	id := int32(1) // int32 | Identity entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentityAPI.IdentityDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentityAPI.IdentityDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdentityDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `IdentityAPI.IdentityDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Identity entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiIdentityDestroyRequest struct via the builder pattern


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


## IdentityIndex

> IdentityIndex200Response IdentityIndex(ctx).Execute()

Identity@index



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
	resp, r, err := apiClient.IdentityAPI.IdentityIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentityAPI.IdentityIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdentityIndex`: IdentityIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `IdentityAPI.IdentityIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiIdentityIndexRequest struct via the builder pattern


### Return type

[**IdentityIndex200Response**](IdentityIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IdentityShow

> IdentityIndex200Response IdentityShow(ctx, id).Execute()

Identity@show



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
	id := int32(1) // int32 | Identity ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentityAPI.IdentityShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentityAPI.IdentityShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdentityShow`: IdentityIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `IdentityAPI.IdentityShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Identity ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiIdentityShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IdentityIndex200Response**](IdentityIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IdentityStore

> IdentityStore201Response IdentityStore(ctx).IdentityStoreRequest(identityStoreRequest).Execute()

Identity@store



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
	identityStoreRequest := *openapiclient.NewIdentityStoreRequest() // IdentityStoreRequest | Identity definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentityAPI.IdentityStore(context.Background()).IdentityStoreRequest(identityStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentityAPI.IdentityStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdentityStore`: IdentityStore201Response
	fmt.Fprintf(os.Stdout, "Response from `IdentityAPI.IdentityStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIdentityStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **identityStoreRequest** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition | 

### Return type

[**IdentityStore201Response**](IdentityStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IdentityUpdate

> IdentityUpdate200Response IdentityUpdate(ctx, id).IdentityStoreRequest(identityStoreRequest).Execute()

Identity@update



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
	id := int32(1) // int32 | Identity entry ID
	identityStoreRequest := *openapiclient.NewIdentityStoreRequest() // IdentityStoreRequest | Identity definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentityAPI.IdentityUpdate(context.Background(), id).IdentityStoreRequest(identityStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentityAPI.IdentityUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IdentityUpdate`: IdentityUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `IdentityAPI.IdentityUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Identity entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiIdentityUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **identityStoreRequest** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition | 

### Return type

[**IdentityUpdate200Response**](IdentityUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

