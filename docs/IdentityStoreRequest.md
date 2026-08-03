# IdentityStoreRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegistryId** | Pointer to **int32** |  | [optional] 
**SelfiePath** | Pointer to **string** |  | [optional] 
**PassportPath** | Pointer to **string** |  | [optional] 
**DriversLicensePath** | Pointer to **string** |  | [optional] 
**Address1** | Pointer to **string** |  | [optional] 
**Address2** | Pointer to **string** |  | [optional] 
**Town** | Pointer to **string** |  | [optional] 
**County** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**Postcode** | Pointer to **string** |  | [optional] 
**Dob** | Pointer to **string** |  | [optional] 

## Methods

### NewIdentityStoreRequest

`func NewIdentityStoreRequest() *IdentityStoreRequest`

NewIdentityStoreRequest instantiates a new IdentityStoreRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityStoreRequestWithDefaults

`func NewIdentityStoreRequestWithDefaults() *IdentityStoreRequest`

NewIdentityStoreRequestWithDefaults instantiates a new IdentityStoreRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegistryId

`func (o *IdentityStoreRequest) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *IdentityStoreRequest) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *IdentityStoreRequest) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *IdentityStoreRequest) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetSelfiePath

`func (o *IdentityStoreRequest) GetSelfiePath() string`

GetSelfiePath returns the SelfiePath field if non-nil, zero value otherwise.

### GetSelfiePathOk

`func (o *IdentityStoreRequest) GetSelfiePathOk() (*string, bool)`

GetSelfiePathOk returns a tuple with the SelfiePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelfiePath

`func (o *IdentityStoreRequest) SetSelfiePath(v string)`

SetSelfiePath sets SelfiePath field to given value.

### HasSelfiePath

`func (o *IdentityStoreRequest) HasSelfiePath() bool`

HasSelfiePath returns a boolean if a field has been set.

### GetPassportPath

`func (o *IdentityStoreRequest) GetPassportPath() string`

GetPassportPath returns the PassportPath field if non-nil, zero value otherwise.

### GetPassportPathOk

`func (o *IdentityStoreRequest) GetPassportPathOk() (*string, bool)`

GetPassportPathOk returns a tuple with the PassportPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassportPath

`func (o *IdentityStoreRequest) SetPassportPath(v string)`

SetPassportPath sets PassportPath field to given value.

### HasPassportPath

`func (o *IdentityStoreRequest) HasPassportPath() bool`

HasPassportPath returns a boolean if a field has been set.

### GetDriversLicensePath

`func (o *IdentityStoreRequest) GetDriversLicensePath() string`

GetDriversLicensePath returns the DriversLicensePath field if non-nil, zero value otherwise.

### GetDriversLicensePathOk

`func (o *IdentityStoreRequest) GetDriversLicensePathOk() (*string, bool)`

GetDriversLicensePathOk returns a tuple with the DriversLicensePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriversLicensePath

`func (o *IdentityStoreRequest) SetDriversLicensePath(v string)`

SetDriversLicensePath sets DriversLicensePath field to given value.

### HasDriversLicensePath

`func (o *IdentityStoreRequest) HasDriversLicensePath() bool`

HasDriversLicensePath returns a boolean if a field has been set.

### GetAddress1

`func (o *IdentityStoreRequest) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *IdentityStoreRequest) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *IdentityStoreRequest) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *IdentityStoreRequest) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *IdentityStoreRequest) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *IdentityStoreRequest) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *IdentityStoreRequest) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *IdentityStoreRequest) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetTown

`func (o *IdentityStoreRequest) GetTown() string`

GetTown returns the Town field if non-nil, zero value otherwise.

### GetTownOk

`func (o *IdentityStoreRequest) GetTownOk() (*string, bool)`

GetTownOk returns a tuple with the Town field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTown

`func (o *IdentityStoreRequest) SetTown(v string)`

SetTown sets Town field to given value.

### HasTown

`func (o *IdentityStoreRequest) HasTown() bool`

HasTown returns a boolean if a field has been set.

### GetCounty

`func (o *IdentityStoreRequest) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *IdentityStoreRequest) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *IdentityStoreRequest) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *IdentityStoreRequest) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetCountry

`func (o *IdentityStoreRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *IdentityStoreRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *IdentityStoreRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *IdentityStoreRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetPostcode

`func (o *IdentityStoreRequest) GetPostcode() string`

GetPostcode returns the Postcode field if non-nil, zero value otherwise.

### GetPostcodeOk

`func (o *IdentityStoreRequest) GetPostcodeOk() (*string, bool)`

GetPostcodeOk returns a tuple with the Postcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostcode

`func (o *IdentityStoreRequest) SetPostcode(v string)`

SetPostcode sets Postcode field to given value.

### HasPostcode

`func (o *IdentityStoreRequest) HasPostcode() bool`

HasPostcode returns a boolean if a field has been set.

### GetDob

`func (o *IdentityStoreRequest) GetDob() string`

GetDob returns the Dob field if non-nil, zero value otherwise.

### GetDobOk

`func (o *IdentityStoreRequest) GetDobOk() (*string, bool)`

GetDobOk returns a tuple with the Dob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDob

`func (o *IdentityStoreRequest) SetDob(v string)`

SetDob sets Dob field to given value.

### HasDob

`func (o *IdentityStoreRequest) HasDob() bool`

HasDob returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


