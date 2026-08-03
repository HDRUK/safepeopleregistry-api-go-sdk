# Charity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the charity | [optional] 
**RegistrationId** | Pointer to **string** | Registration ID of the charity | [optional] 
**Name** | Pointer to **string** | Name of the charity | [optional] 
**Website** | Pointer to **string** | Website URL of the charity | [optional] 
**Address1** | Pointer to **string** | First line of the charity&#39;s address | [optional] 
**Address2** | Pointer to **string** | Second line of the charity&#39;s address | [optional] 
**Town** | Pointer to **string** | Town where the charity is located | [optional] 
**County** | Pointer to **string** | County where the charity is located | [optional] 
**Country** | Pointer to **string** | Country where the charity is located | [optional] 
**Postcode** | Pointer to **string** | Postcode of the charity&#39;s address | [optional] 

## Methods

### NewCharity

`func NewCharity() *Charity`

NewCharity instantiates a new Charity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCharityWithDefaults

`func NewCharityWithDefaults() *Charity`

NewCharityWithDefaults instantiates a new Charity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Charity) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Charity) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Charity) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Charity) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRegistrationId

`func (o *Charity) GetRegistrationId() string`

GetRegistrationId returns the RegistrationId field if non-nil, zero value otherwise.

### GetRegistrationIdOk

`func (o *Charity) GetRegistrationIdOk() (*string, bool)`

GetRegistrationIdOk returns a tuple with the RegistrationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistrationId

`func (o *Charity) SetRegistrationId(v string)`

SetRegistrationId sets RegistrationId field to given value.

### HasRegistrationId

`func (o *Charity) HasRegistrationId() bool`

HasRegistrationId returns a boolean if a field has been set.

### GetName

`func (o *Charity) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Charity) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Charity) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Charity) HasName() bool`

HasName returns a boolean if a field has been set.

### GetWebsite

`func (o *Charity) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Charity) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Charity) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *Charity) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### GetAddress1

`func (o *Charity) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *Charity) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *Charity) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *Charity) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *Charity) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *Charity) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *Charity) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *Charity) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetTown

`func (o *Charity) GetTown() string`

GetTown returns the Town field if non-nil, zero value otherwise.

### GetTownOk

`func (o *Charity) GetTownOk() (*string, bool)`

GetTownOk returns a tuple with the Town field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTown

`func (o *Charity) SetTown(v string)`

SetTown sets Town field to given value.

### HasTown

`func (o *Charity) HasTown() bool`

HasTown returns a boolean if a field has been set.

### GetCounty

`func (o *Charity) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *Charity) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *Charity) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *Charity) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetCountry

`func (o *Charity) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Charity) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Charity) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Charity) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetPostcode

`func (o *Charity) GetPostcode() string`

GetPostcode returns the Postcode field if non-nil, zero value otherwise.

### GetPostcodeOk

`func (o *Charity) GetPostcodeOk() (*string, bool)`

GetPostcodeOk returns a tuple with the Postcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostcode

`func (o *Charity) SetPostcode(v string)`

SetPostcode sets Postcode field to given value.

### HasPostcode

`func (o *Charity) HasPostcode() bool`

HasPostcode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


