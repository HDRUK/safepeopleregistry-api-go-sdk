# IDVTPlugin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the IDVT plugin | [optional] 
**Function** | Pointer to **string** | Function name of the plugin | [optional] 
**Args** | Pointer to **string** | Arguments passed to the plugin function | [optional] 
**Config** | Pointer to **string** | Configuration settings for the plugin | [optional] 
**Enabled** | Pointer to **int32** | Indicates whether the plugin is enabled (1 for enabled, 0 for disabled) | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the plugin was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the plugin was last updated | [optional] 

## Methods

### NewIDVTPlugin

`func NewIDVTPlugin() *IDVTPlugin`

NewIDVTPlugin instantiates a new IDVTPlugin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIDVTPluginWithDefaults

`func NewIDVTPluginWithDefaults() *IDVTPlugin`

NewIDVTPluginWithDefaults instantiates a new IDVTPlugin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IDVTPlugin) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IDVTPlugin) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IDVTPlugin) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *IDVTPlugin) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFunction

`func (o *IDVTPlugin) GetFunction() string`

GetFunction returns the Function field if non-nil, zero value otherwise.

### GetFunctionOk

`func (o *IDVTPlugin) GetFunctionOk() (*string, bool)`

GetFunctionOk returns a tuple with the Function field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunction

`func (o *IDVTPlugin) SetFunction(v string)`

SetFunction sets Function field to given value.

### HasFunction

`func (o *IDVTPlugin) HasFunction() bool`

HasFunction returns a boolean if a field has been set.

### GetArgs

`func (o *IDVTPlugin) GetArgs() string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *IDVTPlugin) GetArgsOk() (*string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *IDVTPlugin) SetArgs(v string)`

SetArgs sets Args field to given value.

### HasArgs

`func (o *IDVTPlugin) HasArgs() bool`

HasArgs returns a boolean if a field has been set.

### GetConfig

`func (o *IDVTPlugin) GetConfig() string`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *IDVTPlugin) GetConfigOk() (*string, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *IDVTPlugin) SetConfig(v string)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *IDVTPlugin) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetEnabled

`func (o *IDVTPlugin) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *IDVTPlugin) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *IDVTPlugin) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *IDVTPlugin) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *IDVTPlugin) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *IDVTPlugin) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *IDVTPlugin) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *IDVTPlugin) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *IDVTPlugin) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *IDVTPlugin) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *IDVTPlugin) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *IDVTPlugin) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


