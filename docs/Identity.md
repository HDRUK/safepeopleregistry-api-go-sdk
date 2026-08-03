# Identity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the identity record | [optional] 
**RegistryId** | Pointer to **int32** | ID of the registry associated with the identity record | [optional] 
**Address1** | Pointer to **string** | First line of the address | [optional] 
**Address2** | Pointer to **string** | Second line of the address | [optional] 
**Town** | Pointer to **string** | Town of the address | [optional] 
**County** | Pointer to **string** | County of the address | [optional] 
**Country** | Pointer to **string** | Country of the address | [optional] 
**Postcode** | Pointer to **string** | Postcode of the address | [optional] 
**Dob** | Pointer to **string** | Date of birth | [optional] 
**IdvtSuccess** | Pointer to **int32** | Indicates whether IDVT was successful (1 for success, 0 for failure) | [optional] 
**IdvtIdentificationNumber** | Pointer to **string** | Identification number from IDVT | [optional] 
**IdvtDocumentType** | Pointer to **string** | Type of document used for IDVT | [optional] 
**IdvtDocumentNumber** | Pointer to **string** | Document number used for IDVT | [optional] 
**IdvtDocumentCountry** | Pointer to **string** | Country of the document used for IDVT | [optional] 
**IdvtDocumentValidUntil** | Pointer to **string** | Validity date of the document used for IDVT | [optional] 
**IdvtAttemptId** | Pointer to **string** | ID of the IDVT attempt | [optional] 
**IdvtContextId** | Pointer to **string** | Context ID for IDVT | [optional] 
**IdvtDocumentDob** | Pointer to **string** | Date of birth on the document used for IDVT | [optional] 
**IdvtContext** | Pointer to **string** | Context of the IDVT process | [optional] 
**IdvtCompletedAt** | Pointer to **time.Time** | Timestamp when IDVT was completed | [optional] 
**IdvtResultText** | Pointer to **string** | Result text of the IDVT process | [optional] 
**IdvtStartedAt** | Pointer to **time.Time** | Timestamp when IDVT was started | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the identity record was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the identity record was last updated | [optional] 
**DeletedAt** | Pointer to **time.Time** | Timestamp when the identity record was deleted | [optional] 

## Methods

### NewIdentity

`func NewIdentity() *Identity`

NewIdentity instantiates a new Identity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityWithDefaults

`func NewIdentityWithDefaults() *Identity`

NewIdentityWithDefaults instantiates a new Identity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Identity) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Identity) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Identity) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Identity) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRegistryId

`func (o *Identity) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *Identity) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *Identity) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *Identity) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetAddress1

`func (o *Identity) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *Identity) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *Identity) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *Identity) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *Identity) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *Identity) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *Identity) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *Identity) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetTown

`func (o *Identity) GetTown() string`

GetTown returns the Town field if non-nil, zero value otherwise.

### GetTownOk

`func (o *Identity) GetTownOk() (*string, bool)`

GetTownOk returns a tuple with the Town field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTown

`func (o *Identity) SetTown(v string)`

SetTown sets Town field to given value.

### HasTown

`func (o *Identity) HasTown() bool`

HasTown returns a boolean if a field has been set.

### GetCounty

`func (o *Identity) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *Identity) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *Identity) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *Identity) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetCountry

`func (o *Identity) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Identity) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Identity) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Identity) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetPostcode

`func (o *Identity) GetPostcode() string`

GetPostcode returns the Postcode field if non-nil, zero value otherwise.

### GetPostcodeOk

`func (o *Identity) GetPostcodeOk() (*string, bool)`

GetPostcodeOk returns a tuple with the Postcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostcode

`func (o *Identity) SetPostcode(v string)`

SetPostcode sets Postcode field to given value.

### HasPostcode

`func (o *Identity) HasPostcode() bool`

HasPostcode returns a boolean if a field has been set.

### GetDob

`func (o *Identity) GetDob() string`

GetDob returns the Dob field if non-nil, zero value otherwise.

### GetDobOk

`func (o *Identity) GetDobOk() (*string, bool)`

GetDobOk returns a tuple with the Dob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDob

`func (o *Identity) SetDob(v string)`

SetDob sets Dob field to given value.

### HasDob

`func (o *Identity) HasDob() bool`

HasDob returns a boolean if a field has been set.

### GetIdvtSuccess

`func (o *Identity) GetIdvtSuccess() int32`

GetIdvtSuccess returns the IdvtSuccess field if non-nil, zero value otherwise.

### GetIdvtSuccessOk

`func (o *Identity) GetIdvtSuccessOk() (*int32, bool)`

