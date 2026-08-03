# HistoryStore201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**HistoryIndex200ResponseData**](HistoryIndex200ResponseData.md) |  | [optional] 

## Methods

### NewHistoryStore201Response

`func NewHistoryStore201Response() *HistoryStore201Response`

NewHistoryStore201Response instantiates a new HistoryStore201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryStore201ResponseWithDefaults

`func NewHistoryStore201ResponseWithDefaults() *HistoryStore201Response`

NewHistoryStore201ResponseWithDefaults instantiates a new HistoryStore201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *HistoryStore201Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *HistoryStore201Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *HistoryStore201Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *HistoryStore201Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *HistoryStore201Response) GetData() HistoryIndex200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *HistoryStore201Response) GetDataOk() (*HistoryIndex200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *HistoryStore201Response) SetData(v HistoryIndex200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *HistoryStore201Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


