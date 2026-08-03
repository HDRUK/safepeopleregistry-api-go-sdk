# \EndorsementsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EndorsementsStore**](EndorsementsAPI.md#EndorsementsStore) | **Post** /api/v1/endorsements | Endorsements@store



## EndorsementsStore

> EndorsementsStore201Response EndorsementsStore(ctx).EndorsementsStoreRequest(endorsementsStoreRequest).Execute()

Endorsements@store



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
	endorsementsStoreRequest := *openapiclient.NewEndorsementsStoreRequest() // EndorsementsStoreRequest | Endorsements definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EndorsementsAPI.EndorsementsStore(context.Background()).EndorsementsStoreRequest(endorsementsStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndorsementsAPI.EndorsementsStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EndorsementsStore`: EndorsementsStore201Response
	fmt.Fprintf(os.Stdout, "Response from `EndorsementsAPI.EndorsementsStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEndorsementsStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **endorsementsStoreRequest** | [**EndorsementsStoreRequest**](EndorsementsStoreRequest.md) | Endorsements definition | 

### Return type

[**EndorsementsStore201Response**](EndorsementsStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

