# \ONSSubmissionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ONSSubmissionReceiveCSV**](ONSSubmissionAPI.md#ONSSubmissionReceiveCSV) | **Post** /api/v1/ons-submissions/csv | Upload a CSV file for ONS submission



## ONSSubmissionReceiveCSV

> ONSSubmissionReceiveCSV200Response ONSSubmissionReceiveCSV(ctx).File(file).Execute()

Upload a CSV file for ONS submission

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
	file := os.NewFile(1234, "some_file") // *os.File | CSV file to upload (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ONSSubmissionAPI.ONSSubmissionReceiveCSV(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ONSSubmissionAPI.ONSSubmissionReceiveCSV``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ONSSubmissionReceiveCSV`: ONSSubmissionReceiveCSV200Response
	fmt.Fprintf(os.Stdout, "Response from `ONSSubmissionAPI.ONSSubmissionReceiveCSV`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiONSSubmissionReceiveCSVRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | CSV file to upload | 

### Return type

[**ONSSubmissionReceiveCSV200Response**](ONSSubmissionReceiveCSV200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

