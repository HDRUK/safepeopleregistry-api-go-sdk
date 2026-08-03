# UksaLiveFeed

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the UKSA live feed record | [optional] 
**FirstName** | Pointer to **string** | First name of the individual | [optional] 
**LastName** | Pointer to **string** | Last name of the individual | [optional] 
**OrganisationName** | Pointer to **string** | Name of the organisation | [optional] 
**AccreditationNumber** | Pointer to **string** | Accreditation number | [optional] 
**AccreditationType** | Pointer to **string** | Type of accreditation | [optional] 
**ExpiryDate** | Pointer to **string** | Expiry date of the accreditation | [optional] 
**PublicRecord** | Pointer to **string** | Indicates whether the record is public | [optional] 
**Stage** | Pointer to **string** | Current stage of the accreditation process | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the record was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the record was last updated | [optional] 

## Methods

### NewUksaLiveFeed

`func NewUksaLiveFeed() *UksaLiveFeed`

NewUksaLiveFeed instantiates a new UksaLiveFeed object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUksaLiveFeedWithDefaults

`func NewUksaLiveFeedWithDefaults() *UksaLiveFeed`

NewUksaLiveFeedWithDefaults instantiates a new UksaLiveFeed object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UksaLiveFeed) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UksaLiveFeed) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UksaLiveFeed) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *UksaLiveFeed) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFirstName

`func (o *UksaLiveFeed) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *UksaLiveFeed) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *UksaLiveFeed) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *UksaLiveFeed) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *UksaLiveFeed) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *UksaLiveFeed) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *UksaLiveFeed) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *UksaLiveFeed) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetOrganisationName

`func (o *UksaLiveFeed) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *UksaLiveFeed) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *UksaLiveFeed) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *UksaLiveFeed) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetAccreditationNumber

`func (o *UksaLiveFeed) GetAccreditationNumber() string`

GetAccreditationNumber returns the AccreditationNumber field if non-nil, zero value otherwise.

### GetAccreditationNumberOk

`func (o *UksaLiveFeed) GetAccreditationNumberOk() (*string, bool)`

GetAccreditationNumberOk returns a tuple with the AccreditationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditationNumber

`func (o *UksaLiveFeed) SetAccreditationNumber(v string)`

SetAccreditationNumber sets AccreditationNumber field to given value.

### HasAccreditationNumber

`func (o *UksaLiveFeed) HasAccreditationNumber() bool`

HasAccreditationNumber returns a boolean if a field has been set.

### GetAccreditationType

`func (o *UksaLiveFeed) GetAccreditationType() string`

GetAccreditationType returns the AccreditationType field if non-nil, zero value otherwise.

### GetAccreditationTypeOk

`func (o *UksaLiveFeed) GetAccreditationTypeOk() (*string, bool)`

GetAccreditationTypeOk returns a tuple with the AccreditationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditationType

`func (o *UksaLiveFeed) SetAccreditationType(v string)`

SetAccreditationType sets AccreditationType field to given value.

### HasAccreditationType

`func (o *UksaLiveFeed) HasAccreditationType() bool`

HasAccreditationType returns a boolean if a field has been set.

### GetExpiryDate

`func (o *UksaLiveFeed) GetExpiryDate() string`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *UksaLiveFeed) GetExpiryDateOk() (*string, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *UksaLiveFeed) SetExpiryDate(v string)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *UksaLiveFeed) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### GetPublicRecord

`func (o *UksaLiveFeed) GetPublicRecord() string`

GetPublicRecord returns the PublicRecord field if non-nil, zero value otherwise.

### GetPublicRecordOk

`func (o *UksaLiveFeed) GetPublicRecordOk() (*string, bool)`

GetPublicRecordOk returns a tuple with the PublicRecord field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicRecord

`func (o *UksaLiveFeed) SetPublicRecord(v string)`

SetPublicRecord sets PublicRecord field to given value.

### HasPublicRecord

`func (o *UksaLiveFeed) HasPublicRecord() bool`

HasPublicRecord returns a boolean if a field has been set.

### GetStage

`func (o *UksaLiveFeed) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *UksaLiveFeed) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *UksaLiveFeed) SetStage(v string)`

SetStage sets Stage field to given value.

### HasStage

`func (o *UksaLiveFeed) HasStage() bool`

HasStage returns a boolean if a field has been set.

### GetCreatedAt

`func (o *UksaLiveFeed) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UksaLiveFeed) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UksaLiveFeed) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *UksaLiveFeed) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *UksaLiveFeed) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UksaLiveFeed) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UksaLiveFeed) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *UksaLiveFeed) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


