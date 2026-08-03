# ProjectHasCustodian

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the project-custodian relationship | [optional] 
**ProjectId** | Pointer to **int32** | ID of the project | [optional] 
**CustodianId** | Pointer to **int32** | ID of the custodian | [optional] 
**Approved** | Pointer to **int32** | Indicates whether the custodian is approved for the project (1 for approved, 0 for not approved) | [optional] 

## Methods

### NewProjectHasCustodian

`func NewProjectHasCustodian() *ProjectHasCustodian`

NewProjectHasCustodian instantiates a new ProjectHasCustodian object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectHasCustodianWithDefaults

`func NewProjectHasCustodianWithDefaults() *ProjectHasCustodian`

NewProjectHasCustodianWithDefaults instantiates a new ProjectHasCustodian object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectHasCustodian) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectHasCustodian) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectHasCustodian) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProjectHasCustodian) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *ProjectHasCustodian) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectHasCustodian) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectHasCustodian) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ProjectHasCustodian) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetCustodianId

`func (o *ProjectHasCustodian) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *ProjectHasCustodian) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *ProjectHasCustodian) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.

### HasCustodianId

`func (o *ProjectHasCustodian) HasCustodianId() bool`

HasCustodianId returns a boolean if a field has been set.

### GetApproved

`func (o *ProjectHasCustodian) GetApproved() int32`

GetApproved returns the Approved field if non-nil, zero value otherwise.

### GetApprovedOk

`func (o *ProjectHasCustodian) GetApprovedOk() (*int32, bool)`

GetApprovedOk returns a tuple with the Approved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproved

`func (o *ProjectHasCustodian) SetApproved(v int32)`

SetApproved sets Approved field to given value.

### HasApproved

`func (o *ProjectHasCustodian) HasApproved() bool`

HasApproved returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


