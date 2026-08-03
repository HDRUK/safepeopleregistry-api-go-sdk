# \CustodianAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianAddProject**](CustodianAPI.md#CustodianAddProject) | **Post** /api/v1/custodians/{custodianId}/projects | Custodian@addProject
[**CustodianDestroy**](CustodianAPI.md#CustodianDestroy) | **Delete** /api/v1/custodians/{id} | Custodian@destroy
[**CustodianGetOrganisations**](CustodianAPI.md#CustodianGetOrganisations) | **Get** /api/v1/custodian/{custodianId}/organisations | Return all custodian organisations with projects
[**CustodianGetProjects**](CustodianAPI.md#CustodianGetProjects) | **Get** /api/v1/custodian/{custodianId}/projects | Return all projects associated with a custodian
[**CustodianGetProjectsUsers**](CustodianAPI.md#CustodianGetProjectsUsers) | **Get** /api/v1/custodians/{custodianId}/projects_users | Get all users associated with custodian&#39;s projects
[**CustodianGetUserProjects**](CustodianAPI.md#CustodianGetUserProjects) | **Get** /api/v1/custodian/{custodianId}/users/{userId}/projects | Return all custodian projects associated with a user
[**CustodianIndex**](CustodianAPI.md#CustodianIndex) | **Get** /api/v1/custodians | Custodian@index
[**CustodianShow**](CustodianAPI.md#CustodianShow) | **Get** /api/v1/custodians/{id} | Custodian@show
[**CustodianShowByUniqueIdentifier**](CustodianAPI.md#CustodianShowByUniqueIdentifier) | **Get** /api/v1/custodians/identifier/{id} | Custodian@showByUniqueIdentifier
[**CustodianStore**](CustodianAPI.md#CustodianStore) | **Post** /api/v1/custodians | Custodian@store
[**CustodianUpdate**](CustodianAPI.md#CustodianUpdate) | **Put** /api/v1/custodians/{id} | Custodian@update



## CustodianAddProject

> CustodianAddProject201Response CustodianAddProject(ctx, custodianId).CustodianAddProjectRequest(custodianAddProjectRequest).Execute()

Custodian@addProject



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
	custodianId := int32(56) // int32 | ID of the custodian
	custodianAddProjectRequest := *openapiclient.NewCustodianAddProjectRequest() // CustodianAddProjectRequest | Project definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianAddProject(context.Background(), custodianId).CustodianAddProjectRequest(custodianAddProjectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianAddProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianAddProject`: CustodianAddProject201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianAddProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianAddProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **custodianAddProjectRequest** | [**CustodianAddProjectRequest**](CustodianAddProjectRequest.md) | Project definition | 

### Return type

[**CustodianAddProject201Response**](CustodianAddProject201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianDestroy

> AffiliationDestroy200Response CustodianDestroy(ctx, id).Execute()

Custodian@destroy



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
	id := int32(1) // int32 | Custodian entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Custodian entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianDestroyRequest struct via the builder pattern


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


## CustodianGetOrganisations

> CustodianGetOrganisations200Response CustodianGetOrganisations(ctx, custodianId).Execute()

Return all custodian organisations with projects



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
	custodianId := int32(1) // int32 | The ID of the custodian whose organisations are to be retrieved

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianGetOrganisations(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianGetOrganisations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianGetOrganisations`: CustodianGetOrganisations200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianGetOrganisations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian whose organisations are to be retrieved | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianGetOrganisationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianGetOrganisations200Response**](CustodianGetOrganisations200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianGetProjects

> CustodianGetProjects200Response CustodianGetProjects(ctx, custodianId).Execute()

Return all projects associated with a custodian



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
	custodianId := int32(1) // int32 | The ID of the custodian whose projects are to be retrieved

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianGetProjects(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianGetProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianGetProjects`: CustodianGetProjects200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianGetProjects`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian whose projects are to be retrieved | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianGetProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianGetProjects200Response**](CustodianGetProjects200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianGetProjectsUsers

> CustodianGetProjectsUsers200Response CustodianGetProjectsUsers(ctx, custodianId).Execute()

Get all users associated with custodian's projects



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
	custodianId := int32(56) // int32 | Custodian ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianGetProjectsUsers(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianGetProjectsUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianGetProjectsUsers`: CustodianGetProjectsUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianGetProjectsUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | Custodian ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianGetProjectsUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianGetProjectsUsers200Response**](CustodianGetProjectsUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianGetUserProjects

> CustodianGetUserProjects200Response CustodianGetUserProjects(ctx, custodianId, userId).Execute()

Return all custodian projects associated with a user



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
	custodianId := int32(1) // int32 | The ID of the custodian whose projects are to be retrieved
	userId := int32(1) // int32 | The ID of the user whose projects are to be retrieved

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianGetUserProjects(context.Background(), custodianId, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianGetUserProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianGetUserProjects`: CustodianGetUserProjects200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianGetUserProjects`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian whose projects are to be retrieved | 
**userId** | **int32** | The ID of the user whose projects are to be retrieved | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianGetUserProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustodianGetUserProjects200Response**](CustodianGetUserProjects200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianIndex

> CustodianIndex200Response CustodianIndex(ctx).Execute()

Custodian@index



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
	resp, r, err := apiClient.CustodianAPI.CustodianIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianIndex`: CustodianIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianIndexRequest struct via the builder pattern


### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianShow

> CustodianIndex200Response CustodianShow(ctx, id).Execute()

Custodian@show



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
	id := int32(1) // int32 | Custodian ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianShow`: CustodianIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Custodian ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianShowByUniqueIdentifier

> CustodianIndex200Response CustodianShowByUniqueIdentifier(ctx, id).Execute()

Custodian@showByUniqueIdentifier



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
	id := "c3eddb33-db74-4ea7-961a-778740f17e25" // string | Custodian Unique Identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianShowByUniqueIdentifier(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianShowByUniqueIdentifier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianShowByUniqueIdentifier`: CustodianIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianShowByUniqueIdentifier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Custodian Unique Identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianShowByUniqueIdentifierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianStore

> CustodianStore201Response CustodianStore(ctx).CustodianStoreRequest(custodianStoreRequest).Execute()

Custodian@store



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
	custodianStoreRequest := *openapiclient.NewCustodianStoreRequest() // CustodianStoreRequest | Custodian definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianStore(context.Background()).CustodianStoreRequest(custodianStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianStore`: CustodianStore201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustodianStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **custodianStoreRequest** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition | 

### Return type

[**CustodianStore201Response**](CustodianStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianUpdate

> CustodianStore201Response CustodianUpdate(ctx, id).CustodianStoreRequest(custodianStoreRequest).Execute()

Custodian@update



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
	id := int32(1) // int32 | Custodian ID
	custodianStoreRequest := *openapiclient.NewCustodianStoreRequest() // CustodianStoreRequest | Custodian definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianAPI.CustodianUpdate(context.Background(), id).CustodianStoreRequest(custodianStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianAPI.CustodianUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUpdate`: CustodianStore201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianAPI.CustodianUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Custodian ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **custodianStoreRequest** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition | 

### Return type

[**CustodianStore201Response**](CustodianStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

