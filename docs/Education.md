# Education

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the education record | [optional] 
**Title** | Pointer to **string** | Title of the education qualification | [optional] 
**From** | Pointer to **string** | Start date of the education qualification | [optional] 
**To** | Pointer to **string** | End date of the education qualification | [optional] 
**InstituteName** | Pointer to **string** | Name of the educational institute | [optional] 
**InstituteAddress** | Pointer to **string** | Address of the educational institute | [optional] 
**InstituteIdentifier** | Pointer to **string** | Identifier for the educational institute | [optional] 
**Source** | Pointer to **string** | Source of the education record | [optional] 
**RegistryId** | Pointer to **int32** | ID of the registry associated with the education record | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the education record was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the education record was last updated | [optional] 

## Methods

### NewEducation

`func NewEducation() *Education`

NewEducation instantiates a new Education object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEducationWithDefaults

`func NewEducationWithDefaults() *Education`

NewEducationWithDefaults instantiates a new Education object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Education) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Education) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Education) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Education) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *Education) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Education) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Education) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Education) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetFrom

`func (o *Education) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *Education) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *Education) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *Education) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *Education) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *Education) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *Education) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *Education) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetInstituteName

`func (o *Education) GetInstituteName() string`

GetInstituteName returns the InstituteName field if non-nil, zero value otherwise.

### GetInstituteNameOk

`func (o *Education) GetInstituteNameOk() (*string, bool)`

GetInstituteNameOk returns a tuple with the InstituteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstituteName

`func (o *Education) SetInstituteName(v string)`

SetInstituteName sets InstituteName field to given value.

### HasInstituteName

`func (o *Education) HasInstituteName() bool`

HasInstituteName returns a boolean if a field has been set.

### GetInstituteAddress

`func (o *Education) GetInstituteAddress() string`

GetInstituteAddress returns the InstituteAddress field if non-nil, zero value otherwise.

### GetInstituteAddressOk

`func (o *Education) GetInstituteAddressOk() (*string, bool)`

GetInstituteAddressOk returns a tuple with the InstituteAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstituteAddress

`func (o *Education) SetInstituteAddress(v string)`

SetInstituteAddress sets InstituteAddress field to given value.

### HasInstituteAddress

`func (o *Education) HasInstituteAddress() bool`

HasInstituteAddress returns a boolean if a field has been set.

### GetInstituteIdentifier

`func (o *Education) GetInstituteIdentifier() string`

GetInstituteIdentifier returns the InstituteIdentifier field if non-nil, zero value otherwise.

### GetInstituteIdentifierOk

`func (o *Education) GetInstituteIdentifierOk() (*string, bool)`

GetInstituteIdentifierOk returns a tuple with the InstituteIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstituteIdentifier

`func (o *Education) SetInstituteIdentifier(v string)`

SetInstituteIdentifier sets InstituteIdentifier field to given value.

### HasInstituteIdentifier

`func (o *Education) HasInstituteIdentifier() bool`

HasInstituteIdentifier returns a boolean if a field has been set.

### GetSource

`func (o *Education) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Education) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Education) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *Education) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetRegistryId

`func (o *Education) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *Education) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *Education) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *Education) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Education) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Education) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Education) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Education) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Education) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Education) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Education) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Education) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


