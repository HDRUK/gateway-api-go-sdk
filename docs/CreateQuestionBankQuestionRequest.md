# CreateQuestionBankQuestionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SectionId** | **int32** |  | 
**UserId** | Pointer to **int32** |  | [optional] 
**TeamIds** | Pointer to **[]int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**Required** | Pointer to **bool** |  | [optional] 
**ForceRequired** | **bool** |  | 
**AllowGuidanceOverride** | **bool** |  | 
**Default** | Pointer to **bool** |  | [optional] 
**Guidance** | **string** |  | 
**Title** | **string** |  | 
**Field** | **[]map[string]interface{}** |  | 
**Component** | **string** |  | 
**Validations** | **[]map[string]interface{}** |  | 
**Options** | [**[]CreateQuestionBankQuestionRequestOptionsInner**](CreateQuestionBankQuestionRequestOptionsInner.md) |  | 
**IsChild** | Pointer to **bool** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateQuestionBankQuestionRequest

`func NewCreateQuestionBankQuestionRequest(sectionId int32, forceRequired bool, allowGuidanceOverride bool, guidance string, title string, field []map[string]interface{}, component string, validations []map[string]interface{}, options []CreateQuestionBankQuestionRequestOptionsInner, ) *CreateQuestionBankQuestionRequest`

NewCreateQuestionBankQuestionRequest instantiates a new CreateQuestionBankQuestionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateQuestionBankQuestionRequestWithDefaults

`func NewCreateQuestionBankQuestionRequestWithDefaults() *CreateQuestionBankQuestionRequest`

NewCreateQuestionBankQuestionRequestWithDefaults instantiates a new CreateQuestionBankQuestionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSectionId

`func (o *CreateQuestionBankQuestionRequest) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *CreateQuestionBankQuestionRequest) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *CreateQuestionBankQuestionRequest) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.


### GetUserId

`func (o *CreateQuestionBankQuestionRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateQuestionBankQuestionRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateQuestionBankQuestionRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateQuestionBankQuestionRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamIds

`func (o *CreateQuestionBankQuestionRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *CreateQuestionBankQuestionRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *CreateQuestionBankQuestionRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.

### HasTeamIds

`func (o *CreateQuestionBankQuestionRequest) HasTeamIds() bool`

HasTeamIds returns a boolean if a field has been set.

### GetLocked

`func (o *CreateQuestionBankQuestionRequest) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *CreateQuestionBankQuestionRequest) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *CreateQuestionBankQuestionRequest) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *CreateQuestionBankQuestionRequest) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *CreateQuestionBankQuestionRequest) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *CreateQuestionBankQuestionRequest) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *CreateQuestionBankQuestionRequest) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *CreateQuestionBankQuestionRequest) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetRequired

`func (o *CreateQuestionBankQuestionRequest) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *CreateQuestionBankQuestionRequest) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *CreateQuestionBankQuestionRequest) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *CreateQuestionBankQuestionRequest) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetForceRequired

`func (o *CreateQuestionBankQuestionRequest) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *CreateQuestionBankQuestionRequest) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *CreateQuestionBankQuestionRequest) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.


### GetAllowGuidanceOverride

`func (o *CreateQuestionBankQuestionRequest) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *CreateQuestionBankQuestionRequest) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *CreateQuestionBankQuestionRequest) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.


### GetDefault

`func (o *CreateQuestionBankQuestionRequest) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *CreateQuestionBankQuestionRequest) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *CreateQuestionBankQuestionRequest) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *CreateQuestionBankQuestionRequest) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetGuidance

`func (o *CreateQuestionBankQuestionRequest) GetGuidance() string`

GetGuidance returns the Guidance field if non-nil, zero value otherwise.

### GetGuidanceOk

`func (o *CreateQuestionBankQuestionRequest) GetGuidanceOk() (*string, bool)`

GetGuidanceOk returns a tuple with the Guidance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidance

`func (o *CreateQuestionBankQuestionRequest) SetGuidance(v string)`

SetGuidance sets Guidance field to given value.


### GetTitle

`func (o *CreateQuestionBankQuestionRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateQuestionBankQuestionRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateQuestionBankQuestionRequest) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetField

`func (o *CreateQuestionBankQuestionRequest) GetField() []map[string]interface{}`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *CreateQuestionBankQuestionRequest) GetFieldOk() (*[]map[string]interface{}, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *CreateQuestionBankQuestionRequest) SetField(v []map[string]interface{})`

SetField sets Field field to given value.


### GetComponent

`func (o *CreateQuestionBankQuestionRequest) GetComponent() string`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *CreateQuestionBankQuestionRequest) GetComponentOk() (*string, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *CreateQuestionBankQuestionRequest) SetComponent(v string)`

SetComponent sets Component field to given value.


### GetValidations

`func (o *CreateQuestionBankQuestionRequest) GetValidations() []map[string]interface{}`

GetValidations returns the Validations field if non-nil, zero value otherwise.

### GetValidationsOk

`func (o *CreateQuestionBankQuestionRequest) GetValidationsOk() (*[]map[string]interface{}, bool)`

GetValidationsOk returns a tuple with the Validations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidations

`func (o *CreateQuestionBankQuestionRequest) SetValidations(v []map[string]interface{})`

SetValidations sets Validations field to given value.


### GetOptions

`func (o *CreateQuestionBankQuestionRequest) GetOptions() []CreateQuestionBankQuestionRequestOptionsInner`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *CreateQuestionBankQuestionRequest) GetOptionsOk() (*[]CreateQuestionBankQuestionRequestOptionsInner, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *CreateQuestionBankQuestionRequest) SetOptions(v []CreateQuestionBankQuestionRequestOptionsInner)`

SetOptions sets Options field to given value.


### GetIsChild

`func (o *CreateQuestionBankQuestionRequest) GetIsChild() bool`

GetIsChild returns the IsChild field if non-nil, zero value otherwise.

### GetIsChildOk

`func (o *CreateQuestionBankQuestionRequest) GetIsChildOk() (*bool, bool)`

GetIsChildOk returns a tuple with the IsChild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChild

`func (o *CreateQuestionBankQuestionRequest) SetIsChild(v bool)`

SetIsChild sets IsChild field to given value.

### HasIsChild

`func (o *CreateQuestionBankQuestionRequest) HasIsChild() bool`

HasIsChild returns a boolean if a field has been set.

### GetQuestionType

`func (o *CreateQuestionBankQuestionRequest) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *CreateQuestionBankQuestionRequest) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *CreateQuestionBankQuestionRequest) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *CreateQuestionBankQuestionRequest) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


