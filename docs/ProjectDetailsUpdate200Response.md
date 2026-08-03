# ProjectDetailsUpdate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**ProjectDetail**](ProjectDetail.md) |  | [optional] 

## Methods

### NewProjectDetailsUpdate200Response

`func NewProjectDetailsUpdate200Response() *ProjectDetailsUpdate200Response`

NewProjectDetailsUpdate200Response instantiates a new ProjectDetailsUpdate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsUpdate200ResponseWithDefaults

`func NewProjectDetailsUpdate200ResponseWithDefaults() *ProjectDetailsUpdate200Response`

NewProjectDetailsUpdate200ResponseWithDefaults instantiates a new ProjectDetailsUpdate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ProjectDetailsUpdate200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ProjectDetailsUpdate200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ProjectDetailsUpdate200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ProjectDetailsUpdate200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *ProjectDetailsUpdate200Response) GetData() ProjectDetail`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ProjectDetailsUpdate200Response) GetDataOk() (*ProjectDetail, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ProjectDetailsUpdate200Response) SetData(v ProjectDetail)`

SetData sets Data field to given value.

### HasData

`func (o *ProjectDetailsUpdate200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


