# ProjectGetProjectUsers200ResponseDataInnerRegistry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**Verified** | Pointer to **bool** |  | [optional] 
**User** | Pointer to [**ProjectGetProjectUsers200ResponseDataInnerRegistryUser**](ProjectGetProjectUsers200ResponseDataInnerRegistryUser.md) |  | [optional] 
**Organisations** | Pointer to [**[]ProjectGetProjectUsers200ResponseDataInnerRegistryOrganisationsInner**](ProjectGetProjectUsers200ResponseDataInnerRegistryOrganisationsInner.md) |  | [optional] 
**Affiliation** | Pointer to [**NullableProjectGetProjectUsers200ResponseDataInnerRegistryAffiliation**](ProjectGetProjectUsers200ResponseDataInnerRegistryAffiliation.md) |  | [optional] 

## Methods

### NewProjectGetProjectUsers200ResponseDataInnerRegistry

`func NewProjectGetProjectUsers200ResponseDataInnerRegistry() *ProjectGetProjectUsers200ResponseDataInnerRegistry`

NewProjectGetProjectUsers200ResponseDataInnerRegistry instantiates a new ProjectGetProjectUsers200ResponseDataInnerRegistry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectGetProjectUsers200ResponseDataInnerRegistryWithDefaults

`func NewProjectGetProjectUsers200ResponseDataInnerRegistryWithDefaults() *ProjectGetProjectUsers200ResponseDataInnerRegistry`

NewProjectGetProjectUsers200ResponseDataInnerRegistryWithDefaults instantiates a new ProjectGetProjectUsers200ResponseDataInnerRegistry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetVerified

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### GetUser

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetUser() ProjectGetProjectUsers200ResponseDataInnerRegistryUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetUserOk() (*ProjectGetProjectUsers200ResponseDataInnerRegistryUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetUser(v ProjectGetProjectUsers200ResponseDataInnerRegistryUser)`

SetUser sets User field to given value.

### HasUser

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetOrganisations

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetOrganisations() []ProjectGetProjectUsers200ResponseDataInnerRegistryOrganisationsInner`

GetOrganisations returns the Organisations field if non-nil, zero value otherwise.

### GetOrganisationsOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetOrganisationsOk() (*[]ProjectGetProjectUsers200ResponseDataInnerRegistryOrganisationsInner, bool)`

GetOrganisationsOk returns a tuple with the Organisations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisations

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetOrganisations(v []ProjectGetProjectUsers200ResponseDataInnerRegistryOrganisationsInner)`

SetOrganisations sets Organisations field to given value.

### HasOrganisations

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasOrganisations() bool`

HasOrganisations returns a boolean if a field has been set.

### GetAffiliation

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetAffiliation() ProjectGetProjectUsers200ResponseDataInnerRegistryAffiliation`

GetAffiliation returns the Affiliation field if non-nil, zero value otherwise.

### GetAffiliationOk

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) GetAffiliationOk() (*ProjectGetProjectUsers200ResponseDataInnerRegistryAffiliation, bool)`

GetAffiliationOk returns a tuple with the Affiliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliation

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetAffiliation(v ProjectGetProjectUsers200ResponseDataInnerRegistryAffiliation)`

SetAffiliation sets Affiliation field to given value.

### HasAffiliation

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) HasAffiliation() bool`

HasAffiliation returns a boolean if a field has been set.

### SetAffiliationNil

`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) SetAffiliationNil(b bool)`

 SetAffiliationNil sets the value for Affiliation to be an explicit nil

### UnsetAffiliation
`func (o *ProjectGetProjectUsers200ResponseDataInnerRegistry) UnsetAffiliation()`

UnsetAffiliation ensures that no value is present for Affiliation, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


