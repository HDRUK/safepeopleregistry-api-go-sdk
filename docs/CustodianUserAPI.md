# \CustodianUserAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianUserBulkStore**](CustodianUserAPI.md#CustodianUserBulkStore) | **Post** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries
[**CustodianUserDestroy**](CustodianUserAPI.md#CustodianUserDestroy) | **Delete** /api/v1/custodian_users/{id} | CustodianUser@destroy
[**CustodianUserShow**](CustodianUserAPI.md#CustodianUserShow) | **Get** /api/v1/custodian_users/{id} | CustodianUser@show
[**CustodianUserStore**](CustodianUserAPI.md#CustodianUserStore) | **Post** /api/v1/custodian_users | CustodianUser@store
[**CustodianUserUpdate**](CustodianUserAPI.md#CustodianUserUpdate) | **Put** /api/v1/custodian_users | CustodianUser@update



## CustodianUserBulkStore

> CustodianUserBulkStore201Response CustodianUserBulkStore(ctx).CustodianUserBulkStoreRequest(custodianUserBulkStoreRequest).Execute()

Create multiple CustodianUser entries



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
	custodianUserBulkStoreRequest := *openapiclient.NewCustodianUserBulkStoreRequest() // CustodianUserBulkStoreRequest | Array of CustodianUser definitions

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianUserAPI.CustodianUserBulkStore(context.Background()).CustodianUserBulkStoreRequest(custodianUserBulkStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUserAPI.CustodianUserBulkStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUserBulkStore`: CustodianUserBulkStore201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUserAPI.CustodianUserBulkStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUserBulkStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **custodianUserBulkStoreRequest** | [**CustodianUserBulkStoreRequest**](CustodianUserBulkStoreRequest.md) | Array of CustodianUser definitions | 

### Return type

[**CustodianUserBulkStore201Response**](CustodianUserBulkStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianUserDestroy

> AffiliationDestroy200Response CustodianUserDestroy(ctx, id).Execute()

CustodianUser@destroy



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
	id := int32(1) // int32 | CustodianUser entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianUserAPI.CustodianUserDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUserAPI.CustodianUserDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUserDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUserAPI.CustodianUserDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | CustodianUser entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUserDestroyRequest struct via the builder pattern


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


## CustodianUserShow

> CustodianUserShow200Response CustodianUserShow(ctx, id).Execute()

CustodianUser@show



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
	id := int32(1) // int32 | CustodianUser entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianUserAPI.CustodianUserShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUserAPI.CustodianUserShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUserShow`: CustodianUserShow200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUserAPI.CustodianUserShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | CustodianUser entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUserShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianUserShow200Response**](CustodianUserShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianUserStore

> AccreditationStoreByRegistryId201Response CustodianUserStore(ctx).CustodianUser(custodianUser).Execute()

CustodianUser@store



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
	custodianUser := *openapiclient.NewCustodianUser() // CustodianUser | CustodianUser definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianUserAPI.CustodianUserStore(context.Background()).CustodianUser(custodianUser).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUserAPI.CustodianUserStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUserStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUserAPI.CustodianUserStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUserStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **custodianUser** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition | 

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


## CustodianUserUpdate

> CustodianUserUpdate201Response CustodianUserUpdate(ctx).CustodianUser(custodianUser).Execute()

CustodianUser@update



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
	custodianUser := *openapiclient.NewCustodianUser() // CustodianUser | CustodianUser definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianUserAPI.CustodianUserUpdate(context.Background()).CustodianUser(custodianUser).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUserAPI.CustodianUserUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUserUpdate`: CustodianUserUpdate201Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUserAPI.CustodianUserUpdate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUserUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **custodianUser** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition | 

### Return type

[**CustodianUserUpdate201Response**](CustodianUserUpdate201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

