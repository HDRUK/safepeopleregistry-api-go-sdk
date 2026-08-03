# ProjectHasUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Project** | Pointer to [**Project**](Project.md) |  | [optional] 
**Role** | Pointer to [**ProjectRole**](ProjectRole.md) |  | [optional] 
**Affiliation** | Pointer to [**Affiliation**](Affiliation.md) |  | [optional] 

## Methods

### NewProjectHasUser

`func NewProjectHasUser() *ProjectHasUser`

NewProjectHasUser instantiates a new ProjectHasUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectHasUserWithDefaults

`func NewProjectHasUserWithDefaults() *ProjectHasUser`

NewProjectHasUserWithDefaults instantiates a new ProjectHasUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProject

`func (o *ProjectHasUser) GetProject() Project`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectHasUser) GetProjectOk() (*Project, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectHasUser) SetProject(v Project)`

SetProject sets Project field to given value.

### HasProject

`func (o *ProjectHasUser) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetRole

`func (o *ProjectHasUser) GetRole() ProjectRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ProjectHasUser) GetRoleOk() (*ProjectRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ProjectHasUser) SetRole(v ProjectRole)`

SetRole sets Role field to given value.

### HasRole

`func (o *ProjectHasUser) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetAffiliation

`func (o *ProjectHasUser) GetAffiliation() Affiliation`

GetAffiliation returns the Affiliation field if non-nil, zero value otherwise.

### GetAffiliationOk

`func (o *ProjectHasUser) GetAffiliationOk() (*Affiliation, bool)`

GetAffiliationOk returns a tuple with the Affiliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliation

`func (o *ProjectHasUser) SetAffiliation(v Affiliation)`

SetAffiliation sets Affiliation field to given value.

### HasAffiliation

`func (o *ProjectHasUser) HasAffiliation() bool`

HasAffiliation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


