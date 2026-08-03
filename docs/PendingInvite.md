# PendingInvite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the pending invite | [optional] 
**UserId** | Pointer to **int32** | ID of the user associated with the invite | [optional] 
**OrganisationId** | Pointer to **int32** | ID of the organisation associated with the invite | [optional] 
**Status** | Pointer to **string** | Status of the invite | [optional] 
**InviteAcceptedAt** | Pointer to **time.Time** | Timestamp when the invite was accepted | [optional] 
**InviteSentAt** | Pointer to **time.Time** | Timestamp when the invite was sent | [optional] 
**InviteCode** | Pointer to **string** | Unique code for the invite | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the invite record was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the invite record was last updated | [optional] 

## Methods

### NewPendingInvite

`func NewPendingInvite() *PendingInvite`

NewPendingInvite instantiates a new PendingInvite object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingInviteWithDefaults

`func NewPendingInviteWithDefaults() *PendingInvite`

NewPendingInviteWithDefaults instantiates a new PendingInvite object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PendingInvite) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PendingInvite) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PendingInvite) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *PendingInvite) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUserId

`func (o *PendingInvite) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *PendingInvite) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *PendingInvite) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *PendingInvite) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetOrganisationId

`func (o *PendingInvite) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *PendingInvite) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *PendingInvite) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *PendingInvite) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetStatus

`func (o *PendingInvite) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PendingInvite) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PendingInvite) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PendingInvite) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetInviteAcceptedAt

`func (o *PendingInvite) GetInviteAcceptedAt() time.Time`

GetInviteAcceptedAt returns the InviteAcceptedAt field if non-nil, zero value otherwise.

### GetInviteAcceptedAtOk

`func (o *PendingInvite) GetInviteAcceptedAtOk() (*time.Time, bool)`

GetInviteAcceptedAtOk returns a tuple with the InviteAcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteAcceptedAt

`func (o *PendingInvite) SetInviteAcceptedAt(v time.Time)`

SetInviteAcceptedAt sets InviteAcceptedAt field to given value.

### HasInviteAcceptedAt

`func (o *PendingInvite) HasInviteAcceptedAt() bool`

HasInviteAcceptedAt returns a boolean if a field has been set.

### GetInviteSentAt

`func (o *PendingInvite) GetInviteSentAt() time.Time`

GetInviteSentAt returns the InviteSentAt field if non-nil, zero value otherwise.

### GetInviteSentAtOk

`func (o *PendingInvite) GetInviteSentAtOk() (*time.Time, bool)`

GetInviteSentAtOk returns a tuple with the InviteSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteSentAt

`func (o *PendingInvite) SetInviteSentAt(v time.Time)`

SetInviteSentAt sets InviteSentAt field to given value.

### HasInviteSentAt

`func (o *PendingInvite) HasInviteSentAt() bool`

HasInviteSentAt returns a boolean if a field has been set.

### GetInviteCode

`func (o *PendingInvite) GetInviteCode() string`

GetInviteCode returns the InviteCode field if non-nil, zero value otherwise.

### GetInviteCodeOk

`func (o *PendingInvite) GetInviteCodeOk() (*string, bool)`

GetInviteCodeOk returns a tuple with the InviteCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteCode

`func (o *PendingInvite) SetInviteCode(v string)`

SetInviteCode sets InviteCode field to given value.

### HasInviteCode

`func (o *PendingInvite) HasInviteCode() bool`

HasInviteCode returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PendingInvite) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PendingInvite) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PendingInvite) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PendingInvite) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *PendingInvite) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PendingInvite) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PendingInvite) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PendingInvite) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


