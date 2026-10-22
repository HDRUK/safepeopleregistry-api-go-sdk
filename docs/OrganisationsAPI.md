# \OrganisationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrganisationsAppointSro**](OrganisationsAPI.md#OrganisationsAppointSro) | **Put** /api/v1/organisations/{id}/sro | organisations@appointSro
[**OrganisationsInviteSro**](OrganisationsAPI.md#OrganisationsInviteSro) | **Post** /api/v1/organisations/{id}/sro/invite | organisations@inviteSro
[**OrganisationsRemoveDelegate**](OrganisationsAPI.md#OrganisationsRemoveDelegate) | **Delete** /api/v1/organisations/{id}/delegates/{userId} | organisations@removeDelegate
[**OrganisationsResendSroInvite**](OrganisationsAPI.md#OrganisationsResendSroInvite) | **Post** /api/v1/organisations/{id}/sro/resend_invite | organisations@resendSroInvite



## OrganisationsAppointSro

> OrganisationsAppointSro200Response OrganisationsAppointSro(ctx, id).OrganisationsAppointSroRequest(organisationsAppointSroRequest).Execute()

organisations@appointSro



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
	id := int32(1) // int32 | organisations entry ID
	organisationsAppointSroRequest := *openapiclient.NewOrganisationsAppointSroRequest() // OrganisationsAppointSroRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsAppointSro(context.Background(), id).OrganisationsAppointSroRequest(organisationsAppointSroRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsAppointSro``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsAppointSro`: OrganisationsAppointSro200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsAppointSro`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsAppointSroRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisationsAppointSroRequest** | [**OrganisationsAppointSroRequest**](OrganisationsAppointSroRequest.md) |  | 

### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsInviteSro

> OrganisationsInviteSro201Response OrganisationsInviteSro(ctx, id).OrganisationsInviteSroRequest(organisationsInviteSroRequest).Execute()

organisations@inviteSro



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
	id := int32(1) // int32 | organisations entry ID
	organisationsInviteSroRequest := *openapiclient.NewOrganisationsInviteSroRequest() // OrganisationsInviteSroRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsInviteSro(context.Background(), id).OrganisationsInviteSroRequest(organisationsInviteSroRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsInviteSro``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsInviteSro`: OrganisationsInviteSro201Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsInviteSro`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsInviteSroRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organisationsInviteSroRequest** | [**OrganisationsInviteSroRequest**](OrganisationsInviteSroRequest.md) |  | 

### Return type

[**OrganisationsInviteSro201Response**](OrganisationsInviteSro201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsRemoveDelegate

> OrganisationsAppointSro200Response OrganisationsRemoveDelegate(ctx, id, userId).Execute()

organisations@removeDelegate



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
	id := int32(1) // int32 | organisations entry ID
	userId := int32(1) // int32 | ID of the delegate to remove

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsRemoveDelegate(context.Background(), id, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsRemoveDelegate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsRemoveDelegate`: OrganisationsAppointSro200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsRemoveDelegate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 
**userId** | **int32** | ID of the delegate to remove | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsRemoveDelegateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganisationsResendSroInvite

> OrganisationsAppointSro200Response OrganisationsResendSroInvite(ctx, id).Execute()

organisations@resendSroInvite



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
	id := int32(1) // int32 | organisations entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganisationsAPI.OrganisationsResendSroInvite(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganisationsAPI.OrganisationsResendSroInvite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganisationsResendSroInvite`: OrganisationsAppointSro200Response
	fmt.Fprintf(os.Stdout, "Response from `OrganisationsAPI.OrganisationsResendSroInvite`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrganisationsResendSroInviteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

