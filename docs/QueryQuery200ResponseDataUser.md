# QueryQuery200ResponseDataUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**RegistryId** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**UserGroup** | Pointer to **string** |  | [optional] 
**ConsentScrape** | Pointer to **bool** |  | [optional] 
**OrcId** | Pointer to **NullableString** |  | [optional] 
**Unclaimed** | Pointer to **int32** |  | [optional] 
**FeedSource** | Pointer to **NullableString** |  | [optional] 
**PublicOptIn** | Pointer to **int32** |  | [optional] 
**OrganisationId** | Pointer to **int32** |  | [optional] 
**OrcidScanning** | Pointer to **bool** |  | [optional] 
**OrcidScanningCompletedAt** | Pointer to **NullableString** |  | [optional] 
**IsDelegate** | Pointer to **int32** |  | [optional] 
**IsOrgAdmin** | Pointer to **int32** |  | [optional] 
**CustodianId** | Pointer to **NullableInt32** |  | [optional] 
**CustodianUserId** | Pointer to **NullableInt32** |  | [optional] 
**Role** | Pointer to **NullableString** |  | [optional] 
**Location** | Pointer to **NullableString** |  | [optional] 
**TAndCAgreed** | Pointer to **bool** |  | [optional] 
**TAndCAgreementDate** | Pointer to **NullableString** |  | [optional] 
**IsSro** | Pointer to **bool** |  | [optional] 
**InvitedBy** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Evaluation** | Pointer to **NullableString** |  | [optional] 
**Identity** | Pointer to [**NullableIdentity**](Identity.md) |  | [optional] 

## Methods

### NewQueryQuery200ResponseDataUser

`func NewQueryQuery200ResponseDataUser() *QueryQuery200ResponseDataUser`

NewQueryQuery200ResponseDataUser instantiates a new QueryQuery200ResponseDataUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryQuery200ResponseDataUserWithDefaults

`func NewQueryQuery200ResponseDataUserWithDefaults() *QueryQuery200ResponseDataUser`

NewQueryQuery200ResponseDataUserWithDefaults instantiates a new QueryQuery200ResponseDataUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *QueryQuery200ResponseDataUser) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QueryQuery200ResponseDataUser) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QueryQuery200ResponseDataUser) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *QueryQuery200ResponseDataUser) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFirstName

`func (o *QueryQuery200ResponseDataUser) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *QueryQuery200ResponseDataUser) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *QueryQuery200ResponseDataUser) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *QueryQuery200ResponseDataUser) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *QueryQuery200ResponseDataUser) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *QueryQuery200ResponseDataUser) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *QueryQuery200ResponseDataUser) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *QueryQuery200ResponseDataUser) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetName

`func (o *QueryQuery200ResponseDataUser) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *QueryQuery200ResponseDataUser) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *QueryQuery200ResponseDataUser) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *QueryQuery200ResponseDataUser) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRegistryId

