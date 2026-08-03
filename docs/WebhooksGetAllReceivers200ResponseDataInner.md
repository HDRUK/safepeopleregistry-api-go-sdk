# WebhooksGetAllReceivers200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CustodianId** | Pointer to **int32** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**WebhookEvent** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**EventTrigger** | Pointer to [**WebhooksGetAllReceivers200ResponseDataInnerEventTrigger**](WebhooksGetAllReceivers200ResponseDataInnerEventTrigger.md) |  | [optional] 

## Methods

### NewWebhooksGetAllReceivers200ResponseDataInner

`func NewWebhooksGetAllReceivers200ResponseDataInner() *WebhooksGetAllReceivers200ResponseDataInner`

NewWebhooksGetAllReceivers200ResponseDataInner instantiates a new WebhooksGetAllReceivers200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhooksGetAllReceivers200ResponseDataInnerWithDefaults

`func NewWebhooksGetAllReceivers200ResponseDataInnerWithDefaults() *WebhooksGetAllReceivers200ResponseDataInner`

NewWebhooksGetAllReceivers200ResponseDataInnerWithDefaults instantiates a new WebhooksGetAllReceivers200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustodianId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.

### HasCustodianId

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasCustodianId() bool`

HasCustodianId returns a boolean if a field has been set.

### GetUrl

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetWebhookEvent

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetWebhookEvent() int32`

GetWebhookEvent returns the WebhookEvent field if non-nil, zero value otherwise.

### GetWebhookEventOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetWebhookEventOk() (*int32, bool)`

GetWebhookEventOk returns a tuple with the WebhookEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEvent

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetWebhookEvent(v int32)`

SetWebhookEvent sets WebhookEvent field to given value.

### HasWebhookEvent

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasWebhookEvent() bool`

HasWebhookEvent returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetEventTrigger

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetEventTrigger() WebhooksGetAllReceivers200ResponseDataInnerEventTrigger`

GetEventTrigger returns the EventTrigger field if non-nil, zero value otherwise.

### GetEventTriggerOk

`func (o *WebhooksGetAllReceivers200ResponseDataInner) GetEventTriggerOk() (*WebhooksGetAllReceivers200ResponseDataInnerEventTrigger, bool)`

GetEventTriggerOk returns a tuple with the EventTrigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTrigger

`func (o *WebhooksGetAllReceivers200ResponseDataInner) SetEventTrigger(v WebhooksGetAllReceivers200ResponseDataInnerEventTrigger)`

SetEventTrigger sets EventTrigger field to given value.

### HasEventTrigger

`func (o *WebhooksGetAllReceivers200ResponseDataInner) HasEventTrigger() bool`

HasEventTrigger returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


