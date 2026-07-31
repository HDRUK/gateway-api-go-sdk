# UpdateApplicationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**ImageLink** | **string** |  | 
**Description** | **string** |  | 
**TeamId** | **int32** |  | 
**UserId** | **int32** |  | 
**Enabled** | **bool** |  | 
**Permissions** | **[]interface{}** |  | 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewUpdateApplicationsRequest

`func NewUpdateApplicationsRequest(name string, imageLink string, description string, teamId int32, userId int32, enabled bool, permissions []interface{}, ) *UpdateApplicationsRequest`

NewUpdateApplicationsRequest instantiates a new UpdateApplicationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateApplicationsRequestWithDefaults

`func NewUpdateApplicationsRequestWithDefaults() *UpdateApplicationsRequest`

NewUpdateApplicationsRequestWithDefaults instantiates a new UpdateApplicationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateApplicationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateApplicationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateApplicationsRequest) SetName(v string)`

SetName sets Name field to given value.


### GetImageLink

`func (o *UpdateApplicationsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *UpdateApplicationsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *UpdateApplicationsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.


### GetDescription

`func (o *UpdateApplicationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateApplicationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateApplicationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetTeamId

`func (o *UpdateApplicationsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *UpdateApplicationsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *UpdateApplicationsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.


### GetUserId

`func (o *UpdateApplicationsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateApplicationsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateApplicationsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.


### GetEnabled

`func (o *UpdateApplicationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateApplicationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateApplicationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetPermissions

`func (o *UpdateApplicationsRequest) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *UpdateApplicationsRequest) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *UpdateApplicationsRequest) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.


### GetNotifications

`func (o *UpdateApplicationsRequest) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *UpdateApplicationsRequest) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *UpdateApplicationsRequest) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *UpdateApplicationsRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


