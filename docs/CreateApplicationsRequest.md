# CreateApplicationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Permissions** | Pointer to **[]interface{}** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewCreateApplicationsRequest

`func NewCreateApplicationsRequest() *CreateApplicationsRequest`

NewCreateApplicationsRequest instantiates a new CreateApplicationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApplicationsRequestWithDefaults

`func NewCreateApplicationsRequestWithDefaults() *CreateApplicationsRequest`

NewCreateApplicationsRequestWithDefaults instantiates a new CreateApplicationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateApplicationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApplicationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApplicationsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateApplicationsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetImageLink

`func (o *CreateApplicationsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *CreateApplicationsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *CreateApplicationsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *CreateApplicationsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetDescription

`func (o *CreateApplicationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateApplicationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateApplicationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateApplicationsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTeamId

`func (o *CreateApplicationsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateApplicationsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateApplicationsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *CreateApplicationsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateApplicationsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateApplicationsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateApplicationsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateApplicationsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateApplicationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateApplicationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateApplicationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateApplicationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPermissions

`func (o *CreateApplicationsRequest) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateApplicationsRequest) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateApplicationsRequest) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *CreateApplicationsRequest) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetNotifications

`func (o *CreateApplicationsRequest) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *CreateApplicationsRequest) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *CreateApplicationsRequest) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *CreateApplicationsRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


