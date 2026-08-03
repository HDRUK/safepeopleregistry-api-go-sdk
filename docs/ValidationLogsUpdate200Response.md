# ValidationLogsUpdate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**ValidationLog**](ValidationLog.md) |  | [optional] 

## Methods

### NewValidationLogsUpdate200Response

`func NewValidationLogsUpdate200Response() *ValidationLogsUpdate200Response`

NewValidationLogsUpdate200Response instantiates a new ValidationLogsUpdate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationLogsUpdate200ResponseWithDefaults

`func NewValidationLogsUpdate200ResponseWithDefaults() *ValidationLogsUpdate200Response`

NewValidationLogsUpdate200ResponseWithDefaults instantiates a new ValidationLogsUpdate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ValidationLogsUpdate200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ValidationLogsUpdate200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ValidationLogsUpdate200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ValidationLogsUpdate200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *ValidationLogsUpdate200Response) GetData() ValidationLog`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ValidationLogsUpdate200Response) GetDataOk() (*ValidationLog, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ValidationLogsUpdate200Response) SetData(v ValidationLog)`

SetData sets Data field to given value.

### HasData

`func (o *ValidationLogsUpdate200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


