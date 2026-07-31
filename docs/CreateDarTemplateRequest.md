# CreateDarTemplateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TeamId** | **int32** |  | 
**UserId** | Pointer to **int32** |  | [optional] 
**Published** | Pointer to **bool** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Questions** | Pointer to [**[]CreateDarTemplateRequestQuestionsInner**](CreateDarTemplateRequestQuestionsInner.md) |  | [optional] 

## Methods

### NewCreateDarTemplateRequest

`func NewCreateDarTemplateRequest(teamId int32, ) *CreateDarTemplateRequest`

NewCreateDarTemplateRequest instantiates a new CreateDarTemplateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDarTemplateRequestWithDefaults

`func NewCreateDarTemplateRequestWithDefaults() *CreateDarTemplateRequest`

NewCreateDarTemplateRequestWithDefaults instantiates a new CreateDarTemplateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTeamId

`func (o *CreateDarTemplateRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateDarTemplateRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateDarTemplateRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.


### GetUserId

`func (o *CreateDarTemplateRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateDarTemplateRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateDarTemplateRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateDarTemplateRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetPublished

`func (o *CreateDarTemplateRequest) GetPublished() bool`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *CreateDarTemplateRequest) GetPublishedOk() (*bool, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *CreateDarTemplateRequest) SetPublished(v bool)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *CreateDarTemplateRequest) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetLocked

`func (o *CreateDarTemplateRequest) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *CreateDarTemplateRequest) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *CreateDarTemplateRequest) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *CreateDarTemplateRequest) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetQuestions

`func (o *CreateDarTemplateRequest) GetQuestions() []CreateDarTemplateRequestQuestionsInner`

GetQuestions returns the Questions field if non-nil, zero value otherwise.

### GetQuestionsOk

`func (o *CreateDarTemplateRequest) GetQuestionsOk() (*[]CreateDarTemplateRequestQuestionsInner, bool)`

GetQuestionsOk returns a tuple with the Questions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestions

`func (o *CreateDarTemplateRequest) SetQuestions(v []CreateDarTemplateRequestQuestionsInner)`

SetQuestions sets Questions field to given value.

### HasQuestions

`func (o *CreateDarTemplateRequest) HasQuestions() bool`

HasQuestions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


