# CustodianGetProjects200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]Custodian**](Custodian.md) |  | [optional] 
**FirstPageUrl** | Pointer to **string** |  | [optional] 
**LastPageUrl** | Pointer to **string** |  | [optional] 
**NextPageUrl** | Pointer to **string** |  | [optional] 
**PrevPageUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewCustodianGetProjects200ResponseData

`func NewCustodianGetProjects200ResponseData() *CustodianGetProjects200ResponseData`

NewCustodianGetProjects200ResponseData instantiates a new CustodianGetProjects200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianGetProjects200ResponseDataWithDefaults

`func NewCustodianGetProjects200ResponseDataWithDefaults() *CustodianGetProjects200ResponseData`

NewCustodianGetProjects200ResponseDataWithDefaults instantiates a new CustodianGetProjects200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *CustodianGetProjects200ResponseData) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *CustodianGetProjects200ResponseData) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *CustodianGetProjects200ResponseData) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *CustodianGetProjects200ResponseData) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetPerPage

`func (o *CustodianGetProjects200ResponseData) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CustodianGetProjects200ResponseData) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CustodianGetProjects200ResponseData) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *CustodianGetProjects200ResponseData) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *CustodianGetProjects200ResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CustodianGetProjects200ResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CustodianGetProjects200ResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *CustodianGetProjects200ResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *CustodianGetProjects200ResponseData) GetData() []Custodian`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CustodianGetProjects200ResponseData) GetDataOk() (*[]Custodian, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CustodianGetProjects200ResponseData) SetData(v []Custodian)`

SetData sets Data field to given value.

### HasData

`func (o *CustodianGetProjects200ResponseData) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFirstPageUrl

`func (o *CustodianGetProjects200ResponseData) GetFirstPageUrl() string`

GetFirstPageUrl returns the FirstPageUrl field if non-nil, zero value otherwise.

### GetFirstPageUrlOk

`func (o *CustodianGetProjects200ResponseData) GetFirstPageUrlOk() (*string, bool)`

GetFirstPageUrlOk returns a tuple with the FirstPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPageUrl

`func (o *CustodianGetProjects200ResponseData) SetFirstPageUrl(v string)`

SetFirstPageUrl sets FirstPageUrl field to given value.

### HasFirstPageUrl

`func (o *CustodianGetProjects200ResponseData) HasFirstPageUrl() bool`

HasFirstPageUrl returns a boolean if a field has been set.

### GetLastPageUrl

`func (o *CustodianGetProjects200ResponseData) GetLastPageUrl() string`

GetLastPageUrl returns the LastPageUrl field if non-nil, zero value otherwise.

### GetLastPageUrlOk

`func (o *CustodianGetProjects200ResponseData) GetLastPageUrlOk() (*string, bool)`

GetLastPageUrlOk returns a tuple with the LastPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPageUrl

`func (o *CustodianGetProjects200ResponseData) SetLastPageUrl(v string)`

SetLastPageUrl sets LastPageUrl field to given value.

### HasLastPageUrl

`func (o *CustodianGetProjects200ResponseData) HasLastPageUrl() bool`

HasLastPageUrl returns a boolean if a field has been set.

### GetNextPageUrl

`func (o *CustodianGetProjects200ResponseData) GetNextPageUrl() string`

GetNextPageUrl returns the NextPageUrl field if non-nil, zero value otherwise.

### GetNextPageUrlOk

`func (o *CustodianGetProjects200ResponseData) GetNextPageUrlOk() (*string, bool)`

GetNextPageUrlOk returns a tuple with the NextPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageUrl

`func (o *CustodianGetProjects200ResponseData) SetNextPageUrl(v string)`

SetNextPageUrl sets NextPageUrl field to given value.

### HasNextPageUrl

`func (o *CustodianGetProjects200ResponseData) HasNextPageUrl() bool`

HasNextPageUrl returns a boolean if a field has been set.

### GetPrevPageUrl

`func (o *CustodianGetProjects200ResponseData) GetPrevPageUrl() string`

GetPrevPageUrl returns the PrevPageUrl field if non-nil, zero value otherwise.

### GetPrevPageUrlOk

`func (o *CustodianGetProjects200ResponseData) GetPrevPageUrlOk() (*string, bool)`

GetPrevPageUrlOk returns a tuple with the PrevPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPageUrl

`func (o *CustodianGetProjects200ResponseData) SetPrevPageUrl(v string)`

SetPrevPageUrl sets PrevPageUrl field to given value.

### HasPrevPageUrl

`func (o *CustodianGetProjects200ResponseData) HasPrevPageUrl() bool`

HasPrevPageUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


