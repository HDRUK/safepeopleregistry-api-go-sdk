# Organisation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**OrganisationName** | Pointer to **string** |  | [optional] 
**Address1** | Pointer to **string** |  | [optional] 
**Address2** | Pointer to **string** |  | [optional] 
**Town** | Pointer to **string** |  | [optional] 
**County** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**Postcode** | Pointer to **string** |  | [optional] 
**LeadApplicantOrganisationName** | Pointer to **string** |  | [optional] 
**LeadApplicantEmail** | Pointer to **string** |  | [optional] 
**OrganisationUniqueId** | Pointer to **string** |  | [optional] 
**ApplicantNames** | Pointer to **string** |  | [optional] 
**FundersAndSponsors** | Pointer to **string** |  | [optional] 
**SubLicenseArrangements** | Pointer to **string** |  | [optional] 
**Verified** | Pointer to **bool** |  | [optional] 
**DsptkOdsCode** | Pointer to **string** |  | [optional] 
**DsptkCertified** | Pointer to **bool** |  | [optional] 
**DsptkExpiryDate** | Pointer to **string** |  | [optional] 
**Iso27001Certified** | Pointer to **bool** |  | [optional] 
**Iso27001CertificationNum** | Pointer to **string** |  | [optional] 
**IsoExpiryDate** | Pointer to **string** |  | [optional] 
**CeCertified** | Pointer to **bool** |  | [optional] 
**CeCertificationNum** | Pointer to **string** |  | [optional] 
**CeExpiryDate** | Pointer to **string** |  | [optional] 
**CePlusCertified** | Pointer to **bool** |  | [optional] 
**CePlusCertificationNum** | Pointer to **string** |  | [optional] 
**CePlusExpiryDate** | Pointer to **string** |  | [optional] 
**CeOrIsoCertified** | Pointer to **bool** | True if either CE or ISO 27001 certification is currently valid | [optional] 
**CePlusOrIsoCertified** | Pointer to **bool** | True if either CE+ or ISO 27001 certification is currently valid | [optional] 
**IdvtResult** | Pointer to **int32** |  | [optional] 
**IdvtResultPerc** | Pointer to **int32** |  | [optional] 
**IdvtErrors** | Pointer to **string** |  | [optional] 
**IdvtCompletedAt** | Pointer to **string** |  | [optional] 
**CompaniesHouseNo** | Pointer to **string** |  | [optional] 
**SectorId** | Pointer to **int32** |  | [optional] 
**RorId** | Pointer to **string** | ROR.org identification for Research Organisations | [optional] 
**Website** | Pointer to **string** |  | [optional] 
**SmbStatus** | Pointer to **bool** | Declaration of small/medium business | [optional] 
**OrganisationSize** | Pointer to **int32** | Organisation size. Integer denotes list index rather than absolute value | [optional] 
**Unclaimed** | Pointer to **bool** | Unclaimed | [optional] 
**SystemApproved** | Pointer to **bool** | Whether this Organisation has been approved to use the system or not | [optional] 
**OdsId** | Pointer to **string** |  | [optional] 
**DsptkStatus** | Pointer to **string** |  | [optional] 
**DsptkDateLastPublished** | Pointer to **string** |  | [optional] 
**IcoRegistrationId** | Pointer to **string** |  | [optional] 
**IcoDateRegistered** | Pointer to **string** |  | [optional] 
**IcoExpiryDate** | Pointer to **string** |  | [optional] 

## Methods

### NewOrganisation

`func NewOrganisation() *Organisation`

NewOrganisation instantiates a new Organisation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganisationWithDefaults

`func NewOrganisationWithDefaults() *Organisation`

NewOrganisationWithDefaults instantiates a new Organisation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Organisation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Organisation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Organisation) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Organisation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Organisation) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Organisation) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Organisation) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Organisation) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Organisation) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Organisation) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Organisation) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Organisation) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetOrganisationName

`func (o *Organisation) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *Organisation) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *Organisation) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *Organisation) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetAddress1

`func (o *Organisation) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *Organisation) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *Organisation) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *Organisation) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *Organisation) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *Organisation) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *Organisation) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *Organisation) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetTown

`func (o *Organisation) GetTown() string`

GetTown returns the Town field if non-nil, zero value otherwise.

### GetTownOk

`func (o *Organisation) GetTownOk() (*string, bool)`

