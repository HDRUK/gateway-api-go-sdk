# CreateApplications200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**ClientId** | Pointer to **string** |  | [optional] 
**ClientSecret** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Permissions** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**User** | Pointer to **[]interface{}** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCreateApplications200ResponseDataInner

`func NewCreateApplications200ResponseDataInner() *CreateApplications200ResponseDataInner`

NewCreateApplications200ResponseDataInner instantiates a new CreateApplications200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApplications200ResponseDataInnerWithDefaults

`func NewCreateApplications200ResponseDataInnerWithDefaults() *CreateApplications200ResponseDataInner`

NewCreateApplications200ResponseDataInnerWithDefaults instantiates a new CreateApplications200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateApplications200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateApplications200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateApplications200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CreateApplications200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *CreateApplications200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApplications200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApplications200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateApplications200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAppId

`func (o *CreateApplications200ResponseDataInner) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateApplications200ResponseDataInner) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateApplications200ResponseDataInner) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateApplications200ResponseDataInner) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetClientId

`func (o *CreateApplications200ResponseDataInner) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *CreateApplications200ResponseDataInner) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *CreateApplications200ResponseDataInner) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *CreateApplications200ResponseDataInner) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### GetClientSecret

`func (o *CreateApplications200ResponseDataInner) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *CreateApplications200ResponseDataInner) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *CreateApplications200ResponseDataInner) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.

### HasClientSecret

`func (o *CreateApplications200ResponseDataInner) HasClientSecret() bool`

HasClientSecret returns a boolean if a field has been set.

### GetImageLink

`func (o *CreateApplications200ResponseDataInner) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *CreateApplications200ResponseDataInner) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *CreateApplications200ResponseDataInner) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *CreateApplications200ResponseDataInner) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetDescription

`func (o *CreateApplications200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateApplications200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateApplications200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateApplications200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTeamId

`func (o *CreateApplications200ResponseDataInner) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateApplications200ResponseDataInner) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateApplications200ResponseDataInner) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *CreateApplications200ResponseDataInner) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateApplications200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateApplications200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateApplications200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateApplications200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateApplications200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateApplications200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateApplications200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateApplications200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPermissions

`func (o *CreateApplications200ResponseDataInner) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateApplications200ResponseDataInner) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateApplications200ResponseDataInner) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *CreateApplications200ResponseDataInner) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetTeam

`func (o *CreateApplications200ResponseDataInner) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *CreateApplications200ResponseDataInner) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *CreateApplications200ResponseDataInner) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *CreateApplications200ResponseDataInner) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetUser

`func (o *CreateApplications200ResponseDataInner) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CreateApplications200ResponseDataInner) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CreateApplications200ResponseDataInner) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *CreateApplications200ResponseDataInner) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetNotifications

`func (o *CreateApplications200ResponseDataInner) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *CreateApplications200ResponseDataInner) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *CreateApplications200ResponseDataInner) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *CreateApplications200ResponseDataInner) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CreateApplications200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateApplications200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateApplications200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateApplications200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateApplications200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateApplications200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateApplications200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateApplications200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *CreateApplications200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *CreateApplications200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *CreateApplications200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *CreateApplications200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


