# CustodianWebhookReceiver

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Unique identifier for the webhook receiver | [optional] 
**CustodianId** | Pointer to **int32** | ID of the custodian associated with the webhook receiver | [optional] 
**Url** | Pointer to **string** | URL of the webhook receiver | [optional] 
**WebhookEvent** | Pointer to **int32** | ID of the webhook event associated with the receiver | [optional] 
**CreatedAt** | Pointer to **time.Time** | Timestamp when the webhook receiver was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Timestamp when the webhook receiver was last updated | [optional] 

## Methods

### NewCustodianWebhookReceiver

`func NewCustodianWebhookReceiver() *CustodianWebhookReceiver`

NewCustodianWebhookReceiver instantiates a new CustodianWebhookReceiver object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianWebhookReceiverWithDefaults

`func NewCustodianWebhookReceiverWithDefaults() *CustodianWebhookReceiver`

NewCustodianWebhookReceiverWithDefaults instantiates a new CustodianWebhookReceiver object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustodianWebhookReceiver) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustodianWebhookReceiver) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustodianWebhookReceiver) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CustodianWebhookReceiver) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCustodianId

`func (o *CustodianWebhookReceiver) GetCustodianId() int32`

GetCustodianId returns the CustodianId field if non-nil, zero value otherwise.

### GetCustodianIdOk

`func (o *CustodianWebhookReceiver) GetCustodianIdOk() (*int32, bool)`

GetCustodianIdOk returns a tuple with the CustodianId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustodianId

`func (o *CustodianWebhookReceiver) SetCustodianId(v int32)`

SetCustodianId sets CustodianId field to given value.

### HasCustodianId

`func (o *CustodianWebhookReceiver) HasCustodianId() bool`

HasCustodianId returns a boolean if a field has been set.

### GetUrl

`func (o *CustodianWebhookReceiver) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CustodianWebhookReceiver) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CustodianWebhookReceiver) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CustodianWebhookReceiver) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetWebhookEvent

`func (o *CustodianWebhookReceiver) GetWebhookEvent() int32`

GetWebhookEvent returns the WebhookEvent field if non-nil, zero value otherwise.

### GetWebhookEventOk

`func (o *CustodianWebhookReceiver) GetWebhookEventOk() (*int32, bool)`

GetWebhookEventOk returns a tuple with the WebhookEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEvent

`func (o *CustodianWebhookReceiver) SetWebhookEvent(v int32)`

SetWebhookEvent sets WebhookEvent field to given value.

### HasWebhookEvent

`func (o *CustodianWebhookReceiver) HasWebhookEvent() bool`

HasWebhookEvent returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CustodianWebhookReceiver) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustodianWebhookReceiver) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustodianWebhookReceiver) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CustodianWebhookReceiver) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CustodianWebhookReceiver) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustodianWebhookReceiver) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustodianWebhookReceiver) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CustodianWebhookReceiver) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