GetTownOk returns a tuple with the Town field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTown

`func (o *Organisation) SetTown(v string)`

SetTown sets Town field to given value.

### HasTown

`func (o *Organisation) HasTown() bool`

HasTown returns a boolean if a field has been set.

### GetCounty

`func (o *Organisation) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *Organisation) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *Organisation) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *Organisation) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetCountry

`func (o *Organisation) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Organisation) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Organisation) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Organisation) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetPostcode

`func (o *Organisation) GetPostcode() string`

GetPostcode returns the Postcode field if non-nil, zero value otherwise.

### GetPostcodeOk

`func (o *Organisation) GetPostcodeOk() (*string, bool)`

GetPostcodeOk returns a tuple with the Postcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostcode

`func (o *Organisation) SetPostcode(v string)`

SetPostcode sets Postcode field to given value.

### HasPostcode

`func (o *Organisation) HasPostcode() bool`

HasPostcode returns a boolean if a field has been set.

### GetLeadApplicantOrganisationName

`func (o *Organisation) GetLeadApplicantOrganisationName() string`

GetLeadApplicantOrganisationName returns the LeadApplicantOrganisationName field if non-nil, zero value otherwise.

### GetLeadApplicantOrganisationNameOk

`func (o *Organisation) GetLeadApplicantOrganisationNameOk() (*string, bool)`

GetLeadApplicantOrganisationNameOk returns a tuple with the LeadApplicantOrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadApplicantOrganisationName

`func (o *Organisation) SetLeadApplicantOrganisationName(v string)`

SetLeadApplicantOrganisationName sets LeadApplicantOrganisationName field to given value.

### HasLeadApplicantOrganisationName

`func (o *Organisation) HasLeadApplicantOrganisationName() bool`

HasLeadApplicantOrganisationName returns a boolean if a field has been set.

### GetLeadApplicantEmail

`func (o *Organisation) GetLeadApplicantEmail() string`

GetLeadApplicantEmail returns the LeadApplicantEmail field if non-nil, zero value otherwise.

### GetLeadApplicantEmailOk

`func (o *Organisation) GetLeadApplicantEmailOk() (*string, bool)`

GetLeadApplicantEmailOk returns a tuple with the LeadApplicantEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadApplicantEmail

`func (o *Organisation) SetLeadApplicantEmail(v string)`

SetLeadApplicantEmail sets LeadApplicantEmail field to given value.

### HasLeadApplicantEmail

`func (o *Organisation) HasLeadApplicantEmail() bool`

HasLeadApplicantEmail returns a boolean if a field has been set.

### GetOrganisationUniqueId

`func (o *Organisation) GetOrganisationUniqueId() string`

GetOrganisationUniqueId returns the OrganisationUniqueId field if non-nil, zero value otherwise.

### GetOrganisationUniqueIdOk

`func (o *Organisation) GetOrganisationUniqueIdOk() (*string, bool)`

GetOrganisationUniqueIdOk returns a tuple with the OrganisationUniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationUniqueId

`func (o *Organisation) SetOrganisationUniqueId(v string)`

SetOrganisationUniqueId sets OrganisationUniqueId field to given value.

### HasOrganisationUniqueId

`func (o *Organisation) HasOrganisationUniqueId() bool`

HasOrganisationUniqueId returns a boolean if a field has been set.

### GetApplicantNames

`func (o *Organisation) GetApplicantNames() string`

GetApplicantNames returns the ApplicantNames field if non-nil, zero value otherwise.

### GetApplicantNamesOk

`func (o *Organisation) GetApplicantNamesOk() (*string, bool)`

GetApplicantNamesOk returns a tuple with the ApplicantNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantNames

`func (o *Organisation) SetApplicantNames(v string)`

SetApplicantNames sets ApplicantNames field to given value.

### HasApplicantNames

`func (o *Organisation) HasApplicantNames() bool`

HasApplicantNames returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *Organisation) GetFundersAndSponsors() string`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *Organisation) GetFundersAndSponsorsOk() (*string, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *Organisation) SetFundersAndSponsors(v string)`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *Organisation) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetSubLicenseArrangements

`func (o *Organisation) GetSubLicenseArrangements() string`

GetSubLicenseArrangements returns the SubLicenseArrangements field if non-nil, zero value otherwise.

### GetSubLicenseArrangementsOk

