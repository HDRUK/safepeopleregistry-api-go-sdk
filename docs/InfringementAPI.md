# \InfringementAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**InfringementIndex**](InfringementAPI.md#InfringementIndex) | **Get** /api/v1/infringements | Infringement@index
[**InfringementShow**](InfringementAPI.md#InfringementShow) | **Get** /api/v1/infringements/{id} | Infringement@show
[**InfringementStore**](InfringementAPI.md#InfringementStore) | **Post** /api/v1/infringements | Infringement@store



## InfringementIndex

> InfringementIndex200Response InfringementIndex(ctx).Execute()

Infringement@index



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
	resp, r, err := apiClient.InfringementAPI.InfringementIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InfringementAPI.InfringementIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InfringementIndex`: InfringementIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `InfringementAPI.InfringementIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiInfringementIndexRequest struct via the builder pattern


### Return type

[**InfringementIndex200Response**](InfringementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InfringementShow

> InfringementIndex200Response InfringementShow(ctx, id).Execute()

Infringement@show



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
	id := int32(1) // int32 | Infringement entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InfringementAPI.InfringementShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InfringementAPI.InfringementShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InfringementShow`: InfringementIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `InfringementAPI.InfringementShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Infringement entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiInfringementShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InfringementIndex200Response**](InfringementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InfringementStore

> InfringementStore201Response InfringementStore(ctx).InfringementStoreRequest(infringementStoreRequest).Execute()

Infringement@store



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
	infringementStoreRequest := *openapiclient.NewInfringementStoreRequest() // InfringementStoreRequest | Infringement definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InfringementAPI.InfringementStore(context.Background()).InfringementStoreRequest(infringementStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InfringementAPI.InfringementStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InfringementStore`: InfringementStore201Response
	fmt.Fprintf(os.Stdout, "Response from `InfringementAPI.InfringementStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInfringementStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **infringementStoreRequest** | [**InfringementStoreRequest**](InfringementStoreRequest.md) | Infringement definition | 

### Return type

[**InfringementStore201Response**](InfringementStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

