# Custodian

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**UniqueIdentifier** | Pointer to **string** | A unique identifier for Custodian&#39;s within SOURSD | [optional] 
**ContactEmail** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**InviteAcceptedAt** | Pointer to **string** |  | [optional] 
**InviteSentAt** | Pointer to **string** |  | [optional] 
**IdvtRequired** | Pointer to **bool** |  | [optional] 
**GatewayAppId** | Pointer to **string** |  | [optional] 
**GatewayClientId** | Pointer to **string** |  | [optional] 
**ClientId** | Pointer to **string** |  | [optional] 

## Methods

### NewCustodian

`func NewCustodian() *Custodian`

NewCustodian instantiates a new Custodian object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianWithDefaults

`func NewCustodianWithDefaults() *Custodian`

NewCustodianWithDefaults instantiates a new Custodian object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Custodian) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Custodian) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Custodian) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Custodian) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Custodian) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Custodian) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Custodian) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Custodian) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Custodian) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Custodian) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Custodian) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Custodian) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetName

`func (o *Custodian) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Custodian) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Custodian) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Custodian) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUniqueIdentifier

`func (o *Custodian) GetUniqueIdentifier() string`

GetUniqueIdentifier returns the UniqueIdentifier field if non-nil, zero value otherwise.

### GetUniqueIdentifierOk

`func (o *Custodian) GetUniqueIdentifierOk() (*string, bool)`

GetUniqueIdentifierOk returns a tuple with the UniqueIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueIdentifier

`func (o *Custodian) SetUniqueIdentifier(v string)`

SetUniqueIdentifier sets UniqueIdentifier field to given value.

### HasUniqueIdentifier

`func (o *Custodian) HasUniqueIdentifier() bool`

HasUniqueIdentifier returns a boolean if a field has been set.

### GetContactEmail

`func (o *Custodian) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *Custodian) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *Custodian) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.

### HasContactEmail

`func (o *Custodian) HasContactEmail() bool`

HasContactEmail returns a boolean if a field has been set.

### GetEnabled

`func (o *Custodian) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Custodian) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Custodian) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Custodian) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetInviteAcceptedAt

`func (o *Custodian) GetInviteAcceptedAt() string`

GetInviteAcceptedAt returns the InviteAcceptedAt field if non-nil, zero value otherwise.

### GetInviteAcceptedAtOk

`func (o *Custodian) GetInviteAcceptedAtOk() (*string, bool)`

GetInviteAcceptedAtOk returns a tuple with the InviteAcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteAcceptedAt

`func (o *Custodian) SetInviteAcceptedAt(v string)`

SetInviteAcceptedAt sets InviteAcceptedAt field to given value.

### HasInviteAcceptedAt

`func (o *Custodian) HasInviteAcceptedAt() bool`

HasInviteAcceptedAt returns a boolean if a field has been set.

### GetInviteSentAt

`func (o *Custodian) GetInviteSentAt() string`

GetInviteSentAt returns the InviteSentAt field if non-nil, zero value otherwise.

### GetInviteSentAtOk

`func (o *Custodian) GetInviteSentAtOk() (*string, bool)`

GetInviteSentAtOk returns a tuple with the InviteSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteSentAt

`func (o *Custodian) SetInviteSentAt(v string)`

SetInviteSentAt sets InviteSentAt field to given value.

### HasInviteSentAt

`func (o *Custodian) HasInviteSentAt() bool`

HasInviteSentAt returns a boolean if a field has been set.

### GetIdvtRequired

`func (o *Custodian) GetIdvtRequired() bool`

GetIdvtRequired returns the IdvtRequired field if non-nil, zero value otherwise.

### GetIdvtRequiredOk

`func (o *Custodian) GetIdvtRequiredOk() (*bool, bool)`

GetIdvtRequiredOk returns a tuple with the IdvtRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtRequired

`func (o *Custodian) SetIdvtRequired(v bool)`

SetIdvtRequired sets IdvtRequired field to given value.

### HasIdvtRequired

`func (o *Custodian) HasIdvtRequired() bool`

HasIdvtRequired returns a boolean if a field has been set.

### GetGatewayAppId

`func (o *Custodian) GetGatewayAppId() string`

GetGatewayAppId returns the GatewayAppId field if non-nil, zero value otherwise.

### GetGatewayAppIdOk

`func (o *Custodian) GetGatewayAppIdOk() (*string, bool)`

GetGatewayAppIdOk returns a tuple with the GatewayAppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayAppId

`func (o *Custodian) SetGatewayAppId(v string)`

SetGatewayAppId sets GatewayAppId field to given value.

### HasGatewayAppId

`func (o *Custodian) HasGatewayAppId() bool`

HasGatewayAppId returns a boolean if a field has been set.

### GetGatewayClientId

`func (o *Custodian) GetGatewayClientId() string`

GetGatewayClientId returns the GatewayClientId field if non-nil, zero value otherwise.

### GetGatewayClientIdOk

`func (o *Custodian) GetGatewayClientIdOk() (*string, bool)`

GetGatewayClientIdOk returns a tuple with the GatewayClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayClientId

`func (o *Custodian) SetGatewayClientId(v string)`

SetGatewayClientId sets GatewayClientId field to given value.

### HasGatewayClientId

`func (o *Custodian) HasGatewayClientId() bool`

HasGatewayClientId returns a boolean if a field has been set.

### GetClientId

`func (o *Custodian) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *Custodian) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *Custodian) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *Custodian) HasClientId() bool`

HasClientId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