`func (o *Organisation) GetSubLicenseArrangementsOk() (*string, bool)`

GetSubLicenseArrangementsOk returns a tuple with the SubLicenseArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubLicenseArrangements

`func (o *Organisation) SetSubLicenseArrangements(v string)`

SetSubLicenseArrangements sets SubLicenseArrangements field to given value.

### HasSubLicenseArrangements

`func (o *Organisation) HasSubLicenseArrangements() bool`

HasSubLicenseArrangements returns a boolean if a field has been set.

### GetVerified

`func (o *Organisation) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *Organisation) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *Organisation) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *Organisation) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### GetDsptkOdsCode

`func (o *Organisation) GetDsptkOdsCode() string`

GetDsptkOdsCode returns the DsptkOdsCode field if non-nil, zero value otherwise.

### GetDsptkOdsCodeOk

`func (o *Organisation) GetDsptkOdsCodeOk() (*string, bool)`

GetDsptkOdsCodeOk returns a tuple with the DsptkOdsCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDsptkOdsCode

`func (o *Organisation) SetDsptkOdsCode(v string)`

SetDsptkOdsCode sets DsptkOdsCode field to given value.

### HasDsptkOdsCode

`func (o *Organisation) HasDsptkOdsCode() bool`

HasDsptkOdsCode returns a boolean if a field has been set.

### GetDsptkCertified

`func (o *Organisation) GetDsptkCertified() bool`

GetDsptkCertified returns the DsptkCertified field if non-nil, zero value otherwise.

### GetDsptkCertifiedOk

`func (o *Organisation) GetDsptkCertifiedOk() (*bool, bool)`

GetDsptkCertifiedOk returns a tuple with the DsptkCertified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDsptkCertified

`func (o *Organisation) SetDsptkCertified(v bool)`

SetDsptkCertified sets DsptkCertified field to given value.

### HasDsptkCertified

`func (o *Organisation) HasDsptkCertified() bool`

HasDsptkCertified returns a boolean if a field has been set.

### GetDsptkExpiryDate

`func (o *Organisation) GetDsptkExpiryDate() string`

GetDsptkExpiryDate returns the DsptkExpiryDate field if non-nil, zero value otherwise.

### GetDsptkExpiryDateOk

`func (o *Organisation) GetDsptkExpiryDateOk() (*string, bool)`

GetDsptkExpiryDateOk returns a tuple with the DsptkExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDsptkExpiryDate

`func (o *Organisation) SetDsptkExpiryDate(v string)`

SetDsptkExpiryDate sets DsptkExpiryDate field to given value.

### HasDsptkExpiryDate

`func (o *Organisation) HasDsptkExpiryDate() bool`

HasDsptkExpiryDate returns a boolean if a field has been set.

### GetIso27001Certified

`func (o *Organisation) GetIso27001Certified() bool`

GetIso27001Certified returns the Iso27001Certified field if non-nil, zero value otherwise.

### GetIso27001CertifiedOk

`func (o *Organisation) GetIso27001CertifiedOk() (*bool, bool)`

GetIso27001CertifiedOk returns a tuple with the Iso27001Certified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIso27001Certified

`func (o *Organisation) SetIso27001Certified(v bool)`

SetIso27001Certified sets Iso27001Certified field to given value.

### HasIso27001Certified

`func (o *Organisation) HasIso27001Certified() bool`

HasIso27001Certified returns a boolean if a field has been set.

### GetIso27001CertificationNum

`func (o *Organisation) GetIso27001CertificationNum() string`

GetIso27001CertificationNum returns the Iso27001CertificationNum field if non-nil, zero value otherwise.

### GetIso27001CertificationNumOk

`func (o *Organisation) GetIso27001CertificationNumOk() (*string, bool)`

GetIso27001CertificationNumOk returns a tuple with the Iso27001CertificationNum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIso27001CertificationNum

`func (o *Organisation) SetIso27001CertificationNum(v string)`

SetIso27001CertificationNum sets Iso27001CertificationNum field to given value.

### HasIso27001CertificationNum

`func (o *Organisation) HasIso27001CertificationNum() bool`

HasIso27001CertificationNum returns a boolean if a field has been set.

### GetIsoExpiryDate

`func (o *Organisation) GetIsoExpiryDate() string`

GetIsoExpiryDate returns the IsoExpiryDate field if non-nil, zero value otherwise.

### GetIsoExpiryDateOk

`func (o *Organisation) GetIsoExpiryDateOk() (*string, bool)`

GetIsoExpiryDateOk returns a tuple with the IsoExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsoExpiryDate

`func (o *Organisation) SetIsoExpiryDate(v string)`

SetIsoExpiryDate sets IsoExpiryDate field to given value.

### HasIsoExpiryDate

`func (o *Organisation) HasIsoExpiryDate() bool`

HasIsoExpiryDate returns a boolean if a field has been set.

### GetCeCertified

`func (o *Organisation) GetCeCertified() bool`

GetCeCertified returns the CeCertified field if non-nil, zero value otherwise.

### GetCeCertifiedOk

`func (o *Organisation) GetCeCertifiedOk() (*bool, bool)`

GetCeCertifiedOk returns a tuple with the CeCertified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCeCertified

`func (o *Organisation) SetCeCertified(v bool)`

SetCeCertified sets CeCertified field to given value.

### HasCeCertified

`func (o *Organisation) HasCeCertified() bool`

HasCeCertified returns a boolean if a field has been set.

### GetCeCertificationNum

`func (o *Organisation) GetCeCertificationNum() string`

GetCeCertificationNum returns the CeCertificationNum field if non-nil, zero value otherwise.

### GetCeCertificationNumOk

`func (o *Organisation) GetCeCertificationNumOk() (*string, bool)`

GetCeCertificationNumOk returns a tuple with the CeCertificationNum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCeCertificationNum

`func (o *Organisation) SetCeCertificationNum(v string)`

SetCeCertificationNum sets CeCertificationNum field to given value.

### HasCeCertificationNum

`func (o *Organisation) HasCeCertificationNum() bool`

HasCeCertificationNum returns a boolean if a field has been set.

### GetCeExpiryDate

`func (o *Organisation) GetCeExpiryDate() string`

GetCeExpiryDate returns the CeExpiryDate field if non-nil, zero value otherwise.

### GetCeExpiryDateOk

`func (o *Organisation) GetCeExpiryDateOk() (*string, bool)`

GetCeExpiryDateOk returns a tuple with the CeExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCeExpiryDate

`func (o *Organisation) SetCeExpiryDate(v string)`

SetCeExpiryDate sets CeExpiryDate field to given value.

### HasCeExpiryDate

`func (o *Organisation) HasCeExpiryDate() bool`

HasCeExpiryDate returns a boolean if a field has been set.

### GetCePlusCertified

`func (o *Organisation) GetCePlusCertified() bool`

GetCePlusCertified returns the CePlusCertified field if non-nil, zero value otherwise.

### GetCePlusCertifiedOk

`func (o *Organisation) GetCePlusCertifiedOk() (*bool, bool)`

GetCePlusCertifiedOk returns a tuple with the CePlusCertified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCePlusCertified

`func (o *Organisation) SetCePlusCertified(v bool)`

SetCePlusCertified sets CePlusCertified field to given value.

### HasCePlusCertified

`func (o *Organisation) HasCePlusCertified() bool`

HasCePlusCertified returns a boolean if a field has been set.

### GetCePlusCertificationNum

`func (o *Organisation) GetCePlusCertificationNum() string`

GetCePlusCertificationNum returns the CePlusCertificationNum field if non-nil, zero value otherwise.

### GetCePlusCertificationNumOk

`func (o *Organisation) GetCePlusCertificationNumOk() (*string, bool)`

GetCePlusCertificationNumOk returns a tuple with the CePlusCertificationNum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCePlusCertificationNum

`func (o *Organisation) SetCePlusCertificationNum(v string)`

SetCePlusCertificationNum sets CePlusCertificationNum field to given value.

### HasCePlusCertificationNum

`func (o *Organisation) HasCePlusCertificationNum() bool`

HasCePlusCertificationNum returns a boolean if a field has been set.

### GetCePlusExpiryDate

`func (o *Organisation) GetCePlusExpiryDate() string`

GetCePlusExpiryDate returns the CePlusExpiryDate field if non-nil, zero value otherwise.

### GetCePlusExpiryDateOk

`func (o *Organisation) GetCePlusExpiryDateOk() (*string, bool)`

GetCePlusExpiryDateOk returns a tuple with the CePlusExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCePlusExpiryDate

`func (o *Organisation) SetCePlusExpiryDate(v string)`

SetCePlusExpiryDate sets CePlusExpiryDate field to given value.

### HasCePlusExpiryDate

`func (o *Organisation) HasCePlusExpiryDate() bool`

HasCePlusExpiryDate returns a boolean if a field has been set.

### GetCeOrIsoCertified

`func (o *Organisation) GetCeOrIsoCertified() bool`

GetCeOrIsoCertified returns the CeOrIsoCertified field if non-nil, zero value otherwise.

### GetCeOrIsoCertifiedOk

`func (o *Organisation) GetCeOrIsoCertifiedOk() (*bool, bool)`

GetCeOrIsoCertifiedOk returns a tuple with the CeOrIsoCertified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCeOrIsoCertified

`func (o *Organisation) SetCeOrIsoCertified(v bool)`

SetCeOrIsoCertified sets CeOrIsoCertified field to given value.

### HasCeOrIsoCertified

`func (o *Organisation) HasCeOrIsoCertified() bool`

HasCeOrIsoCertified returns a boolean if a field has been set.

### GetCePlusOrIsoCertified

`func (o *Organisation) GetCePlusOrIsoCertified() bool`

GetCePlusOrIsoCertified returns the CePlusOrIsoCertified field if non-nil, zero value otherwise.

### GetCePlusOrIsoCertifiedOk

`func (o *Organisation) GetCePlusOrIsoCertifiedOk() (*bool, bool)`

GetCePlusOrIsoCertifiedOk returns a tuple with the CePlusOrIsoCertified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCePlusOrIsoCertified

`func (o *Organisation) SetCePlusOrIsoCertified(v bool)`

SetCePlusOrIsoCertified sets CePlusOrIsoCertified field to given value.

### HasCePlusOrIsoCertified

`func (o *Organisation) HasCePlusOrIsoCertified() bool`

HasCePlusOrIsoCertified returns a boolean if a field has been set.

### GetIdvtResult

`func (o *Organisation) GetIdvtResult() int32`

GetIdvtResult returns the IdvtResult field if non-nil, zero value otherwise.

### GetIdvtResultOk

`func (o *Organisation) GetIdvtResultOk() (*int32, bool)`

GetIdvtResultOk returns a tuple with the IdvtResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtResult

`func (o *Organisation) SetIdvtResult(v int32)`

SetIdvtResult sets IdvtResult field to given value.

### HasIdvtResult

`func (o *Organisation) HasIdvtResult() bool`

HasIdvtResult returns a boolean if a field has been set.

### GetIdvtResultPerc

`func (o *Organisation) GetIdvtResultPerc() int32`

GetIdvtResultPerc returns the IdvtResultPerc field if non-nil, zero value otherwise.

### GetIdvtResultPercOk

`func (o *Organisation) GetIdvtResultPercOk() (*int32, bool)`

GetIdvtResultPercOk returns a tuple with the IdvtResultPerc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtResultPerc

`func (o *Organisation) SetIdvtResultPerc(v int32)`

SetIdvtResultPerc sets IdvtResultPerc field to given value.

### HasIdvtResultPerc

`func (o *Organisation) HasIdvtResultPerc() bool`

HasIdvtResultPerc returns a boolean if a field has been set.

### GetIdvtErrors

`func (o *Organisation) GetIdvtErrors() string`

GetIdvtErrors returns the IdvtErrors field if non-nil, zero value otherwise.

### GetIdvtErrorsOk

`func (o *Organisation) GetIdvtErrorsOk() (*string, bool)`

GetIdvtErrorsOk returns a tuple with the IdvtErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtErrors

`func (o *Organisation) SetIdvtErrors(v string)`

SetIdvtErrors sets IdvtErrors field to given value.

### HasIdvtErrors

`func (o *Organisation) HasIdvtErrors() bool`

HasIdvtErrors returns a boolean if a field has been set.

### GetIdvtCompletedAt

`func (o *Organisation) GetIdvtCompletedAt() string`

GetIdvtCompletedAt returns the IdvtCompletedAt field if non-nil, zero value otherwise.

### GetIdvtCompletedAtOk

`func (o *Organisation) GetIdvtCompletedAtOk() (*string, bool)`

GetIdvtCompletedAtOk returns a tuple with the IdvtCompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtCompletedAt

`func (o *Organisation) SetIdvtCompletedAt(v string)`

SetIdvtCompletedAt sets IdvtCompletedAt field to given value.

### HasIdvtCompletedAt

`func (o *Organisation) HasIdvtCompletedAt() bool`

HasIdvtCompletedAt returns a boolean if a field has been set.

### GetCompaniesHouseNo

`func (o *Organisation) GetCompaniesHouseNo() string`

GetCompaniesHouseNo returns the CompaniesHouseNo field if non-nil, zero value otherwise.

### GetCompaniesHouseNoOk

`func (o *Organisation) GetCompaniesHouseNoOk() (*string, bool)`

GetCompaniesHouseNoOk returns a tuple with the CompaniesHouseNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompaniesHouseNo

`func (o *Organisation) SetCompaniesHouseNo(v string)`

SetCompaniesHouseNo sets CompaniesHouseNo field to given value.

### HasCompaniesHouseNo

`func (o *Organisation) HasCompaniesHouseNo() bool`

HasCompaniesHouseNo returns a boolean if a field has been set.

### GetSectorId

`func (o *Organisation) GetSectorId() int32`

GetSectorId returns the SectorId field if non-nil, zero value otherwise.

### GetSectorIdOk

`func (o *Organisation) GetSectorIdOk() (*int32, bool)`

GetSectorIdOk returns a tuple with the SectorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectorId

`func (o *Organisation) SetSectorId(v int32)`

SetSectorId sets SectorId field to given value.

### HasSectorId

`func (o *Organisation) HasSectorId() bool`

HasSectorId returns a boolean if a field has been set.

### GetRorId

`func (o *Organisation) GetRorId() string`

GetRorId returns the RorId field if non-nil, zero value otherwise.

### GetRorIdOk

`func (o *Organisation) GetRorIdOk() (*string, bool)`

GetRorIdOk returns a tuple with the RorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRorId

`func (o *Organisation) SetRorId(v string)`

SetRorId sets RorId field to given value.

### HasRorId

`func (o *Organisation) HasRorId() bool`

HasRorId returns a boolean if a field has been set.

### GetWebsite

`func (o *Organisation) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Organisation) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Organisation) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *Organisation) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### GetSmbStatus

