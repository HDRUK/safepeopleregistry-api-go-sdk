# QueryQuery200ResponseDataRegistryAllOfHistoryInner

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
**Affiliation** | Pointer to [**NullableAffiliation**](Affiliation.md) |  | [optional] 
**Project** | Pointer to [**NullableProject**](Project.md) |  | [optional] 

## Methods

### NewQueryQuery200ResponseDataRegistryAllOfHistoryInner

`func NewQueryQuery200ResponseDataRegistryAllOfHistoryInner() *QueryQuery200ResponseDataRegistryAllOfHistoryInner`

NewQueryQuery200ResponseDataRegistryAllOfHistoryInner instantiates a new QueryQuery200ResponseDataRegistryAllOfHistoryInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryQuery200ResponseDataRegistryAllOfHistoryInnerWithDefaults

`func NewQueryQuery200ResponseDataRegistryAllOfHistoryInnerWithDefaults() *QueryQuery200ResponseDataRegistryAllOfHistoryInner`

NewQueryQuery200ResponseDataRegistryAllOfHistoryInnerWithDefaults instantiates a new QueryQuery200ResponseDataRegistryAllOfHistoryInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAffiliationId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAffiliationId() int32`

GetAffiliationId returns the AffiliationId field if non-nil, zero value otherwise.

### GetAffiliationIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAffiliationIdOk() (*int32, bool)`

GetAffiliationIdOk returns a tuple with the AffiliationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliationId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetAffiliationId(v int32)`

SetAffiliationId sets AffiliationId field to given value.

### HasAffiliationId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasAffiliationId() bool`

HasAffiliationId returns a boolean if a field has been set.

### GetEndorsementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetEndorsementId() int32`

GetEndorsementId returns the EndorsementId field if non-nil, zero value otherwise.

### GetEndorsementIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetEndorsementIdOk() (*int32, bool)`

GetEndorsementIdOk returns a tuple with the EndorsementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndorsementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetEndorsementId(v int32)`

SetEndorsementId sets EndorsementId field to given value.

### HasEndorsementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasEndorsementId() bool`

HasEndorsementId returns a boolean if a field has been set.

### GetInfringementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetInfringementId() int32`

GetInfringementId returns the InfringementId field if non-nil, zero value otherwise.

### GetInfringementIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetInfringementIdOk() (*int32, bool)`

GetInfringementIdOk returns a tuple with the InfringementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfringementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetInfringementId(v int32)`

SetInfringementId sets InfringementId field to given value.

### HasInfringementId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasInfringementId() bool`

HasInfringementId returns a boolean if a field has been set.

### GetProjectId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetAccessKeyId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAccessKeyId() int32`

GetAccessKeyId returns the AccessKeyId field if non-nil, zero value otherwise.

### GetAccessKeyIdOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAccessKeyIdOk() (*int32, bool)`

GetAccessKeyIdOk returns a tuple with the AccessKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeyId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetAccessKeyId(v int32)`

SetAccessKeyId sets AccessKeyId field to given value.

### HasAccessKeyId

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasAccessKeyId() bool`

HasAccessKeyId returns a boolean if a field has been set.

### GetCustodianIdentifier

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetCustodianIdentifier() string`

GetCustodianIdentifier returns the CustodianIdentifier field if non-nil, zero value otherwise.

### GetCustodianIdentifierOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetCustodianIdentifierOk() (*string, bool)`

GetCustodianIdentifierOk returns a tuple with the CustodianIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianIdentifier

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetCustodianIdentifier(v string)`

SetCustodianIdentifier sets CustodianIdentifier field to given value.

### HasCustodianIdentifier

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasCustodianIdentifier() bool`

HasCustodianIdentifier returns a boolean if a field has been set.

### GetLedgerHash

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetLedgerHash() string`

GetLedgerHash returns the LedgerHash field if non-nil, zero value otherwise.

### GetLedgerHashOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetLedgerHashOk() (*string, bool)`

GetLedgerHashOk returns a tuple with the LedgerHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerHash

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetLedgerHash(v string)`

SetLedgerHash sets LedgerHash field to given value.

### HasLedgerHash

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasLedgerHash() bool`

HasLedgerHash returns a boolean if a field has been set.

### GetCreatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetAffiliation

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAffiliation() Affiliation`

GetAffiliation returns the Affiliation field if non-nil, zero value otherwise.

### GetAffiliationOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetAffiliationOk() (*Affiliation, bool)`

GetAffiliationOk returns a tuple with the Affiliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliation

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetAffiliation(v Affiliation)`

SetAffiliation sets Affiliation field to given value.

### HasAffiliation

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasAffiliation() bool`

HasAffiliation returns a boolean if a field has been set.

### SetAffiliationNil

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetAffiliationNil(b bool)`

 SetAffiliationNil sets the value for Affiliation to be an explicit nil

### UnsetAffiliation
`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) UnsetAffiliation()`

UnsetAffiliation ensures that no value is present for Affiliation, not even an explicit nil
### GetProject

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetProject() Project`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) GetProjectOk() (*Project, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetProject(v Project)`

SetProject sets Project field to given value.

### HasProject

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *QueryQuery200ResponseDataRegistryAllOfHistoryInner) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


