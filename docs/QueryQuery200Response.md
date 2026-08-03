# QueryQuery200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**QueryQuery200ResponseData**](QueryQuery200ResponseData.md) |  | [optional] 

## Methods

### NewQueryQuery200Response

`func NewQueryQuery200Response() *QueryQuery200Response`

NewQueryQuery200Response instantiates a new QueryQuery200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryQuery200ResponseWithDefaults

`func NewQueryQuery200ResponseWithDefaults() *QueryQuery200Response`

NewQueryQuery200ResponseWithDefaults instantiates a new QueryQuery200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *QueryQuery200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *QueryQuery200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *QueryQuery200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *QueryQuery200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *QueryQuery200Response) GetData() QueryQuery200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *QueryQuery200Response) GetDataOk() (*QueryQuery200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *QueryQuery200Response) SetData(v QueryQuery200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *QueryQuery200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