`func (o *Organisation) GetSmbStatus() bool`

GetSmbStatus returns the SmbStatus field if non-nil, zero value otherwise.

### GetSmbStatusOk

`func (o *Organisation) GetSmbStatusOk() (*bool, bool)`

GetSmbStatusOk returns a tuple with the SmbStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmbStatus

`func (o *Organisation) SetSmbStatus(v bool)`

SetSmbStatus sets SmbStatus field to given value.

### HasSmbStatus

`func (o *Organisation) HasSmbStatus() bool`

HasSmbStatus returns a boolean if a field has been set.

### GetOrganisationSize

`func (o *Organisation) GetOrganisationSize() int32`

GetOrganisationSize returns the OrganisationSize field if non-nil, zero value otherwise.

### GetOrganisationSizeOk

`func (o *Organisation) GetOrganisationSizeOk() (*int32, bool)`

GetOrganisationSizeOk returns a tuple with the OrganisationSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSize

`func (o *Organisation) SetOrganisationSize(v int32)`

SetOrganisationSize sets OrganisationSize field to given value.

### HasOrganisationSize

`func (o *Organisation) HasOrganisationSize() bool`

HasOrganisationSize returns a boolean if a field has been set.

### GetUnclaimed

`func (o *Organisation) GetUnclaimed() bool`

