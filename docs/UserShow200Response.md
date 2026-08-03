# UserShow200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**UserShow200ResponseData**](UserShow200ResponseData.md) |  | [optional] 

## Methods

### NewUserShow200Response

`func NewUserShow200Response() *UserShow200Response`

NewUserShow200Response instantiates a new UserShow200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserShow200ResponseWithDefaults

`func NewUserShow200ResponseWithDefaults() *UserShow200Response`

NewUserShow200ResponseWithDefaults instantiates a new UserShow200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UserShow200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UserShow200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UserShow200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UserShow200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *UserShow200Response) GetData() UserShow200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UserShow200Response) GetDataOk() (*UserShow200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UserShow200Response) SetData(v UserShow200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *UserShow200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


