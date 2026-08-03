# EntityModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the entity model | [optional] 
**Name** | Pointer to **string** | Name of the entity model | [optional] 
**Description** | Pointer to **string** | Description of the entity model | [optional] 
**EntityModelTypeId** | Pointer to **int32** | ID of the entity model type associated with this model | [optional] 
**CallsFile** | Pointer to **bool** | Indicates whether the model calls a file | [optional] 
**FilePath** | Pointer to **string** | Path to the file called by the model | [optional] 
**CallsOperation** | Pointer to **bool** | Indicates whether the model calls an operation | [optional] 
**Operation** | Pointer to **string** | Operation called by the model | [optional] 
**Active** | Pointer to **int32** | Indicates whether the model is active (1 for active, 0 for inactive) | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the entity model was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the entity model was last updated | [optional] 

## Methods

### NewEntityModel

`func NewEntityModel() *EntityModel`

NewEntityModel instantiates a new EntityModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityModelWithDefaults

`func NewEntityModelWithDefaults() *EntityModel`

NewEntityModelWithDefaults instantiates a new EntityModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EntityModel) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntityModel) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntityModel) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *EntityModel) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *EntityModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EntityModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EntityModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EntityModel) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *EntityModel) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EntityModel) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EntityModel) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EntityModel) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEntityModelTypeId

`func (o *EntityModel) GetEntityModelTypeId() int32`

GetEntityModelTypeId returns the EntityModelTypeId field if non-nil, zero value otherwise.

### GetEntityModelTypeIdOk

`func (o *EntityModel) GetEntityModelTypeIdOk() (*int32, bool)`

GetEntityModelTypeIdOk returns a tuple with the EntityModelTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityModelTypeId

`func (o *EntityModel) SetEntityModelTypeId(v int32)`

SetEntityModelTypeId sets EntityModelTypeId field to given value.

### HasEntityModelTypeId

`func (o *EntityModel) HasEntityModelTypeId() bool`

HasEntityModelTypeId returns a boolean if a field has been set.

### GetCallsFile

`func (o *EntityModel) GetCallsFile() bool`

GetCallsFile returns the CallsFile field if non-nil, zero value otherwise.

### GetCallsFileOk

`func (o *EntityModel) GetCallsFileOk() (*bool, bool)`

GetCallsFileOk returns a tuple with the CallsFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallsFile

`func (o *EntityModel) SetCallsFile(v bool)`

SetCallsFile sets CallsFile field to given value.

### HasCallsFile

`func (o *EntityModel) HasCallsFile() bool`

HasCallsFile returns a boolean if a field has been set.

### GetFilePath

`func (o *EntityModel) GetFilePath() string`

GetFilePath returns the FilePath field if non-nil, zero value otherwise.

### GetFilePathOk

`func (o *EntityModel) GetFilePathOk() (*string, bool)`

GetFilePathOk returns a tuple with the FilePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilePath

`func (o *EntityModel) SetFilePath(v string)`

SetFilePath sets FilePath field to given value.

### HasFilePath

`func (o *EntityModel) HasFilePath() bool`

HasFilePath returns a boolean if a field has been set.

### GetCallsOperation

`func (o *EntityModel) GetCallsOperation() bool`

GetCallsOperation returns the CallsOperation field if non-nil, zero value otherwise.

### GetCallsOperationOk

`func (o *EntityModel) GetCallsOperationOk() (*bool, bool)`

GetCallsOperationOk returns a tuple with the CallsOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallsOperation

`func (o *EntityModel) SetCallsOperation(v bool)`

SetCallsOperation sets CallsOperation field to given value.

### HasCallsOperation

`func (o *EntityModel) HasCallsOperation() bool`

HasCallsOperation returns a boolean if a field has been set.

### GetOperation

`func (o *EntityModel) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *EntityModel) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *EntityModel) SetOperation(v string)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *EntityModel) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetActive

`func (o *EntityModel) GetActive() int32`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EntityModel) GetActiveOk() (*int32, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EntityModel) SetActive(v int32)`

SetActive sets Active field to given value.

### HasActive

`func (o *EntityModel) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedAt

`func (o *EntityModel) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *EntityModel) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *EntityModel) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *EntityModel) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *EntityModel) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EntityModel) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EntityModel) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *EntityModel) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


