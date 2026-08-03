# \CustodianProjectOrganisationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianProjectOrganisationsGetWorkflowStates**](CustodianProjectOrganisationsAPI.md#CustodianProjectOrganisationsGetWorkflowStates) | **Get** /api/v1/custodian_approvals/projectOrganisations/getWorkflowStates | Get all workflow states for custodian project organisation approvals
[**CustodianProjectOrganisationsIndex**](CustodianProjectOrganisationsAPI.md#CustodianProjectOrganisationsIndex) | **Get** /api/v1/custodian_approvals/{custodianId}/projectOrganisations | List all project organisations associated with a custodian
[**CustodianProjectOrganisationsShow**](CustodianProjectOrganisationsAPI.md#CustodianProjectOrganisationsShow) | **Get** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Get custodian approval for a project organisation
[**CustodianProjectOrganisationsUpdate**](CustodianProjectOrganisationsAPI.md#CustodianProjectOrganisationsUpdate) | **Put** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Update custodian approval for a project organisation



## CustodianProjectOrganisationsGetWorkflowStates

> CustodianProjectOrganisationsGetWorkflowStates200Response CustodianProjectOrganisationsGetWorkflowStates(ctx).Execute()

Get all workflow states for custodian project organisation approvals



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
	resp, r, err := apiClient.CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsGetWorkflowStates(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsGetWorkflowStates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectOrganisationsGetWorkflowStates`: CustodianProjectOrganisationsGetWorkflowStates200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsGetWorkflowStates`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectOrganisationsGetWorkflowStatesRequest struct via the builder pattern


### Return type

[**CustodianProjectOrganisationsGetWorkflowStates200Response**](CustodianProjectOrganisationsGetWorkflowStates200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianProjectOrganisationsIndex

> CustodianProjectOrganisationsIndex200Response CustodianProjectOrganisationsIndex(ctx, custodianId).Execute()

List all project organisations associated with a custodian



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsIndex(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectOrganisationsIndex`: CustodianProjectOrganisationsIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectOrganisationsIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianProjectOrganisationsIndex200Response**](CustodianProjectOrganisationsIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianProjectOrganisationsShow

> CustodianProjectOrganisationsShow200Response CustodianProjectOrganisationsShow(ctx, custodianId, projectOrganisationId).Execute()

Get custodian approval for a project organisation



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
	projectOrganisationId := int32(56) // int32 | ID of the project organisation

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsShow(context.Background(), custodianId, projectOrganisationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectOrganisationsShow`: CustodianProjectOrganisationsShow200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**projectOrganisationId** | **int32** | ID of the project organisation | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectOrganisationsShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustodianProjectOrganisationsShow200Response**](CustodianProjectOrganisationsShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianProjectOrganisationsUpdate

> CustodianProjectOrganisationsShow200Response CustodianProjectOrganisationsUpdate(ctx, custodianId, projectOrganisationId).CustodianProjectOrganisationsUpdateRequest(custodianProjectOrganisationsUpdateRequest).Execute()

Update custodian approval for a project organisation



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
	projectOrganisationId := int32(56) // int32 | ID of the project organisation
	custodianProjectOrganisationsUpdateRequest := *openapiclient.NewCustodianProjectOrganisationsUpdateRequest() // CustodianProjectOrganisationsUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsUpdate(context.Background(), custodianId, projectOrganisationId).CustodianProjectOrganisationsUpdateRequest(custodianProjectOrganisationsUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectOrganisationsUpdate`: CustodianProjectOrganisationsShow200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectOrganisationsAPI.CustodianProjectOrganisationsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**projectOrganisationId** | **int32** | ID of the project organisation | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectOrganisationsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **custodianProjectOrganisationsUpdateRequest** | [**CustodianProjectOrganisationsUpdateRequest**](CustodianProjectOrganisationsUpdateRequest.md) |  | 

### Return type

[**CustodianProjectOrganisationsShow200Response**](CustodianProjectOrganisationsShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

