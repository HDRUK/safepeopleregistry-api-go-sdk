# CustodianHasProjectOrganisation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] [readonly] 
**ProjectHasOrganisationId** | **int32** | ID of the project organisation | 
**CustodianId** | **int32** | ID of the custodian | 
**Approved** | Pointer to **NullableBool** | Approval flag | [optional] 
**Comment** | Pointer to **NullableString** | Optional comment | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**ProjectOrganisation** | Pointer to [**ProjectHasOrganisation**](ProjectHasOrganisation.md) |  | [optional] 
**Custodian** | Pointer to [**Custodian**](Custodian.md) |  | [optional] 

## Methods

### NewCustodianHasProjectOrganisation

`func NewCustodianHasProjectOrganisation(projectHasOrganisationId int32, custodianId int32, ) *CustodianHasProjectOrganisation`

NewCustodianHasProjectOrganisation instantiates a new CustodianHasProjectOrganisation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianHasProjectOrganisationWithDefaults

`func NewCustodianHasProjectOrganisationWithDefaults() *CustodianHasProjectOrganisation`

NewCustodianHasProjectOrganisationWithDefaults instantiates a new CustodianHasProjectOrganisation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustodianHasProjectOrganisation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustodianHasProjectOrganisation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustodianHasProjectOrganisation) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CustodianHasProjectOrganisation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectHasOrganisationId

`func (o *CustodianHasProjectOrganisation) GetProjectHasOrganisationId() int32`

GetProjectHasOrganisationId returns the ProjectHasOrganisationId field if non-nil, zero value otherwise.

### GetProjectHasOrganisationIdOk

`func (o *CustodianHasProjectOrganisation) GetProjectHasOrganisationIdOk() (*int32, bool)`

GetProjectHasOrganisationIdOk returns a tuple with the ProjectHasOrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectHasOrganisationId

`func (o *CustodianHasProjectOrganisation) SetProjectHasOrganisationId(v int32)`

SetProjectHasOrganisationId sets ProjectHasOrganisationId field to given value.


### GetCustodianId

`func (o *CustodianHasProjectOrganisation) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *CustodianHasProjectOrganisation) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *CustodianHasProjectOrganisation) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.


### GetApproved

`func (o *CustodianHasProjectOrganisation) GetApproved() bool`

GetApproved returns the Approved field if non-nil, zero value otherwise.

### GetApprovedOk

`func (o *CustodianHasProjectOrganisation) GetApprovedOk() (*bool, bool)`

GetApprovedOk returns a tuple with the Approved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproved

`func (o *CustodianHasProjectOrganisation) SetApproved(v bool)`

SetApproved sets Approved field to given value.

### HasApproved

`func (o *CustodianHasProjectOrganisation) HasApproved() bool`

HasApproved returns a boolean if a field has been set.

### SetApprovedNil

`func (o *CustodianHasProjectOrganisation) SetApprovedNil(b bool)`

 SetApprovedNil sets the value for Approved to be an explicit nil

### UnsetApproved
`func (o *CustodianHasProjectOrganisation) UnsetApproved()`

UnsetApproved ensures that no value is present for Approved, not even an explicit nil
### GetComment

`func (o *CustodianHasProjectOrganisation) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *CustodianHasProjectOrganisation) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *CustodianHasProjectOrganisation) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *CustodianHasProjectOrganisation) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *CustodianHasProjectOrganisation) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *CustodianHasProjectOrganisation) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetCreatedAt

`func (o *CustodianHasProjectOrganisation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustodianHasProjectOrganisation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustodianHasProjectOrganisation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CustodianHasProjectOrganisation) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CustodianHasProjectOrganisation) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustodianHasProjectOrganisation) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustodianHasProjectOrganisation) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CustodianHasProjectOrganisation) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetProjectOrganisation

`func (o *CustodianHasProjectOrganisation) GetProjectOrganisation() ProjectHasOrganisation`

GetProjectOrganisation returns the ProjectOrganisation field if non-nil, zero value otherwise.

### GetProjectOrganisationOk

`func (o *CustodianHasProjectOrganisation) GetProjectOrganisationOk() (*ProjectHasOrganisation, bool)`

GetProjectOrganisationOk returns a tuple with the ProjectOrganisation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectOrganisation

`func (o *CustodianHasProjectOrganisation) SetProjectOrganisation(v ProjectHasOrganisation)`

SetProjectOrganisation sets ProjectOrganisation field to given value.

### HasProjectOrganisation

`func (o *CustodianHasProjectOrganisation) HasProjectOrganisation() bool`

HasProjectOrganisation returns a boolean if a field has been set.

### GetCustodian

`func (o *CustodianHasProjectOrganisation) GetCustodian() Custodian`

GetCustodian returns the Custodian field if non-nil, zero value otherwise.

### GetCustodianOk

`func (o *CustodianHasProjectOrganisation) GetCustodianOk() (*Custodian, bool)`

GetCustodianOk returns a tuple with the Custodian field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodian

`func (o *CustodianHasProjectOrganisation) SetCustodian(v Custodian)`

SetCustodian sets Custodian field to given value.

### HasCustodian

`func (o *CustodianHasProjectOrganisation) HasCustodian() bool`

HasCustodian returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


