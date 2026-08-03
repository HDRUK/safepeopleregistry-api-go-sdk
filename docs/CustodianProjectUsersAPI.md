# \CustodianProjectUsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianProjectUsersIndex**](CustodianProjectUsersAPI.md#CustodianProjectUsersIndex) | **Get** /api/v1/custodian_approvals/{custodianId}/projectUsers | List all project users associated with a custodian
[**CustodianProjectUsersShow**](CustodianProjectUsersAPI.md#CustodianProjectUsersShow) | **Get** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Get custodian approval for a project user
[**CustodianProjectUsersUpdate**](CustodianProjectUsersAPI.md#CustodianProjectUsersUpdate) | **Put** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Update custodian approval for a project user



## CustodianProjectUsersIndex

> CustodianProjectUsersIndex200Response CustodianProjectUsersIndex(ctx, custodianId).Execute()

List all project users associated with a custodian



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
	resp, r, err := apiClient.CustodianProjectUsersAPI.CustodianProjectUsersIndex(context.Background(), custodianId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectUsersAPI.CustodianProjectUsersIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectUsersIndex`: CustodianProjectUsersIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectUsersAPI.CustodianProjectUsersIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectUsersIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianProjectUsersIndex200Response**](CustodianProjectUsersIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianProjectUsersShow

> CustodianProjectUsersShow200Response CustodianProjectUsersShow(ctx, custodianId, projectUserId).Execute()

Get custodian approval for a project user



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
	resp, r, err := apiClient.CustodianProjectUsersAPI.CustodianProjectUsersShow(context.Background(), custodianId, projectUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectUsersAPI.CustodianProjectUsersShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectUsersShow`: CustodianProjectUsersShow200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectUsersAPI.CustodianProjectUsersShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**projectUserId** | **int32** | ID of the project user | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectUsersShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CustodianProjectUsersShow200Response**](CustodianProjectUsersShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianProjectUsersUpdate

> CustodianProjectUsersShow200Response CustodianProjectUsersUpdate(ctx, custodianId, projectUserId).CustodianProjectUsersUpdateRequest(custodianProjectUsersUpdateRequest).Execute()

Update custodian approval for a project user



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
	custodianProjectUsersUpdateRequest := *openapiclient.NewCustodianProjectUsersUpdateRequest() // CustodianProjectUsersUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianProjectUsersAPI.CustodianProjectUsersUpdate(context.Background(), custodianId, projectUserId).CustodianProjectUsersUpdateRequest(custodianProjectUsersUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianProjectUsersAPI.CustodianProjectUsersUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianProjectUsersUpdate`: CustodianProjectUsersShow200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianProjectUsersAPI.CustodianProjectUsersUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 
**projectUserId** | **int32** | ID of the project user | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianProjectUsersUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **custodianProjectUsersUpdateRequest** | [**CustodianProjectUsersUpdateRequest**](CustodianProjectUsersUpdateRequest.md) |  | 

### Return type

[**CustodianProjectUsersShow200Response**](CustodianProjectUsersShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

