# EntityModelType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the entity model type | [optional] 
**Name** | Pointer to **string** | Name of the entity model type | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the entity model type was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the entity model type was last updated | [optional] 

## Methods

### NewEntityModelType

`func NewEntityModelType() *EntityModelType`

NewEntityModelType instantiates a new EntityModelType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityModelTypeWithDefaults

`func NewEntityModelTypeWithDefaults() *EntityModelType`

NewEntityModelTypeWithDefaults instantiates a new EntityModelType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EntityModelType) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntityModelType) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntityModelType) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *EntityModelType) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *EntityModelType) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EntityModelType) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EntityModelType) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EntityModelType) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCreatedAt

`func (o *EntityModelType) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *EntityModelType) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *EntityModelType) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *EntityModelType) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *EntityModelType) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EntityModelType) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EntityModelType) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *EntityModelType) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


