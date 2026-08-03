# \FeatureAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FeatureIndex**](FeatureAPI.md#FeatureIndex) | **Get** /api/v1/features | Feature@index
[**FeatureShow**](FeatureAPI.md#FeatureShow) | **Get** /api/v1/features/{featureId} | Feature@show
[**FeatureToggleByFeatureId**](FeatureAPI.md#FeatureToggleByFeatureId) | **Put** /api/v1/features/{featureId}/toggle | Feature@show



## FeatureIndex

> FeatureIndex200Response FeatureIndex(ctx).Execute()

Feature@index



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
	resp, r, err := apiClient.FeatureAPI.FeatureIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeatureAPI.FeatureIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FeatureIndex`: FeatureIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `FeatureAPI.FeatureIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFeatureIndexRequest struct via the builder pattern


### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FeatureShow

> FeatureIndex200Response FeatureShow(ctx, featureId).Execute()

Feature@show



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
	featureId := int32(56) // int32 | ID of the feature

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FeatureAPI.FeatureShow(context.Background(), featureId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeatureAPI.FeatureShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FeatureShow`: FeatureIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `FeatureAPI.FeatureShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**featureId** | **int32** | ID of the feature | 

### Other Parameters

Other parameters are passed through a pointer to a apiFeatureShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FeatureToggleByFeatureId

> FeatureIndex200Response FeatureToggleByFeatureId(ctx, featureId).Execute()

Feature@show



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
	featureId := int32(56) // int32 | ID of the feature

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FeatureAPI.FeatureToggleByFeatureId(context.Background(), featureId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeatureAPI.FeatureToggleByFeatureId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FeatureToggleByFeatureId`: FeatureIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `FeatureAPI.FeatureToggleByFeatureId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**featureId** | **int32** | ID of the feature | 

### Other Parameters

Other parameters are passed through a pointer to a apiFeatureToggleByFeatureIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

