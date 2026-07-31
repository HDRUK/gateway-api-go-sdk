# EditQuestionBankQuestionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SectionId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**TeamIds** | Pointer to **[]int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**ForceRequired** | Pointer to **bool** |  | [optional] 
**AllowGuidanceOverride** | Pointer to **bool** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 
**Default** | Pointer to **bool** |  | [optional] 
**Guidance** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Field** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewEditQuestionBankQuestionRequest

`func NewEditQuestionBankQuestionRequest() *EditQuestionBankQuestionRequest`

NewEditQuestionBankQuestionRequest instantiates a new EditQuestionBankQuestionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditQuestionBankQuestionRequestWithDefaults

`func NewEditQuestionBankQuestionRequestWithDefaults() *EditQuestionBankQuestionRequest`

NewEditQuestionBankQuestionRequestWithDefaults instantiates a new EditQuestionBankQuestionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSectionId

`func (o *EditQuestionBankQuestionRequest) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *EditQuestionBankQuestionRequest) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *EditQuestionBankQuestionRequest) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.

### HasSectionId

`func (o *EditQuestionBankQuestionRequest) HasSectionId() bool`

HasSectionId returns a boolean if a field has been set.

### GetUserId

`func (o *EditQuestionBankQuestionRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EditQuestionBankQuestionRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EditQuestionBankQuestionRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EditQuestionBankQuestionRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamIds

`func (o *EditQuestionBankQuestionRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *EditQuestionBankQuestionRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *EditQuestionBankQuestionRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.

### HasTeamIds

`func (o *EditQuestionBankQuestionRequest) HasTeamIds() bool`

HasTeamIds returns a boolean if a field has been set.

### GetLocked

`func (o *EditQuestionBankQuestionRequest) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *EditQuestionBankQuestionRequest) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *EditQuestionBankQuestionRequest) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *EditQuestionBankQuestionRequest) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *EditQuestionBankQuestionRequest) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *EditQuestionBankQuestionRequest) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *EditQuestionBankQuestionRequest) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *EditQuestionBankQuestionRequest) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetForceRequired

`func (o *EditQuestionBankQuestionRequest) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *EditQuestionBankQuestionRequest) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *EditQuestionBankQuestionRequest) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.

### HasForceRequired

`func (o *EditQuestionBankQuestionRequest) HasForceRequired() bool`

HasForceRequired returns a boolean if a field has been set.

### GetAllowGuidanceOverride

`func (o *EditQuestionBankQuestionRequest) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *EditQuestionBankQuestionRequest) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *EditQuestionBankQuestionRequest) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.

### HasAllowGuidanceOverride

`func (o *EditQuestionBankQuestionRequest) HasAllowGuidanceOverride() bool`

HasAllowGuidanceOverride returns a boolean if a field has been set.

### GetQuestionType

`func (o *EditQuestionBankQuestionRequest) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *EditQuestionBankQuestionRequest) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *EditQuestionBankQuestionRequest) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *EditQuestionBankQuestionRequest) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.

### GetDefault

`func (o *EditQuestionBankQuestionRequest) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *EditQuestionBankQuestionRequest) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *EditQuestionBankQuestionRequest) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *EditQuestionBankQuestionRequest) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetGuidance

`func (o *EditQuestionBankQuestionRequest) GetGuidance() string`

GetGuidance returns the Guidance field if non-nil, zero value otherwise.

### GetGuidanceOk

`func (o *EditQuestionBankQuestionRequest) GetGuidanceOk() (*string, bool)`

GetGuidanceOk returns a tuple with the Guidance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidance

`func (o *EditQuestionBankQuestionRequest) SetGuidance(v string)`

SetGuidance sets Guidance field to given value.

### HasGuidance

`func (o *EditQuestionBankQuestionRequest) HasGuidance() bool`

HasGuidance returns a boolean if a field has been set.

### GetTitle

`func (o *EditQuestionBankQuestionRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *EditQuestionBankQuestionRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *EditQuestionBankQuestionRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *EditQuestionBankQuestionRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetField

`func (o *EditQuestionBankQuestionRequest) GetField() []map[string]interface{}`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *EditQuestionBankQuestionRequest) GetFieldOk() (*[]map[string]interface{}, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *EditQuestionBankQuestionRequest) SetField(v []map[string]interface{})`

SetField sets Field field to given value.

### HasField

`func (o *EditQuestionBankQuestionRequest) HasField() bool`

HasField returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


