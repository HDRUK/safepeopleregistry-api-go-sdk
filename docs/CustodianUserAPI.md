# \CustodianUserAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianUserBulkStore**](CustodianUserAPI.md#CustodianUserBulkStore) | **Post** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries



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

