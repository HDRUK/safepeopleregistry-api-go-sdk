# \ProjectUserAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectUserShow**](ProjectUserAPI.md#ProjectUserShow) | **Get** /api/v1/project_users/{id} | Get project user details



## ProjectUserShow

> CustodianProjectUsersShow200Response ProjectUserShow(ctx, id).Execute()

Get project user details



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
	id := int32(56) // int32 | ID of the project user

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectUserAPI.ProjectUserShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectUserAPI.ProjectUserShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectUserShow`: CustodianProjectUsersShow200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectUserAPI.ProjectUserShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the project user | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectUserShowRequest struct via the builder pattern


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

