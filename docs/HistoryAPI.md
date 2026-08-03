# \HistoryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HistoryIndex**](HistoryAPI.md#HistoryIndex) | **Get** /api/v1/histories | History@index
[**HistoryShow**](HistoryAPI.md#HistoryShow) | **Get** /api/v1/histories/{id} | History@show
[**HistoryStore**](HistoryAPI.md#HistoryStore) | **Post** /api/v1/histories | History@store



## HistoryIndex

> HistoryIndex200Response HistoryIndex(ctx).Execute()

History@index



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
	resp, r, err := apiClient.HistoryAPI.HistoryIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HistoryAPI.HistoryIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HistoryIndex`: HistoryIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `HistoryAPI.HistoryIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHistoryIndexRequest struct via the builder pattern


### Return type

[**HistoryIndex200Response**](HistoryIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HistoryShow

> HistoryIndex200Response HistoryShow(ctx, id).Execute()

History@show



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
	id := int32(1) // int32 | History entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HistoryAPI.HistoryShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HistoryAPI.HistoryShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HistoryShow`: HistoryIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `HistoryAPI.HistoryShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | History entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiHistoryShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**HistoryIndex200Response**](HistoryIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HistoryStore

> HistoryStore201Response HistoryStore(ctx).HistoryStoreRequest(historyStoreRequest).Execute()

History@store



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
	historyStoreRequest := *openapiclient.NewHistoryStoreRequest() // HistoryStoreRequest | History definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HistoryAPI.HistoryStore(context.Background()).HistoryStoreRequest(historyStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HistoryAPI.HistoryStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HistoryStore`: HistoryStore201Response
	fmt.Fprintf(os.Stdout, "Response from `HistoryAPI.HistoryStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHistoryStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **historyStoreRequest** | [**HistoryStoreRequest**](HistoryStoreRequest.md) | History definition | 

### Return type

[**HistoryStore201Response**](HistoryStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

