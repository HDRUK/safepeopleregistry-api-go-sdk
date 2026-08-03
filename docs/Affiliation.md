# Affiliation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**OrganisationId** | Pointer to **int32** | Organisational link | [optional] 
**MemberId** | Pointer to **string** | Member ID UUID | [optional] 
**Relationship** | Pointer to **string** | Textual representation of affiliation relationship | [optional] 
**From** | Pointer to **string** | Date affiliation commenced | [optional] 
**To** | Pointer to **string** | Date affiliation concluded | [optional] 
**Department** | Pointer to **string** | Department worked during affiliation | [optional] 
**Role** | Pointer to **string** | Role held during affiliation | [optional] 
**Email** | Pointer to **string** | Professional email held during affiliation | [optional] 
**Ror** | Pointer to **string** | The ROR.org identifier for this affiliation institute | [optional] 
**RegistryId** | Pointer to **int32** | The Registry primary key associated with this affiliation | [optional] 
**CurrentEmployer** | Pointer to **bool** | Flag indicating if affiliation is for the current employer | [optional] 
**VerificationCode** | Pointer to **string** | Unique verification code issued for confirmation | [optional] 
**VerificationSentAt** | Pointer to **time.Time** | Timestamp when verification code was sent | [optional] 
**VerificationConfirmedAt** | Pointer to **time.Time** | Timestamp when verification was confirmed | [optional] 
**IsVerified** | Pointer to **bool** | Flag indicating if affiliation is verified | [optional] 

## Methods

### NewAffiliation

`func NewAffiliation() *Affiliation`

NewAffiliation instantiates a new Affiliation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAffiliationWithDefaults

`func NewAffiliationWithDefaults() *Affiliation`

NewAffiliationWithDefaults instantiates a new Affiliation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Affiliation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Affiliation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Affiliation) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Affiliation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Affiliation) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Affiliation) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Affiliation) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Affiliation) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Affiliation) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Affiliation) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Affiliation) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Affiliation) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetOrganisationId

`func (o *Affiliation) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *Affiliation) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *Affiliation) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *Affiliation) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetMemberId

`func (o *Affiliation) GetMemberId() string`

GetMemberId returns the MemberId field if non-nil, zero value otherwise.

### GetMemberIdOk

`func (o *Affiliation) GetMemberIdOk() (*string, bool)`

GetMemberIdOk returns a tuple with the MemberId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberId

`func (o *Affiliation) SetMemberId(v string)`

SetMemberId sets MemberId field to given value.

### HasMemberId

`func (o *Affiliation) HasMemberId() bool`

HasMemberId returns a boolean if a field has been set.

### GetRelationship

`func (o *Affiliation) GetRelationship() string`

GetRelationship returns the Relationship field if non-nil, zero value otherwise.

### GetRelationshipOk

`func (o *Affiliation) GetRelationshipOk() (*string, bool)`

GetRelationshipOk returns a tuple with the Relationship field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelationship

`func (o *Affiliation) SetRelationship(v string)`

SetRelationship sets Relationship field to given value.

### HasRelationship

`func (o *Affiliation) HasRelationship() bool`

HasRelationship returns a boolean if a field has been set.

### GetFrom

`func (o *Affiliation) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *Affiliation) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *Affiliation) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *Affiliation) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *Affiliation) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *Affiliation) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *Affiliation) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *Affiliation) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDepartment

`func (o *Affiliation) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *Affiliation) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *Affiliation) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *Affiliation) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### GetRole

`func (o *Affiliation) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *Affiliation) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *Affiliation) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *Affiliation) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetEmail

`func (o *Affiliation) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Affiliation) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Affiliation) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Affiliation) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetRor

`func (o *Affiliation) GetRor() string`

GetRor returns the Ror field if non-nil, zero value otherwise.

### GetRorOk

`func (o *Affiliation) GetRorOk() (*string, bool)`

GetRorOk returns a tuple with the Ror field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRor

`func (o *Affiliation) SetRor(v string)`

SetRor sets Ror field to given value.

### HasRor

`func (o *Affiliation) HasRor() bool`

HasRor returns a boolean if a field has been set.

### GetRegistryId

`func (o *Affiliation) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *Affiliation) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *Affiliation) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *Affiliation) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetCurrentEmployer

`func (o *Affiliation) GetCurrentEmployer() bool`

GetCurrentEmployer returns the CurrentEmployer field if non-nil, zero value otherwise.

### GetCurrentEmployerOk

`func (o *Affiliation) GetCurrentEmployerOk() (*bool, bool)`

GetCurrentEmployerOk returns a tuple with the CurrentEmployer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentEmployer

`func (o *Affiliation) SetCurrentEmployer(v bool)`

SetCurrentEmployer sets CurrentEmployer field to given value.

### HasCurrentEmployer

`func (o *Affiliation) HasCurrentEmployer() bool`

HasCurrentEmployer returns a boolean if a field has been set.

### GetVerificationCode

`func (o *Affiliation) GetVerificationCode() string`

GetVerificationCode returns the VerificationCode field if non-nil, zero value otherwise.

### GetVerificationCodeOk

`func (o *Affiliation) GetVerificationCodeOk() (*string, bool)`

GetVerificationCodeOk returns a tuple with the VerificationCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationCode

`func (o *Affiliation) SetVerificationCode(v string)`

SetVerificationCode sets VerificationCode field to given value.

### HasVerificationCode

`func (o *Affiliation) HasVerificationCode() bool`

HasVerificationCode returns a boolean if a field has been set.

### GetVerificationSentAt

`func (o *Affiliation) GetVerificationSentAt() time.Time`

GetVerificationSentAt returns the VerificationSentAt field if non-nil, zero value otherwise.

### GetVerificationSentAtOk

`func (o *Affiliation) GetVerificationSentAtOk() (*time.Time, bool)`

GetVerificationSentAtOk returns a tuple with the VerificationSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationSentAt

`func (o *Affiliation) SetVerificationSentAt(v time.Time)`

SetVerificationSentAt sets VerificationSentAt field to given value.

### HasVerificationSentAt

`func (o *Affiliation) HasVerificationSentAt() bool`

HasVerificationSentAt returns a boolean if a field has been set.

### GetVerificationConfirmedAt

`func (o *Affiliation) GetVerificationConfirmedAt() time.Time`

GetVerificationConfirmedAt returns the VerificationConfirmedAt field if non-nil, zero value otherwise.

### GetVerificationConfirmedAtOk

`func (o *Affiliation) GetVerificationConfirmedAtOk() (*time.Time, bool)`

GetVerificationConfirmedAtOk returns a tuple with the VerificationConfirmedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationConfirmedAt

`func (o *Affiliation) SetVerificationConfirmedAt(v time.Time)`

SetVerificationConfirmedAt sets VerificationConfirmedAt field to given value.

### HasVerificationConfirmedAt

`func (o *Affiliation) HasVerificationConfirmedAt() bool`

HasVerificationConfirmedAt returns a boolean if a field has been set.

### GetIsVerified

`func (o *Affiliation) GetIsVerified() bool`

GetIsVerified returns the IsVerified field if non-nil, zero value otherwise.

### GetIsVerifiedOk

`func (o *Affiliation) GetIsVerifiedOk() (*bool, bool)`

GetIsVerifiedOk returns a tuple with the IsVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVerified

`func (o *Affiliation) SetIsVerified(v bool)`

SetIsVerified sets IsVerified field to given value.

### HasIsVerified

`func (o *Affiliation) HasIsVerified() bool`

HasIsVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


