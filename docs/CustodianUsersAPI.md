# \CustodianUsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianUsersIndex**](CustodianUsersAPI.md#CustodianUsersIndex) | **Get** /api/v1/custodian_users | Return a list of Custodian Users



## CustodianUsersIndex

> CustodianUsersIndex200Response CustodianUsersIndex(ctx).Execute()

Return a list of Custodian Users



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
	resp, r, err := apiClient.CustodianUsersAPI.CustodianUsersIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianUsersAPI.CustodianUsersIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianUsersIndex`: CustodianUsersIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianUsersAPI.CustodianUsersIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianUsersIndexRequest struct via the builder pattern


### Return type

[**CustodianUsersIndex200Response**](CustodianUsersIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

