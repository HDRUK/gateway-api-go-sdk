# FetchAllApplications200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**ClientId** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **bool** |  | [optional] 
**Permissions** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**User** | Pointer to **[]interface{}** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewFetchAllApplications200ResponseDataInner

`func NewFetchAllApplications200ResponseDataInner() *FetchAllApplications200ResponseDataInner`

NewFetchAllApplications200ResponseDataInner instantiates a new FetchAllApplications200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllApplications200ResponseDataInnerWithDefaults

`func NewFetchAllApplications200ResponseDataInnerWithDefaults() *FetchAllApplications200ResponseDataInner`

NewFetchAllApplications200ResponseDataInnerWithDefaults instantiates a new FetchAllApplications200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchAllApplications200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchAllApplications200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchAllApplications200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchAllApplications200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *FetchAllApplications200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FetchAllApplications200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FetchAllApplications200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FetchAllApplications200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAppId

`func (o *FetchAllApplications200ResponseDataInner) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *FetchAllApplications200ResponseDataInner) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *FetchAllApplications200ResponseDataInner) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *FetchAllApplications200ResponseDataInner) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetClientId

`func (o *FetchAllApplications200ResponseDataInner) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *FetchAllApplications200ResponseDataInner) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *FetchAllApplications200ResponseDataInner) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *FetchAllApplications200ResponseDataInner) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### GetImageLink

`func (o *FetchAllApplications200ResponseDataInner) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *FetchAllApplications200ResponseDataInner) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *FetchAllApplications200ResponseDataInner) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *FetchAllApplications200ResponseDataInner) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetDescription

`func (o *FetchAllApplications200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FetchAllApplications200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FetchAllApplications200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FetchAllApplications200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTeamId

`func (o *FetchAllApplications200ResponseDataInner) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *FetchAllApplications200ResponseDataInner) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *FetchAllApplications200ResponseDataInner) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *FetchAllApplications200ResponseDataInner) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *FetchAllApplications200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *FetchAllApplications200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *FetchAllApplications200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *FetchAllApplications200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetStatus

`func (o *FetchAllApplications200ResponseDataInner) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FetchAllApplications200ResponseDataInner) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FetchAllApplications200ResponseDataInner) SetStatus(v bool)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *FetchAllApplications200ResponseDataInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPermissions

`func (o *FetchAllApplications200ResponseDataInner) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *FetchAllApplications200ResponseDataInner) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *FetchAllApplications200ResponseDataInner) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *FetchAllApplications200ResponseDataInner) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetTeam

`func (o *FetchAllApplications200ResponseDataInner) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *FetchAllApplications200ResponseDataInner) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *FetchAllApplications200ResponseDataInner) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *FetchAllApplications200ResponseDataInner) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetUser

`func (o *FetchAllApplications200ResponseDataInner) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *FetchAllApplications200ResponseDataInner) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *FetchAllApplications200ResponseDataInner) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *FetchAllApplications200ResponseDataInner) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetNotifications

`func (o *FetchAllApplications200ResponseDataInner) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *FetchAllApplications200ResponseDataInner) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *FetchAllApplications200ResponseDataInner) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *FetchAllApplications200ResponseDataInner) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchAllApplications200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchAllApplications200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchAllApplications200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchAllApplications200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchAllApplications200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchAllApplications200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchAllApplications200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchAllApplications200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchAllApplications200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchAllApplications200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchAllApplications200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchAllApplications200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


