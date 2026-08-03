# ValidationLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**EntityType** | Pointer to **string** | Type of the primary entity associated with the validation log | [optional] 
**EntityId** | Pointer to **int32** | ID of the primary entity associated with the validation log | [optional] 
**SecondaryEntityType** | Pointer to **string** | Type of the secondary entity associated with the validation log | [optional] 
**SecondaryEntityId** | Pointer to **int32** | ID of the secondary entity associated with the validation log | [optional] 
**TertiaryEntityType** | Pointer to **string** | Type of the tertiary entity associated with the validation log | [optional] 
**TertiaryEntityId** | Pointer to **int32** | ID of the tertiary entity associated with the validation log | [optional] 
**Name** | Pointer to **string** | Name of the validation log entry | [optional] 
**CompletedAt** | Pointer to **time.Time** | Timestamp when the validation was completed (nullable) | [optional] 
**ManuallyConfirmed** | Pointer to **bool** | Whether the validation was manually confirmed | [optional] 

## Methods

### NewValidationLog

`func NewValidationLog() *ValidationLog`

NewValidationLog instantiates a new ValidationLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationLogWithDefaults

`func NewValidationLogWithDefaults() *ValidationLog`

NewValidationLogWithDefaults instantiates a new ValidationLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ValidationLog) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ValidationLog) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ValidationLog) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ValidationLog) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEntityType

`func (o *ValidationLog) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *ValidationLog) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *ValidationLog) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.

### HasEntityType

`func (o *ValidationLog) HasEntityType() bool`

HasEntityType returns a boolean if a field has been set.

### GetEntityId

`func (o *ValidationLog) GetEntityId() int32`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *ValidationLog) GetEntityIdOk() (*int32, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *ValidationLog) SetEntityId(v int32)`

SetEntityId sets EntityId field to given value.

### HasEntityId

`func (o *ValidationLog) HasEntityId() bool`

HasEntityId returns a boolean if a field has been set.

### GetSecondaryEntityType

`func (o *ValidationLog) GetSecondaryEntityType() string`

GetSecondaryEntityType returns the SecondaryEntityType field if non-nil, zero value otherwise.

### GetSecondaryEntityTypeOk

`func (o *ValidationLog) GetSecondaryEntityTypeOk() (*string, bool)`

GetSecondaryEntityTypeOk returns a tuple with the SecondaryEntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryEntityType

`func (o *ValidationLog) SetSecondaryEntityType(v string)`

SetSecondaryEntityType sets SecondaryEntityType field to given value.

### HasSecondaryEntityType

`func (o *ValidationLog) HasSecondaryEntityType() bool`

HasSecondaryEntityType returns a boolean if a field has been set.

### GetSecondaryEntityId

`func (o *ValidationLog) GetSecondaryEntityId() int32`

GetSecondaryEntityId returns the SecondaryEntityId field if non-nil, zero value otherwise.

### GetSecondaryEntityIdOk

`func (o *ValidationLog) GetSecondaryEntityIdOk() (*int32, bool)`

GetSecondaryEntityIdOk returns a tuple with the SecondaryEntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryEntityId

`func (o *ValidationLog) SetSecondaryEntityId(v int32)`

SetSecondaryEntityId sets SecondaryEntityId field to given value.

### HasSecondaryEntityId

`func (o *ValidationLog) HasSecondaryEntityId() bool`

HasSecondaryEntityId returns a boolean if a field has been set.

### GetTertiaryEntityType

`func (o *ValidationLog) GetTertiaryEntityType() string`

GetTertiaryEntityType returns the TertiaryEntityType field if non-nil, zero value otherwise.

### GetTertiaryEntityTypeOk

`func (o *ValidationLog) GetTertiaryEntityTypeOk() (*string, bool)`

GetTertiaryEntityTypeOk returns a tuple with the TertiaryEntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTertiaryEntityType

`func (o *ValidationLog) SetTertiaryEntityType(v string)`

SetTertiaryEntityType sets TertiaryEntityType field to given value.

### HasTertiaryEntityType

`func (o *ValidationLog) HasTertiaryEntityType() bool`

HasTertiaryEntityType returns a boolean if a field has been set.

### GetTertiaryEntityId

`func (o *ValidationLog) GetTertiaryEntityId() int32`

GetTertiaryEntityId returns the TertiaryEntityId field if non-nil, zero value otherwise.

### GetTertiaryEntityIdOk

`func (o *ValidationLog) GetTertiaryEntityIdOk() (*int32, bool)`

GetTertiaryEntityIdOk returns a tuple with the TertiaryEntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTertiaryEntityId

`func (o *ValidationLog) SetTertiaryEntityId(v int32)`

SetTertiaryEntityId sets TertiaryEntityId field to given value.

### HasTertiaryEntityId

`func (o *ValidationLog) HasTertiaryEntityId() bool`

HasTertiaryEntityId returns a boolean if a field has been set.

### GetName

`func (o *ValidationLog) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ValidationLog) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ValidationLog) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ValidationLog) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCompletedAt

`func (o *ValidationLog) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ValidationLog) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ValidationLog) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ValidationLog) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### GetManuallyConfirmed

`func (o *ValidationLog) GetManuallyConfirmed() bool`

GetManuallyConfirmed returns the ManuallyConfirmed field if non-nil, zero value otherwise.

### GetManuallyConfirmedOk

`func (o *ValidationLog) GetManuallyConfirmedOk() (*bool, bool)`

GetManuallyConfirmedOk returns a tuple with the ManuallyConfirmed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyConfirmed

`func (o *ValidationLog) SetManuallyConfirmed(v bool)`

SetManuallyConfirmed sets ManuallyConfirmed field to given value.

### HasManuallyConfirmed

`func (o *ValidationLog) HasManuallyConfirmed() bool`

HasManuallyConfirmed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


