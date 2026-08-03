# \SectorAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SectorDestroy**](SectorAPI.md#SectorDestroy) | **Delete** /api/v1/sectors/{id} | Delete a sector
[**SectorIndex**](SectorAPI.md#SectorIndex) | **Get** /api/v1/sectors | Get a list of sectors
[**SectorShow**](SectorAPI.md#SectorShow) | **Get** /api/v1/sectors/{id} | Get a specific sector by ID
[**SectorStore**](SectorAPI.md#SectorStore) | **Post** /api/v1/sectors | Create a new sector
[**SectorUpdate**](SectorAPI.md#SectorUpdate) | **Put** /api/v1/sectors/{id} | Update an existing sector



## SectorDestroy

> AffiliationDestroy200Response SectorDestroy(ctx, id).Execute()

Delete a sector

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
	id := int32(1) // int32 | ID of the sector

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SectorAPI.SectorDestroy(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SectorAPI.SectorDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SectorDestroy`: AffiliationDestroy200Response
	fmt.Fprintf(os.Stdout, "Response from `SectorAPI.SectorDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the sector | 

### Other Parameters

Other parameters are passed through a pointer to a apiSectorDestroyRequest struct via the builder pattern


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


## SectorIndex

> []Sector SectorIndex(ctx).Execute()

Get a list of sectors

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
	resp, r, err := apiClient.SectorAPI.SectorIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SectorAPI.SectorIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SectorIndex`: []Sector
	fmt.Fprintf(os.Stdout, "Response from `SectorAPI.SectorIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSectorIndexRequest struct via the builder pattern


### Return type

[**[]Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SectorShow

> Sector SectorShow(ctx, id).Execute()

Get a specific sector by ID

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
	id := int32(1) // int32 | ID of the sector

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SectorAPI.SectorShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SectorAPI.SectorShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SectorShow`: Sector
	fmt.Fprintf(os.Stdout, "Response from `SectorAPI.SectorShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the sector | 

### Other Parameters

Other parameters are passed through a pointer to a apiSectorShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SectorStore

> AccreditationStoreByRegistryId201Response SectorStore(ctx).Sector(sector).Execute()

Create a new sector

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
	sector := *openapiclient.NewSector() // Sector | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SectorAPI.SectorStore(context.Background()).Sector(sector).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SectorAPI.SectorStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SectorStore`: AccreditationStoreByRegistryId201Response
	fmt.Fprintf(os.Stdout, "Response from `SectorAPI.SectorStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSectorStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sector** | [**Sector**](Sector.md) |  | 

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


## SectorUpdate

> Sector SectorUpdate(ctx, id).Sector(sector).Execute()

Update an existing sector

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
	id := int32(1) // int32 | ID of the sector
	sector := *openapiclient.NewSector() // Sector | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SectorAPI.SectorUpdate(context.Background(), id).Sector(sector).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SectorAPI.SectorUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SectorUpdate`: Sector
	fmt.Fprintf(os.Stdout, "Response from `SectorAPI.SectorUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the sector | 

### Other Parameters

Other parameters are passed through a pointer to a apiSectorUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sector** | [**Sector**](Sector.md) |  | 

### Return type

[**Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

