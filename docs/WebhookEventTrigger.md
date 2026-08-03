# WebhookEventTrigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the webhook event trigger | [optional] 
**Name** | Pointer to **string** | Name of the webhook event trigger | [optional] 
**Description** | Pointer to **string** | Description of the webhook event trigger | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether the webhook event trigger is enabled | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the webhook event trigger was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the webhook event trigger was last updated | [optional] 

## Methods

### NewWebhookEventTrigger

`func NewWebhookEventTrigger() *WebhookEventTrigger`

NewWebhookEventTrigger instantiates a new WebhookEventTrigger object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEventTriggerWithDefaults

`func NewWebhookEventTriggerWithDefaults() *WebhookEventTrigger`

NewWebhookEventTriggerWithDefaults instantiates a new WebhookEventTrigger object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookEventTrigger) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookEventTrigger) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookEventTrigger) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookEventTrigger) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *WebhookEventTrigger) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WebhookEventTrigger) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WebhookEventTrigger) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WebhookEventTrigger) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *WebhookEventTrigger) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WebhookEventTrigger) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WebhookEventTrigger) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *WebhookEventTrigger) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEnabled

`func (o *WebhookEventTrigger) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WebhookEventTrigger) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WebhookEventTrigger) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WebhookEventTrigger) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WebhookEventTrigger) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookEventTrigger) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookEventTrigger) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookEventTrigger) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhookEventTrigger) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookEventTrigger) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookEventTrigger) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookEventTrigger) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


