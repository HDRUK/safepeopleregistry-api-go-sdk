# \CustodiansAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodiansCreateCustodianValidationChecks**](CustodiansAPI.md#CustodiansCreateCustodianValidationChecks) | **Post** /api/v1/custodians/{custodianId}/validation_checks | Assign a validation check to a custodian
[**CustodiansGetCustodianUsers**](CustodiansAPI.md#CustodiansGetCustodianUsers) | **Get** /api/v1/custodians/{custodianId}/custodian_users | Get list of people for a custodian
[**CustodiansGetCustodianValidationChecks**](CustodiansAPI.md#CustodiansGetCustodianValidationChecks) | **Get** /api/v1/custodians/{custodianId}/validation_checks | Get validation checks assigned to a custodian
[**CustodiansGetOrganisationUsers**](CustodiansAPI.md#CustodiansGetOrganisationUsers) | **Get** /api/v1/custodians/{custodianId}/organisations/{organisationId}/users | Get list of people for organisation
[**CustodiansGetRules**](CustodiansAPI.md#CustodiansGetRules) | **Get** /api/v1/custodians/{id}/rules | Get rules for a specific custodian
[**CustodiansGetStatusesUsers**](CustodiansAPI.md#CustodiansGetStatusesUsers) | **Get** /api/v1/custodians/{custodianId}/projectUsers/{projectUserId}/statuses | Get statuses for a user in a project/organisation/custodian



## CustodiansCreateCustodianValidationChecks

> ValidationCheck CustodiansCreateCustodianValidationChecks(ctx, custodianId).CustodiansCreateCustodianValidationChecksRequest(custodiansCreateCustodianValidationChecksRequest).Execute()

Assign a validation check to a custodian



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
	custodiansCreateCustodianValidationChecksRequest := *openapiclient.NewCustodiansCreateCustodianValidationChecksRequest("Check format", "format") // CustodiansCreateCustodianValidationChecksRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodiansAPI.CustodiansCreateCustodianValidationChecks(context.Background(), custodianId).CustodiansCreateCustodianValidationChecksRequest(custodiansCreateCustodianValidationChecksRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansCreateCustodianValidationChecks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansCreateCustodianValidationChecks`: ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansCreateCustodianValidationChecks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansCreateCustodianValidationChecksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **custodiansCreateCustodianValidationChecksRequest** | [**CustodiansCreateCustodianValidationChecksRequest**](CustodiansCreateCustodianValidationChecksRequest.md) |  | 

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodiansGetCustodianUsers

> CustodiansGetCustodianUsers200Response CustodiansGetCustodianUsers(ctx, custodianId).Execute()

Get list of people for a custodian



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
	resp, r, err := apiClient.CustodiansAPI.CustodiansGetCustodianUsers(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansGetCustodianUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansGetCustodianUsers`: CustodiansGetCustodianUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansGetCustodianUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansGetCustodianUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodiansGetCustodianUsers200Response**](CustodiansGetCustodianUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodiansGetCustodianValidationChecks

> []ValidationCheck CustodiansGetCustodianValidationChecks(ctx, custodianId).Execute()

Get validation checks assigned to a custodian



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
	resp, r, err := apiClient.CustodiansAPI.CustodiansGetCustodianValidationChecks(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansGetCustodianValidationChecks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansGetCustodianValidationChecks`: []ValidationCheck
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansGetCustodianValidationChecks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansGetCustodianValidationChecksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodiansGetOrganisationUsers

> CustodiansGetOrganisationUsers200Response CustodiansGetOrganisationUsers(ctx, custodianId, organisationId).Execute()

Get list of people for organisation



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
	organisationId := int32(56) // int32 | ID of the organisation

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodiansAPI.CustodiansGetOrganisationUsers(context.Background(), custodianId, organisationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansGetOrganisationUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansGetOrganisationUsers`: CustodiansGetOrganisationUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansGetOrganisationUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**organisationId** | **int32** | ID of the organisation | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansGetOrganisationUsersRequest struct via the builder pattern


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


## CustodiansGetRules

> CustodiansGetRules200Response CustodiansGetRules(ctx, id).Execute()

Get rules for a specific custodian



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
	id := int32(56) // int32 | ID of the custodian

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodiansAPI.CustodiansGetRules(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansGetRules``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansGetRules`: CustodiansGetRules200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansGetRules`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansGetRulesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodiansGetRules200Response**](CustodiansGetRules200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodiansGetStatusesUsers

> CustodiansGetOrganisationUsers200Response CustodiansGetStatusesUsers(ctx, custodianId, projectUserId).Execute()

Get statuses for a user in a project/organisation/custodian



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
	projectUserId := int32(56) // int32 | ID of the project user

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodiansAPI.CustodiansGetStatusesUsers(context.Background(), custodianId, projectUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodiansAPI.CustodiansGetStatusesUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodiansGetStatusesUsers`: CustodiansGetOrganisationUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodiansAPI.CustodiansGetStatusesUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**projectUserId** | **int32** | ID of the project user | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodiansGetStatusesUsersRequest struct via the builder pattern


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

