# ProjectHasOrganisation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ProjectId** | **int32** | ID of the related project | 
**OrganisationId** | **int32** | ID of the related organisation | 
**Organisation** | Pointer to [**Organisation**](Organisation.md) |  | [optional] 
**Project** | Pointer to [**Project**](Project.md) |  | [optional] 

## Methods

### NewProjectHasOrganisation

`func NewProjectHasOrganisation(projectId int32, organisationId int32, ) *ProjectHasOrganisation`

NewProjectHasOrganisation instantiates a new ProjectHasOrganisation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectHasOrganisationWithDefaults

`func NewProjectHasOrganisationWithDefaults() *ProjectHasOrganisation`

NewProjectHasOrganisationWithDefaults instantiates a new ProjectHasOrganisation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectHasOrganisation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectHasOrganisation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectHasOrganisation) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProjectHasOrganisation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *ProjectHasOrganisation) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectHasOrganisation) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectHasOrganisation) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetOrganisationId

`func (o *ProjectHasOrganisation) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *ProjectHasOrganisation) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *ProjectHasOrganisation) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.


### GetOrganisation

`func (o *ProjectHasOrganisation) GetOrganisation() Organisation`

GetOrganisation returns the Organisation field if non-nil, zero value otherwise.

### GetOrganisationOk

`func (o *ProjectHasOrganisation) GetOrganisationOk() (*Organisation, bool)`

GetOrganisationOk returns a tuple with the Organisation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisation

`func (o *ProjectHasOrganisation) SetOrganisation(v Organisation)`

SetOrganisation sets Organisation field to given value.

### HasOrganisation

`func (o *ProjectHasOrganisation) HasOrganisation() bool`

HasOrganisation returns a boolean if a field has been set.

### GetProject

`func (o *ProjectHasOrganisation) GetProject() Project`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectHasOrganisation) GetProjectOk() (*Project, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectHasOrganisation) SetProject(v Project)`

SetProject sets Project field to given value.

### HasProject

`func (o *ProjectHasOrganisation) HasProject() bool`

HasProject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


