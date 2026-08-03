# QueryQuery200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | Pointer to [**QueryQuery200ResponseDataUser**](QueryQuery200ResponseDataUser.md) |  | [optional] 
**Registry** | Pointer to [**QueryQuery200ResponseDataRegistry**](QueryQuery200ResponseDataRegistry.md) |  | [optional] 
**Projects** | Pointer to [**[]QueryQuery200ResponseDataProjectsInner**](QueryQuery200ResponseDataProjectsInner.md) | Projects the queried user is linked to, scoped to the requesting custodian | [optional] 

## Methods

### NewQueryQuery200ResponseData

`func NewQueryQuery200ResponseData() *QueryQuery200ResponseData`

NewQueryQuery200ResponseData instantiates a new QueryQuery200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryQuery200ResponseDataWithDefaults

`func NewQueryQuery200ResponseDataWithDefaults() *QueryQuery200ResponseData`

NewQueryQuery200ResponseDataWithDefaults instantiates a new QueryQuery200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *QueryQuery200ResponseData) GetUser() QueryQuery200ResponseDataUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *QueryQuery200ResponseData) GetUserOk() (*QueryQuery200ResponseDataUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *QueryQuery200ResponseData) SetUser(v QueryQuery200ResponseDataUser)`

SetUser sets User field to given value.

### HasUser

`func (o *QueryQuery200ResponseData) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetRegistry

`func (o *QueryQuery200ResponseData) GetRegistry() QueryQuery200ResponseDataRegistry`

GetRegistry returns the Registry field if non-nil, zero value otherwise.

### GetRegistryOk

`func (o *QueryQuery200ResponseData) GetRegistryOk() (*QueryQuery200ResponseDataRegistry, bool)`

GetRegistryOk returns a tuple with the Registry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistry

`func (o *QueryQuery200ResponseData) SetRegistry(v QueryQuery200ResponseDataRegistry)`

SetRegistry sets Registry field to given value.

### HasRegistry

`func (o *QueryQuery200ResponseData) HasRegistry() bool`

HasRegistry returns a boolean if a field has been set.

### GetProjects

`func (o *QueryQuery200ResponseData) GetProjects() []QueryQuery200ResponseDataProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *QueryQuery200ResponseData) GetProjectsOk() (*[]QueryQuery200ResponseDataProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *QueryQuery200ResponseData) SetProjects(v []QueryQuery200ResponseDataProjectsInner)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *QueryQuery200ResponseData) HasProjects() bool`

HasProjects returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


