# \ProjectHasOrganisationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectHasOrganisationShow**](ProjectHasOrganisationAPI.md#ProjectHasOrganisationShow) | **Get** /api/v1/project-organisations/{projectOrganisationId} | Get details of a project-organisation relationship



## ProjectHasOrganisationShow

> ProjectHasOrganisation ProjectHasOrganisationShow(ctx, projectOrganisationId).Execute()

Get details of a project-organisation relationship

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
	projectOrganisationId := int32(1) // int32 | ID of the project-organisation relationship

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectHasOrganisationAPI.ProjectHasOrganisationShow(context.Background(), projectOrganisationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectHasOrganisationAPI.ProjectHasOrganisationShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectHasOrganisationShow`: ProjectHasOrganisation
	fmt.Fprintf(os.Stdout, "Response from `ProjectHasOrganisationAPI.ProjectHasOrganisationShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectOrganisationId** | **int32** | ID of the project-organisation relationship | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectHasOrganisationShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectHasOrganisation**](ProjectHasOrganisation.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

