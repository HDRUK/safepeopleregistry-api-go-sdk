# Accreditation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the accreditation | [optional] 
**AssociatedOrganisationName** | Pointer to **string** | Name of the associated organisation | [optional] 
**IdString** | Pointer to **string** | ID string for the accreditation | [optional] 
**IssueDate** | Pointer to **string** | Date when the accreditation was issued | [optional] 
**ExpiryDate** | Pointer to **string** | Date when the accreditation expires | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the accreditation was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the accreditation was last updated | [optional] 

## Methods

### NewAccreditation

`func NewAccreditation() *Accreditation`

NewAccreditation instantiates a new Accreditation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccreditationWithDefaults

`func NewAccreditationWithDefaults() *Accreditation`

NewAccreditationWithDefaults instantiates a new Accreditation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Accreditation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Accreditation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Accreditation) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Accreditation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAssociatedOrganisationName

`func (o *Accreditation) GetAssociatedOrganisationName() string`

GetAssociatedOrganisationName returns the AssociatedOrganisationName field if non-nil, zero value otherwise.

### GetAssociatedOrganisationNameOk

`func (o *Accreditation) GetAssociatedOrganisationNameOk() (*string, bool)`

GetAssociatedOrganisationNameOk returns a tuple with the AssociatedOrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedOrganisationName

`func (o *Accreditation) SetAssociatedOrganisationName(v string)`

SetAssociatedOrganisationName sets AssociatedOrganisationName field to given value.

### HasAssociatedOrganisationName

`func (o *Accreditation) HasAssociatedOrganisationName() bool`

HasAssociatedOrganisationName returns a boolean if a field has been set.

### GetIdString

`func (o *Accreditation) GetIdString() string`

GetIdString returns the IdString field if non-nil, zero value otherwise.

### GetIdStringOk

`func (o *Accreditation) GetIdStringOk() (*string, bool)`

GetIdStringOk returns a tuple with the IdString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdString

`func (o *Accreditation) SetIdString(v string)`

SetIdString sets IdString field to given value.

### HasIdString

`func (o *Accreditation) HasIdString() bool`

HasIdString returns a boolean if a field has been set.

### GetIssueDate

`func (o *Accreditation) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *Accreditation) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *Accreditation) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.

### HasIssueDate

`func (o *Accreditation) HasIssueDate() bool`

HasIssueDate returns a boolean if a field has been set.

### GetExpiryDate

`func (o *Accreditation) GetExpiryDate() string`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *Accreditation) GetExpiryDateOk() (*string, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *Accreditation) SetExpiryDate(v string)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *Accreditation) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Accreditation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Accreditation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Accreditation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Accreditation) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Accreditation) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Accreditation) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Accreditation) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Accreditation) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


