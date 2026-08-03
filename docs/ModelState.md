# ModelState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the model state | [optional] 
**StateId** | Pointer to **int32** | ID of the state associated with the model state | [optional] 
**StateableType** | Pointer to **string** | Type of the model associated with the state | [optional] 
**StateableId** | Pointer to **int32** | ID of the model associated with the state | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the model state was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the model state was last updated | [optional] 

## Methods

### NewModelState

`func NewModelState() *ModelState`

NewModelState instantiates a new ModelState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelStateWithDefaults

`func NewModelStateWithDefaults() *ModelState`

NewModelStateWithDefaults instantiates a new ModelState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ModelState) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ModelState) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ModelState) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ModelState) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStateId

`func (o *ModelState) GetStateId() int32`

GetStateId returns the StateId field if non-nil, zero value otherwise.

### GetStateIdOk

`func (o *ModelState) GetStateIdOk() (*int32, bool)`

GetStateIdOk returns a tuple with the StateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateId

`func (o *ModelState) SetStateId(v int32)`

SetStateId sets StateId field to given value.

### HasStateId

`func (o *ModelState) HasStateId() bool`

HasStateId returns a boolean if a field has been set.

### GetStateableType

`func (o *ModelState) GetStateableType() string`

GetStateableType returns the StateableType field if non-nil, zero value otherwise.

### GetStateableTypeOk

`func (o *ModelState) GetStateableTypeOk() (*string, bool)`

GetStateableTypeOk returns a tuple with the StateableType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateableType

`func (o *ModelState) SetStateableType(v string)`

SetStateableType sets StateableType field to given value.

### HasStateableType

`func (o *ModelState) HasStateableType() bool`

HasStateableType returns a boolean if a field has been set.

### GetStateableId

`func (o *ModelState) GetStateableId() int32`

GetStateableId returns the StateableId field if non-nil, zero value otherwise.

### GetStateableIdOk

`func (o *ModelState) GetStateableIdOk() (*int32, bool)`

GetStateableIdOk returns a tuple with the StateableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateableId

`func (o *ModelState) SetStateableId(v int32)`

SetStateableId sets StateableId field to given value.

### HasStateableId

`func (o *ModelState) HasStateableId() bool`

HasStateableId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ModelState) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ModelState) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ModelState) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ModelState) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ModelState) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ModelState) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ModelState) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ModelState) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