`func (o *QueryQuery200ResponseDataUser) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *QueryQuery200ResponseDataUser) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *QueryQuery200ResponseDataUser) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *QueryQuery200ResponseDataUser) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *QueryQuery200ResponseDataUser) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *QueryQuery200ResponseDataUser) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *QueryQuery200ResponseDataUser) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *QueryQuery200ResponseDataUser) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *QueryQuery200ResponseDataUser) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *QueryQuery200ResponseDataUser) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *QueryQuery200ResponseDataUser) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *QueryQuery200ResponseDataUser) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetUserGroup

`func (o *QueryQuery200ResponseDataUser) GetUserGroup() string`

GetUserGroup returns the UserGroup field if non-nil, zero value otherwise.

### GetUserGroupOk

`func (o *QueryQuery200ResponseDataUser) GetUserGroupOk() (*string, bool)`

GetUserGroupOk returns a tuple with the UserGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserGroup

`func (o *QueryQuery200ResponseDataUser) SetUserGroup(v string)`

SetUserGroup sets UserGroup field to given value.

### HasUserGroup

`func (o *QueryQuery200ResponseDataUser) HasUserGroup() bool`

HasUserGroup returns a boolean if a field has been set.

### GetConsentScrape

`func (o *QueryQuery200ResponseDataUser) GetConsentScrape() bool`

GetConsentScrape returns the ConsentScrape field if non-nil, zero value otherwise.

### GetConsentScrapeOk

`func (o *QueryQuery200ResponseDataUser) GetConsentScrapeOk() (*bool, bool)`

GetConsentScrapeOk returns a tuple with the ConsentScrape field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsentScrape

`func (o *QueryQuery200ResponseDataUser) SetConsentScrape(v bool)`

SetConsentScrape sets ConsentScrape field to given value.

### HasConsentScrape

`func (o *QueryQuery200ResponseDataUser) HasConsentScrape() bool`

HasConsentScrape returns a boolean if a field has been set.

### GetOrcId

`func (o *QueryQuery200ResponseDataUser) GetOrcId() string`

GetOrcId returns the OrcId field if non-nil, zero value otherwise.

### GetOrcIdOk

`func (o *QueryQuery200ResponseDataUser) GetOrcIdOk() (*string, bool)`

GetOrcIdOk returns a tuple with the OrcId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcId

`func (o *QueryQuery200ResponseDataUser) SetOrcId(v string)`

SetOrcId sets OrcId field to given value.

### HasOrcId

`func (o *QueryQuery200ResponseDataUser) HasOrcId() bool`

HasOrcId returns a boolean if a field has been set.

### SetOrcIdNil

`func (o *QueryQuery200ResponseDataUser) SetOrcIdNil(b bool)`

 SetOrcIdNil sets the value for OrcId to be an explicit nil

### UnsetOrcId
`func (o *QueryQuery200ResponseDataUser) UnsetOrcId()`

UnsetOrcId ensures that no value is present for OrcId, not even an explicit nil
### GetUnclaimed

`func (o *QueryQuery200ResponseDataUser) GetUnclaimed() int32`

GetUnclaimed returns the Unclaimed field if non-nil, zero value otherwise.

### GetUnclaimedOk

`func (o *QueryQuery200ResponseDataUser) GetUnclaimedOk() (*int32, bool)`

GetUnclaimedOk returns a tuple with the Unclaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnclaimed

`func (o *QueryQuery200ResponseDataUser) SetUnclaimed(v int32)`

SetUnclaimed sets Unclaimed field to given value.

### HasUnclaimed

`func (o *QueryQuery200ResponseDataUser) HasUnclaimed() bool`

HasUnclaimed returns a boolean if a field has been set.

### GetFeedSource

`func (o *QueryQuery200ResponseDataUser) GetFeedSource() string`

GetFeedSource returns the FeedSource field if non-nil, zero value otherwise.

### GetFeedSourceOk

`func (o *QueryQuery200ResponseDataUser) GetFeedSourceOk() (*string, bool)`

GetFeedSourceOk returns a tuple with the FeedSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeedSource

`func (o *QueryQuery200ResponseDataUser) SetFeedSource(v string)`

SetFeedSource sets FeedSource field to given value.

### HasFeedSource

`func (o *QueryQuery200ResponseDataUser) HasFeedSource() bool`

HasFeedSource returns a boolean if a field has been set.

### SetFeedSourceNil

`func (o *QueryQuery200ResponseDataUser) SetFeedSourceNil(b bool)`

 SetFeedSourceNil sets the value for FeedSource to be an explicit nil

### UnsetFeedSource
`func (o *QueryQuery200ResponseDataUser) UnsetFeedSource()`

UnsetFeedSource ensures that no value is present for FeedSource, not even an explicit nil
### GetPublicOptIn

`func (o *QueryQuery200ResponseDataUser) GetPublicOptIn() int32`

GetPublicOptIn returns the PublicOptIn field if non-nil, zero value otherwise.

### GetPublicOptInOk

`func (o *QueryQuery200ResponseDataUser) GetPublicOptInOk() (*int32, bool)`

GetPublicOptInOk returns a tuple with the PublicOptIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicOptIn

`func (o *QueryQuery200ResponseDataUser) SetPublicOptIn(v int32)`

SetPublicOptIn sets PublicOptIn field to given value.

### HasPublicOptIn

`func (o *QueryQuery200ResponseDataUser) HasPublicOptIn() bool`

HasPublicOptIn returns a boolean if a field has been set.

### GetOrganisationId

`func (o *QueryQuery200ResponseDataUser) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *QueryQuery200ResponseDataUser) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *QueryQuery200ResponseDataUser) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *QueryQuery200ResponseDataUser) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetOrcidScanning

`func (o *QueryQuery200ResponseDataUser) GetOrcidScanning() bool`

GetOrcidScanning returns the OrcidScanning field if non-nil, zero value otherwise.

### GetOrcidScanningOk

`func (o *QueryQuery200ResponseDataUser) GetOrcidScanningOk() (*bool, bool)`

GetOrcidScanningOk returns a tuple with the OrcidScanning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcidScanning

`func (o *QueryQuery200ResponseDataUser) SetOrcidScanning(v bool)`

SetOrcidScanning sets OrcidScanning field to given value.

### HasOrcidScanning

`func (o *QueryQuery200ResponseDataUser) HasOrcidScanning() bool`

HasOrcidScanning returns a boolean if a field has been set.

### GetOrcidScanningCompletedAt

`func (o *QueryQuery200ResponseDataUser) GetOrcidScanningCompletedAt() string`

GetOrcidScanningCompletedAt returns the OrcidScanningCompletedAt field if non-nil, zero value otherwise.

### GetOrcidScanningCompletedAtOk

`func (o *QueryQuery200ResponseDataUser) GetOrcidScanningCompletedAtOk() (*string, bool)`

GetOrcidScanningCompletedAtOk returns a tuple with the OrcidScanningCompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcidScanningCompletedAt

`func (o *QueryQuery200ResponseDataUser) SetOrcidScanningCompletedAt(v string)`

SetOrcidScanningCompletedAt sets OrcidScanningCompletedAt field to given value.

### HasOrcidScanningCompletedAt

`func (o *QueryQuery200ResponseDataUser) HasOrcidScanningCompletedAt() bool`

HasOrcidScanningCompletedAt returns a boolean if a field has been set.

### SetOrcidScanningCompletedAtNil

`func (o *QueryQuery200ResponseDataUser) SetOrcidScanningCompletedAtNil(b bool)`

 SetOrcidScanningCompletedAtNil sets the value for OrcidScanningCompletedAt to be an explicit nil

### UnsetOrcidScanningCompletedAt
`func (o *QueryQuery200ResponseDataUser) UnsetOrcidScanningCompletedAt()`

UnsetOrcidScanningCompletedAt ensures that no value is present for OrcidScanningCompletedAt, not even an explicit nil
### GetIsDelegate

`func (o *QueryQuery200ResponseDataUser) GetIsDelegate() int32`

GetIsDelegate returns the IsDelegate field if non-nil, zero value otherwise.

### GetIsDelegateOk

`func (o *QueryQuery200ResponseDataUser) GetIsDelegateOk() (*int32, bool)`

GetIsDelegateOk returns a tuple with the IsDelegate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDelegate

`func (o *QueryQuery200ResponseDataUser) SetIsDelegate(v int32)`

SetIsDelegate sets IsDelegate field to given value.

### HasIsDelegate

`func (o *QueryQuery200ResponseDataUser) HasIsDelegate() bool`

HasIsDelegate returns a boolean if a field has been set.

### GetIsOrgAdmin

`func (o *QueryQuery200ResponseDataUser) GetIsOrgAdmin() int32`

GetIsOrgAdmin returns the IsOrgAdmin field if non-nil, zero value otherwise.

### GetIsOrgAdminOk

`func (o *QueryQuery200ResponseDataUser) GetIsOrgAdminOk() (*int32, bool)`

GetIsOrgAdminOk returns a tuple with the IsOrgAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOrgAdmin

`func (o *QueryQuery200ResponseDataUser) SetIsOrgAdmin(v int32)`

SetIsOrgAdmin sets IsOrgAdmin field to given value.

### HasIsOrgAdmin

`func (o *QueryQuery200ResponseDataUser) HasIsOrgAdmin() bool`

HasIsOrgAdmin returns a boolean if a field has been set.

### GetCustodianId

