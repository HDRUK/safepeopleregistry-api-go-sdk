# \ProjectDetailAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectDetailIndex**](ProjectDetailAPI.md#ProjectDetailIndex) | **Get** /api/v1/project_details | ProjectDetail@index
[**ProjectDetailShow**](ProjectDetailAPI.md#ProjectDetailShow) | **Get** /api/v1/project_details/{id} | ProjectDetail@show



## ProjectDetailIndex

> ProjectDetailIndex200Response ProjectDetailIndex(ctx).Execute()

ProjectDetail@index



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
	resp, r, err := apiClient.ProjectDetailAPI.ProjectDetailIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectDetailAPI.ProjectDetailIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDetailIndex`: ProjectDetailIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectDetailAPI.ProjectDetailIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiProjectDetailIndexRequest struct via the builder pattern


### Return type

[**ProjectDetailIndex200Response**](ProjectDetailIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectDetailShow

> ProjectDetailIndex200Response ProjectDetailShow(ctx, id).Execute()

ProjectDetail@show



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
	id := int32(1) // int32 | ProjectDetail entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectDetailAPI.ProjectDetailShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectDetailAPI.ProjectDetailShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDetailShow`: ProjectDetailIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectDetailAPI.ProjectDetailShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ProjectDetail entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectDetailShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectDetailIndex200Response**](ProjectDetailIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

