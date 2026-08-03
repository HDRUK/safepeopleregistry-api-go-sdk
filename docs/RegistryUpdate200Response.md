# RegistryUpdate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Registry**](Registry.md) |  | [optional] 

## Methods

### NewRegistryUpdate200Response

`func NewRegistryUpdate200Response() *RegistryUpdate200Response`

NewRegistryUpdate200Response instantiates a new RegistryUpdate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegistryUpdate200ResponseWithDefaults

`func NewRegistryUpdate200ResponseWithDefaults() *RegistryUpdate200Response`

NewRegistryUpdate200ResponseWithDefaults instantiates a new RegistryUpdate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *RegistryUpdate200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegistryUpdate200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegistryUpdate200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegistryUpdate200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *RegistryUpdate200Response) GetData() Registry`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RegistryUpdate200Response) GetDataOk() (*Registry, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RegistryUpdate200Response) SetData(v Registry)`

SetData sets Data field to given value.

### HasData

`func (o *RegistryUpdate200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


