# UpdateDarTemplateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TeamId** | **int32** |  | 
**UserId** | Pointer to **int32** |  | [optional] 
**Published** | Pointer to **bool** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateDarTemplateRequest

`func NewUpdateDarTemplateRequest(teamId int32, ) *UpdateDarTemplateRequest`

NewUpdateDarTemplateRequest instantiates a new UpdateDarTemplateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDarTemplateRequestWithDefaults

`func NewUpdateDarTemplateRequestWithDefaults() *UpdateDarTemplateRequest`

NewUpdateDarTemplateRequestWithDefaults instantiates a new UpdateDarTemplateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTeamId

`func (o *UpdateDarTemplateRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *UpdateDarTemplateRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *UpdateDarTemplateRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.


### GetUserId

`func (o *UpdateDarTemplateRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateDarTemplateRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateDarTemplateRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UpdateDarTemplateRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetPublished

`func (o *UpdateDarTemplateRequest) GetPublished() bool`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *UpdateDarTemplateRequest) GetPublishedOk() (*bool, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *UpdateDarTemplateRequest) SetPublished(v bool)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *UpdateDarTemplateRequest) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetLocked

`func (o *UpdateDarTemplateRequest) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *UpdateDarTemplateRequest) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *UpdateDarTemplateRequest) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *UpdateDarTemplateRequest) HasLocked() bool`

HasLocked returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


