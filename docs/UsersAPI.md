# \UsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UsersStore**](UsersAPI.md#UsersStore) | **Post** /api/v1/users | Users@store



## UsersStore

> UsersStore201Response UsersStore(ctx).UsersStoreRequest(usersStoreRequest).Execute()

Users@store



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
	usersStoreRequest := *openapiclient.NewUsersStoreRequest() // UsersStoreRequest | User definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UsersStore(context.Background()).UsersStoreRequest(usersStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UsersStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersStore`: UsersStore201Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UsersStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUsersStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **usersStoreRequest** | [**UsersStoreRequest**](UsersStoreRequest.md) | User definition | 

### Return type

[**UsersStore201Response**](UsersStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