GetUnclaimed returns the Unclaimed field if non-nil, zero value otherwise.

### GetUnclaimedOk

`func (o *Organisation) GetUnclaimedOk() (*bool, bool)`

GetUnclaimedOk returns a tuple with the Unclaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnclaimed

`func (o *Organisation) SetUnclaimed(v bool)`

SetUnclaimed sets Unclaimed field to given value.

### HasUnclaimed

`func (o *Organisation) HasUnclaimed() bool`

HasUnclaimed returns a boolean if a field has been set.

### GetSystemApproved

`func (o *Organisation) GetSystemApproved() bool`

GetSystemApproved returns the SystemApproved field if non-nil, zero value otherwise.

### GetSystemApprovedOk

`func (o *Organisation) GetSystemApprovedOk() (*bool, bool)`

GetSystemApprovedOk returns a tuple with the SystemApproved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemApproved

`func (o *Organisation) SetSystemApproved(v bool)`

SetSystemApproved sets SystemApproved field to given value.

### HasSystemApproved

`func (o *Organisation) HasSystemApproved() bool`

HasSystemApproved returns a boolean if a field has been set.

### GetOdsId

`func (o *Organisation) GetOdsId() string`

GetOdsId returns the OdsId field if non-nil, zero value otherwise.

### GetOdsIdOk

