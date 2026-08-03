# \ActionLogsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ActionLogsGetEntityActionLog**](ActionLogsAPI.md#ActionLogsGetEntityActionLog) | **Get** /api/v1/{entity}/{id}/action_log | Get Action Logs for an Entity
[**ActionLogsUpdate**](ActionLogsAPI.md#ActionLogsUpdate) | **Put** /api/v1/action_logs/{id} | Update an Action Log



## ActionLogsGetEntityActionLog

> ActionLogsGetEntityActionLog200Response ActionLogsGetEntityActionLog(ctx, entity, id).Execute()

Get Action Logs for an Entity



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
	entity := "entity_example" // string | The entity type (e.g., users, organisations)
	id := int32(56) // int32 | The ID of the entity

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActionLogsAPI.ActionLogsGetEntityActionLog(context.Background(), entity, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActionLogsAPI.ActionLogsGetEntityActionLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActionLogsGetEntityActionLog`: ActionLogsGetEntityActionLog200Response
	fmt.Fprintf(os.Stdout, "Response from `ActionLogsAPI.ActionLogsGetEntityActionLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**entity** | **string** | The entity type (e.g., users, organisations) | 
**id** | **int32** | The ID of the entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiActionLogsGetEntityActionLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ActionLogsGetEntityActionLog200Response**](ActionLogsGetEntityActionLog200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ActionLogsUpdate

> ActionLogsUpdate200Response ActionLogsUpdate(ctx, id).Complete(complete).Incomplete(incomplete).Execute()

Update an Action Log



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
	id := int32(56) // int32 | ID of the action log
	complete := true // bool | Mark as complete (optional)
	incomplete := true // bool | Mark as incomplete (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActionLogsAPI.ActionLogsUpdate(context.Background(), id).Complete(complete).Incomplete(incomplete).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActionLogsAPI.ActionLogsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ActionLogsUpdate`: ActionLogsUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ActionLogsAPI.ActionLogsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the action log | 

### Other Parameters

Other parameters are passed through a pointer to a apiActionLogsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **complete** | **bool** | Mark as complete | 
 **incomplete** | **bool** | Mark as incomplete | 

### Return type

[**ActionLogsUpdate200Response**](ActionLogsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

