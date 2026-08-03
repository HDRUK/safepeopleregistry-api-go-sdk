# Project

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**UniqueId** | Pointer to **string** |  | [optional] 
**LaySummary** | Pointer to **string** |  | [optional] 
**PublicBenefit** | Pointer to **string** | A unique identifier for Custodian&#39;s within SOURSD | [optional] 
**RequestCategoryType** | Pointer to **string** |  | [optional] 
**TechnicalSummary** | Pointer to **string** |  | [optional] 
**OtherApprovalCommitees** | Pointer to **string** |  | [optional] 
**StartDate** | Pointer to **string** |  | [optional] 
**EndDate** | Pointer to **string** |  | [optional] 

## Methods

### NewProject

`func NewProject() *Project`

NewProject instantiates a new Project object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWithDefaults

`func NewProjectWithDefaults() *Project`

NewProjectWithDefaults instantiates a new Project object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Project) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Project) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Project) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Project) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *Project) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Project) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Project) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Project) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetUniqueId

`func (o *Project) GetUniqueId() string`

GetUniqueId returns the UniqueId field if non-nil, zero value otherwise.

### GetUniqueIdOk

`func (o *Project) GetUniqueIdOk() (*string, bool)`

GetUniqueIdOk returns a tuple with the UniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueId

`func (o *Project) SetUniqueId(v string)`

SetUniqueId sets UniqueId field to given value.

### HasUniqueId

`func (o *Project) HasUniqueId() bool`

HasUniqueId returns a boolean if a field has been set.

### GetLaySummary

`func (o *Project) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *Project) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *Project) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *Project) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetPublicBenefit

`func (o *Project) GetPublicBenefit() string`

GetPublicBenefit returns the PublicBenefit field if non-nil, zero value otherwise.

### GetPublicBenefitOk

`func (o *Project) GetPublicBenefitOk() (*string, bool)`

GetPublicBenefitOk returns a tuple with the PublicBenefit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefit

`func (o *Project) SetPublicBenefit(v string)`

SetPublicBenefit sets PublicBenefit field to given value.

### HasPublicBenefit

`func (o *Project) HasPublicBenefit() bool`

HasPublicBenefit returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *Project) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *Project) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *Project) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *Project) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *Project) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *Project) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *Project) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *Project) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetOtherApprovalCommitees

`func (o *Project) GetOtherApprovalCommitees() string`

GetOtherApprovalCommitees returns the OtherApprovalCommitees field if non-nil, zero value otherwise.

### GetOtherApprovalCommiteesOk

`func (o *Project) GetOtherApprovalCommiteesOk() (*string, bool)`

GetOtherApprovalCommiteesOk returns a tuple with the OtherApprovalCommitees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommitees

`func (o *Project) SetOtherApprovalCommitees(v string)`

SetOtherApprovalCommitees sets OtherApprovalCommitees field to given value.

### HasOtherApprovalCommitees

`func (o *Project) HasOtherApprovalCommitees() bool`

HasOtherApprovalCommitees returns a boolean if a field has been set.

### GetStartDate

`func (o *Project) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *Project) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *Project) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *Project) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetEndDate

`func (o *Project) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *Project) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *Project) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *Project) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