GetIdvtSuccessOk returns a tuple with the IdvtSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtSuccess

`func (o *Identity) SetIdvtSuccess(v int32)`

SetIdvtSuccess sets IdvtSuccess field to given value.

### HasIdvtSuccess

`func (o *Identity) HasIdvtSuccess() bool`

HasIdvtSuccess returns a boolean if a field has been set.

### GetIdvtIdentificationNumber

`func (o *Identity) GetIdvtIdentificationNumber() string`

GetIdvtIdentificationNumber returns the IdvtIdentificationNumber field if non-nil, zero value otherwise.

### GetIdvtIdentificationNumberOk

`func (o *Identity) GetIdvtIdentificationNumberOk() (*string, bool)`

GetIdvtIdentificationNumberOk returns a tuple with the IdvtIdentificationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtIdentificationNumber

`func (o *Identity) SetIdvtIdentificationNumber(v string)`

SetIdvtIdentificationNumber sets IdvtIdentificationNumber field to given value.

### HasIdvtIdentificationNumber

`func (o *Identity) HasIdvtIdentificationNumber() bool`

HasIdvtIdentificationNumber returns a boolean if a field has been set.

### GetIdvtDocumentType

`func (o *Identity) GetIdvtDocumentType() string`

GetIdvtDocumentType returns the IdvtDocumentType field if non-nil, zero value otherwise.

### GetIdvtDocumentTypeOk

`func (o *Identity) GetIdvtDocumentTypeOk() (*string, bool)`

GetIdvtDocumentTypeOk returns a tuple with the IdvtDocumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtDocumentType

`func (o *Identity) SetIdvtDocumentType(v string)`

SetIdvtDocumentType sets IdvtDocumentType field to given value.

### HasIdvtDocumentType

`func (o *Identity) HasIdvtDocumentType() bool`

HasIdvtDocumentType returns a boolean if a field has been set.

### GetIdvtDocumentNumber

`func (o *Identity) GetIdvtDocumentNumber() string`

GetIdvtDocumentNumber returns the IdvtDocumentNumber field if non-nil, zero value otherwise.

### GetIdvtDocumentNumberOk

`func (o *Identity) GetIdvtDocumentNumberOk() (*string, bool)`

GetIdvtDocumentNumberOk returns a tuple with the IdvtDocumentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtDocumentNumber

`func (o *Identity) SetIdvtDocumentNumber(v string)`

SetIdvtDocumentNumber sets IdvtDocumentNumber field to given value.

### HasIdvtDocumentNumber

`func (o *Identity) HasIdvtDocumentNumber() bool`

HasIdvtDocumentNumber returns a boolean if a field has been set.

### GetIdvtDocumentCountry

`func (o *Identity) GetIdvtDocumentCountry() string`

GetIdvtDocumentCountry returns the IdvtDocumentCountry field if non-nil, zero value otherwise.

### GetIdvtDocumentCountryOk

`func (o *Identity) GetIdvtDocumentCountryOk() (*string, bool)`

GetIdvtDocumentCountryOk returns a tuple with the IdvtDocumentCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtDocumentCountry

`func (o *Identity) SetIdvtDocumentCountry(v string)`

SetIdvtDocumentCountry sets IdvtDocumentCountry field to given value.

### HasIdvtDocumentCountry

`func (o *Identity) HasIdvtDocumentCountry() bool`

HasIdvtDocumentCountry returns a boolean if a field has been set.

### GetIdvtDocumentValidUntil

`func (o *Identity) GetIdvtDocumentValidUntil() string`

GetIdvtDocumentValidUntil returns the IdvtDocumentValidUntil field if non-nil, zero value otherwise.

### GetIdvtDocumentValidUntilOk

`func (o *Identity) GetIdvtDocumentValidUntilOk() (*string, bool)`

GetIdvtDocumentValidUntilOk returns a tuple with the IdvtDocumentValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtDocumentValidUntil

`func (o *Identity) SetIdvtDocumentValidUntil(v string)`

SetIdvtDocumentValidUntil sets IdvtDocumentValidUntil field to given value.

### HasIdvtDocumentValidUntil

`func (o *Identity) HasIdvtDocumentValidUntil() bool`

HasIdvtDocumentValidUntil returns a boolean if a field has been set.

### GetIdvtAttemptId

`func (o *Identity) GetIdvtAttemptId() string`

GetIdvtAttemptId returns the IdvtAttemptId field if non-nil, zero value otherwise.

### GetIdvtAttemptIdOk

`func (o *Identity) GetIdvtAttemptIdOk() (*string, bool)`

