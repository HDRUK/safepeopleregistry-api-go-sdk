# DebugLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the debug log | [optional] 
**Class** | Pointer to **string** | Class name where the log was generated | [optional] 
**Log** | Pointer to **string** | Log message | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the log was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the log was last updated | [optional] 

## Methods

### NewDebugLog

`func NewDebugLog() *DebugLog`

NewDebugLog instantiates a new DebugLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDebugLogWithDefaults

`func NewDebugLogWithDefaults() *DebugLog`

NewDebugLogWithDefaults instantiates a new DebugLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DebugLog) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DebugLog) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DebugLog) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DebugLog) HasId() bool`

HasId returns a boolean if a field has been set.

### GetClass

`func (o *DebugLog) GetClass() string`

GetClass returns the Class field if non-nil, zero value otherwise.

### GetClassOk

`func (o *DebugLog) GetClassOk() (*string, bool)`

GetClassOk returns a tuple with the Class field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClass

`func (o *DebugLog) SetClass(v string)`

SetClass sets Class field to given value.

### HasClass

`func (o *DebugLog) HasClass() bool`

HasClass returns a boolean if a field has been set.

### GetLog

`func (o *DebugLog) GetLog() string`

GetLog returns the Log field if non-nil, zero value otherwise.

### GetLogOk

`func (o *DebugLog) GetLogOk() (*string, bool)`

GetLogOk returns a tuple with the Log field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLog

`func (o *DebugLog) SetLog(v string)`

SetLog sets Log field to given value.

### HasLog

`func (o *DebugLog) HasLog() bool`

HasLog returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DebugLog) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DebugLog) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DebugLog) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DebugLog) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DebugLog) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DebugLog) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DebugLog) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DebugLog) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


