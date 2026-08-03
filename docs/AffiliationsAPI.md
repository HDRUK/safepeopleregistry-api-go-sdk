# \AffiliationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AffiliationsGetOrganisationAffiliation**](AffiliationsAPI.md#AffiliationsGetOrganisationAffiliation) | **Get** /api/v1/affiliations/{registryId}/organisation/{organisationId} | Return a specific organisation&#39;s affiliation by registry ID and organisation ID
[**AffiliationsIndexByRegistryId**](AffiliationsAPI.md#AffiliationsIndexByRegistryId) | **Get** /api/v1/affiliations/{registryId} | Affiliations@show
[**AffiliationsStoreByRegistryId**](AffiliationsAPI.md#AffiliationsStoreByRegistryId) | **Post** /api/v1/affiliations/{registryId} | Affiliations@store
[**AffiliationsUpdate**](AffiliationsAPI.md#AffiliationsUpdate) | **Put** /api/v1/affiliations/{id} | Affiliations@update
[**AffiliationsVerifyEmail**](AffiliationsAPI.md#AffiliationsVerifyEmail) | **Put** /api/v1/affiliations/verify_email/{verificationCode} | Affiliations@verifyEmail



## AffiliationsGetOrganisationAffiliation

> AffiliationsGetOrganisationAffiliation200Response AffiliationsGetOrganisationAffiliation(ctx, registryId, organisationId).Execute()

Return a specific organisation's affiliation by registry ID and organisation ID



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
	registryId := int32(1) // int32 | Registry ID
	organisationId := int32(100) // int32 | Organisation ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AffiliationsAPI.AffiliationsGetOrganisationAffiliation(context.Background(), registryId, organisationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AffiliationsAPI.AffiliationsGetOrganisationAffiliation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AffiliationsGetOrganisationAffiliation`: AffiliationsGetOrganisationAffiliation200Response
	fmt.Fprintf(os.Stdout, "Response from `AffiliationsAPI.AffiliationsGetOrganisationAffiliation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | Registry ID | 
**organisationId** | **int32** | Organisation ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiAffiliationsGetOrganisationAffiliationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AffiliationsGetOrganisationAffiliation200Response**](AffiliationsGetOrganisationAffiliation200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AffiliationsIndexByRegistryId

> AffiliationsIndexByRegistryId200Response AffiliationsIndexByRegistryId(ctx, registryId).Execute()

Affiliations@show



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
	registryId := int32(1) // int32 | Affiliations registry id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AffiliationsAPI.AffiliationsIndexByRegistryId(context.Background(), registryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AffiliationsAPI.AffiliationsIndexByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AffiliationsIndexByRegistryId`: AffiliationsIndexByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AffiliationsAPI.AffiliationsIndexByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | Affiliations registry id | 

### Other Parameters

Other parameters are passed through a pointer to a apiAffiliationsIndexByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AffiliationsIndexByRegistryId200Response**](AffiliationsIndexByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AffiliationsStoreByRegistryId

> AffiliationsStoreByRegistryId200Response AffiliationsStoreByRegistryId(ctx, registryId).Affiliation(affiliation).Execute()

Affiliations@store



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
	registryId := int32(1) // int32 | Registry entry ID
	affiliation := *openapiclient.NewAffiliation() // Affiliation | Affiliation definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AffiliationsAPI.AffiliationsStoreByRegistryId(context.Background(), registryId).Affiliation(affiliation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AffiliationsAPI.AffiliationsStoreByRegistryId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AffiliationsStoreByRegistryId`: AffiliationsStoreByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AffiliationsAPI.AffiliationsStoreByRegistryId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**registryId** | **int32** | Registry entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiAffiliationsStoreByRegistryIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition | 

### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AffiliationsUpdate

> AffiliationsStoreByRegistryId200Response AffiliationsUpdate(ctx, id).Affiliation(affiliation).Execute()

Affiliations@update



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
	id := int32(1) // int32 | Affiliation entry ID
	affiliation := *openapiclient.NewAffiliation() // Affiliation | Affiliation definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AffiliationsAPI.AffiliationsUpdate(context.Background(), id).Affiliation(affiliation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AffiliationsAPI.AffiliationsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AffiliationsUpdate`: AffiliationsStoreByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AffiliationsAPI.AffiliationsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Affiliation entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiAffiliationsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition | 

### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AffiliationsVerifyEmail

> AffiliationsStoreByRegistryId200Response AffiliationsVerifyEmail(ctx, verificationCode).Execute()

Affiliations@verifyEmail



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
	verificationCode := "1" // string | Email verification code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AffiliationsAPI.AffiliationsVerifyEmail(context.Background(), verificationCode).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AffiliationsAPI.AffiliationsVerifyEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AffiliationsVerifyEmail`: AffiliationsStoreByRegistryId200Response
	fmt.Fprintf(os.Stdout, "Response from `AffiliationsAPI.AffiliationsVerifyEmail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**verificationCode** | **string** | Email verification code | 

### Other Parameters

Other parameters are passed through a pointer to a apiAffiliationsVerifyEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

