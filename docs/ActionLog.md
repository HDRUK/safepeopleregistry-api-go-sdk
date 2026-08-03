# ActionLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**EntityType** | Pointer to **string** | Type of the entity associated with the action log | [optional] 
**EntityId** | Pointer to **int32** | ID of the entity associated with the action log | [optional] 
**Action** | Pointer to **string** | Description of the action performed | [optional] 
**CompletedAt** | Pointer to **time.Time** | Timestamp when the action was completed (nullable) | [optional] 

## Methods

### NewActionLog

`func NewActionLog() *ActionLog`

NewActionLog instantiates a new ActionLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActionLogWithDefaults

`func NewActionLogWithDefaults() *ActionLog`

NewActionLogWithDefaults instantiates a new ActionLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ActionLog) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ActionLog) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ActionLog) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ActionLog) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEntityType

`func (o *ActionLog) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *ActionLog) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *ActionLog) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.

### HasEntityType

`func (o *ActionLog) HasEntityType() bool`

HasEntityType returns a boolean if a field has been set.

### GetEntityId

`func (o *ActionLog) GetEntityId() int32`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *ActionLog) GetEntityIdOk() (*int32, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *ActionLog) SetEntityId(v int32)`

SetEntityId sets EntityId field to given value.

### HasEntityId

`func (o *ActionLog) HasEntityId() bool`

HasEntityId returns a boolean if a field has been set.

### GetAction

`func (o *ActionLog) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ActionLog) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ActionLog) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *ActionLog) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetCompletedAt

`func (o *ActionLog) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ActionLog) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ActionLog) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ActionLog) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


