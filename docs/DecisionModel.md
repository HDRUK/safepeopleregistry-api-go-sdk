# DecisionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the decision model | [optional] 
**ModelType** | **string** | Type of the model associated with the decision | 
**Conditions** | **string** | Conditions for the decision model | 
**RuleClass** | **string** | Class defining the rules for the decision model | 
**Description** | Pointer to **string** | Description of the decision model | [optional] 
**DecisionModelTypeId** | Pointer to **int32** | ID of the decision model type associated with the decision | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the decision model was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the decision model was last updated | [optional] 

## Methods

### NewDecisionModel

`func NewDecisionModel(modelType string, conditions string, ruleClass string, ) *DecisionModel`

NewDecisionModel instantiates a new DecisionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDecisionModelWithDefaults

`func NewDecisionModelWithDefaults() *DecisionModel`

NewDecisionModelWithDefaults instantiates a new DecisionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DecisionModel) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DecisionModel) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DecisionModel) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DecisionModel) HasId() bool`

HasId returns a boolean if a field has been set.

### GetModelType

`func (o *DecisionModel) GetModelType() string`

GetModelType returns the ModelType field if non-nil, zero value otherwise.

### GetModelTypeOk

`func (o *DecisionModel) GetModelTypeOk() (*string, bool)`

GetModelTypeOk returns a tuple with the ModelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelType

`func (o *DecisionModel) SetModelType(v string)`

SetModelType sets ModelType field to given value.


### GetConditions

`func (o *DecisionModel) GetConditions() string`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *DecisionModel) GetConditionsOk() (*string, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *DecisionModel) SetConditions(v string)`

SetConditions sets Conditions field to given value.


### GetRuleClass

`func (o *DecisionModel) GetRuleClass() string`

GetRuleClass returns the RuleClass field if non-nil, zero value otherwise.

### GetRuleClassOk

`func (o *DecisionModel) GetRuleClassOk() (*string, bool)`

GetRuleClassOk returns a tuple with the RuleClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleClass

`func (o *DecisionModel) SetRuleClass(v string)`

SetRuleClass sets RuleClass field to given value.


### GetDescription

`func (o *DecisionModel) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DecisionModel) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DecisionModel) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DecisionModel) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDecisionModelTypeId

`func (o *DecisionModel) GetDecisionModelTypeId() int32`

GetDecisionModelTypeId returns the DecisionModelTypeId field if non-nil, zero value otherwise.

### GetDecisionModelTypeIdOk

`func (o *DecisionModel) GetDecisionModelTypeIdOk() (*int32, bool)`

GetDecisionModelTypeIdOk returns a tuple with the DecisionModelTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecisionModelTypeId

`func (o *DecisionModel) SetDecisionModelTypeId(v int32)`

SetDecisionModelTypeId sets DecisionModelTypeId field to given value.

### HasDecisionModelTypeId

`func (o *DecisionModel) HasDecisionModelTypeId() bool`

HasDecisionModelTypeId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DecisionModel) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DecisionModel) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DecisionModel) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DecisionModel) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DecisionModel) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DecisionModel) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DecisionModel) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DecisionModel) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


