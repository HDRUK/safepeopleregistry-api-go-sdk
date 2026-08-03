# \CustodianModelConfigAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustodianModelConfigDestroy**](CustodianModelConfigAPI.md#CustodianModelConfigDestroy) | **Delete** /api/v1/custodian_config/{id} | CustodianModelConfig@destroy
[**CustodianModelConfigGetByCustodianID**](CustodianModelConfigAPI.md#CustodianModelConfigGetByCustodianID) | **Get** /api/v1/custodian_config/{id} | CustodianModelConfig@getByCustodianID
[**CustodianModelConfigGetEntityModels**](CustodianModelConfigAPI.md#CustodianModelConfigGetEntityModels) | **Get** /api/v1/custodian_config/{custodianId}/entity_models | Get entity models for custodian config
[**CustodianModelConfigStore**](CustodianModelConfigAPI.md#CustodianModelConfigStore) | **Post** /api/v1/custodian_config | CustodianModelConfig@store
[**CustodianModelConfigUpdate**](CustodianModelConfigAPI.md#CustodianModelConfigUpdate) | **Put** /api/v1/custodian_config/{id} | CustodianModelConfig@update
[**CustodianModelConfigUpdateEntityModels**](CustodianModelConfigAPI.md#CustodianModelConfigUpdateEntityModels) | **Put** /api/v1/custodian_config/{custodianId}/entity_models | Update a custodian&#39;s entity models



## CustodianModelConfigDestroy

> AffiliationDestroy200Response CustodianModelConfigDestroy(ctx, id).Execute()

CustodianModelConfig@destroy



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
	id := int32(1) // int32 | CustodianModelConfig entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | CustodianModelConfig entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigDestroyRequest struct via the builder pattern


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


## CustodianModelConfigGetByCustodianID

> CustodianModelConfigGetByCustodianID200Response CustodianModelConfigGetByCustodianID(ctx, id).Execute()

CustodianModelConfig@getByCustodianID



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
	id := int32(1) // int32 | CustodianModelConfig entry ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigGetByCustodianID(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigGetByCustodianID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigGetByCustodianID`: CustodianModelConfigGetByCustodianID200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigGetByCustodianID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | CustodianModelConfig entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigGetByCustodianIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustodianModelConfigGetByCustodianID200Response**](CustodianModelConfigGetByCustodianID200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianModelConfigGetEntityModels

> CustodianModelConfigGetEntityModels200Response CustodianModelConfigGetEntityModels(ctx, custodianId).EntityModelType(entityModelType).Execute()

Get entity models for custodian config



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
	custodianId := int32(56) // int32 | ID of the custodian
	entityModelType := "entityModelType_example" // string | Type of entity model to retrieve

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigGetEntityModels(context.Background(), custodianId).EntityModelType(entityModelType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigGetEntityModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigGetEntityModels`: CustodianModelConfigGetEntityModels200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigGetEntityModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigGetEntityModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **entityModelType** | **string** | Type of entity model to retrieve | 

### Return type

[**CustodianModelConfigGetEntityModels200Response**](CustodianModelConfigGetEntityModels200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianModelConfigStore

> CustodianModelConfigUpdate200Response CustodianModelConfigStore(ctx).CustodianModelConfig(custodianModelConfig).Execute()

CustodianModelConfig@store



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
	custodianModelConfig := *openapiclient.NewCustodianModelConfig() // CustodianModelConfig | CustodianModelConfig definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigStore(context.Background()).CustodianModelConfig(custodianModelConfig).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigStore`: CustodianModelConfigUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **custodianModelConfig** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition | 

### Return type

[**CustodianModelConfigUpdate200Response**](CustodianModelConfigUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianModelConfigUpdate

> CustodianModelConfigUpdate200Response CustodianModelConfigUpdate(ctx, id).CustodianModelConfig(custodianModelConfig).Execute()

CustodianModelConfig@update



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
	id := int32(1) // int32 | CustodianModelConfig entry ID
	custodianModelConfig := *openapiclient.NewCustodianModelConfig() // CustodianModelConfig | CustodianModelConfig definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigUpdate(context.Background(), id).CustodianModelConfig(custodianModelConfig).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigUpdate`: CustodianModelConfigUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | CustodianModelConfig entry ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **custodianModelConfig** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition | 

### Return type

[**CustodianModelConfigUpdate200Response**](CustodianModelConfigUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustodianModelConfigUpdateEntityModels

> CustodianModelConfigUpdateEntityModels200Response CustodianModelConfigUpdateEntityModels(ctx, custodianId).CustodianModelConfigUpdateEntityModelsRequest(custodianModelConfigUpdateEntityModelsRequest).Execute()

Update a custodian's entity models



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
	custodianId := int32(56) // int32 | ID of the custodian
	custodianModelConfigUpdateEntityModelsRequest := *openapiclient.NewCustodianModelConfigUpdateEntityModelsRequest() // CustodianModelConfigUpdateEntityModelsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustodianModelConfigAPI.CustodianModelConfigUpdateEntityModels(context.Background(), custodianId).CustodianModelConfigUpdateEntityModelsRequest(custodianModelConfigUpdateEntityModelsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustodianModelConfigAPI.CustodianModelConfigUpdateEntityModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustodianModelConfigUpdateEntityModels`: CustodianModelConfigUpdateEntityModels200Response
	fmt.Fprintf(os.Stdout, "Response from `CustodianModelConfigAPI.CustodianModelConfigUpdateEntityModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**custodianId** | **int32** | ID of the custodian | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustodianModelConfigUpdateEntityModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **custodianModelConfigUpdateEntityModelsRequest** | [**CustodianModelConfigUpdateEntityModelsRequest**](CustodianModelConfigUpdateEntityModelsRequest.md) |  | 

### Return type

[**CustodianModelConfigUpdateEntityModels200Response**](CustodianModelConfigUpdateEntityModels200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

