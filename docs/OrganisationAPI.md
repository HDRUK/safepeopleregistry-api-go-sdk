# \OrganisationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrganisationGetDelegates**](OrganisationAPI.md#OrganisationGetDelegates) | **Get** /api/v1/organisations/{id}/delegates | Return all delegates associated with an organisation
[**OrganisationGetProjects**](OrganisationAPI.md#OrganisationGetProjects) | **Get** /api/v1/organisations/{id}/projects | organisation@getProjects
[**OrganisationGetSponsorshipsProjects**](OrganisationAPI.md#OrganisationGetSponsorshipsProjects) | **Get** /api/v1/organisations/{id}/projects/sponsorships | organisation@getSponsorshipsProjects
[**OrganisationGetUsers**](OrganisationAPI.md#OrganisationGetUsers) | **Get** /api/v1/organisations/{id}/users | organisation@getUsers
[**OrganisationIndex**](OrganisationAPI.md#OrganisationIndex) | **Get** /api/v1/organisations | organisation@index



## OrganisationGetDelegates

> OrganisationGetDelegates200Response OrganisationGetDelegates(ctx, id).Execute()

Return all delegates associated with an organisation



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
	id := int32(1) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationAPI.OrganisationGetDelegates(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationAPI.OrganisationGetDelegates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationGetDelegates`: OrganisationGetDelegates200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationAPI.OrganisationGetDelegates`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationGetDelegatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationGetDelegates200Response**](OrganisationGetDelegates200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationGetProjects

> OrganisationGetProjects200Response OrganisationGetProjects(ctx, id).Execute()

organisation@getProjects



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
	id := int32(1) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationAPI.OrganisationGetProjects(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationAPI.OrganisationGetProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationGetProjects`: OrganisationGetProjects200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationAPI.OrganisationGetProjects`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationGetProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationGetProjects200Response**](OrganisationGetProjects200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationGetSponsorshipsProjects

> OrganisationGetProjects200Response OrganisationGetSponsorshipsProjects(ctx, id).Execute()

organisation@getSponsorshipsProjects



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
	id := int32(1) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationAPI.OrganisationGetSponsorshipsProjects(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationAPI.OrganisationGetSponsorshipsProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationGetSponsorshipsProjects`: OrganisationGetProjects200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationAPI.OrganisationGetSponsorshipsProjects`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationGetSponsorshipsProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationGetProjects200Response**](OrganisationGetProjects200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationGetUsers

> OrganisationGetUsers200Response OrganisationGetUsers(ctx, id).Execute()

organisation@getUsers



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
	id := int32(1) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationAPI.OrganisationGetUsers(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationAPI.OrganisationGetUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationGetUsers`: OrganisationGetUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationAPI.OrganisationGetUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationGetUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationGetUsers200Response**](OrganisationGetUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationIndex

> OrganisationIndex200Response OrganisationIndex(ctx).Execute()

organisation@index



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
	resp, r, err := apiClient.OrganisationAPI.OrganisationIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationAPI.OrganisationIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationIndex`: OrganisationIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationAPI.OrganisationIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationIndexRequest struct via the builder pattern


### Return type

[**OrganisationIndex200Response**](OrganisationIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

