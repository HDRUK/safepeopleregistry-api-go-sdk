# QueryQuery200ResponseDataRegistry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**DeletedAt** | Pointer to **string** |  | [optional] 
**DigiIdent** | Pointer to **string** |  | [optional] 
**DlIdent** | Pointer to **string** |  | [optional] 
**PpIdent** | Pointer to **string** |  | [optional] 
**Verified** | Pointer to **int32** |  | [optional] 
**Training** | Pointer to [**[]Training**](Training.md) | Training records linked to the registry | [optional] 
**History** | Pointer to [**[]QueryQuery200ResponseDataRegistryAllOfHistoryInner**](QueryQuery200ResponseDataRegistryAllOfHistoryInner.md) | History records linked to the registry, each with its related affiliation and project | [optional] 

## Methods

### NewQueryQuery200ResponseDataRegistry

`func NewQueryQuery200ResponseDataRegistry() *QueryQuery200ResponseDataRegistry`

NewQueryQuery200ResponseDataRegistry instantiates a new QueryQuery200ResponseDataRegistry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryQuery200ResponseDataRegistryWithDefaults

`func NewQueryQuery200ResponseDataRegistryWithDefaults() *QueryQuery200ResponseDataRegistry`

NewQueryQuery200ResponseDataRegistryWithDefaults instantiates a new QueryQuery200ResponseDataRegistry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *QueryQuery200ResponseDataRegistry) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QueryQuery200ResponseDataRegistry) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QueryQuery200ResponseDataRegistry) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *QueryQuery200ResponseDataRegistry) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *QueryQuery200ResponseDataRegistry) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *QueryQuery200ResponseDataRegistry) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *QueryQuery200ResponseDataRegistry) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *QueryQuery200ResponseDataRegistry) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *QueryQuery200ResponseDataRegistry) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *QueryQuery200ResponseDataRegistry) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *QueryQuery200ResponseDataRegistry) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *QueryQuery200ResponseDataRegistry) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *QueryQuery200ResponseDataRegistry) GetDeletedAt() string`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *QueryQuery200ResponseDataRegistry) GetDeletedAtOk() (*string, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *QueryQuery200ResponseDataRegistry) SetDeletedAt(v string)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *QueryQuery200ResponseDataRegistry) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetDigiIdent

`func (o *QueryQuery200ResponseDataRegistry) GetDigiIdent() string`

GetDigiIdent returns the DigiIdent field if non-nil, zero value otherwise.

### GetDigiIdentOk

`func (o *QueryQuery200ResponseDataRegistry) GetDigiIdentOk() (*string, bool)`

GetDigiIdentOk returns a tuple with the DigiIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigiIdent

`func (o *QueryQuery200ResponseDataRegistry) SetDigiIdent(v string)`

SetDigiIdent sets DigiIdent field to given value.

### HasDigiIdent

`func (o *QueryQuery200ResponseDataRegistry) HasDigiIdent() bool`

HasDigiIdent returns a boolean if a field has been set.

### GetDlIdent

`func (o *QueryQuery200ResponseDataRegistry) GetDlIdent() string`

GetDlIdent returns the DlIdent field if non-nil, zero value otherwise.

### GetDlIdentOk

`func (o *QueryQuery200ResponseDataRegistry) GetDlIdentOk() (*string, bool)`

GetDlIdentOk returns a tuple with the DlIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlIdent

`func (o *QueryQuery200ResponseDataRegistry) SetDlIdent(v string)`

SetDlIdent sets DlIdent field to given value.

### HasDlIdent

`func (o *QueryQuery200ResponseDataRegistry) HasDlIdent() bool`

HasDlIdent returns a boolean if a field has been set.

### GetPpIdent

`func (o *QueryQuery200ResponseDataRegistry) GetPpIdent() string`

GetPpIdent returns the PpIdent field if non-nil, zero value otherwise.

### GetPpIdentOk

`func (o *QueryQuery200ResponseDataRegistry) GetPpIdentOk() (*string, bool)`

GetPpIdentOk returns a tuple with the PpIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPpIdent

`func (o *QueryQuery200ResponseDataRegistry) SetPpIdent(v string)`

SetPpIdent sets PpIdent field to given value.

### HasPpIdent

`func (o *QueryQuery200ResponseDataRegistry) HasPpIdent() bool`

HasPpIdent returns a boolean if a field has been set.

### GetVerified

`func (o *QueryQuery200ResponseDataRegistry) GetVerified() int32`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *QueryQuery200ResponseDataRegistry) GetVerifiedOk() (*int32, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *QueryQuery200ResponseDataRegistry) SetVerified(v int32)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *QueryQuery200ResponseDataRegistry) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### GetTraining

`func (o *QueryQuery200ResponseDataRegistry) GetTraining() []Training`

GetTraining returns the Training field if non-nil, zero value otherwise.

### GetTrainingOk

`func (o *QueryQuery200ResponseDataRegistry) GetTrainingOk() (*[]Training, bool)`

GetTrainingOk returns a tuple with the Training field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraining

`func (o *QueryQuery200ResponseDataRegistry) SetTraining(v []Training)`

SetTraining sets Training field to given value.

### HasTraining

`func (o *QueryQuery200ResponseDataRegistry) HasTraining() bool`

HasTraining returns a boolean if a field has been set.

### GetHistory

`func (o *QueryQuery200ResponseDataRegistry) GetHistory() []QueryQuery200ResponseDataRegistryAllOfHistoryInner`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *QueryQuery200ResponseDataRegistry) GetHistoryOk() (*[]QueryQuery200ResponseDataRegistryAllOfHistoryInner, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *QueryQuery200ResponseDataRegistry) SetHistory(v []QueryQuery200ResponseDataRegistryAllOfHistoryInner)`

SetHistory sets History field to given value.

### HasHistory

`func (o *QueryQuery200ResponseDataRegistry) HasHistory() bool`

HasHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


