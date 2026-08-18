# User

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**EmailVerifiedAt** | Pointer to **string** |  | [optional] 
**ConsentScrape** | Pointer to **bool** |  | [optional] 
**PublicOptIn** | Pointer to **bool** |  | [optional] 
**OrganisationId** | Pointer to **int32** |  | [optional] 
**OrcidScanning** | Pointer to **int32** |  | [optional] 
**OrcidScanningCompletedAt** | Pointer to **string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**TAndCAgreed** | Pointer to **bool** |  | [optional] 
**TAndCAgreementDate** | Pointer to **string** |  | [optional] 

## Methods

### NewUser

`func NewUser() *User`

NewUser instantiates a new User object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserWithDefaults

`func NewUserWithDefaults() *User`

NewUserWithDefaults instantiates a new User object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *User) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *User) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *User) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *User) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *User) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *User) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *User) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *User) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *User) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *User) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *User) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *User) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetFirstName

`func (o *User) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *User) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *User) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *User) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *User) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *User) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *User) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *User) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetEmail

`func (o *User) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *User) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *User) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *User) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetEmailVerifiedAt

`func (o *User) GetEmailVerifiedAt() string`

GetEmailVerifiedAt returns the EmailVerifiedAt field if non-nil, zero value otherwise.

### GetEmailVerifiedAtOk

`func (o *User) GetEmailVerifiedAtOk() (*string, bool)`

GetEmailVerifiedAtOk returns a tuple with the EmailVerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailVerifiedAt

`func (o *User) SetEmailVerifiedAt(v string)`

SetEmailVerifiedAt sets EmailVerifiedAt field to given value.

### HasEmailVerifiedAt

`func (o *User) HasEmailVerifiedAt() bool`

HasEmailVerifiedAt returns a boolean if a field has been set.

### GetConsentScrape

`func (o *User) GetConsentScrape() bool`

GetConsentScrape returns the ConsentScrape field if non-nil, zero value otherwise.

### GetConsentScrapeOk

`func (o *User) GetConsentScrapeOk() (*bool, bool)`

GetConsentScrapeOk returns a tuple with the ConsentScrape field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsentScrape

`func (o *User) SetConsentScrape(v bool)`

SetConsentScrape sets ConsentScrape field to given value.

### HasConsentScrape

`func (o *User) HasConsentScrape() bool`

HasConsentScrape returns a boolean if a field has been set.

### GetPublicOptIn

`func (o *User) GetPublicOptIn() bool`

GetPublicOptIn returns the PublicOptIn field if non-nil, zero value otherwise.

### GetPublicOptInOk

`func (o *User) GetPublicOptInOk() (*bool, bool)`

GetPublicOptInOk returns a tuple with the PublicOptIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicOptIn

`func (o *User) SetPublicOptIn(v bool)`

SetPublicOptIn sets PublicOptIn field to given value.

### HasPublicOptIn

`func (o *User) HasPublicOptIn() bool`

HasPublicOptIn returns a boolean if a field has been set.

### GetOrganisationId

`func (o *User) GetOrganisationId() int32`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *User) GetOrganisationIdOk() (*int32, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *User) SetOrganisationId(v int32)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *User) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetOrcidScanning

`func (o *User) GetOrcidScanning() int32`

GetOrcidScanning returns the OrcidScanning field if non-nil, zero value otherwise.

### GetOrcidScanningOk

`func (o *User) GetOrcidScanningOk() (*int32, bool)`

GetOrcidScanningOk returns a tuple with the OrcidScanning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcidScanning

`func (o *User) SetOrcidScanning(v int32)`

SetOrcidScanning sets OrcidScanning field to given value.

### HasOrcidScanning

`func (o *User) HasOrcidScanning() bool`

HasOrcidScanning returns a boolean if a field has been set.

### GetOrcidScanningCompletedAt

`func (o *User) GetOrcidScanningCompletedAt() string`

GetOrcidScanningCompletedAt returns the OrcidScanningCompletedAt field if non-nil, zero value otherwise.

### GetOrcidScanningCompletedAtOk

`func (o *User) GetOrcidScanningCompletedAtOk() (*string, bool)`

GetOrcidScanningCompletedAtOk returns a tuple with the OrcidScanningCompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcidScanningCompletedAt

`func (o *User) SetOrcidScanningCompletedAt(v string)`

SetOrcidScanningCompletedAt sets OrcidScanningCompletedAt field to given value.

### HasOrcidScanningCompletedAt

`func (o *User) HasOrcidScanningCompletedAt() bool`

HasOrcidScanningCompletedAt returns a boolean if a field has been set.

### GetLocation

`func (o *User) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *User) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *User) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *User) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetTAndCAgreed

`func (o *User) GetTAndCAgreed() bool`

GetTAndCAgreed returns the TAndCAgreed field if non-nil, zero value otherwise.

### GetTAndCAgreedOk

`func (o *User) GetTAndCAgreedOk() (*bool, bool)`

GetTAndCAgreedOk returns a tuple with the TAndCAgreed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAndCAgreed

`func (o *User) SetTAndCAgreed(v bool)`

SetTAndCAgreed sets TAndCAgreed field to given value.

### HasTAndCAgreed

`func (o *User) HasTAndCAgreed() bool`

HasTAndCAgreed returns a boolean if a field has been set.

### GetTAndCAgreementDate

`func (o *User) GetTAndCAgreementDate() string`

GetTAndCAgreementDate returns the TAndCAgreementDate field if non-nil, zero value otherwise.

### GetTAndCAgreementDateOk

`func (o *User) GetTAndCAgreementDateOk() (*string, bool)`

GetTAndCAgreementDateOk returns a tuple with the TAndCAgreementDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAndCAgreementDate

`func (o *User) SetTAndCAgreementDate(v string)`

SetTAndCAgreementDate sets TAndCAgreementDate field to given value.

### HasTAndCAgreementDate

`func (o *User) HasTAndCAgreementDate() bool`

HasTAndCAgreementDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


