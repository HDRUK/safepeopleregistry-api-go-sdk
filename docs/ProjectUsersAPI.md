# \ProjectUsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectUsersBulkInviteProjectUsers**](ProjectUsersAPI.md#ProjectUsersBulkInviteProjectUsers) | **Post** /api/v1/project_users/bulk | Bulk invite Project Users



## ProjectUsersBulkInviteProjectUsers

> ProjectUsersBulkInviteProjectUsers(ctx).ProjectUsersBulkInviteProjectUsersRequest(projectUsersBulkInviteProjectUsersRequest).Execute()

Bulk invite Project Users



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
	projectUsersBulkInviteProjectUsersRequest := *openapiclient.NewProjectUsersBulkInviteProjectUsersRequest(int32(1), []openapiclient.ProjectUsersBulkInviteProjectUsersRequestUsersInner{*openapiclient.NewProjectUsersBulkInviteProjectUsersRequestUsersInner()}) // ProjectUsersBulkInviteProjectUsersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectUsersAPI.ProjectUsersBulkInviteProjectUsers(context.Background()).ProjectUsersBulkInviteProjectUsersRequest(projectUsersBulkInviteProjectUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectUsersAPI.ProjectUsersBulkInviteProjectUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProjectUsersBulkInviteProjectUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUsersBulkInviteProjectUsersRequest** | [**ProjectUsersBulkInviteProjectUsersRequest**](ProjectUsersBulkInviteProjectUsersRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

