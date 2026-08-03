# Experience

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the experience | [optional] 
**ProjectId** | Pointer to **int32** | ID of the project associated with the experience | [optional] 
**From** | Pointer to **string** | Start date of the experience | [optional] 
**To** | Pointer to **string** | End date of the experience | [optional] 
**OrganisationId** | Pointer to **int32** | ID of the organisation associated with the experience | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the experience was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the experience was last updated | [optional] 

## Methods

### NewExperience

`func NewExperience() *Experience`

NewExperience instantiates a new Experience object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperienceWithDefaults

`func NewExperienceWithDefaults() *Experience`

NewExperienceWithDefaults instantiates a new Experience object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Experience) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Experience) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Experience) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Experience) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *Experience) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Experience) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Experience) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *Experience) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *Experience) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *Experience) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *Experience) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *Experience) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *Experience) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *Experience) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *Experience) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *Experience) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetOrganisationId

`func (o *Experience) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *Experience) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *Experience) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *Experience) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Experience) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Experience) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Experience) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Experience) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Experience) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Experience) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Experience) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Experience) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


