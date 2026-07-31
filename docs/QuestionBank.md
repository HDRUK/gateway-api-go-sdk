# QuestionBank

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**SectionId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**ArchivedDate** | Pointer to **NullableTime** |  | [optional] 
**ForceRequired** | Pointer to **bool** |  | [optional] 
**AllowGuidanceOverride** | Pointer to **bool** |  | [optional] 
**IsChild** | Pointer to **bool** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewQuestionBank

`func NewQuestionBank() *QuestionBank`

NewQuestionBank instantiates a new QuestionBank object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuestionBankWithDefaults

`func NewQuestionBankWithDefaults() *QuestionBank`

NewQuestionBankWithDefaults instantiates a new QuestionBank object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *QuestionBank) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QuestionBank) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QuestionBank) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *QuestionBank) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSectionId

`func (o *QuestionBank) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *QuestionBank) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *QuestionBank) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.

### HasSectionId

`func (o *QuestionBank) HasSectionId() bool`

HasSectionId returns a boolean if a field has been set.

### GetUserId

`func (o *QuestionBank) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *QuestionBank) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *QuestionBank) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *QuestionBank) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetLocked

`func (o *QuestionBank) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *QuestionBank) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *QuestionBank) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *QuestionBank) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *QuestionBank) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *QuestionBank) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *QuestionBank) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *QuestionBank) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetArchivedDate

`func (o *QuestionBank) GetArchivedDate() time.Time`

GetArchivedDate returns the ArchivedDate field if non-nil, zero value otherwise.

### GetArchivedDateOk

`func (o *QuestionBank) GetArchivedDateOk() (*time.Time, bool)`

GetArchivedDateOk returns a tuple with the ArchivedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedDate

`func (o *QuestionBank) SetArchivedDate(v time.Time)`

SetArchivedDate sets ArchivedDate field to given value.

### HasArchivedDate

`func (o *QuestionBank) HasArchivedDate() bool`

HasArchivedDate returns a boolean if a field has been set.

### SetArchivedDateNil

`func (o *QuestionBank) SetArchivedDateNil(b bool)`

 SetArchivedDateNil sets the value for ArchivedDate to be an explicit nil

### UnsetArchivedDate
`func (o *QuestionBank) UnsetArchivedDate()`

UnsetArchivedDate ensures that no value is present for ArchivedDate, not even an explicit nil
### GetForceRequired

`func (o *QuestionBank) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *QuestionBank) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *QuestionBank) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.

### HasForceRequired

`func (o *QuestionBank) HasForceRequired() bool`

HasForceRequired returns a boolean if a field has been set.

### GetAllowGuidanceOverride

`func (o *QuestionBank) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *QuestionBank) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *QuestionBank) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.

### HasAllowGuidanceOverride

`func (o *QuestionBank) HasAllowGuidanceOverride() bool`

HasAllowGuidanceOverride returns a boolean if a field has been set.

### GetIsChild

`func (o *QuestionBank) GetIsChild() bool`

GetIsChild returns the IsChild field if non-nil, zero value otherwise.

### GetIsChildOk

`func (o *QuestionBank) GetIsChildOk() (*bool, bool)`

GetIsChildOk returns a tuple with the IsChild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChild

`func (o *QuestionBank) SetIsChild(v bool)`

SetIsChild sets IsChild field to given value.

### HasIsChild

`func (o *QuestionBank) HasIsChild() bool`

HasIsChild returns a boolean if a field has been set.

### GetQuestionType

`func (o *QuestionBank) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *QuestionBank) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *QuestionBank) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *QuestionBank) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.

### GetCreatedAt

`func (o *QuestionBank) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *QuestionBank) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *QuestionBank) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *QuestionBank) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *QuestionBank) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *QuestionBank) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *QuestionBank) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *QuestionBank) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


