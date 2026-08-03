# CustodianGetProjectsUsers200ResponseDataDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**UserDigitalIdent** | Pointer to **string** |  | [optional] 
**ProjectRoleId** | Pointer to **int32** |  | [optional] 
**PrimaryContact** | Pointer to **bool** |  | [optional] 
**AffiliationId** | Pointer to **int32** |  | [optional] 
**Role** | Pointer to [**CustodianGetProjectsUsers200ResponseDataDataInnerRole**](CustodianGetProjectsUsers200ResponseDataDataInnerRole.md) |  | [optional] 
**Affiliation** | Pointer to [**CustodianGetProjectsUsers200ResponseDataDataInnerAffiliation**](CustodianGetProjectsUsers200ResponseDataDataInnerAffiliation.md) |  | [optional] 
**Registry** | Pointer to [**CustodianGetProjectsUsers200ResponseDataDataInnerRegistry**](CustodianGetProjectsUsers200ResponseDataDataInnerRegistry.md) |  | [optional] 
**Project** | Pointer to [**CustodianGetProjectsUsers200ResponseDataDataInnerProject**](CustodianGetProjectsUsers200ResponseDataDataInnerProject.md) |  | [optional] 

## Methods

### NewCustodianGetProjectsUsers200ResponseDataDataInner

`func NewCustodianGetProjectsUsers200ResponseDataDataInner() *CustodianGetProjectsUsers200ResponseDataDataInner`

NewCustodianGetProjectsUsers200ResponseDataDataInner instantiates a new CustodianGetProjectsUsers200ResponseDataDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianGetProjectsUsers200ResponseDataDataInnerWithDefaults

`func NewCustodianGetProjectsUsers200ResponseDataDataInnerWithDefaults() *CustodianGetProjectsUsers200ResponseDataDataInner`

NewCustodianGetProjectsUsers200ResponseDataDataInnerWithDefaults instantiates a new CustodianGetProjectsUsers200ResponseDataDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetUserDigitalIdent

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetUserDigitalIdent() string`

GetUserDigitalIdent returns the UserDigitalIdent field if non-nil, zero value otherwise.

### GetUserDigitalIdentOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetUserDigitalIdentOk() (*string, bool)`

GetUserDigitalIdentOk returns a tuple with the UserDigitalIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserDigitalIdent

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetUserDigitalIdent(v string)`

SetUserDigitalIdent sets UserDigitalIdent field to given value.

### HasUserDigitalIdent

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasUserDigitalIdent() bool`

HasUserDigitalIdent returns a boolean if a field has been set.

### GetProjectRoleId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProjectRoleId() int32`

GetProjectRoleId returns the ProjectRoleId field if non-nil, zero value otherwise.

### GetProjectRoleIdOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProjectRoleIdOk() (*int32, bool)`

GetProjectRoleIdOk returns a tuple with the ProjectRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectRoleId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetProjectRoleId(v int32)`

SetProjectRoleId sets ProjectRoleId field to given value.

### HasProjectRoleId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasProjectRoleId() bool`

HasProjectRoleId returns a boolean if a field has been set.

### GetPrimaryContact

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetPrimaryContact() bool`

GetPrimaryContact returns the PrimaryContact field if non-nil, zero value otherwise.

### GetPrimaryContactOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetPrimaryContactOk() (*bool, bool)`

GetPrimaryContactOk returns a tuple with the PrimaryContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryContact

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetPrimaryContact(v bool)`

SetPrimaryContact sets PrimaryContact field to given value.

### HasPrimaryContact

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasPrimaryContact() bool`

HasPrimaryContact returns a boolean if a field has been set.

### GetAffiliationId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetAffiliationId() int32`

GetAffiliationId returns the AffiliationId field if non-nil, zero value otherwise.

### GetAffiliationIdOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetAffiliationIdOk() (*int32, bool)`

GetAffiliationIdOk returns a tuple with the AffiliationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliationId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetAffiliationId(v int32)`

SetAffiliationId sets AffiliationId field to given value.

### HasAffiliationId

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasAffiliationId() bool`

HasAffiliationId returns a boolean if a field has been set.

### GetRole

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetRole() CustodianGetProjectsUsers200ResponseDataDataInnerRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetRoleOk() (*CustodianGetProjectsUsers200ResponseDataDataInnerRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetRole(v CustodianGetProjectsUsers200ResponseDataDataInnerRole)`

SetRole sets Role field to given value.

### HasRole

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetAffiliation

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetAffiliation() CustodianGetProjectsUsers200ResponseDataDataInnerAffiliation`

GetAffiliation returns the Affiliation field if non-nil, zero value otherwise.

### GetAffiliationOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetAffiliationOk() (*CustodianGetProjectsUsers200ResponseDataDataInnerAffiliation, bool)`

GetAffiliationOk returns a tuple with the Affiliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliation

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetAffiliation(v CustodianGetProjectsUsers200ResponseDataDataInnerAffiliation)`

SetAffiliation sets Affiliation field to given value.

### HasAffiliation

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasAffiliation() bool`

HasAffiliation returns a boolean if a field has been set.

### GetRegistry

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetRegistry() CustodianGetProjectsUsers200ResponseDataDataInnerRegistry`

GetRegistry returns the Registry field if non-nil, zero value otherwise.

### GetRegistryOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetRegistryOk() (*CustodianGetProjectsUsers200ResponseDataDataInnerRegistry, bool)`

GetRegistryOk returns a tuple with the Registry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistry

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetRegistry(v CustodianGetProjectsUsers200ResponseDataDataInnerRegistry)`

SetRegistry sets Registry field to given value.

### HasRegistry

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasRegistry() bool`

HasRegistry returns a boolean if a field has been set.

### GetProject

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProject() CustodianGetProjectsUsers200ResponseDataDataInnerProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) GetProjectOk() (*CustodianGetProjectsUsers200ResponseDataDataInnerProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) SetProject(v CustodianGetProjectsUsers200ResponseDataDataInnerProject)`

SetProject sets Project field to given value.

### HasProject

`func (o *CustodianGetProjectsUsers200ResponseDataDataInner) HasProject() bool`

HasProject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


