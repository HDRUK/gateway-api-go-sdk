# FetchApplications200ResponseDataInner

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
**Enabled** | Pointer to **bool** |  | [optional] 
**Permissions** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**User** | Pointer to **[]interface{}** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewFetchApplications200ResponseDataInner

`func NewFetchApplications200ResponseDataInner() *FetchApplications200ResponseDataInner`

NewFetchApplications200ResponseDataInner instantiates a new FetchApplications200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchApplications200ResponseDataInnerWithDefaults

`func NewFetchApplications200ResponseDataInnerWithDefaults() *FetchApplications200ResponseDataInner`

NewFetchApplications200ResponseDataInnerWithDefaults instantiates a new FetchApplications200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchApplications200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchApplications200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchApplications200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchApplications200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *FetchApplications200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FetchApplications200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FetchApplications200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FetchApplications200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAppId

`func (o *FetchApplications200ResponseDataInner) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *FetchApplications200ResponseDataInner) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *FetchApplications200ResponseDataInner) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *FetchApplications200ResponseDataInner) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetClientId

`func (o *FetchApplications200ResponseDataInner) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *FetchApplications200ResponseDataInner) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *FetchApplications200ResponseDataInner) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *FetchApplications200ResponseDataInner) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### GetImageLink

`func (o *FetchApplications200ResponseDataInner) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *FetchApplications200ResponseDataInner) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *FetchApplications200ResponseDataInner) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *FetchApplications200ResponseDataInner) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetDescription

`func (o *FetchApplications200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FetchApplications200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FetchApplications200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FetchApplications200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTeamId

`func (o *FetchApplications200ResponseDataInner) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *FetchApplications200ResponseDataInner) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *FetchApplications200ResponseDataInner) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *FetchApplications200ResponseDataInner) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *FetchApplications200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *FetchApplications200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *FetchApplications200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *FetchApplications200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *FetchApplications200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FetchApplications200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FetchApplications200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *FetchApplications200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPermissions

`func (o *FetchApplications200ResponseDataInner) GetPermissions() []interface{}`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *FetchApplications200ResponseDataInner) GetPermissionsOk() (*[]interface{}, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *FetchApplications200ResponseDataInner) SetPermissions(v []interface{})`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *FetchApplications200ResponseDataInner) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetTeam

`func (o *FetchApplications200ResponseDataInner) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *FetchApplications200ResponseDataInner) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *FetchApplications200ResponseDataInner) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *FetchApplications200ResponseDataInner) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetUser

`func (o *FetchApplications200ResponseDataInner) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *FetchApplications200ResponseDataInner) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *FetchApplications200ResponseDataInner) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *FetchApplications200ResponseDataInner) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchApplications200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchApplications200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchApplications200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchApplications200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchApplications200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchApplications200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchApplications200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchApplications200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchApplications200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchApplications200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchApplications200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchApplications200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