`func (o *Organisation) GetOdsIdOk() (*string, bool)`

GetOdsIdOk returns a tuple with the OdsId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOdsId

`func (o *Organisation) SetOdsId(v string)`

SetOdsId sets OdsId field to given value.

### HasOdsId

`func (o *Organisation) HasOdsId() bool`

HasOdsId returns a boolean if a field has been set.

### GetDsptkStatus

`func (o *Organisation) GetDsptkStatus() string`

GetDsptkStatus returns the DsptkStatus field if non-nil, zero value otherwise.

### GetDsptkStatusOk

`func (o *Organisation) GetDsptkStatusOk() (*string, bool)`

GetDsptkStatusOk returns a tuple with the DsptkStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDsptkStatus

`func (o *Organisation) SetDsptkStatus(v string)`

SetDsptkStatus sets DsptkStatus field to given value.

### HasDsptkStatus

`func (o *Organisation) HasDsptkStatus() bool`

HasDsptkStatus returns a boolean if a field has been set.

### GetDsptkDateLastPublished

`func (o *Organisation) GetDsptkDateLastPublished() string`

GetDsptkDateLastPublished returns the DsptkDateLastPublished field if non-nil, zero value otherwise.

### GetDsptkDateLastPublishedOk

`func (o *Organisation) GetDsptkDateLastPublishedOk() (*string, bool)`

