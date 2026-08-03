# Subsidiary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the subsidiary | [optional] 
**Name** | Pointer to **string** | Name of the subsidiary | [optional] 
**Address1** | Pointer to **string** | Primary address line of the subsidiary | [optional] 
**Address2** | Pointer to **string** | Secondary address line of the subsidiary | [optional] 
**Town** | Pointer to **string** | Town where the subsidiary is located | [optional] 
**County** | Pointer to **string** | County where the subsidiary is located | [optional] 
**Country** | Pointer to **string** | Country where the subsidiary is located | [optional] 
**Postcode** | Pointer to **string** | Postcode of the subsidiary | [optional] 
**Website** | Pointer to **string** | Website of the subsidiary | [optional] 
**IsParent** | Pointer to **int32** | Indicates if the subsidiary is a parent company | [optional] 

## Methods

### NewSubsidiary

`func NewSubsidiary() *Subsidiary`

NewSubsidiary instantiates a new Subsidiary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubsidiaryWithDefaults

`func NewSubsidiaryWithDefaults() *Subsidiary`

NewSubsidiaryWithDefaults instantiates a new Subsidiary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Subsidiary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Subsidiary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Subsidiary) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Subsidiary) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Subsidiary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Subsidiary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Subsidiary) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Subsidiary) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress1

`func (o *Subsidiary) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *Subsidiary) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *Subsidiary) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *Subsidiary) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *Subsidiary) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *Subsidiary) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *Subsidiary) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *Subsidiary) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetTown

`func (o *Subsidiary) GetTown() string`

GetTown returns the Town field if non-nil, zero value otherwise.

### GetTownOk

`func (o *Subsidiary) GetTownOk() (*string, bool)`

GetTownOk returns a tuple with the Town field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTown

`func (o *Subsidiary) SetTown(v string)`

SetTown sets Town field to given value.

### HasTown

`func (o *Subsidiary) HasTown() bool`

HasTown returns a boolean if a field has been set.

### GetCounty

`func (o *Subsidiary) GetCounty() string`

GetCounty returns the County field if non-nil, zero value otherwise.

### GetCountyOk

`func (o *Subsidiary) GetCountyOk() (*string, bool)`

GetCountyOk returns a tuple with the County field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounty

`func (o *Subsidiary) SetCounty(v string)`

SetCounty sets County field to given value.

### HasCounty

`func (o *Subsidiary) HasCounty() bool`

HasCounty returns a boolean if a field has been set.

### GetCountry

`func (o *Subsidiary) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Subsidiary) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Subsidiary) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Subsidiary) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetPostcode

`func (o *Subsidiary) GetPostcode() string`

GetPostcode returns the Postcode field if non-nil, zero value otherwise.

### GetPostcodeOk

`func (o *Subsidiary) GetPostcodeOk() (*string, bool)`

GetPostcodeOk returns a tuple with the Postcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostcode

`func (o *Subsidiary) SetPostcode(v string)`

SetPostcode sets Postcode field to given value.

### HasPostcode

`func (o *Subsidiary) HasPostcode() bool`

HasPostcode returns a boolean if a field has been set.

### GetWebsite

`func (o *Subsidiary) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Subsidiary) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Subsidiary) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *Subsidiary) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### GetIsParent

`func (o *Subsidiary) GetIsParent() int32`

GetIsParent returns the IsParent field if non-nil, zero value otherwise.

### GetIsParentOk

`func (o *Subsidiary) GetIsParentOk() (*int32, bool)`

GetIsParentOk returns a tuple with the IsParent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsParent

`func (o *Subsidiary) SetIsParent(v int32)`

SetIsParent sets IsParent field to given value.

### HasIsParent

`func (o *Subsidiary) HasIsParent() bool`

HasIsParent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


