# \PendingInvitesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PendingInvitesIndex**](PendingInvitesAPI.md#PendingInvitesIndex) | **Get** /api/v1/pending_invites | PendingInvite@index



## PendingInvitesIndex

> PendingInvitesIndex200Response PendingInvitesIndex(ctx).Execute()

PendingInvite@index



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
	resp, r, err := apiClient.PendingInvitesAPI.PendingInvitesIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingInvitesAPI.PendingInvitesIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PendingInvitesIndex`: PendingInvitesIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `PendingInvitesAPI.PendingInvitesIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPendingInvitesIndexRequest struct via the builder pattern


### Return type

[**PendingInvitesIndex200Response**](PendingInvitesIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

