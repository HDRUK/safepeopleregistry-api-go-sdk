# \ProjectDetailsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectDetailsDestroy**](ProjectDetailsAPI.md#ProjectDetailsDestroy) | **Delete** /api/v1/project_details/{id} | ProjectDetails@destroy
[**ProjectDetailsStore**](ProjectDetailsAPI.md#ProjectDetailsStore) | **Post** /api/v1/project_details | ProjectDetails@store
[**ProjectDetailsUpdate**](ProjectDetailsAPI.md#ProjectDetailsUpdate) | **Put** /api/v1/project_details/{id} | ProjectDetails@update



## ProjectDetailsDestroy

> AffiliationDestroy200Response ProjectDetailsDestroy(ctx, id).Execute()

ProjectDetails@destroy



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
	id := int32(1) // int32 | ProjectDetails entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectDetailsAPI.ProjectDetailsDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectDetailsAPI.ProjectDetailsDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDetailsDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectDetailsAPI.ProjectDetailsDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ProjectDetails entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectDetailsDestroyRequest struct via the builder pattern


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


## ProjectDetailsStore

> IdentityStore201Response ProjectDetailsStore(ctx).ProjectDetail(projectDetail).Execute()

ProjectDetails@store



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
	projectDetail := *openapiclient.NewProjectDetail() // ProjectDetail | ProjectDetail definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectDetailsAPI.ProjectDetailsStore(context.Background()).ProjectDetail(projectDetail).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectDetailsAPI.ProjectDetailsStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDetailsStore`: IdentityStore201Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectDetailsAPI.ProjectDetailsStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProjectDetailsStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectDetail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetail definition | 

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


## ProjectDetailsUpdate

> ProjectDetailsUpdate200Response ProjectDetailsUpdate(ctx, id).ProjectDetail(projectDetail).Execute()

ProjectDetails@update



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
	id := int32(1) // int32 | ProjectDetails entry ID
	projectDetail := *openapiclient.NewProjectDetail() // ProjectDetail | ProjectDetails definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectDetailsAPI.ProjectDetailsUpdate(context.Background(), id).ProjectDetail(projectDetail).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectDetailsAPI.ProjectDetailsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDetailsUpdate`: ProjectDetailsUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectDetailsAPI.ProjectDetailsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ProjectDetails entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectDetailsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectDetail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetails definition | 

### Return type

[**ProjectDetailsUpdate200Response**](ProjectDetailsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

