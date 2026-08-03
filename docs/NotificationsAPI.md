# \NotificationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**NotificationsGetNotificationCounts**](NotificationsAPI.md#NotificationsGetNotificationCounts) | **Get** /api/v1/users/{id}/notifications/count | Get notification counts for a specific user
[**NotificationsGetUserNotifications**](NotificationsAPI.md#NotificationsGetUserNotifications) | **Get** /api/v1/users/{id}/notifications | Get notifications for a specific user
[**NotificationsMarkUserNotificationAsRead**](NotificationsAPI.md#NotificationsMarkUserNotificationAsRead) | **Patch** /api/v1/users/{id}/notifications/{notificationId}/read | Mark a specific notification as read
[**NotificationsMarkUserNotificationAsUnread**](NotificationsAPI.md#NotificationsMarkUserNotificationAsUnread) | **Patch** /api/v1/users/{id}/notifications/{notificationId}/unread | Mark a specific notification as unread
[**NotificationsMarkUserNotificationsAsRead**](NotificationsAPI.md#NotificationsMarkUserNotificationsAsRead) | **Patch** /api/v1/users/{id}/notifications/read | Mark all notifications as read for a specific user



## NotificationsGetNotificationCounts

> NotificationsGetNotificationCounts200Response NotificationsGetNotificationCounts(ctx, id).Execute()

Get notification counts for a specific user



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
	id := int32(56) // int32 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAPI.NotificationsGetNotificationCounts(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAPI.NotificationsGetNotificationCounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `NotificationsGetNotificationCounts`: NotificationsGetNotificationCounts200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAPI.NotificationsGetNotificationCounts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiNotificationsGetNotificationCountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NotificationsGetNotificationCounts200Response**](NotificationsGetNotificationCounts200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## NotificationsGetUserNotifications

> NotificationsGetUserNotifications200Response NotificationsGetUserNotifications(ctx, id).Status(status).Execute()

Get notifications for a specific user



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
	id := int32(1) // int32 | User ID
	status := "unread" // string | Filter notifications by status (read/unread) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAPI.NotificationsGetUserNotifications(context.Background(), id).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAPI.NotificationsGetUserNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `NotificationsGetUserNotifications`: NotificationsGetUserNotifications200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAPI.NotificationsGetUserNotifications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiNotificationsGetUserNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** | Filter notifications by status (read/unread) | 

### Return type

[**NotificationsGetUserNotifications200Response**](NotificationsGetUserNotifications200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## NotificationsMarkUserNotificationAsRead

> NotificationsMarkUserNotificationAsRead200Response NotificationsMarkUserNotificationAsRead(ctx, id, notificationId).Execute()

Mark a specific notification as read

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
	id := int32(1) // int32 | User ID
	notificationId := "abc95e84-0ebd-45d2-8129-9bf7ed043433" // string | Notification ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAPI.NotificationsMarkUserNotificationAsRead(context.Background(), id, notificationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAPI.NotificationsMarkUserNotificationAsRead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `NotificationsMarkUserNotificationAsRead`: NotificationsMarkUserNotificationAsRead200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAPI.NotificationsMarkUserNotificationAsRead`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 
**notificationId** | **string** | Notification ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiNotificationsMarkUserNotificationAsReadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**NotificationsMarkUserNotificationAsRead200Response**](NotificationsMarkUserNotificationAsRead200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## NotificationsMarkUserNotificationAsUnread

> NotificationsMarkUserNotificationAsUnread(ctx, id, notificationId).Execute()

Mark a specific notification as unread

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
	id := int32(1) // int32 | User ID
	notificationId := "abc95e84-0ebd-45d2-8129-9bf7ed043433" // string | Notification ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NotificationsAPI.NotificationsMarkUserNotificationAsUnread(context.Background(), id, notificationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAPI.NotificationsMarkUserNotificationAsUnread``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 
**notificationId** | **string** | Notification ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiNotificationsMarkUserNotificationAsUnreadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## NotificationsMarkUserNotificationsAsRead

> NotificationsMarkUserNotificationsAsRead200Response NotificationsMarkUserNotificationsAsRead(ctx, id).Execute()

Mark all notifications as read for a specific user

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
	id := int32(1) // int32 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAPI.NotificationsMarkUserNotificationsAsRead(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAPI.NotificationsMarkUserNotificationsAsRead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `NotificationsMarkUserNotificationsAsRead`: NotificationsMarkUserNotificationsAsRead200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAPI.NotificationsMarkUserNotificationsAsRead`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiNotificationsMarkUserNotificationsAsReadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NotificationsMarkUserNotificationsAsRead200Response**](NotificationsMarkUserNotificationsAsRead200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

