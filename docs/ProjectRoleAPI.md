# \ProjectRoleAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectRoleIndex**](ProjectRoleAPI.md#ProjectRoleIndex) | **Get** /api/v1/project_roles | ProjectRole@index
[**ProjectRoleShow**](ProjectRoleAPI.md#ProjectRoleShow) | **Get** /api/v1/project_roles/{id} | ProjectRole@show
[**ProjectRoleStore**](ProjectRoleAPI.md#ProjectRoleStore) | **Post** /api/v1/project_roles | ProjectRole@store
[**ProjectRoleUpdate**](ProjectRoleAPI.md#ProjectRoleUpdate) | **Put** /api/v1/project_roles/{id} | ProjectRole@update



## ProjectRoleIndex

> ProjectRoleIndex200Response ProjectRoleIndex(ctx).Execute()

ProjectRole@index



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
	resp, r, err := apiClient.ProjectRoleAPI.ProjectRoleIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectRoleAPI.ProjectRoleIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectRoleIndex`: ProjectRoleIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectRoleAPI.ProjectRoleIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiProjectRoleIndexRequest struct via the builder pattern


### Return type

[**ProjectRoleIndex200Response**](ProjectRoleIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectRoleShow

> ProjectRoleIndex200Response ProjectRoleShow(ctx, id).Execute()

ProjectRole@show



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
	id := int32(1) // int32 | ProjectRole entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectRoleAPI.ProjectRoleShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectRoleAPI.ProjectRoleShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectRoleShow`: ProjectRoleIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectRoleAPI.ProjectRoleShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ProjectRole entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectRoleShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectRoleIndex200Response**](ProjectRoleIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectRoleStore

> IdentityStore201Response ProjectRoleStore(ctx).ProjectRole(projectRole).Execute()

ProjectRole@store



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
	projectRole := *openapiclient.NewProjectRole() // ProjectRole | ProjectRole definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectRoleAPI.ProjectRoleStore(context.Background()).ProjectRole(projectRole).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectRoleAPI.ProjectRoleStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectRoleStore`: IdentityStore201Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectRoleAPI.ProjectRoleStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProjectRoleStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectRole** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition | 

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


## ProjectRoleUpdate

> ProjectRoleUpdate200Response ProjectRoleUpdate(ctx, id).ProjectRole(projectRole).Execute()

ProjectRole@update



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
	id := int32(1) // int32 | ProjectRole entry ID
	projectRole := *openapiclient.NewProjectRole() // ProjectRole | ProjectRole definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectRoleAPI.ProjectRoleUpdate(context.Background(), id).ProjectRole(projectRole).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectRoleAPI.ProjectRoleUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectRoleUpdate`: ProjectRoleUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectRoleAPI.ProjectRoleUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ProjectRole entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectRoleUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectRole** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition | 

### Return type

[**ProjectRoleUpdate200Response**](ProjectRoleUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