GetDsptkDateLastPublishedOk returns a tuple with the DsptkDateLastPublished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDsptkDateLastPublished

`func (o *Organisation) SetDsptkDateLastPublished(v string)`

SetDsptkDateLastPublished sets DsptkDateLastPublished field to given value.

### HasDsptkDateLastPublished

`func (o *Organisation) HasDsptkDateLastPublished() bool`

HasDsptkDateLastPublished returns a boolean if a field has been set.

### GetIcoRegistrationId

`func (o *Organisation) GetIcoRegistrationId() string`

GetIcoRegistrationId returns the IcoRegistrationId field if non-nil, zero value otherwise.

### GetIcoRegistrationIdOk

`func (o *Organisation) GetIcoRegistrationIdOk() (*string, bool)`

GetIcoRegistrationIdOk returns a tuple with the IcoRegistrationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcoRegistrationId

`func (o *Organisation) SetIcoRegistrationId(v string)`

SetIcoRegistrationId sets IcoRegistrationId field to given value.

### HasIcoRegistrationId

`func (o *Organisation) HasIcoRegistrationId() bool`

HasIcoRegistrationId returns a boolean if a field has been set.

### GetIcoDateRegistered

`func (o *Organisation) GetIcoDateRegistered() string`

GetIcoDateRegistered returns the IcoDateRegistered field if non-nil, zero value otherwise.

### GetIcoDateRegisteredOk

`func (o *Organisation) GetIcoDateRegisteredOk() (*string, bool)`

GetIcoDateRegisteredOk returns a tuple with the IcoDateRegistered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcoDateRegistered

`func (o *Organisation) SetIcoDateRegistered(v string)`

SetIcoDateRegistered sets IcoDateRegistered field to given value.

### HasIcoDateRegistered

`func (o *Organisation) HasIcoDateRegistered() bool`

HasIcoDateRegistered returns a boolean if a field has been set.

### GetIcoExpiryDate

`func (o *Organisation) GetIcoExpiryDate() string`

GetIcoExpiryDate returns the IcoExpiryDate field if non-nil, zero value otherwise.

### GetIcoExpiryDateOk

`func (o *Organisation) GetIcoExpiryDateOk() (*string, bool)`

GetIcoExpiryDateOk returns a tuple with the IcoExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcoExpiryDate

`func (o *Organisation) SetIcoExpiryDate(v string)`

SetIcoExpiryDate sets IcoExpiryDate field to given value.

### HasIcoExpiryDate

`func (o *Organisation) HasIcoExpiryDate() bool`

HasIcoExpiryDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


