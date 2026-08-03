# CustodianModelConfigGetEntityModels200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**EntityModelTypeId** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 
**Active** | Pointer to **bool** |  | [optional] 

## Methods

### NewCustodianModelConfigGetEntityModels200ResponseDataInner

`func NewCustodianModelConfigGetEntityModels200ResponseDataInner() *CustodianModelConfigGetEntityModels200ResponseDataInner`

NewCustodianModelConfigGetEntityModels200ResponseDataInner instantiates a new CustodianModelConfigGetEntityModels200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianModelConfigGetEntityModels200ResponseDataInnerWithDefaults

`func NewCustodianModelConfigGetEntityModels200ResponseDataInnerWithDefaults() *CustodianModelConfigGetEntityModels200ResponseDataInner`

NewCustodianModelConfigGetEntityModels200ResponseDataInnerWithDefaults instantiates a new CustodianModelConfigGetEntityModels200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEntityModelTypeId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetEntityModelTypeId() int32`

GetEntityModelTypeId returns the EntityModelTypeId field if non-nil, zero value otherwise.

### GetEntityModelTypeIdOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetEntityModelTypeIdOk() (*int32, bool)`

GetEntityModelTypeIdOk returns a tuple with the EntityModelTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityModelTypeId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetEntityModelTypeId(v int32)`

SetEntityModelTypeId sets EntityModelTypeId field to given value.

### HasEntityModelTypeId

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasEntityModelTypeId() bool`

HasEntityModelTypeId returns a boolean if a field has been set.

### GetDescription

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCreatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetActive

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CustodianModelConfigGetEntityModels200ResponseDataInner) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


