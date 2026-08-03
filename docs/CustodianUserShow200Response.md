# CustodianUserShow200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**CustodianUser**](CustodianUser.md) |  | [optional] 
**UserPermissions** | Pointer to [**[]CustodianUserShow200ResponseUserPermissionsInner**](CustodianUserShow200ResponseUserPermissionsInner.md) |  | [optional] 

## Methods

### NewCustodianUserShow200Response

`func NewCustodianUserShow200Response() *CustodianUserShow200Response`

NewCustodianUserShow200Response instantiates a new CustodianUserShow200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustodianUserShow200ResponseWithDefaults

`func NewCustodianUserShow200ResponseWithDefaults() *CustodianUserShow200Response`

NewCustodianUserShow200ResponseWithDefaults instantiates a new CustodianUserShow200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CustodianUserShow200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CustodianUserShow200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CustodianUserShow200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CustodianUserShow200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *CustodianUserShow200Response) GetData() CustodianUser`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CustodianUserShow200Response) GetDataOk() (*CustodianUser, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CustodianUserShow200Response) SetData(v CustodianUser)`

SetData sets Data field to given value.

### HasData

`func (o *CustodianUserShow200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetUserPermissions

`func (o *CustodianUserShow200Response) GetUserPermissions() []CustodianUserShow200ResponseUserPermissionsInner`

GetUserPermissions returns the UserPermissions field if non-nil, zero value otherwise.

### GetUserPermissionsOk

`func (o *CustodianUserShow200Response) GetUserPermissionsOk() (*[]CustodianUserShow200ResponseUserPermissionsInner, bool)`

GetUserPermissionsOk returns a tuple with the UserPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserPermissions

`func (o *CustodianUserShow200Response) SetUserPermissions(v []CustodianUserShow200ResponseUserPermissionsInner)`

SetUserPermissions sets UserPermissions field to given value.

### HasUserPermissions

`func (o *CustodianUserShow200Response) HasUserPermissions() bool`

HasUserPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