`func (o *QueryQuery200ResponseDataUser) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *QueryQuery200ResponseDataUser) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *QueryQuery200ResponseDataUser) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.

### HasCustodianId

`func (o *QueryQuery200ResponseDataUser) HasCustodianId() bool`

HasCustodianId returns a boolean if a field has been set.

### SetCustodianIdNil

`func (o *QueryQuery200ResponseDataUser) SetCustodianIdNil(b bool)`

 SetCustodianIdNil sets the value for CustodianId to be an explicit nil

### UnsetCustodianId
`func (o *QueryQuery200ResponseDataUser) UnsetCustodianId()`

UnsetCustodianId ensures that no value is present for CustodianId, not even an explicit nil
### GetCustodianUserId

`func (o *QueryQuery200ResponseDataUser) GetCustodianUserId() int32`

GetCustodianUserId returns the CustodianUserId field if non-nil, zero value otherwise.

### GetCustodianUserIdOk

`func (o *QueryQuery200ResponseDataUser) GetCustodianUserIdOk() (*int32, bool)`

GetCustodianUserIdOk returns a tuple with the CustodianUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianUserId

`func (o *QueryQuery200ResponseDataUser) SetCustodianUserId(v int32)`

SetCustodianUserId sets CustodianUserId field to given value.

### HasCustodianUserId

`func (o *QueryQuery200ResponseDataUser) HasCustodianUserId() bool`

HasCustodianUserId returns a boolean if a field has been set.

### SetCustodianUserIdNil

`func (o *QueryQuery200ResponseDataUser) SetCustodianUserIdNil(b bool)`

 SetCustodianUserIdNil sets the value for CustodianUserId to be an explicit nil

### UnsetCustodianUserId
`func (o *QueryQuery200ResponseDataUser) UnsetCustodianUserId()`

UnsetCustodianUserId ensures that no value is present for CustodianUserId, not even an explicit nil
### GetRole

`func (o *QueryQuery200ResponseDataUser) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *QueryQuery200ResponseDataUser) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *QueryQuery200ResponseDataUser) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *QueryQuery200ResponseDataUser) HasRole() bool`

HasRole returns a boolean if a field has been set.

### SetRoleNil

`func (o *QueryQuery200ResponseDataUser) SetRoleNil(b bool)`

 SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole
`func (o *QueryQuery200ResponseDataUser) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil
### GetLocation

