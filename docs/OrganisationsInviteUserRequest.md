# OrganisationsInviteUserRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LastName** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**IsDelegate** | Pointer to **int32** |  | [optional] 
**DepartmentId** | Pointer to **int32** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**UserGroup** | Pointer to **string** |  | [optional] 
**FromCustodian** | Pointer to **bool** |  | [optional] 

## Methods

### NewOrganisationsInviteUserRequest

`func NewOrganisationsInviteUserRequest() *OrganisationsInviteUserRequest`

NewOrganisationsInviteUserRequest instantiates a new OrganisationsInviteUserRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganisationsInviteUserRequestWithDefaults

`func NewOrganisationsInviteUserRequestWithDefaults() *OrganisationsInviteUserRequest`

NewOrganisationsInviteUserRequestWithDefaults instantiates a new OrganisationsInviteUserRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLastName

`func (o *OrganisationsInviteUserRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *OrganisationsInviteUserRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *OrganisationsInviteUserRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *OrganisationsInviteUserRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetFirstName

`func (o *OrganisationsInviteUserRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *OrganisationsInviteUserRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *OrganisationsInviteUserRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *OrganisationsInviteUserRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetEmail

`func (o *OrganisationsInviteUserRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *OrganisationsInviteUserRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *OrganisationsInviteUserRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *OrganisationsInviteUserRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetIsDelegate

`func (o *OrganisationsInviteUserRequest) GetIsDelegate() int32`

GetIsDelegate returns the IsDelegate field if non-nil, zero value otherwise.

### GetIsDelegateOk

`func (o *OrganisationsInviteUserRequest) GetIsDelegateOk() (*int32, bool)`

GetIsDelegateOk returns a tuple with the IsDelegate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDelegate

`func (o *OrganisationsInviteUserRequest) SetIsDelegate(v int32)`

SetIsDelegate sets IsDelegate field to given value.

### HasIsDelegate

`func (o *OrganisationsInviteUserRequest) HasIsDelegate() bool`

HasIsDelegate returns a boolean if a field has been set.

### GetDepartmentId

`func (o *OrganisationsInviteUserRequest) GetDepartmentId() int32`

GetDepartmentId returns the DepartmentId field if non-nil, zero value otherwise.

### GetDepartmentIdOk

`func (o *OrganisationsInviteUserRequest) GetDepartmentIdOk() (*int32, bool)`

GetDepartmentIdOk returns a tuple with the DepartmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentId

`func (o *OrganisationsInviteUserRequest) SetDepartmentId(v int32)`

SetDepartmentId sets DepartmentId field to given value.

### HasDepartmentId

`func (o *OrganisationsInviteUserRequest) HasDepartmentId() bool`

HasDepartmentId returns a boolean if a field has been set.

### GetRole

`func (o *OrganisationsInviteUserRequest) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *OrganisationsInviteUserRequest) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *OrganisationsInviteUserRequest) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *OrganisationsInviteUserRequest) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetUserGroup

`func (o *OrganisationsInviteUserRequest) GetUserGroup() string`

GetUserGroup returns the UserGroup field if non-nil, zero value otherwise.

### GetUserGroupOk

`func (o *OrganisationsInviteUserRequest) GetUserGroupOk() (*string, bool)`

GetUserGroupOk returns a tuple with the UserGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserGroup

`func (o *OrganisationsInviteUserRequest) SetUserGroup(v string)`

SetUserGroup sets UserGroup field to given value.

### HasUserGroup

`func (o *OrganisationsInviteUserRequest) HasUserGroup() bool`

HasUserGroup returns a boolean if a field has been set.

### GetFromCustodian

`func (o *OrganisationsInviteUserRequest) GetFromCustodian() bool`

GetFromCustodian returns the FromCustodian field if non-nil, zero value otherwise.

### GetFromCustodianOk

`func (o *OrganisationsInviteUserRequest) GetFromCustodianOk() (*bool, bool)`

GetFromCustodianOk returns a tuple with the FromCustodian field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromCustodian

`func (o *OrganisationsInviteUserRequest) SetFromCustodian(v bool)`

SetFromCustodian sets FromCustodian field to given value.

### HasFromCustodian

`func (o *OrganisationsInviteUserRequest) HasFromCustodian() bool`

HasFromCustodian returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


