# ProjectUsersBulkInviteProjectUsersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Users** | [**[]ProjectUsersBulkInviteProjectUsersRequestUsersInner**](ProjectUsersBulkInviteProjectUsersRequestUsersInner.md) |  | 

## Methods

### NewProjectUsersBulkInviteProjectUsersRequest

`func NewProjectUsersBulkInviteProjectUsersRequest(projectId int32, users []ProjectUsersBulkInviteProjectUsersRequestUsersInner, ) *ProjectUsersBulkInviteProjectUsersRequest`

NewProjectUsersBulkInviteProjectUsersRequest instantiates a new ProjectUsersBulkInviteProjectUsersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectUsersBulkInviteProjectUsersRequestWithDefaults

`func NewProjectUsersBulkInviteProjectUsersRequestWithDefaults() *ProjectUsersBulkInviteProjectUsersRequest`

NewProjectUsersBulkInviteProjectUsersRequestWithDefaults instantiates a new ProjectUsersBulkInviteProjectUsersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ProjectUsersBulkInviteProjectUsersRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectUsersBulkInviteProjectUsersRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectUsersBulkInviteProjectUsersRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUsers

`func (o *ProjectUsersBulkInviteProjectUsersRequest) GetUsers() []ProjectUsersBulkInviteProjectUsersRequestUsersInner`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *ProjectUsersBulkInviteProjectUsersRequest) GetUsersOk() (*[]ProjectUsersBulkInviteProjectUsersRequestUsersInner, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *ProjectUsersBulkInviteProjectUsersRequest) SetUsers(v []ProjectUsersBulkInviteProjectUsersRequestUsersInner)`

SetUsers sets Users field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


