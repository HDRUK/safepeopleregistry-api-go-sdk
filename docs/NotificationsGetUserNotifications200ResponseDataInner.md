# NotificationsGetUserNotifications200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**NotifiableType** | Pointer to **string** |  | [optional] 
**NotifiableId** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**NotificationsGetUserNotifications200ResponseDataInnerData**](NotificationsGetUserNotifications200ResponseDataInnerData.md) |  | [optional] 
**ReadAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewNotificationsGetUserNotifications200ResponseDataInner

`func NewNotificationsGetUserNotifications200ResponseDataInner() *NotificationsGetUserNotifications200ResponseDataInner`

NewNotificationsGetUserNotifications200ResponseDataInner instantiates a new NotificationsGetUserNotifications200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationsGetUserNotifications200ResponseDataInnerWithDefaults

`func NewNotificationsGetUserNotifications200ResponseDataInnerWithDefaults() *NotificationsGetUserNotifications200ResponseDataInner`

NewNotificationsGetUserNotifications200ResponseDataInnerWithDefaults instantiates a new NotificationsGetUserNotifications200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNotifiableType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetNotifiableType() string`

GetNotifiableType returns the NotifiableType field if non-nil, zero value otherwise.

### GetNotifiableTypeOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetNotifiableTypeOk() (*string, bool)`

GetNotifiableTypeOk returns a tuple with the NotifiableType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifiableType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetNotifiableType(v string)`

SetNotifiableType sets NotifiableType field to given value.

### HasNotifiableType

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasNotifiableType() bool`

HasNotifiableType returns a boolean if a field has been set.

### GetNotifiableId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetNotifiableId() int32`

GetNotifiableId returns the NotifiableId field if non-nil, zero value otherwise.

### GetNotifiableIdOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetNotifiableIdOk() (*int32, bool)`

GetNotifiableIdOk returns a tuple with the NotifiableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifiableId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetNotifiableId(v int32)`

SetNotifiableId sets NotifiableId field to given value.

### HasNotifiableId

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasNotifiableId() bool`

HasNotifiableId returns a boolean if a field has been set.

### GetData

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetData() NotificationsGetUserNotifications200ResponseDataInnerData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetDataOk() (*NotificationsGetUserNotifications200ResponseDataInnerData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetData(v NotificationsGetUserNotifications200ResponseDataInnerData)`

SetData sets Data field to given value.

### HasData

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasData() bool`

HasData returns a boolean if a field has been set.

### GetReadAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetReadAt() time.Time`

GetReadAt returns the ReadAt field if non-nil, zero value otherwise.

### GetReadAtOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetReadAtOk() (*time.Time, bool)`

GetReadAtOk returns a tuple with the ReadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetReadAt(v time.Time)`

SetReadAt sets ReadAt field to given value.

### HasReadAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasReadAt() bool`

HasReadAt returns a boolean if a field has been set.

### SetReadAtNil

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetReadAtNil(b bool)`

 SetReadAtNil sets the value for ReadAt to be an explicit nil

### UnsetReadAt
`func (o *NotificationsGetUserNotifications200ResponseDataInner) UnsetReadAt()`

UnsetReadAt ensures that no value is present for ReadAt, not even an explicit nil
### GetCreatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *NotificationsGetUserNotifications200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *NotificationsGetUserNotifications200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


