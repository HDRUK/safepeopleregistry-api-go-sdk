# OrganisationGetUsers200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]OrganisationGetUsers200ResponseDataDataInner**](OrganisationGetUsers200ResponseDataDataInner.md) |  | [optional] 
**FirstPageUrl** | Pointer to **string** |  | [optional] 
**From** | Pointer to **int32** |  | [optional] 
**LastPage** | Pointer to **int32** |  | [optional] 
**LastPageUrl** | Pointer to **string** |  | [optional] 
**NextPageUrl** | Pointer to **string** |  | [optional] 
**Path** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**PrevPageUrl** | Pointer to **string** |  | [optional] 
**To** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewOrganisationGetUsers200ResponseData

`func NewOrganisationGetUsers200ResponseData() *OrganisationGetUsers200ResponseData`

NewOrganisationGetUsers200ResponseData instantiates a new OrganisationGetUsers200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganisationGetUsers200ResponseDataWithDefaults

`func NewOrganisationGetUsers200ResponseDataWithDefaults() *OrganisationGetUsers200ResponseData`

NewOrganisationGetUsers200ResponseDataWithDefaults instantiates a new OrganisationGetUsers200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *OrganisationGetUsers200ResponseData) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *OrganisationGetUsers200ResponseData) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *OrganisationGetUsers200ResponseData) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *OrganisationGetUsers200ResponseData) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetData

`func (o *OrganisationGetUsers200ResponseData) GetData() []OrganisationGetUsers200ResponseDataDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OrganisationGetUsers200ResponseData) GetDataOk() (*[]OrganisationGetUsers200ResponseDataDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OrganisationGetUsers200ResponseData) SetData(v []OrganisationGetUsers200ResponseDataDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *OrganisationGetUsers200ResponseData) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFirstPageUrl

`func (o *OrganisationGetUsers200ResponseData) GetFirstPageUrl() string`

GetFirstPageUrl returns the FirstPageUrl field if non-nil, zero value otherwise.

### GetFirstPageUrlOk

`func (o *OrganisationGetUsers200ResponseData) GetFirstPageUrlOk() (*string, bool)`

GetFirstPageUrlOk returns a tuple with the FirstPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPageUrl

`func (o *OrganisationGetUsers200ResponseData) SetFirstPageUrl(v string)`

SetFirstPageUrl sets FirstPageUrl field to given value.

### HasFirstPageUrl

`func (o *OrganisationGetUsers200ResponseData) HasFirstPageUrl() bool`

HasFirstPageUrl returns a boolean if a field has been set.

### GetFrom

`func (o *OrganisationGetUsers200ResponseData) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *OrganisationGetUsers200ResponseData) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *OrganisationGetUsers200ResponseData) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *OrganisationGetUsers200ResponseData) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetLastPage

`func (o *OrganisationGetUsers200ResponseData) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *OrganisationGetUsers200ResponseData) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *OrganisationGetUsers200ResponseData) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *OrganisationGetUsers200ResponseData) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLastPageUrl

`func (o *OrganisationGetUsers200ResponseData) GetLastPageUrl() string`

GetLastPageUrl returns the LastPageUrl field if non-nil, zero value otherwise.

### GetLastPageUrlOk

`func (o *OrganisationGetUsers200ResponseData) GetLastPageUrlOk() (*string, bool)`

GetLastPageUrlOk returns a tuple with the LastPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPageUrl

`func (o *OrganisationGetUsers200ResponseData) SetLastPageUrl(v string)`

SetLastPageUrl sets LastPageUrl field to given value.

### HasLastPageUrl

`func (o *OrganisationGetUsers200ResponseData) HasLastPageUrl() bool`

HasLastPageUrl returns a boolean if a field has been set.

### GetNextPageUrl

`func (o *OrganisationGetUsers200ResponseData) GetNextPageUrl() string`

GetNextPageUrl returns the NextPageUrl field if non-nil, zero value otherwise.

### GetNextPageUrlOk

`func (o *OrganisationGetUsers200ResponseData) GetNextPageUrlOk() (*string, bool)`

GetNextPageUrlOk returns a tuple with the NextPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageUrl

`func (o *OrganisationGetUsers200ResponseData) SetNextPageUrl(v string)`

SetNextPageUrl sets NextPageUrl field to given value.

### HasNextPageUrl

`func (o *OrganisationGetUsers200ResponseData) HasNextPageUrl() bool`

HasNextPageUrl returns a boolean if a field has been set.

### GetPath

`func (o *OrganisationGetUsers200ResponseData) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *OrganisationGetUsers200ResponseData) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *OrganisationGetUsers200ResponseData) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *OrganisationGetUsers200ResponseData) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *OrganisationGetUsers200ResponseData) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *OrganisationGetUsers200ResponseData) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *OrganisationGetUsers200ResponseData) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *OrganisationGetUsers200ResponseData) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetPrevPageUrl

`func (o *OrganisationGetUsers200ResponseData) GetPrevPageUrl() string`

GetPrevPageUrl returns the PrevPageUrl field if non-nil, zero value otherwise.

### GetPrevPageUrlOk

`func (o *OrganisationGetUsers200ResponseData) GetPrevPageUrlOk() (*string, bool)`

GetPrevPageUrlOk returns a tuple with the PrevPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPageUrl

`func (o *OrganisationGetUsers200ResponseData) SetPrevPageUrl(v string)`

SetPrevPageUrl sets PrevPageUrl field to given value.

### HasPrevPageUrl

`func (o *OrganisationGetUsers200ResponseData) HasPrevPageUrl() bool`

HasPrevPageUrl returns a boolean if a field has been set.

### GetTo

`func (o *OrganisationGetUsers200ResponseData) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *OrganisationGetUsers200ResponseData) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *OrganisationGetUsers200ResponseData) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *OrganisationGetUsers200ResponseData) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetTotal

`func (o *OrganisationGetUsers200ResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OrganisationGetUsers200ResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OrganisationGetUsers200ResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OrganisationGetUsers200ResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