GetIdvtAttemptIdOk returns a tuple with the IdvtAttemptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtAttemptId

`func (o *Identity) SetIdvtAttemptId(v string)`

SetIdvtAttemptId sets IdvtAttemptId field to given value.

### HasIdvtAttemptId

`func (o *Identity) HasIdvtAttemptId() bool`

HasIdvtAttemptId returns a boolean if a field has been set.

### GetIdvtContextId

`func (o *Identity) GetIdvtContextId() string`

GetIdvtContextId returns the IdvtContextId field if non-nil, zero value otherwise.

### GetIdvtContextIdOk

`func (o *Identity) GetIdvtContextIdOk() (*string, bool)`

GetIdvtContextIdOk returns a tuple with the IdvtContextId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtContextId

`func (o *Identity) SetIdvtContextId(v string)`

SetIdvtContextId sets IdvtContextId field to given value.

### HasIdvtContextId

`func (o *Identity) HasIdvtContextId() bool`

HasIdvtContextId returns a boolean if a field has been set.

### GetIdvtDocumentDob

`func (o *Identity) GetIdvtDocumentDob() string`

GetIdvtDocumentDob returns the IdvtDocumentDob field if non-nil, zero value otherwise.

### GetIdvtDocumentDobOk

`func (o *Identity) GetIdvtDocumentDobOk() (*string, bool)`

GetIdvtDocumentDobOk returns a tuple with the IdvtDocumentDob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtDocumentDob

`func (o *Identity) SetIdvtDocumentDob(v string)`

SetIdvtDocumentDob sets IdvtDocumentDob field to given value.

### HasIdvtDocumentDob

`func (o *Identity) HasIdvtDocumentDob() bool`

HasIdvtDocumentDob returns a boolean if a field has been set.

### GetIdvtContext

`func (o *Identity) GetIdvtContext() string`

GetIdvtContext returns the IdvtContext field if non-nil, zero value otherwise.

### GetIdvtContextOk

`func (o *Identity) GetIdvtContextOk() (*string, bool)`

GetIdvtContextOk returns a tuple with the IdvtContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtContext

`func (o *Identity) SetIdvtContext(v string)`

SetIdvtContext sets IdvtContext field to given value.

### HasIdvtContext

`func (o *Identity) HasIdvtContext() bool`

HasIdvtContext returns a boolean if a field has been set.

### GetIdvtCompletedAt

`func (o *Identity) GetIdvtCompletedAt() time.Time`

GetIdvtCompletedAt returns the IdvtCompletedAt field if non-nil, zero value otherwise.

### GetIdvtCompletedAtOk

`func (o *Identity) GetIdvtCompletedAtOk() (*time.Time, bool)`

GetIdvtCompletedAtOk returns a tuple with the IdvtCompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtCompletedAt

`func (o *Identity) SetIdvtCompletedAt(v time.Time)`

SetIdvtCompletedAt sets IdvtCompletedAt field to given value.

### HasIdvtCompletedAt

`func (o *Identity) HasIdvtCompletedAt() bool`

HasIdvtCompletedAt returns a boolean if a field has been set.

### GetIdvtResultText

`func (o *Identity) GetIdvtResultText() string`

GetIdvtResultText returns the IdvtResultText field if non-nil, zero value otherwise.

### GetIdvtResultTextOk

`func (o *Identity) GetIdvtResultTextOk() (*string, bool)`

GetIdvtResultTextOk returns a tuple with the IdvtResultText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtResultText

`func (o *Identity) SetIdvtResultText(v string)`

SetIdvtResultText sets IdvtResultText field to given value.

### HasIdvtResultText

`func (o *Identity) HasIdvtResultText() bool`

HasIdvtResultText returns a boolean if a field has been set.

### GetIdvtStartedAt

`func (o *Identity) GetIdvtStartedAt() time.Time`

GetIdvtStartedAt returns the IdvtStartedAt field if non-nil, zero value otherwise.

### GetIdvtStartedAtOk

`func (o *Identity) GetIdvtStartedAtOk() (*time.Time, bool)`

GetIdvtStartedAtOk returns a tuple with the IdvtStartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdvtStartedAt

`func (o *Identity) SetIdvtStartedAt(v time.Time)`

SetIdvtStartedAt sets IdvtStartedAt field to given value.

### HasIdvtStartedAt

`func (o *Identity) HasIdvtStartedAt() bool`

HasIdvtStartedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Identity) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Identity) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Identity) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Identity) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Identity) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Identity) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Identity) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Identity) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *Identity) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *Identity) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *Identity) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *Identity) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


