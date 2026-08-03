# \ProjectAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectDestroy**](ProjectAPI.md#ProjectDestroy) | **Delete** /api/v1/projects/{id} | Project@destroy
[**ProjectGetAllUsersFlagProjectByUserId**](ProjectAPI.md#ProjectGetAllUsersFlagProjectByUserId) | **Get** /api/v1/projects/{projectId}/all_users/{userId} | Get all users by projectID and userID
[**ProjectGetProjectByIdAndOrganisationId**](ProjectAPI.md#ProjectGetProjectByIdAndOrganisationId) | **Get** /api/v1/projects/{projectId}/organisations/{organisationId} | Get project details by projectID and organisationID
[**ProjectGetProjectByIdAndUserId**](ProjectAPI.md#ProjectGetProjectByIdAndUserId) | **Get** /api/v1/projects/{projectId}/users/{userId} | Get project details by projectID and userID
[**ProjectGetProjectUsers**](ProjectAPI.md#ProjectGetProjectUsers) | **Get** /api/v1/projects/{id}/users | Project@getProjectUsers
[**ProjectGetProjectUsersByOrganisationId**](ProjectAPI.md#ProjectGetProjectUsersByOrganisationId) | **Get** /api/v1/projects/{projectId}/organisations/{organisationId}/users | Get all users by projectID and organisationID
[**ProjectIndex**](ProjectAPI.md#ProjectIndex) | **Get** /api/v1/projects | Project@index
[**ProjectMakePrimaryContact**](ProjectAPI.md#ProjectMakePrimaryContact) | **Put** /api/v1/projects/{id}/users/{registryId}/primary_contact | Project@edit
[**ProjectShow**](ProjectAPI.md#ProjectShow) | **Get** /api/v1/projects/{id} | Project@show
[**ProjectStore**](ProjectAPI.md#ProjectStore) | **Post** /api/v1/projects | Project@store
[**ProjectUpdate**](ProjectAPI.md#ProjectUpdate) | **Put** /api/v1/projects/{id} | Project@update
[**ProjectUpdateAllProjectUsers**](ProjectAPI.md#ProjectUpdateAllProjectUsers) | **Put** /api/v1/projects/{id}/all_users | Project@updateAllProjectUsers



## ProjectDestroy

> AffiliationDestroy200Response ProjectDestroy(ctx, id).Execute()

Project@destroy



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
	id := int32(1) // int32 | Project entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectDestroyRequest struct via the builder pattern


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


## ProjectGetAllUsersFlagProjectByUserId

> ProjectGetAllUsersFlagProjectByUserId200Response ProjectGetAllUsersFlagProjectByUserId(ctx, userId, projectId).Execute()

Get all users by projectID and userID



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
	userId := int32(56) // int32 | ID of the user
	projectId := int32(56) // int32 | ID of the project

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectGetAllUsersFlagProjectByUserId(context.Background(), userId, projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectGetAllUsersFlagProjectByUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectGetAllUsersFlagProjectByUserId`: ProjectGetAllUsersFlagProjectByUserId200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectGetAllUsersFlagProjectByUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | ID of the user | 
**projectId** | **int32** | ID of the project | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectGetAllUsersFlagProjectByUserIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProjectGetAllUsersFlagProjectByUserId200Response**](ProjectGetAllUsersFlagProjectByUserId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectGetProjectByIdAndOrganisationId

> CustodiansGetOrganisationUsers200Response ProjectGetProjectByIdAndOrganisationId(ctx, organisationId, projectId).Execute()

Get project details by projectID and organisationID



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
	organisationId := int32(56) // int32 | ID of the organisation
	projectId := int32(56) // int32 | ID of the project

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectGetProjectByIdAndOrganisationId(context.Background(), organisationId, projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectGetProjectByIdAndOrganisationId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectGetProjectByIdAndOrganisationId`: CustodiansGetOrganisationUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectGetProjectByIdAndOrganisationId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organisationId** | **int32** | ID of the organisation | 
**projectId** | **int32** | ID of the project | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectGetProjectByIdAndOrganisationIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustodiansGetOrganisationUsers200Response**](CustodiansGetOrganisationUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectGetProjectByIdAndUserId

> ProjectGetProjectByIdAndUserId200Response ProjectGetProjectByIdAndUserId(ctx, userId, projectId).Execute()

Get project details by projectID and userID



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
	userId := int32(56) // int32 | ID of the user
	projectId := int32(56) // int32 | ID of the project

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectGetProjectByIdAndUserId(context.Background(), userId, projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectGetProjectByIdAndUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectGetProjectByIdAndUserId`: ProjectGetProjectByIdAndUserId200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectGetProjectByIdAndUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | ID of the user | 
**projectId** | **int32** | ID of the project | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectGetProjectByIdAndUserIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProjectGetProjectByIdAndUserId200Response**](ProjectGetProjectByIdAndUserId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectGetProjectUsers

> ProjectGetProjectUsers200Response ProjectGetProjectUsers(ctx, id).Execute()

Project@getProjectUsers



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
	id := int32(1) // int32 | Project entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectGetProjectUsers(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectGetProjectUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectGetProjectUsers`: ProjectGetProjectUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectGetProjectUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectGetProjectUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectGetProjectUsers200Response**](ProjectGetProjectUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectGetProjectUsersByOrganisationId

> CustodiansGetOrganisationUsers200Response ProjectGetProjectUsersByOrganisationId(ctx, organisationId, projectId).Execute()

Get all users by projectID and organisationID



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
	organisationId := int32(56) // int32 | ID of the organisation
	projectId := int32(56) // int32 | ID of the project

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectGetProjectUsersByOrganisationId(context.Background(), organisationId, projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectGetProjectUsersByOrganisationId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectGetProjectUsersByOrganisationId`: CustodiansGetOrganisationUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectGetProjectUsersByOrganisationId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organisationId** | **int32** | ID of the organisation | 
**projectId** | **int32** | ID of the project | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectGetProjectUsersByOrganisationIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustodiansGetOrganisationUsers200Response**](CustodiansGetOrganisationUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectIndex

> ProjectIndex200Response ProjectIndex(ctx).Execute()

Project@index



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
	resp, r, err := apiClient.ProjectAPI.ProjectIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectIndex`: ProjectIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiProjectIndexRequest struct via the builder pattern


### Return type

[**ProjectIndex200Response**](ProjectIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectMakePrimaryContact

> ProjectMakePrimaryContact200Response ProjectMakePrimaryContact(ctx, id, registryId).ProjectMakePrimaryContactRequest(projectMakePrimaryContactRequest).Execute()

Project@edit



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
	id := int32(1) // int32 | Project entry ID
	registryId := int32(1) // int32 | Registry ID
	projectMakePrimaryContactRequest := *openapiclient.NewProjectMakePrimaryContactRequest() // ProjectMakePrimaryContactRequest | Project definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectMakePrimaryContact(context.Background(), id, registryId).ProjectMakePrimaryContactRequest(projectMakePrimaryContactRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectMakePrimaryContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectMakePrimaryContact`: ProjectMakePrimaryContact200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectMakePrimaryContact`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 
**registryId** | **int32** | Registry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectMakePrimaryContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **projectMakePrimaryContactRequest** | [**ProjectMakePrimaryContactRequest**](ProjectMakePrimaryContactRequest.md) | Project definition | 

### Return type

[**ProjectMakePrimaryContact200Response**](ProjectMakePrimaryContact200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectShow

> ProjectIndex200Response ProjectShow(ctx, id).Execute()

Project@show



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
	id := int32(1) // int32 | Project entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectShow`: ProjectIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectIndex200Response**](ProjectIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectStore

> AccreditationStoreByRegistryId201Response ProjectStore(ctx).ProjectStoreRequest(projectStoreRequest).Execute()

Project@store



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
	projectStoreRequest := *openapiclient.NewProjectStoreRequest() // ProjectStoreRequest | Project definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectStore(context.Background()).ProjectStoreRequest(projectStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProjectStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectStoreRequest** | [**ProjectStoreRequest**](ProjectStoreRequest.md) | Project definition | 

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectUpdate

> ProjectUpdate200Response ProjectUpdate(ctx, id).ProjectIndex200ResponseData(projectIndex200ResponseData).Execute()

Project@update



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
	id := int32(1) // int32 | Project entry ID
	projectIndex200ResponseData := *openapiclient.NewProjectIndex200ResponseData() // ProjectIndex200ResponseData | Project definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectUpdate(context.Background(), id).ProjectIndex200ResponseData(projectIndex200ResponseData).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectUpdate`: ProjectUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectIndex200ResponseData** | [**ProjectIndex200ResponseData**](ProjectIndex200ResponseData.md) | Project definition | 

### Return type

[**ProjectUpdate200Response**](ProjectUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectUpdateAllProjectUsers

> ONSSubmissionReceiveCSV200Response ProjectUpdateAllProjectUsers(ctx, id).ProjectUpdateAllProjectUsersRequest(projectUpdateAllProjectUsersRequest).Execute()

Project@updateAllProjectUsers



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
	id := int32(1) // int32 | Project entry ID
	projectUpdateAllProjectUsersRequest := *openapiclient.NewProjectUpdateAllProjectUsersRequest() // ProjectUpdateAllProjectUsersRequest | Project definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectAPI.ProjectUpdateAllProjectUsers(context.Background(), id).ProjectUpdateAllProjectUsersRequest(projectUpdateAllProjectUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectAPI.ProjectUpdateAllProjectUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectUpdateAllProjectUsers`: ONSSubmissionReceiveCSV200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectAPI.ProjectUpdateAllProjectUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Project entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectUpdateAllProjectUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUpdateAllProjectUsersRequest** | [**ProjectUpdateAllProjectUsersRequest**](ProjectUpdateAllProjectUsersRequest.md) | Project definition | 

### Return type

[**ONSSubmissionReceiveCSV200Response**](ONSSubmissionReceiveCSV200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

