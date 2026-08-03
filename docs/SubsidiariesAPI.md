# \SubsidiariesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SubsidiariesDestroy**](SubsidiariesAPI.md#SubsidiariesDestroy) | **Delete** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@destroy
[**SubsidiariesStore**](SubsidiariesAPI.md#SubsidiariesStore) | **Post** /api/v1/subsidiaries/organisations/{organisationId} | subsidiaries@store
[**SubsidiariesUpdate**](SubsidiariesAPI.md#SubsidiariesUpdate) | **Put** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@update



## SubsidiariesDestroy

> AffiliationDestroy200Response SubsidiariesDestroy(ctx, organisationId, subsidiaryId).Execute()

subsidiaries@destroy



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
	organisationId := int32(1) // int32 | organisations entry ID
	subsidiaryId := int32(1) // int32 | subsidiary entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubsidiariesAPI.SubsidiariesDestroy(context.Background(), organisationId, subsidiaryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubsidiariesAPI.SubsidiariesDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubsidiariesDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `SubsidiariesAPI.SubsidiariesDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organisationId** | **int32** | organisations entry ID | 
**subsidiaryId** | **int32** | subsidiary entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubsidiariesDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AffiliationDestroy200Response**](AffiliationDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubsidiariesStore

> SubsidiariesStore201Response SubsidiariesStore(ctx, organisationId).Subsidiary(subsidiary).Execute()

subsidiaries@store



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
	organisationId := int32(1) // int32 | organisations entry ID
	subsidiary := *openapiclient.NewSubsidiary() // Subsidiary | subsidiary definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubsidiariesAPI.SubsidiariesStore(context.Background(), organisationId).Subsidiary(subsidiary).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubsidiariesAPI.SubsidiariesStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubsidiariesStore`: SubsidiariesStore201Response
	fmt.Fprintf(os.Stdout, "Response from `SubsidiariesAPI.SubsidiariesStore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organisationId** | **int32** | organisations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubsidiariesStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition | 

### Return type

[**SubsidiariesStore201Response**](SubsidiariesStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubsidiariesUpdate

> SubsidiariesStore201Response SubsidiariesUpdate(ctx, organisationId, subsidiaryId).Subsidiary(subsidiary).Execute()

subsidiaries@update



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
	organisationId := int32(1) // int32 | organisations entry ID
	subsidiaryId := int32(1) // int32 | subsidiary entry ID
	subsidiary := *openapiclient.NewSubsidiary() // Subsidiary | subsidiary definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubsidiariesAPI.SubsidiariesUpdate(context.Background(), organisationId, subsidiaryId).Subsidiary(subsidiary).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubsidiariesAPI.SubsidiariesUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubsidiariesUpdate`: SubsidiariesStore201Response
	fmt.Fprintf(os.Stdout, "Response from `SubsidiariesAPI.SubsidiariesUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organisationId** | **int32** | organisations entry ID | 
**subsidiaryId** | **int32** | subsidiary entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubsidiariesUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition | 

### Return type

[**SubsidiariesStore201Response**](SubsidiariesStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

