# CustodianProjectUsersUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Approved** | Pointer to **bool** | Approval status | [optional] 
**Comment** | Pointer to **string** | Optional comment | [optional] 
**Status** | Pointer to **string** | State machine status | [optional] 

## Methods

### NewCustodianProjectUsersUpdateRequest

`func NewCustodianProjectUsersUpdateRequest() *CustodianProjectUsersUpdateRequest`

NewCustodianProjectUsersUpdateRequest instantiates a new CustodianProjectUsersUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianProjectUsersUpdateRequestWithDefaults

`func NewCustodianProjectUsersUpdateRequestWithDefaults() *CustodianProjectUsersUpdateRequest`

NewCustodianProjectUsersUpdateRequestWithDefaults instantiates a new CustodianProjectUsersUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApproved

`func (o *CustodianProjectUsersUpdateRequest) GetApproved() bool`

GetApproved returns the Approved field if non-nil, zero value otherwise.

### GetApprovedOk

`func (o *CustodianProjectUsersUpdateRequest) GetApprovedOk() (*bool, bool)`

GetApprovedOk returns a tuple with the Approved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproved

`func (o *CustodianProjectUsersUpdateRequest) SetApproved(v bool)`

SetApproved sets Approved field to given value.

### HasApproved

`func (o *CustodianProjectUsersUpdateRequest) HasApproved() bool`

HasApproved returns a boolean if a field has been set.

### GetComment

`func (o *CustodianProjectUsersUpdateRequest) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *CustodianProjectUsersUpdateRequest) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *CustodianProjectUsersUpdateRequest) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *CustodianProjectUsersUpdateRequest) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetStatus

`func (o *CustodianProjectUsersUpdateRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CustodianProjectUsersUpdateRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CustodianProjectUsersUpdateRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CustodianProjectUsersUpdateRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


