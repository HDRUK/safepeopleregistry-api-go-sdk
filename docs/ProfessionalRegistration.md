# ProfessionalRegistration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the professional registration | [optional] 
**MemberId** | Pointer to **string** | Member ID associated with the professional registration | [optional] 
**Name** | Pointer to **string** | Name of the professional registration | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the professional registration was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the professional registration was last updated | [optional] 

## Methods

### NewProfessionalRegistration

`func NewProfessionalRegistration() *ProfessionalRegistration`

NewProfessionalRegistration instantiates a new ProfessionalRegistration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProfessionalRegistrationWithDefaults

`func NewProfessionalRegistrationWithDefaults() *ProfessionalRegistration`

NewProfessionalRegistrationWithDefaults instantiates a new ProfessionalRegistration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProfessionalRegistration) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProfessionalRegistration) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProfessionalRegistration) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProfessionalRegistration) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMemberId

`func (o *ProfessionalRegistration) GetMemberId() string`

GetMemberId returns the MemberId field if non-nil, zero value otherwise.

### GetMemberIdOk

`func (o *ProfessionalRegistration) GetMemberIdOk() (*string, bool)`

GetMemberIdOk returns a tuple with the MemberId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberId

`func (o *ProfessionalRegistration) SetMemberId(v string)`

SetMemberId sets MemberId field to given value.

### HasMemberId

`func (o *ProfessionalRegistration) HasMemberId() bool`

HasMemberId returns a boolean if a field has been set.

### GetName

`func (o *ProfessionalRegistration) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProfessionalRegistration) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProfessionalRegistration) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProfessionalRegistration) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ProfessionalRegistration) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProfessionalRegistration) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProfessionalRegistration) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProfessionalRegistration) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ProfessionalRegistration) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProfessionalRegistration) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProfessionalRegistration) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProfessionalRegistration) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


