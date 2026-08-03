# ProjectGetProjectByIdAndUserId200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Project**](Project.md) |  | [optional] 

## Methods

### NewProjectGetProjectByIdAndUserId200Response

`func NewProjectGetProjectByIdAndUserId200Response() *ProjectGetProjectByIdAndUserId200Response`

NewProjectGetProjectByIdAndUserId200Response instantiates a new ProjectGetProjectByIdAndUserId200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectGetProjectByIdAndUserId200ResponseWithDefaults

`func NewProjectGetProjectByIdAndUserId200ResponseWithDefaults() *ProjectGetProjectByIdAndUserId200Response`

NewProjectGetProjectByIdAndUserId200ResponseWithDefaults instantiates a new ProjectGetProjectByIdAndUserId200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ProjectGetProjectByIdAndUserId200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ProjectGetProjectByIdAndUserId200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ProjectGetProjectByIdAndUserId200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ProjectGetProjectByIdAndUserId200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *ProjectGetProjectByIdAndUserId200Response) GetData() []Project`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ProjectGetProjectByIdAndUserId200Response) GetDataOk() (*[]Project, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ProjectGetProjectByIdAndUserId200Response) SetData(v []Project)`

SetData sets Data field to given value.

### HasData

`func (o *ProjectGetProjectByIdAndUserId200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


