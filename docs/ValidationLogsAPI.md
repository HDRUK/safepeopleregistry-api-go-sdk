# \ValidationLogsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ValidationLogsGetCustodianOrganisationValidationLogs**](ValidationLogsAPI.md#ValidationLogsGetCustodianOrganisationValidationLogs) | **Get** /api/v1/custodians/{custodianId}/organisation/{organisationId}/validation_logs | Get Validation Logs for Custodian and Organisation
[**ValidationLogsGetCustodianProjectUserValidationLogs**](ValidationLogsAPI.md#ValidationLogsGetCustodianProjectUserValidationLogs) | **Get** /api/v1/custodians/{custodianId}/projects/{projectId}/registries/{registryId}/validation_logs | Get Validation Logs for Custodian, Project, and Registry
[**ValidationLogsUpdate**](ValidationLogsAPI.md#ValidationLogsUpdate) | **Put** /api/v1/validation_logs/{id} | Update a Validation Log
[**ValidationLogsUpdateCustodianValidationLogs**](ValidationLogsAPI.md#ValidationLogsUpdateCustodianValidationLogs) | **Put** /api/v1/custodians/{custodianId}/validation_Logs | Enable or Disable All Validation Logs for a Custodian Across Projects/Registries



## ValidationLogsGetCustodianOrganisationValidationLogs

> ValidationLogsGetCustodianProjectUserValidationLogs200Response ValidationLogsGetCustodianOrganisationValidationLogs(ctx, custodianId, organisationId).ShowDisabled(showDisabled).Execute()

Get Validation Logs for Custodian and Organisation



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
	custodianId := int32(56) // int32 | The ID of the custodian entity
	organisationId := int32(56) // int32 | The ID of the organisation entity
	showDisabled := true // bool | Whether to include disabled validation logs (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogsAPI.ValidationLogsGetCustodianOrganisationValidationLogs(context.Background(), custodianId, organisationId).ShowDisabled(showDisabled).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogsAPI.ValidationLogsGetCustodianOrganisationValidationLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogsGetCustodianOrganisationValidationLogs`: ValidationLogsGetCustodianProjectUserValidationLogs200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogsAPI.ValidationLogsGetCustodianOrganisationValidationLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian entity | 
**organisationId** | **int32** | The ID of the organisation entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogsGetCustodianOrganisationValidationLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **showDisabled** | **bool** | Whether to include disabled validation logs | 

### Return type

[**ValidationLogsGetCustodianProjectUserValidationLogs200Response**](ValidationLogsGetCustodianProjectUserValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogsGetCustodianProjectUserValidationLogs

> ValidationLogsGetCustodianProjectUserValidationLogs200Response ValidationLogsGetCustodianProjectUserValidationLogs(ctx, custodianId, projectId, registryId).Execute()

Get Validation Logs for Custodian, Project, and Registry



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
	custodianId := int32(56) // int32 | The ID of the custodian entity
	projectId := int32(56) // int32 | The ID of the project entity
	registryId := int32(56) // int32 | The ID of the registry entity

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogsAPI.ValidationLogsGetCustodianProjectUserValidationLogs(context.Background(), custodianId, projectId, registryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogsAPI.ValidationLogsGetCustodianProjectUserValidationLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogsGetCustodianProjectUserValidationLogs`: ValidationLogsGetCustodianProjectUserValidationLogs200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogsAPI.ValidationLogsGetCustodianProjectUserValidationLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian entity | 
**projectId** | **int32** | The ID of the project entity | 
**registryId** | **int32** | The ID of the registry entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogsGetCustodianProjectUserValidationLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**ValidationLogsGetCustodianProjectUserValidationLogs200Response**](ValidationLogsGetCustodianProjectUserValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogsUpdate

> ValidationLogsUpdate200Response ValidationLogsUpdate(ctx, id).ValidationLogsUpdateRequest(validationLogsUpdateRequest).Execute()

Update a Validation Log



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
	id := int32(56) // int32 | The ID of the validation log entry
	validationLogsUpdateRequest := *openapiclient.NewValidationLogsUpdateRequest() // ValidationLogsUpdateRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogsAPI.ValidationLogsUpdate(context.Background(), id).ValidationLogsUpdateRequest(validationLogsUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogsAPI.ValidationLogsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogsUpdate`: ValidationLogsUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogsAPI.ValidationLogsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the validation log entry | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **validationLogsUpdateRequest** | [**ValidationLogsUpdateRequest**](ValidationLogsUpdateRequest.md) |  | 

### Return type

[**ValidationLogsUpdate200Response**](ValidationLogsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidationLogsUpdateCustodianValidationLogs

> ValidationLogsUpdateCustodianValidationLogs200Response ValidationLogsUpdateCustodianValidationLogs(ctx, custodianId).ValidationLogsUpdateCustodianValidationLogsRequest(validationLogsUpdateCustodianValidationLogsRequest).Execute()

Enable or Disable All Validation Logs for a Custodian Across Projects/Registries



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
	custodianId := int32(56) // int32 | The ID of the custodian entity
	validationLogsUpdateCustodianValidationLogsRequest := *openapiclient.NewValidationLogsUpdateCustodianValidationLogsRequest(true) // ValidationLogsUpdateCustodianValidationLogsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationLogsAPI.ValidationLogsUpdateCustodianValidationLogs(context.Background(), custodianId).ValidationLogsUpdateCustodianValidationLogsRequest(validationLogsUpdateCustodianValidationLogsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationLogsAPI.ValidationLogsUpdateCustodianValidationLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidationLogsUpdateCustodianValidationLogs`: ValidationLogsUpdateCustodianValidationLogs200Response
	fmt.Fprintf(os.Stdout, "Response from `ValidationLogsAPI.ValidationLogsUpdateCustodianValidationLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | The ID of the custodian entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidationLogsUpdateCustodianValidationLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **validationLogsUpdateCustodianValidationLogsRequest** | [**ValidationLogsUpdateCustodianValidationLogsRequest**](ValidationLogsUpdateCustodianValidationLogsRequest.md) |  | 

### Return type

[**ValidationLogsUpdateCustodianValidationLogs200Response**](ValidationLogsUpdateCustodianValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

