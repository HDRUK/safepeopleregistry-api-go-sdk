# ONSFile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the ONS file | [optional] 
**Name** | Pointer to **string** | Name of the ONS file | [optional] 
**Path** | Pointer to **string** | Path to the ONS file | [optional] 
**Status** | Pointer to **string** | Status of the ONS file | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the ONS file was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the ONS file was last updated | [optional] 

## Methods

### NewONSFile

`func NewONSFile() *ONSFile`

NewONSFile instantiates a new ONSFile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewONSFileWithDefaults

`func NewONSFileWithDefaults() *ONSFile`

NewONSFileWithDefaults instantiates a new ONSFile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ONSFile) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ONSFile) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ONSFile) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ONSFile) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ONSFile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ONSFile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ONSFile) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ONSFile) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPath

`func (o *ONSFile) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ONSFile) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ONSFile) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *ONSFile) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetStatus

`func (o *ONSFile) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ONSFile) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ONSFile) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ONSFile) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ONSFile) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ONSFile) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ONSFile) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ONSFile) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ONSFile) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ONSFile) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ONSFile) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ONSFile) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


