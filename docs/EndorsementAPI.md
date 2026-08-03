# \EndorsementAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EndorsementIndex**](EndorsementAPI.md#EndorsementIndex) | **Get** /api/v1/endorsements | Endorsement@index
[**EndorsementShow**](EndorsementAPI.md#EndorsementShow) | **Get** /api/v1/endorsements/{id} | Endorsement@show



## EndorsementIndex

> EndorsementIndex200Response EndorsementIndex(ctx).Execute()

Endorsement@index



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
	resp, r, err := apiClient.EndorsementAPI.EndorsementIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndorsementAPI.EndorsementIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EndorsementIndex`: EndorsementIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `EndorsementAPI.EndorsementIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEndorsementIndexRequest struct via the builder pattern


### Return type

[**EndorsementIndex200Response**](EndorsementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EndorsementShow

> EndorsementIndex200Response EndorsementShow(ctx, id).Execute()

Endorsement@show



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
	id := int32(1) // int32 | Endorsement entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EndorsementAPI.EndorsementShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndorsementAPI.EndorsementShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EndorsementShow`: EndorsementIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `EndorsementAPI.EndorsementShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Endorsement entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEndorsementShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EndorsementIndex200Response**](EndorsementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

