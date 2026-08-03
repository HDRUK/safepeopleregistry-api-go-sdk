# \OrganisationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianProjectOrganisationsGetStatus**](OrganisationsAPI.md#CustodianProjectOrganisationsGetStatus) | **Get** /api/v1/custodian_approvals/{custodianId}/project/{projectId}/organisation/{organisationId}/projectOrganisations/status | Get project organisation status
[**OrganisationsCustodianInviteUser**](OrganisationsAPI.md#OrganisationsCustodianInviteUser) | **Post** /api/v1/organisations/{id}/custodian_invite_user | organisations@custodian_invite_user
[**OrganisationsDestroy**](OrganisationsAPI.md#OrganisationsDestroy) | **Delete** /api/v1/organisations/{id} | organisations@destroy
[**OrganisationsGetRegistries**](OrganisationsAPI.md#OrganisationsGetRegistries) | **Get** /api/v1/organisations/{id}/registries | Get all registries for an organisation
[**OrganisationsGetStatus**](OrganisationsAPI.md#OrganisationsGetStatus) | **Get** /api/v1/organisations/{id}/status | Get organisation status
[**OrganisationsIdvt**](OrganisationsAPI.md#OrganisationsIdvt) | **Get** /api/v1/organisations/{id}/idvt | organisations@idvt
[**OrganisationsInviteUser**](OrganisationsAPI.md#OrganisationsInviteUser) | **Post** /api/v1/organisations/{id}/invite_user | organisations@invite_user
[**OrganisationsShow**](OrganisationsAPI.md#OrganisationsShow) | **Get** /api/v1/organisations/{id} | organisations@show
[**OrganisationsStore**](OrganisationsAPI.md#OrganisationsStore) | **Post** /api/v1/organisations | organisations@store
[**OrganisationsUpdate**](OrganisationsAPI.md#OrganisationsUpdate) | **Put** /api/v1/organisations/{id} | organisations@update
[**OrganisationsUpdateApproved**](OrganisationsAPI.md#OrganisationsUpdateApproved) | **Put** /api/v1/organisations/{id}/approved | SuperAdmin update org system_approved flag



## CustodianProjectOrganisationsGetStatus

> CustodianProjectOrganisationsGetStatus200Response CustodianProjectOrganisationsGetStatus(ctx, custodianId, projectId, organisationId).Execute()

Get project organisation status



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
	custodianId := int32(1) // int32 | Custodian ID
	projectId := int32(10) // int32 | Project ID
	organisationId := int32(5) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.CustodianProjectOrganisationsGetStatus(context.Background(), custodianId, projectId, organisationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.CustodianProjectOrganisationsGetStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectOrganisationsGetStatus`: CustodianProjectOrganisationsGetStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.CustodianProjectOrganisationsGetStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | Custodian ID | 
**projectId** | **int32** | Project ID | 
**organisationId** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectOrganisationsGetStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**CustodianProjectOrganisationsGetStatus200Response**](CustodianProjectOrganisationsGetStatus200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsCustodianInviteUser

> AccreditationStoreByRegistryId201Response OrganisationsCustodianInviteUser(ctx, id).OrganisationsInviteUserRequest(organisationsInviteUserRequest).Execute()

organisations@custodian_invite_user



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
	id := int32(1) // int32 | organisations entry ID
	organisationsInviteUserRequest := *openapiclient.NewOrganisationsInviteUserRequest() // OrganisationsInviteUserRequest | Invite definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsCustodianInviteUser(context.Background(), id).OrganisationsInviteUserRequest(organisationsInviteUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsCustodianInviteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsCustodianInviteUser`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsCustodianInviteUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsCustodianInviteUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisationsInviteUserRequest** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition | 

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


## OrganisationsDestroy

> AffiliationDestroy200Response OrganisationsDestroy(ctx, id).Execute()

organisations@destroy



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
	id := int32(1) // int32 | organisations entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsDestroyRequest struct via the builder pattern


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


## OrganisationsGetRegistries

> OrganisationsGetRegistries200Response OrganisationsGetRegistries(ctx, id).ShowPending(showPending).Execute()

Get all registries for an organisation



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
	id := int64(789) // int64 | Organisation ID
	showPending := true // bool | Include users with pending invitations (true/false) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsGetRegistries(context.Background(), id).ShowPending(showPending).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsGetRegistries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsGetRegistries`: OrganisationsGetRegistries200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsGetRegistries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int64** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsGetRegistriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **showPending** | **bool** | Include users with pending invitations (true/false) | 

### Return type

[**OrganisationsGetRegistries200Response**](OrganisationsGetRegistries200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsGetStatus

> CustodianProjectOrganisationsGetStatus200Response OrganisationsGetStatus(ctx, id).Execute()

Get organisation status



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
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsGetStatus(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsGetStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsGetStatus`: CustodianProjectOrganisationsGetStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsGetStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsGetStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianProjectOrganisationsGetStatus200Response**](CustodianProjectOrganisationsGetStatus200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsIdvt

> OrganisationsIdvt200Response OrganisationsIdvt(ctx, id).Execute()

organisations@idvt



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
	id := int32(1) // int32 | organisations entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsIdvt(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsIdvt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsIdvt`: OrganisationsIdvt200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsIdvt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsIdvtRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationsIdvt200Response**](OrganisationsIdvt200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsInviteUser

> AccreditationStoreByRegistryId201Response OrganisationsInviteUser(ctx, id).OrganisationsInviteUserRequest(organisationsInviteUserRequest).Execute()

organisations@invite_user



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
	id := int32(1) // int32 | organisations entry ID
	organisationsInviteUserRequest := *openapiclient.NewOrganisationsInviteUserRequest() // OrganisationsInviteUserRequest | Invite definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsInviteUser(context.Background(), id).OrganisationsInviteUserRequest(organisationsInviteUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsInviteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsInviteUser`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsInviteUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsInviteUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisationsInviteUserRequest** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition | 

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


## OrganisationsShow

> OrganisationIndex200Response OrganisationsShow(ctx, id).Execute()

organisations@show



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
	id := int32(1) // int32 | organisations entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsShow`: OrganisationIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## OrganisationsStore

> IdentityStore201Response OrganisationsStore(ctx).Organisation(organisation).Execute()

organisations@store



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
	organisation := *openapiclient.NewOrganisation() // Organisation | organisations definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsStore(context.Background()).Organisation(organisation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsStore`: IdentityStore201Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organisation** | [**Organisation**](Organisation.md) | organisations definition | 

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


## OrganisationsUpdate

> OrganisationsUpdate200Response OrganisationsUpdate(ctx, id).Organisation(organisation).Execute()

organisations@update



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
	id := int32(1) // int32 | organisations entry ID
	organisation := *openapiclient.NewOrganisation() // Organisation | organisations definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsUpdate(context.Background(), id).Organisation(organisation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsUpdate`: OrganisationsUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisation** | [**Organisation**](Organisation.md) | organisations definition | 

### Return type

[**OrganisationsUpdate200Response**](OrganisationsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsUpdateApproved

> AccreditationStoreByRegistryId201Response OrganisationsUpdateApproved(ctx, id).OrganisationsUpdateApprovedRequest(organisationsUpdateApprovedRequest).Execute()

SuperAdmin update org system_approved flag



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
	id := int32(1) // int32 | organisations entry ID
	organisationsUpdateApprovedRequest := *openapiclient.NewOrganisationsUpdateApprovedRequest() // OrganisationsUpdateApprovedRequest | System approval update definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsUpdateApproved(context.Background(), id).OrganisationsUpdateApprovedRequest(organisationsUpdateApprovedRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsUpdateApproved``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsUpdateApproved`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsUpdateApproved`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsUpdateApprovedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisationsUpdateApprovedRequest** | [**OrganisationsUpdateApprovedRequest**](OrganisationsUpdateApprovedRequest.md) | System approval update definition | 

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

