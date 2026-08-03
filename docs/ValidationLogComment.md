# ValidationLogComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**ValidationLogId** | Pointer to **int32** | ID of the associated validation log | [optional] 
**UserId** | Pointer to **int32** | ID of the user who made the comment | [optional] 
**Comment** | Pointer to **string** | The comment text | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the comment was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the comment was last updated | [optional] 

## Methods

### NewValidationLogComment

`func NewValidationLogComment() *ValidationLogComment`

NewValidationLogComment instantiates a new ValidationLogComment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationLogCommentWithDefaults

`func NewValidationLogCommentWithDefaults() *ValidationLogComment`

NewValidationLogCommentWithDefaults instantiates a new ValidationLogComment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ValidationLogComment) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ValidationLogComment) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ValidationLogComment) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ValidationLogComment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetValidationLogId

`func (o *ValidationLogComment) GetValidationLogId() int32`

GetValidationLogId returns the ValidationLogId field if non-nil, zero value otherwise.

### GetValidationLogIdOk

`func (o *ValidationLogComment) GetValidationLogIdOk() (*int32, bool)`

GetValidationLogIdOk returns a tuple with the ValidationLogId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationLogId

`func (o *ValidationLogComment) SetValidationLogId(v int32)`

SetValidationLogId sets ValidationLogId field to given value.

### HasValidationLogId

`func (o *ValidationLogComment) HasValidationLogId() bool`

HasValidationLogId returns a boolean if a field has been set.

### GetUserId

`func (o *ValidationLogComment) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ValidationLogComment) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ValidationLogComment) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *ValidationLogComment) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetComment

`func (o *ValidationLogComment) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ValidationLogComment) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ValidationLogComment) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ValidationLogComment) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ValidationLogComment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ValidationLogComment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ValidationLogComment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ValidationLogComment) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ValidationLogComment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ValidationLogComment) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ValidationLogComment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ValidationLogComment) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


