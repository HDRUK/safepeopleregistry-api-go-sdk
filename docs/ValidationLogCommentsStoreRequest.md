# ValidationLogCommentsStoreRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ValidationLogId** | **int32** | ID of the associated validation log | 
**Comment** | **string** | Comment text | 

## Methods

### NewValidationLogCommentsStoreRequest

`func NewValidationLogCommentsStoreRequest(validationLogId int32, comment string, ) *ValidationLogCommentsStoreRequest`

NewValidationLogCommentsStoreRequest instantiates a new ValidationLogCommentsStoreRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationLogCommentsStoreRequestWithDefaults

`func NewValidationLogCommentsStoreRequestWithDefaults() *ValidationLogCommentsStoreRequest`

NewValidationLogCommentsStoreRequestWithDefaults instantiates a new ValidationLogCommentsStoreRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValidationLogId

`func (o *ValidationLogCommentsStoreRequest) GetValidationLogId() int32`

GetValidationLogId returns the ValidationLogId field if non-nil, zero value otherwise.

### GetValidationLogIdOk

`func (o *ValidationLogCommentsStoreRequest) GetValidationLogIdOk() (*int32, bool)`

GetValidationLogIdOk returns a tuple with the ValidationLogId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationLogId

`func (o *ValidationLogCommentsStoreRequest) SetValidationLogId(v int32)`

SetValidationLogId sets ValidationLogId field to given value.


### GetComment

`func (o *ValidationLogCommentsStoreRequest) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ValidationLogCommentsStoreRequest) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ValidationLogCommentsStoreRequest) SetComment(v string)`

SetComment sets Comment field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


