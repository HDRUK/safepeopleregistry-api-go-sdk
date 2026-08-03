# \DepartmentAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DepartmentDestroy**](DepartmentAPI.md#DepartmentDestroy) | **Delete** /api/v1/departments/{id} | Delete a department
[**DepartmentIndex**](DepartmentAPI.md#DepartmentIndex) | **Get** /api/v1/departments | Get a list of departments
[**DepartmentShow**](DepartmentAPI.md#DepartmentShow) | **Get** /api/v1/departments/{id} | Get a specific department by ID
[**DepartmentStore**](DepartmentAPI.md#DepartmentStore) | **Post** /api/v1/departments | Create a new department
[**DepartmentUpdate**](DepartmentAPI.md#DepartmentUpdate) | **Put** /api/v1/departments/{id} | Update an existing department



## DepartmentDestroy

> AffiliationDestroy200Response DepartmentDestroy(ctx, id).Execute()

Delete a department

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
	id := int32(1) // int32 | ID of the department

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DepartmentAPI.DepartmentDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DepartmentAPI.DepartmentDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DepartmentDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `DepartmentAPI.DepartmentDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the department | 

### Other Parameters

Other parameters are passed through a pointer to a apiDepartmentDestroyRequest struct via the builder pattern


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


## DepartmentIndex

> []Department DepartmentIndex(ctx).Execute()

Get a list of departments

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
	resp, r, err := apiClient.DepartmentAPI.DepartmentIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DepartmentAPI.DepartmentIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DepartmentIndex`: []Department
	fmt.Fprintf(os.Stdout, "Response from `DepartmentAPI.DepartmentIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDepartmentIndexRequest struct via the builder pattern


### Return type

[**[]Department**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DepartmentShow

> Department DepartmentShow(ctx, id).Execute()

Get a specific department by ID

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
	id := int32(1) // int32 | ID of the department

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DepartmentAPI.DepartmentShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DepartmentAPI.DepartmentShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DepartmentShow`: Department
	fmt.Fprintf(os.Stdout, "Response from `DepartmentAPI.DepartmentShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the department | 

### Other Parameters

Other parameters are passed through a pointer to a apiDepartmentShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Department**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DepartmentStore

> AccreditationStoreByRegistryId201Response DepartmentStore(ctx).Department(department).Execute()

Create a new department

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
	department := *openapiclient.NewDepartment() // Department | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DepartmentAPI.DepartmentStore(context.Background()).Department(department).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DepartmentAPI.DepartmentStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DepartmentStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `DepartmentAPI.DepartmentStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDepartmentStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **department** | [**Department**](Department.md) |  | 

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DepartmentUpdate

> Department DepartmentUpdate(ctx, id).Department(department).Execute()

Update an existing department

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
	id := int32(1) // int32 | ID of the department
	department := *openapiclient.NewDepartment() // Department | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DepartmentAPI.DepartmentUpdate(context.Background(), id).Department(department).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DepartmentAPI.DepartmentUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DepartmentUpdate`: Department
	fmt.Fprintf(os.Stdout, "Response from `DepartmentAPI.DepartmentUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the department | 

### Other Parameters

Other parameters are passed through a pointer to a apiDepartmentUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **department** | [**Department**](Department.md) |  | 

### Return type

[**Department**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

