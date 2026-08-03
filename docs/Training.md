# Training

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**RegistryId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**AwardedAt** | Pointer to **string** |  | [optional] 
**ExpiresAt** | Pointer to **string** |  | [optional] 
**ExpiresInYears** | Pointer to **int32** |  | [optional] 
**TrainingName** | Pointer to **string** |  | [optional] 
**ProRegistration** | Pointer to **int32** |  | [optional] 

## Methods

### NewTraining

`func NewTraining() *Training`

NewTraining instantiates a new Training object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrainingWithDefaults

`func NewTrainingWithDefaults() *Training`

NewTrainingWithDefaults instantiates a new Training object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Training) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Training) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Training) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Training) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Training) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Training) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Training) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Training) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Training) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Training) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Training) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Training) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetRegistryId

`func (o *Training) GetRegistryId() int32`

GetRegistryId returns the RegistryId field if non-nil, zero value otherwise.

### GetRegistryIdOk

`func (o *Training) GetRegistryIdOk() (*int32, bool)`

GetRegistryIdOk returns a tuple with the RegistryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryId

`func (o *Training) SetRegistryId(v int32)`

SetRegistryId sets RegistryId field to given value.

### HasRegistryId

`func (o *Training) HasRegistryId() bool`

HasRegistryId returns a boolean if a field has been set.

### GetProvider

`func (o *Training) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *Training) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *Training) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *Training) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetAwardedAt

`func (o *Training) GetAwardedAt() string`

GetAwardedAt returns the AwardedAt field if non-nil, zero value otherwise.

### GetAwardedAtOk

`func (o *Training) GetAwardedAtOk() (*string, bool)`

GetAwardedAtOk returns a tuple with the AwardedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwardedAt

`func (o *Training) SetAwardedAt(v string)`

SetAwardedAt sets AwardedAt field to given value.

### HasAwardedAt

`func (o *Training) HasAwardedAt() bool`

HasAwardedAt returns a boolean if a field has been set.

### GetExpiresAt

`func (o *Training) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Training) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Training) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *Training) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetExpiresInYears

`func (o *Training) GetExpiresInYears() int32`

GetExpiresInYears returns the ExpiresInYears field if non-nil, zero value otherwise.

### GetExpiresInYearsOk

`func (o *Training) GetExpiresInYearsOk() (*int32, bool)`

GetExpiresInYearsOk returns a tuple with the ExpiresInYears field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresInYears

`func (o *Training) SetExpiresInYears(v int32)`

SetExpiresInYears sets ExpiresInYears field to given value.

### HasExpiresInYears

`func (o *Training) HasExpiresInYears() bool`

HasExpiresInYears returns a boolean if a field has been set.

### GetTrainingName

`func (o *Training) GetTrainingName() string`

GetTrainingName returns the TrainingName field if non-nil, zero value otherwise.

### GetTrainingNameOk

`func (o *Training) GetTrainingNameOk() (*string, bool)`

GetTrainingNameOk returns a tuple with the TrainingName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrainingName

`func (o *Training) SetTrainingName(v string)`

SetTrainingName sets TrainingName field to given value.

### HasTrainingName

`func (o *Training) HasTrainingName() bool`

HasTrainingName returns a boolean if a field has been set.

### GetProRegistration

`func (o *Training) GetProRegistration() int32`

GetProRegistration returns the ProRegistration field if non-nil, zero value otherwise.

### GetProRegistrationOk

`func (o *Training) GetProRegistrationOk() (*int32, bool)`

GetProRegistrationOk returns a tuple with the ProRegistration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProRegistration

`func (o *Training) SetProRegistration(v int32)`

SetProRegistration sets ProRegistration field to given value.

### HasProRegistration

`func (o *Training) HasProRegistration() bool`

HasProRegistration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


