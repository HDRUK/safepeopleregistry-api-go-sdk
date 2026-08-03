# Resolution

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the resolution | [optional] 
**Comment** | Pointer to **string** | Comment associated with the resolution | [optional] 
**CustodianBy** | Pointer to **int32** | ID of the custodian who resolved the issue | [optional] 
**RegistryId** | Pointer to **int32** | ID of the registry associated with the resolution | [optional] 
**Resolved** | Pointer to **bool** | Indicates whether the resolution is resolved | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the resolution was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the resolution was last updated | [optional] 

## Methods

### NewResolution

`func NewResolution() *Resolution`

NewResolution instantiates a new Resolution object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResolutionWithDefaults

`func NewResolutionWithDefaults() *Resolution`

NewResolutionWithDefaults instantiates a new Resolution object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Resolution) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Resolution) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Resolution) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Resolution) HasId() bool`

HasId returns a boolean if a field has been set.

### GetComment

`func (o *Resolution) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *Resolution) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *Resolution) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *Resolution) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetCustodianBy

`func (o *Resolution) GetCustodianBy() int32`

GetCustodianBy returns the CustodianBy field if non-nil, zero value otherwise.

### GetCustodianByOk

`func (o *Resolution) GetCustodianByOk() (*int32, bool)`

GetCustodianByOk returns a tuple with the CustodianBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianBy

`func (o *Resolution) SetCustodianBy(v int32)`

SetCustodianBy sets CustodianBy field to given value.

### HasCustodianBy

`func (o *Resolution) HasCustodianBy() bool`

HasCustodianBy returns a boolean if a field has been set.

### GetRegistryId

`func (o *Resolution) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *Resolution) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *Resolution) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *Resolution) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetResolved

`func (o *Resolution) GetResolved() bool`

GetResolved returns the Resolved field if non-nil, zero value otherwise.

### GetResolvedOk

`func (o *Resolution) GetResolvedOk() (*bool, bool)`

GetResolvedOk returns a tuple with the Resolved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolved

`func (o *Resolution) SetResolved(v bool)`

SetResolved sets Resolved field to given value.

### HasResolved

`func (o *Resolution) HasResolved() bool`

HasResolved returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Resolution) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Resolution) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Resolution) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Resolution) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Resolution) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Resolution) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Resolution) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Resolution) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


