# ValidationCheck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the validation check | [optional] 
**Name** | **string** | Name of the validation check | 
**Description** | **string** | Description of the validation check | 
**AppliesTo** | **string** | Context to which the validation check applies | 
**Enabled** | Pointer to **bool** | Indicates whether the validation check is enabled | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the validation check was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the validation check was last updated | [optional] 
**CustodianId** | Pointer to **int32** | Custodian id or null | [optional] 

## Methods

### NewValidationCheck

`func NewValidationCheck(name string, description string, appliesTo string, ) *ValidationCheck`

NewValidationCheck instantiates a new ValidationCheck object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationCheckWithDefaults

`func NewValidationCheckWithDefaults() *ValidationCheck`

NewValidationCheckWithDefaults instantiates a new ValidationCheck object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ValidationCheck) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ValidationCheck) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ValidationCheck) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ValidationCheck) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ValidationCheck) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ValidationCheck) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ValidationCheck) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ValidationCheck) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ValidationCheck) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ValidationCheck) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetAppliesTo

`func (o *ValidationCheck) GetAppliesTo() string`

GetAppliesTo returns the AppliesTo field if non-nil, zero value otherwise.

### GetAppliesToOk

`func (o *ValidationCheck) GetAppliesToOk() (*string, bool)`

GetAppliesToOk returns a tuple with the AppliesTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppliesTo

`func (o *ValidationCheck) SetAppliesTo(v string)`

SetAppliesTo sets AppliesTo field to given value.


### GetEnabled

`func (o *ValidationCheck) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ValidationCheck) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ValidationCheck) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ValidationCheck) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ValidationCheck) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ValidationCheck) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ValidationCheck) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ValidationCheck) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ValidationCheck) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ValidationCheck) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ValidationCheck) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ValidationCheck) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetCustodianId

`func (o *ValidationCheck) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *ValidationCheck) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *ValidationCheck) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.

### HasCustodianId

`func (o *ValidationCheck) HasCustodianId() bool`

HasCustodianId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


