# ProjectDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Model primary key | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **int32** | Primary key of associated Project for this ProjectDetail | [optional] 
**Datasets** | Pointer to **[]string** |  | [optional] 
**OtherApprovalCommittees** | Pointer to **[]string** |  | [optional] 
**DataSensitivityLevel** | Pointer to **string** |  | [optional] 
**LegalBasisForDataArticle6** | Pointer to **string** |  | [optional] 
**DutyOfConfidentiality** | Pointer to **bool** |  | [optional] 
**NationalDataOptout** | Pointer to **bool** |  | [optional] 
**RequestFrequency** | Pointer to **string** |  | [optional] 
**DatasetLinkageDescription** | Pointer to **string** |  | [optional] 
**DataMinimisation** | Pointer to **string** |  | [optional] 
**DataUseDescription** | Pointer to **string** |  | [optional] 
**AccessDate** | Pointer to **string** |  | [optional] 
**AccessType** | Pointer to **int32** |  | [optional] 
**DataPrivacy** | Pointer to **string** |  | [optional] 
**ResearchOutputs** | Pointer to **map[string]interface{}** |  | [optional] 
**DataAssets** | Pointer to **string** |  | [optional] 

## Methods

### NewProjectDetail

`func NewProjectDetail() *ProjectDetail`

NewProjectDetail instantiates a new ProjectDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailWithDefaults

`func NewProjectDetailWithDefaults() *ProjectDetail`

NewProjectDetailWithDefaults instantiates a new ProjectDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectDetail) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectDetail) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectDetail) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProjectDetail) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ProjectDetail) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectDetail) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectDetail) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProjectDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ProjectDetail) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProjectDetail) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProjectDetail) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProjectDetail) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetProjectId

`func (o *ProjectDetail) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectDetail) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectDetail) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ProjectDetail) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetDatasets

`func (o *ProjectDetail) GetDatasets() []string`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *ProjectDetail) GetDatasetsOk() (*[]string, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *ProjectDetail) SetDatasets(v []string)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *ProjectDetail) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *ProjectDetail) GetOtherApprovalCommittees() []string`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *ProjectDetail) GetOtherApprovalCommitteesOk() (*[]string, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *ProjectDetail) SetOtherApprovalCommittees(v []string)`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *ProjectDetail) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *ProjectDetail) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *ProjectDetail) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *ProjectDetail) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *ProjectDetail) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *ProjectDetail) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *ProjectDetail) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *ProjectDetail) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *ProjectDetail) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *ProjectDetail) GetDutyOfConfidentiality() bool`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *ProjectDetail) GetDutyOfConfidentialityOk() (*bool, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *ProjectDetail) SetDutyOfConfidentiality(v bool)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *ProjectDetail) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *ProjectDetail) GetNationalDataOptout() bool`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *ProjectDetail) GetNationalDataOptoutOk() (*bool, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *ProjectDetail) SetNationalDataOptout(v bool)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *ProjectDetail) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *ProjectDetail) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *ProjectDetail) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *ProjectDetail) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *ProjectDetail) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *ProjectDetail) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *ProjectDetail) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *ProjectDetail) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *ProjectDetail) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetDataMinimisation

`func (o *ProjectDetail) GetDataMinimisation() string`

GetDataMinimisation returns the DataMinimisation field if non-nil, zero value otherwise.

### GetDataMinimisationOk

`func (o *ProjectDetail) GetDataMinimisationOk() (*string, bool)`

GetDataMinimisationOk returns a tuple with the DataMinimisation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataMinimisation

`func (o *ProjectDetail) SetDataMinimisation(v string)`

SetDataMinimisation sets DataMinimisation field to given value.

### HasDataMinimisation

`func (o *ProjectDetail) HasDataMinimisation() bool`

HasDataMinimisation returns a boolean if a field has been set.

### GetDataUseDescription

`func (o *ProjectDetail) GetDataUseDescription() string`

GetDataUseDescription returns the DataUseDescription field if non-nil, zero value otherwise.

### GetDataUseDescriptionOk

`func (o *ProjectDetail) GetDataUseDescriptionOk() (*string, bool)`

GetDataUseDescriptionOk returns a tuple with the DataUseDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataUseDescription

`func (o *ProjectDetail) SetDataUseDescription(v string)`

SetDataUseDescription sets DataUseDescription field to given value.

### HasDataUseDescription

`func (o *ProjectDetail) HasDataUseDescription() bool`

HasDataUseDescription returns a boolean if a field has been set.

### GetAccessDate

`func (o *ProjectDetail) GetAccessDate() string`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *ProjectDetail) GetAccessDateOk() (*string, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *ProjectDetail) SetAccessDate(v string)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *ProjectDetail) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccessType

`func (o *ProjectDetail) GetAccessType() int32`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *ProjectDetail) GetAccessTypeOk() (*int32, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *ProjectDetail) SetAccessType(v int32)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *ProjectDetail) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetDataPrivacy

`func (o *ProjectDetail) GetDataPrivacy() string`

GetDataPrivacy returns the DataPrivacy field if non-nil, zero value otherwise.

### GetDataPrivacyOk

`func (o *ProjectDetail) GetDataPrivacyOk() (*string, bool)`

GetDataPrivacyOk returns a tuple with the DataPrivacy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataPrivacy

`func (o *ProjectDetail) SetDataPrivacy(v string)`

SetDataPrivacy sets DataPrivacy field to given value.

### HasDataPrivacy

`func (o *ProjectDetail) HasDataPrivacy() bool`

HasDataPrivacy returns a boolean if a field has been set.

### GetResearchOutputs

`func (o *ProjectDetail) GetResearchOutputs() map[string]interface{}`

GetResearchOutputs returns the ResearchOutputs field if non-nil, zero value otherwise.

### GetResearchOutputsOk

`func (o *ProjectDetail) GetResearchOutputsOk() (*map[string]interface{}, bool)`

GetResearchOutputsOk returns a tuple with the ResearchOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResearchOutputs

`func (o *ProjectDetail) SetResearchOutputs(v map[string]interface{})`

SetResearchOutputs sets ResearchOutputs field to given value.

### HasResearchOutputs

`func (o *ProjectDetail) HasResearchOutputs() bool`

HasResearchOutputs returns a boolean if a field has been set.

### GetDataAssets

`func (o *ProjectDetail) GetDataAssets() string`

GetDataAssets returns the DataAssets field if non-nil, zero value otherwise.

### GetDataAssetsOk

`func (o *ProjectDetail) GetDataAssetsOk() (*string, bool)`

GetDataAssetsOk returns a tuple with the DataAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataAssets

`func (o *ProjectDetail) SetDataAssets(v string)`

SetDataAssets sets DataAssets field to given value.

### HasDataAssets

`func (o *ProjectDetail) HasDataAssets() bool`

HasDataAssets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


