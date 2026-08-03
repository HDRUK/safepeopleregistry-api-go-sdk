# SystemConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the system configuration | [optional] 
**Name** | Pointer to **string** | Name of the configuration setting | [optional] 
**Value** | Pointer to **string** | Value of the configuration setting | [optional] 
**Description** | Pointer to **string** | Description of the configuration setting | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the configuration was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the configuration was last updated | [optional] 

## Methods

### NewSystemConfig

`func NewSystemConfig() *SystemConfig`

NewSystemConfig instantiates a new SystemConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigWithDefaults

`func NewSystemConfigWithDefaults() *SystemConfig`

NewSystemConfigWithDefaults instantiates a new SystemConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SystemConfig) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SystemConfig) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SystemConfig) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SystemConfig) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SystemConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SystemConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SystemConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SystemConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetValue

`func (o *SystemConfig) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SystemConfig) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SystemConfig) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *SystemConfig) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetDescription

`func (o *SystemConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SystemConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SystemConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SystemConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SystemConfig) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SystemConfig) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SystemConfig) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SystemConfig) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *SystemConfig) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SystemConfig) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SystemConfig) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SystemConfig) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


