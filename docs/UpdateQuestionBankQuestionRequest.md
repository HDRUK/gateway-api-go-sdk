# UpdateQuestionBankQuestionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SectionId** | **int32** |  | 
**UserId** | Pointer to **int32** |  | [optional] 
**TeamIds** | Pointer to **[]int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**IsChild** | Pointer to **bool** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 
**Required** | Pointer to **bool** |  | [optional] 
**ForceRequired** | **bool** |  | 
**AllowGuidanceOverride** | **bool** |  | 
**Default** | Pointer to **bool** |  | [optional] 
**Guidance** | **string** |  | 
**Title** | **string** |  | 
**Field** | **[]map[string]interface{}** |  | 

## Methods

### NewUpdateQuestionBankQuestionRequest

`func NewUpdateQuestionBankQuestionRequest(sectionId int32, forceRequired bool, allowGuidanceOverride bool, guidance string, title string, field []map[string]interface{}, ) *UpdateQuestionBankQuestionRequest`

NewUpdateQuestionBankQuestionRequest instantiates a new UpdateQuestionBankQuestionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateQuestionBankQuestionRequestWithDefaults

`func NewUpdateQuestionBankQuestionRequestWithDefaults() *UpdateQuestionBankQuestionRequest`

NewUpdateQuestionBankQuestionRequestWithDefaults instantiates a new UpdateQuestionBankQuestionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSectionId

`func (o *UpdateQuestionBankQuestionRequest) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *UpdateQuestionBankQuestionRequest) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *UpdateQuestionBankQuestionRequest) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.


### GetUserId

`func (o *UpdateQuestionBankQuestionRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateQuestionBankQuestionRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateQuestionBankQuestionRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UpdateQuestionBankQuestionRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamIds

`func (o *UpdateQuestionBankQuestionRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *UpdateQuestionBankQuestionRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *UpdateQuestionBankQuestionRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.

### HasTeamIds

`func (o *UpdateQuestionBankQuestionRequest) HasTeamIds() bool`

HasTeamIds returns a boolean if a field has been set.

### GetLocked

`func (o *UpdateQuestionBankQuestionRequest) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *UpdateQuestionBankQuestionRequest) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *UpdateQuestionBankQuestionRequest) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *UpdateQuestionBankQuestionRequest) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *UpdateQuestionBankQuestionRequest) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *UpdateQuestionBankQuestionRequest) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *UpdateQuestionBankQuestionRequest) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *UpdateQuestionBankQuestionRequest) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetIsChild

`func (o *UpdateQuestionBankQuestionRequest) GetIsChild() bool`

GetIsChild returns the IsChild field if non-nil, zero value otherwise.

### GetIsChildOk

`func (o *UpdateQuestionBankQuestionRequest) GetIsChildOk() (*bool, bool)`

GetIsChildOk returns a tuple with the IsChild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChild

`func (o *UpdateQuestionBankQuestionRequest) SetIsChild(v bool)`

SetIsChild sets IsChild field to given value.

### HasIsChild

`func (o *UpdateQuestionBankQuestionRequest) HasIsChild() bool`

HasIsChild returns a boolean if a field has been set.

### GetQuestionType

`func (o *UpdateQuestionBankQuestionRequest) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *UpdateQuestionBankQuestionRequest) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *UpdateQuestionBankQuestionRequest) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *UpdateQuestionBankQuestionRequest) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.

### GetRequired

`func (o *UpdateQuestionBankQuestionRequest) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *UpdateQuestionBankQuestionRequest) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *UpdateQuestionBankQuestionRequest) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *UpdateQuestionBankQuestionRequest) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetForceRequired

`func (o *UpdateQuestionBankQuestionRequest) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *UpdateQuestionBankQuestionRequest) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *UpdateQuestionBankQuestionRequest) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.


### GetAllowGuidanceOverride

`func (o *UpdateQuestionBankQuestionRequest) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *UpdateQuestionBankQuestionRequest) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *UpdateQuestionBankQuestionRequest) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.


### GetDefault

`func (o *UpdateQuestionBankQuestionRequest) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *UpdateQuestionBankQuestionRequest) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *UpdateQuestionBankQuestionRequest) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *UpdateQuestionBankQuestionRequest) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetGuidance

`func (o *UpdateQuestionBankQuestionRequest) GetGuidance() string`

GetGuidance returns the Guidance field if non-nil, zero value otherwise.

### GetGuidanceOk

`func (o *UpdateQuestionBankQuestionRequest) GetGuidanceOk() (*string, bool)`

GetGuidanceOk returns a tuple with the Guidance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidance

`func (o *UpdateQuestionBankQuestionRequest) SetGuidance(v string)`

SetGuidance sets Guidance field to given value.


### GetTitle

`func (o *UpdateQuestionBankQuestionRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpdateQuestionBankQuestionRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpdateQuestionBankQuestionRequest) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetField

`func (o *UpdateQuestionBankQuestionRequest) GetField() []map[string]interface{}`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UpdateQuestionBankQuestionRequest) GetFieldOk() (*[]map[string]interface{}, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UpdateQuestionBankQuestionRequest) SetField(v []map[string]interface{})`

SetField sets Field field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


