# History

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the history record | [optional] 
**AffiliationId** | Pointer to **int32** | ID of the affiliation associated with the history record | [optional] 
**EndorsementId** | Pointer to **int32** | ID of the endorsement associated with the history record | [optional] 
**InfringementId** | Pointer to **int32** | ID of the infringement associated with the history record | [optional] 
**ProjectId** | Pointer to **int32** | ID of the project associated with the history record | [optional] 
**AccessKeyId** | Pointer to **int32** | ID of the access key associated with the history record | [optional] 
**CustodianIdentifier** | Pointer to **string** | Identifier for the custodian associated with the history record | [optional] 
**LedgerHash** | Pointer to **string** | Hash of the ledger associated with the history record | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the history record was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the history record was last updated | [optional] 

## Methods

### NewHistory

`func NewHistory() *History`

NewHistory instantiates a new History object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryWithDefaults

`func NewHistoryWithDefaults() *History`

NewHistoryWithDefaults instantiates a new History object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *History) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *History) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *History) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *History) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAffiliationId

`func (o *History) GetAffiliationId() int32`

GetAffiliationId returns the AffiliationId field if non-nil, zero value otherwise.

### GetAffiliationIdOk

`func (o *History) GetAffiliationIdOk() (*int32, bool)`

GetAffiliationIdOk returns a tuple with the AffiliationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliationId

`func (o *History) SetAffiliationId(v int32)`

SetAffiliationId sets AffiliationId field to given value.

### HasAffiliationId

`func (o *History) HasAffiliationId() bool`

HasAffiliationId returns a boolean if a field has been set.

### GetEndorsementId

`func (o *History) GetEndorsementId() int32`

GetEndorsementId returns the EndorsementId field if non-nil, zero value otherwise.

### GetEndorsementIdOk

`func (o *History) GetEndorsementIdOk() (*int32, bool)`

GetEndorsementIdOk returns a tuple with the EndorsementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndorsementId

`func (o *History) SetEndorsementId(v int32)`

SetEndorsementId sets EndorsementId field to given value.

### HasEndorsementId

`func (o *History) HasEndorsementId() bool`

HasEndorsementId returns a boolean if a field has been set.

### GetInfringementId

`func (o *History) GetInfringementId() int32`

GetInfringementId returns the InfringementId field if non-nil, zero value otherwise.

### GetInfringementIdOk

`func (o *History) GetInfringementIdOk() (*int32, bool)`

GetInfringementIdOk returns a tuple with the InfringementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfringementId

`func (o *History) SetInfringementId(v int32)`

SetInfringementId sets InfringementId field to given value.

### HasInfringementId

`func (o *History) HasInfringementId() bool`

HasInfringementId returns a boolean if a field has been set.

### GetProjectId

`func (o *History) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *History) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *History) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *History) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetAccessKeyId

`func (o *History) GetAccessKeyId() int32`

GetAccessKeyId returns the AccessKeyId field if non-nil, zero value otherwise.

### GetAccessKeyIdOk

`func (o *History) GetAccessKeyIdOk() (*int32, bool)`

GetAccessKeyIdOk returns a tuple with the AccessKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeyId

`func (o *History) SetAccessKeyId(v int32)`

SetAccessKeyId sets AccessKeyId field to given value.

### HasAccessKeyId

`func (o *History) HasAccessKeyId() bool`

HasAccessKeyId returns a boolean if a field has been set.

### GetCustodianIdentifier

`func (o *History) GetCustodianIdentifier() string`

GetCustodianIdentifier returns the CustodianIdentifier field if non-nil, zero value otherwise.

### GetCustodianIdentifierOk

`func (o *History) GetCustodianIdentifierOk() (*string, bool)`

GetCustodianIdentifierOk returns a tuple with the CustodianIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianIdentifier

`func (o *History) SetCustodianIdentifier(v string)`

SetCustodianIdentifier sets CustodianIdentifier field to given value.

### HasCustodianIdentifier

`func (o *History) HasCustodianIdentifier() bool`

HasCustodianIdentifier returns a boolean if a field has been set.

### GetLedgerHash

`func (o *History) GetLedgerHash() string`

GetLedgerHash returns the LedgerHash field if non-nil, zero value otherwise.

### GetLedgerHashOk

`func (o *History) GetLedgerHashOk() (*string, bool)`

GetLedgerHashOk returns a tuple with the LedgerHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerHash

`func (o *History) SetLedgerHash(v string)`

SetLedgerHash sets LedgerHash field to given value.

### HasLedgerHash

`func (o *History) HasLedgerHash() bool`

HasLedgerHash returns a boolean if a field has been set.

### GetCreatedAt

`func (o *History) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *History) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *History) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *History) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *History) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *History) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *History) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *History) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


