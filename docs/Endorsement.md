# Endorsement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the endorsement | [optional] 
**ReportedBy** | Pointer to **int32** | ID of the user who reported the endorsement | [optional] 
**Comment** | Pointer to **string** | Optional comment provided by the reporter | [optional] 
**RaisedAgainst** | Pointer to **int32** | ID of the entity the endorsement is raised against | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the endorsement was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the endorsement was last updated | [optional] 

## Methods

### NewEndorsement

`func NewEndorsement() *Endorsement`

NewEndorsement instantiates a new Endorsement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEndorsementWithDefaults

`func NewEndorsementWithDefaults() *Endorsement`

NewEndorsementWithDefaults instantiates a new Endorsement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Endorsement) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Endorsement) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Endorsement) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Endorsement) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReportedBy

`func (o *Endorsement) GetReportedBy() int32`

GetReportedBy returns the ReportedBy field if non-nil, zero value otherwise.

### GetReportedByOk

`func (o *Endorsement) GetReportedByOk() (*int32, bool)`

GetReportedByOk returns a tuple with the ReportedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportedBy

`func (o *Endorsement) SetReportedBy(v int32)`

SetReportedBy sets ReportedBy field to given value.

### HasReportedBy

`func (o *Endorsement) HasReportedBy() bool`

HasReportedBy returns a boolean if a field has been set.

### GetComment

`func (o *Endorsement) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *Endorsement) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *Endorsement) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *Endorsement) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetRaisedAgainst

`func (o *Endorsement) GetRaisedAgainst() int32`

GetRaisedAgainst returns the RaisedAgainst field if non-nil, zero value otherwise.

### GetRaisedAgainstOk

`func (o *Endorsement) GetRaisedAgainstOk() (*int32, bool)`

GetRaisedAgainstOk returns a tuple with the RaisedAgainst field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaisedAgainst

`func (o *Endorsement) SetRaisedAgainst(v int32)`

SetRaisedAgainst sets RaisedAgainst field to given value.

### HasRaisedAgainst

`func (o *Endorsement) HasRaisedAgainst() bool`

HasRaisedAgainst returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Endorsement) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Endorsement) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Endorsement) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Endorsement) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Endorsement) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Endorsement) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Endorsement) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Endorsement) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