`func (o *QueryQuery200ResponseDataUser) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *QueryQuery200ResponseDataUser) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *QueryQuery200ResponseDataUser) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *QueryQuery200ResponseDataUser) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *QueryQuery200ResponseDataUser) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *QueryQuery200ResponseDataUser) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetTAndCAgreed

`func (o *QueryQuery200ResponseDataUser) GetTAndCAgreed() bool`

GetTAndCAgreed returns the TAndCAgreed field if non-nil, zero value otherwise.

### GetTAndCAgreedOk

`func (o *QueryQuery200ResponseDataUser) GetTAndCAgreedOk() (*bool, bool)`

GetTAndCAgreedOk returns a tuple with the TAndCAgreed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAndCAgreed

`func (o *QueryQuery200ResponseDataUser) SetTAndCAgreed(v bool)`

SetTAndCAgreed sets TAndCAgreed field to given value.

### HasTAndCAgreed

`func (o *QueryQuery200ResponseDataUser) HasTAndCAgreed() bool`

HasTAndCAgreed returns a boolean if a field has been set.

### GetTAndCAgreementDate

`func (o *QueryQuery200ResponseDataUser) GetTAndCAgreementDate() string`

GetTAndCAgreementDate returns the TAndCAgreementDate field if non-nil, zero value otherwise.

### GetTAndCAgreementDateOk

`func (o *QueryQuery200ResponseDataUser) GetTAndCAgreementDateOk() (*string, bool)`

GetTAndCAgreementDateOk returns a tuple with the TAndCAgreementDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAndCAgreementDate

`func (o *QueryQuery200ResponseDataUser) SetTAndCAgreementDate(v string)`

SetTAndCAgreementDate sets TAndCAgreementDate field to given value.

### HasTAndCAgreementDate

`func (o *QueryQuery200ResponseDataUser) HasTAndCAgreementDate() bool`

HasTAndCAgreementDate returns a boolean if a field has been set.

### SetTAndCAgreementDateNil

`func (o *QueryQuery200ResponseDataUser) SetTAndCAgreementDateNil(b bool)`

 SetTAndCAgreementDateNil sets the value for TAndCAgreementDate to be an explicit nil

### UnsetTAndCAgreementDate
`func (o *QueryQuery200ResponseDataUser) UnsetTAndCAgreementDate()`

UnsetTAndCAgreementDate ensures that no value is present for TAndCAgreementDate, not even an explicit nil
### GetIsSro

`func (o *QueryQuery200ResponseDataUser) GetIsSro() bool`

GetIsSro returns the IsSro field if non-nil, zero value otherwise.

### GetIsSroOk

`func (o *QueryQuery200ResponseDataUser) GetIsSroOk() (*bool, bool)`

GetIsSroOk returns a tuple with the IsSro field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSro

`func (o *QueryQuery200ResponseDataUser) SetIsSro(v bool)`

SetIsSro sets IsSro field to given value.

### HasIsSro

`func (o *QueryQuery200ResponseDataUser) HasIsSro() bool`

HasIsSro returns a boolean if a field has been set.

### GetInvitedBy

`func (o *QueryQuery200ResponseDataUser) GetInvitedBy() int32`

GetInvitedBy returns the InvitedBy field if non-nil, zero value otherwise.

### GetInvitedByOk

`func (o *QueryQuery200ResponseDataUser) GetInvitedByOk() (*int32, bool)`

GetInvitedByOk returns a tuple with the InvitedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedBy

`func (o *QueryQuery200ResponseDataUser) SetInvitedBy(v int32)`

SetInvitedBy sets InvitedBy field to given value.

### HasInvitedBy

`func (o *QueryQuery200ResponseDataUser) HasInvitedBy() bool`

HasInvitedBy returns a boolean if a field has been set.

### SetInvitedByNil

`func (o *QueryQuery200ResponseDataUser) SetInvitedByNil(b bool)`

 SetInvitedByNil sets the value for InvitedBy to be an explicit nil

### UnsetInvitedBy
`func (o *QueryQuery200ResponseDataUser) UnsetInvitedBy()`

UnsetInvitedBy ensures that no value is present for InvitedBy, not even an explicit nil
### GetStatus

`func (o *QueryQuery200ResponseDataUser) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *QueryQuery200ResponseDataUser) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *QueryQuery200ResponseDataUser) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *QueryQuery200ResponseDataUser) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEvaluation

`func (o *QueryQuery200ResponseDataUser) GetEvaluation() string`

GetEvaluation returns the Evaluation field if non-nil, zero value otherwise.

### GetEvaluationOk

`func (o *QueryQuery200ResponseDataUser) GetEvaluationOk() (*string, bool)`

GetEvaluationOk returns a tuple with the Evaluation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluation

`func (o *QueryQuery200ResponseDataUser) SetEvaluation(v string)`

SetEvaluation sets Evaluation field to given value.

### HasEvaluation

`func (o *QueryQuery200ResponseDataUser) HasEvaluation() bool`

HasEvaluation returns a boolean if a field has been set.

### SetEvaluationNil

`func (o *QueryQuery200ResponseDataUser) SetEvaluationNil(b bool)`

 SetEvaluationNil sets the value for Evaluation to be an explicit nil

### UnsetEvaluation
`func (o *QueryQuery200ResponseDataUser) UnsetEvaluation()`

UnsetEvaluation ensures that no value is present for Evaluation, not even an explicit nil
### GetIdentity

`func (o *QueryQuery200ResponseDataUser) GetIdentity() Identity`

GetIdentity returns the Identity field if non-nil, zero value otherwise.

### GetIdentityOk

`func (o *QueryQuery200ResponseDataUser) GetIdentityOk() (*Identity, bool)`

GetIdentityOk returns a tuple with the Identity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentity

`func (o *QueryQuery200ResponseDataUser) SetIdentity(v Identity)`

SetIdentity sets Identity field to given value.

### HasIdentity

`func (o *QueryQuery200ResponseDataUser) HasIdentity() bool`

HasIdentity returns a boolean if a field has been set.

### SetIdentityNil

`func (o *QueryQuery200ResponseDataUser) SetIdentityNil(b bool)`

 SetIdentityNil sets the value for Identity to be an explicit nil

### UnsetIdentity
`func (o *QueryQuery200ResponseDataUser) UnsetIdentity()`

UnsetIdentity ensures that no value is present for Identity, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


