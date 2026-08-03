# ProjectGetProjectUsers200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]ProjectGetProjectUsers200ResponseDataInner**](ProjectGetProjectUsers200ResponseDataInner.md) |  | [optional] 

## Methods

### NewProjectGetProjectUsers200Response

`func NewProjectGetProjectUsers200Response() *ProjectGetProjectUsers200Response`

NewProjectGetProjectUsers200Response instantiates a new ProjectGetProjectUsers200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectGetProjectUsers200ResponseWithDefaults

`func NewProjectGetProjectUsers200ResponseWithDefaults() *ProjectGetProjectUsers200Response`

NewProjectGetProjectUsers200ResponseWithDefaults instantiates a new ProjectGetProjectUsers200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ProjectGetProjectUsers200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ProjectGetProjectUsers200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ProjectGetProjectUsers200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ProjectGetProjectUsers200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *ProjectGetProjectUsers200Response) GetData() []ProjectGetProjectUsers200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ProjectGetProjectUsers200Response) GetDataOk() (*[]ProjectGetProjectUsers200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ProjectGetProjectUsers200Response) SetData(v []ProjectGetProjectUsers200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *ProjectGetProjectUsers200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


