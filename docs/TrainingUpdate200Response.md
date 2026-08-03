# TrainingUpdate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Training**](Training.md) |  | [optional] 

## Methods

### NewTrainingUpdate200Response

`func NewTrainingUpdate200Response() *TrainingUpdate200Response`

NewTrainingUpdate200Response instantiates a new TrainingUpdate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrainingUpdate200ResponseWithDefaults

`func NewTrainingUpdate200ResponseWithDefaults() *TrainingUpdate200Response`

NewTrainingUpdate200ResponseWithDefaults instantiates a new TrainingUpdate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *TrainingUpdate200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *TrainingUpdate200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *TrainingUpdate200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *TrainingUpdate200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *TrainingUpdate200Response) GetData() Training`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TrainingUpdate200Response) GetDataOk() (*Training, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TrainingUpdate200Response) SetData(v Training)`

SetData sets Data field to given value.

### HasData

`func (o *TrainingUpdate200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


