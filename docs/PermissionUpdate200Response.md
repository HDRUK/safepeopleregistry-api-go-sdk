# PermissionUpdate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**PermissionIndex200ResponseData**](PermissionIndex200ResponseData.md) |  | [optional] 

## Methods

### NewPermissionUpdate200Response

`func NewPermissionUpdate200Response() *PermissionUpdate200Response`

NewPermissionUpdate200Response instantiates a new PermissionUpdate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionUpdate200ResponseWithDefaults

`func NewPermissionUpdate200ResponseWithDefaults() *PermissionUpdate200Response`

NewPermissionUpdate200ResponseWithDefaults instantiates a new PermissionUpdate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *PermissionUpdate200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PermissionUpdate200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PermissionUpdate200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *PermissionUpdate200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *PermissionUpdate200Response) GetData() PermissionIndex200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PermissionUpdate200Response) GetDataOk() (*PermissionIndex200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PermissionUpdate200Response) SetData(v PermissionIndex200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *PermissionUpdate200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


