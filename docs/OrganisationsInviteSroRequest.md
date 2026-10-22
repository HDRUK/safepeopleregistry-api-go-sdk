# OrganisationsInviteSroRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** | Job title | [optional] 
**DepartmentId** | Pointer to **NullableInt32** | One of the organisation&#39;s departments | [optional] 

## Methods

### NewOrganisationsInviteSroRequest

`func NewOrganisationsInviteSroRequest() *OrganisationsInviteSroRequest`

NewOrganisationsInviteSroRequest instantiates a new OrganisationsInviteSroRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganisationsInviteSroRequestWithDefaults

`func NewOrganisationsInviteSroRequestWithDefaults() *OrganisationsInviteSroRequest`

NewOrganisationsInviteSroRequestWithDefaults instantiates a new OrganisationsInviteSroRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *OrganisationsInviteSroRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *OrganisationsInviteSroRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *OrganisationsInviteSroRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *OrganisationsInviteSroRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *OrganisationsInviteSroRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *OrganisationsInviteSroRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *OrganisationsInviteSroRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *OrganisationsInviteSroRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetEmail

`func (o *OrganisationsInviteSroRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *OrganisationsInviteSroRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *OrganisationsInviteSroRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *OrganisationsInviteSroRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetRole

`func (o *OrganisationsInviteSroRequest) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *OrganisationsInviteSroRequest) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *OrganisationsInviteSroRequest) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *OrganisationsInviteSroRequest) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetDepartmentId

`func (o *OrganisationsInviteSroRequest) GetDepartmentId() int32`

GetDepartmentId returns the DepartmentId field if non-nil, zero value otherwise.

### GetDepartmentIdOk

`func (o *OrganisationsInviteSroRequest) GetDepartmentIdOk() (*int32, bool)`

GetDepartmentIdOk returns a tuple with the DepartmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentId

`func (o *OrganisationsInviteSroRequest) SetDepartmentId(v int32)`

SetDepartmentId sets DepartmentId field to given value.

### HasDepartmentId

`func (o *OrganisationsInviteSroRequest) HasDepartmentId() bool`

HasDepartmentId returns a boolean if a field has been set.

### SetDepartmentIdNil

`func (o *OrganisationsInviteSroRequest) SetDepartmentIdNil(b bool)`

 SetDepartmentIdNil sets the value for DepartmentId to be an explicit nil

### UnsetDepartmentId
`func (o *OrganisationsInviteSroRequest) UnsetDepartmentId()`

UnsetDepartmentId ensures that no value is present for DepartmentId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


