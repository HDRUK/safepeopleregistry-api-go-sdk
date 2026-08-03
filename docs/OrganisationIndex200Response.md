# OrganisationIndex200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Organisation**](Organisation.md) |  | [optional] 

## Methods

### NewOrganisationIndex200Response

`func NewOrganisationIndex200Response() *OrganisationIndex200Response`

NewOrganisationIndex200Response instantiates a new OrganisationIndex200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganisationIndex200ResponseWithDefaults

`func NewOrganisationIndex200ResponseWithDefaults() *OrganisationIndex200Response`

NewOrganisationIndex200ResponseWithDefaults instantiates a new OrganisationIndex200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *OrganisationIndex200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OrganisationIndex200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OrganisationIndex200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *OrganisationIndex200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *OrganisationIndex200Response) GetData() Organisation`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OrganisationIndex200Response) GetDataOk() (*Organisation, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OrganisationIndex200Response) SetData(v Organisation)`

SetData sets Data field to given value.

### HasData

`func (o *OrganisationIndex200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


