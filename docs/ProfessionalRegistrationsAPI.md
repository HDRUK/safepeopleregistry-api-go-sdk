# \ProfessionalRegistrationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProfessionalRegistrationsUpdate**](ProfessionalRegistrationsAPI.md#ProfessionalRegistrationsUpdate) | **Put** /api/v1/professional_registrations/{id} | Professional Registrations@update



## ProfessionalRegistrationsUpdate

> ProfessionalRegistrationsUpdate200Response ProfessionalRegistrationsUpdate(ctx, id).ProfessionalRegistrationsUpdateRequest(professionalRegistrationsUpdateRequest).Execute()

Professional Registrations@update



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
	id := int32(1) // int32 | Professional Registrations entry ID
	professionalRegistrationsUpdateRequest := *openapiclient.NewProfessionalRegistrationsUpdateRequest() // ProfessionalRegistrationsUpdateRequest | Professional Registrations definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProfessionalRegistrationsAPI.ProfessionalRegistrationsUpdate(context.Background(), id).ProfessionalRegistrationsUpdateRequest(professionalRegistrationsUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProfessionalRegistrationsAPI.ProfessionalRegistrationsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProfessionalRegistrationsUpdate`: ProfessionalRegistrationsUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ProfessionalRegistrationsAPI.ProfessionalRegistrationsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Professional Registrations entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiProfessionalRegistrationsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **professionalRegistrationsUpdateRequest** | [**ProfessionalRegistrationsUpdateRequest**](ProfessionalRegistrationsUpdateRequest.md) | Professional Registrations definition | 

### Return type

[**ProfessionalRegistrationsUpdate200Response**](ProfessionalRegistrationsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

