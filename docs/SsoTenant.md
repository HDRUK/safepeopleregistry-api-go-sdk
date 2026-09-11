# SsoTenant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**IdpAlias** | Pointer to **string** |  | [optional] 
**MetadataUrl** | Pointer to **string** |  | [optional] 
**EntityId** | Pointer to **string** |  | [optional] 
**MetadataImportedAt** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**SpEntityId** | Pointer to **string** | Keycloak&#39;s own SP entity ID - null until approved. Register this as the SAML Identifier on the customer&#39;s IdP. | [optional] 
**SpAcsUrl** | Pointer to **string** | Keycloak&#39;s ACS/reply URL for this tenant - null until approved. | [optional] 
**SpMetadataUrl** | Pointer to **string** | Downloadable SP metadata descriptor most IdPs can import directly - null until approved. | [optional] 
**Status** | Pointer to **string** | One of pending, approved, rejected | [optional] 
**SubmittedByUserId** | Pointer to **int32** | ID of the user who submitted this tenant for approval | [optional] 
**RejectedReason** | Pointer to **string** | Reason given when status is rejected - null otherwise | [optional] 

## Methods

### NewSsoTenant

`func NewSsoTenant() *SsoTenant`

NewSsoTenant instantiates a new SsoTenant object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSsoTenantWithDefaults

`func NewSsoTenantWithDefaults() *SsoTenant`

NewSsoTenantWithDefaults instantiates a new SsoTenant object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SsoTenant) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SsoTenant) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SsoTenant) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SsoTenant) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SsoTenant) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SsoTenant) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SsoTenant) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SsoTenant) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *SsoTenant) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SsoTenant) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SsoTenant) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SsoTenant) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetName

`func (o *SsoTenant) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SsoTenant) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SsoTenant) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SsoTenant) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIdpAlias

`func (o *SsoTenant) GetIdpAlias() string`

GetIdpAlias returns the IdpAlias field if non-nil, zero value otherwise.

### GetIdpAliasOk

`func (o *SsoTenant) GetIdpAliasOk() (*string, bool)`

GetIdpAliasOk returns a tuple with the IdpAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdpAlias

`func (o *SsoTenant) SetIdpAlias(v string)`

SetIdpAlias sets IdpAlias field to given value.

### HasIdpAlias

`func (o *SsoTenant) HasIdpAlias() bool`

HasIdpAlias returns a boolean if a field has been set.

### GetMetadataUrl

`func (o *SsoTenant) GetMetadataUrl() string`

GetMetadataUrl returns the MetadataUrl field if non-nil, zero value otherwise.

### GetMetadataUrlOk

`func (o *SsoTenant) GetMetadataUrlOk() (*string, bool)`

GetMetadataUrlOk returns a tuple with the MetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataUrl

`func (o *SsoTenant) SetMetadataUrl(v string)`

SetMetadataUrl sets MetadataUrl field to given value.

### HasMetadataUrl

`func (o *SsoTenant) HasMetadataUrl() bool`

HasMetadataUrl returns a boolean if a field has been set.

### GetEntityId

`func (o *SsoTenant) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *SsoTenant) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *SsoTenant) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.

### HasEntityId

`func (o *SsoTenant) HasEntityId() bool`

HasEntityId returns a boolean if a field has been set.

### GetMetadataImportedAt

`func (o *SsoTenant) GetMetadataImportedAt() string`

GetMetadataImportedAt returns the MetadataImportedAt field if non-nil, zero value otherwise.

### GetMetadataImportedAtOk

`func (o *SsoTenant) GetMetadataImportedAtOk() (*string, bool)`

GetMetadataImportedAtOk returns a tuple with the MetadataImportedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataImportedAt

`func (o *SsoTenant) SetMetadataImportedAt(v string)`

SetMetadataImportedAt sets MetadataImportedAt field to given value.

### HasMetadataImportedAt

`func (o *SsoTenant) HasMetadataImportedAt() bool`

HasMetadataImportedAt returns a boolean if a field has been set.

### GetEnabled

`func (o *SsoTenant) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SsoTenant) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SsoTenant) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *SsoTenant) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetSpEntityId

`func (o *SsoTenant) GetSpEntityId() string`

GetSpEntityId returns the SpEntityId field if non-nil, zero value otherwise.

### GetSpEntityIdOk

`func (o *SsoTenant) GetSpEntityIdOk() (*string, bool)`

GetSpEntityIdOk returns a tuple with the SpEntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpEntityId

`func (o *SsoTenant) SetSpEntityId(v string)`

SetSpEntityId sets SpEntityId field to given value.

### HasSpEntityId

`func (o *SsoTenant) HasSpEntityId() bool`

HasSpEntityId returns a boolean if a field has been set.

### GetSpAcsUrl

`func (o *SsoTenant) GetSpAcsUrl() string`

GetSpAcsUrl returns the SpAcsUrl field if non-nil, zero value otherwise.

### GetSpAcsUrlOk

`func (o *SsoTenant) GetSpAcsUrlOk() (*string, bool)`

GetSpAcsUrlOk returns a tuple with the SpAcsUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpAcsUrl

`func (o *SsoTenant) SetSpAcsUrl(v string)`

SetSpAcsUrl sets SpAcsUrl field to given value.

### HasSpAcsUrl

`func (o *SsoTenant) HasSpAcsUrl() bool`

HasSpAcsUrl returns a boolean if a field has been set.

### GetSpMetadataUrl

`func (o *SsoTenant) GetSpMetadataUrl() string`

GetSpMetadataUrl returns the SpMetadataUrl field if non-nil, zero value otherwise.

### GetSpMetadataUrlOk

`func (o *SsoTenant) GetSpMetadataUrlOk() (*string, bool)`

GetSpMetadataUrlOk returns a tuple with the SpMetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpMetadataUrl

`func (o *SsoTenant) SetSpMetadataUrl(v string)`

SetSpMetadataUrl sets SpMetadataUrl field to given value.

### HasSpMetadataUrl

`func (o *SsoTenant) HasSpMetadataUrl() bool`

HasSpMetadataUrl returns a boolean if a field has been set.

### GetStatus

`func (o *SsoTenant) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SsoTenant) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SsoTenant) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SsoTenant) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSubmittedByUserId

`func (o *SsoTenant) GetSubmittedByUserId() int32`

GetSubmittedByUserId returns the SubmittedByUserId field if non-nil, zero value otherwise.

### GetSubmittedByUserIdOk

`func (o *SsoTenant) GetSubmittedByUserIdOk() (*int32, bool)`

GetSubmittedByUserIdOk returns a tuple with the SubmittedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedByUserId

`func (o *SsoTenant) SetSubmittedByUserId(v int32)`

SetSubmittedByUserId sets SubmittedByUserId field to given value.

### HasSubmittedByUserId

`func (o *SsoTenant) HasSubmittedByUserId() bool`

HasSubmittedByUserId returns a boolean if a field has been set.

### GetRejectedReason

`func (o *SsoTenant) GetRejectedReason() string`

GetRejectedReason returns the RejectedReason field if non-nil, zero value otherwise.

### GetRejectedReasonOk

`func (o *SsoTenant) GetRejectedReasonOk() (*string, bool)`

GetRejectedReasonOk returns a tuple with the RejectedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectedReason

`func (o *SsoTenant) SetRejectedReason(v string)`

SetRejectedReason sets RejectedReason field to given value.

### HasRejectedReason

`func (o *SsoTenant) HasRejectedReason() bool`

HasRejectedReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


