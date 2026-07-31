# EditApplicationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**ClientId** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Permissions** | Pointer to **[]interface{}** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewEditApplicationsRequest

`func NewEditApplicationsRequest() *EditApplicationsRequest`

NewEditApplicationsRequest instantiates a new EditApplicationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditApplicationsRequestWithDefaults

`func NewEditApplicationsRequestWithDefaults() *EditApplicationsRequest`

NewEditApplicationsRequestWithDefaults instantiates a new EditApplicationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *EditApplicationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EditApplicationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EditApplicationsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EditApplicationsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAppId

`func (o *EditApplicationsRequest) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *EditApplicationsRequest) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *EditApplicationsRequest) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *EditApplicationsRequest) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetClientId

`func (o *EditApplicationsRequest) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *EditApplicationsRequest) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *EditApplicationsRequest) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *EditApplicationsRequest) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### GetImageLink

`func (o *EditApplicationsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *EditApplicationsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *EditApplicationsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *EditApplicationsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetDescription

`func (o *EditApplicationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EditApplicationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EditApplicationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EditApplicationsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTeamId

`func (o *EditApplicationsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *EditApplicationsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *EditApplicationsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *EditApplicationsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *EditApplicationsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EditApplicationsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EditApplicationsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EditApplicationsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *EditApplicationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditApplicationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditApplicationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditApplicationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPermissions

`func (o *EditApplicationsRequest) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *EditApplicationsRequest) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *EditApplicationsRequest) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *EditApplicationsRequest) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetNotifications

`func (o *EditApplicationsRequest) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *EditApplicationsRequest) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *EditApplicationsRequest) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *EditApplicationsRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


