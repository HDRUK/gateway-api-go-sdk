# FetchTeamQuestionBankQuestionsBySection200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**SectionId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**ArchivedDate** | Pointer to **time.Time** |  | [optional] 
**ForceRequired** | Pointer to **bool** |  | [optional] 
**AllowGuidanceOverride** | Pointer to **bool** |  | [optional] 
**IsChild** | Pointer to **bool** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 
**LatestVersion** | Pointer to **map[string]interface{}** |  | [optional] 
**Versions** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInner

`func NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInner() *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner`

NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInner instantiates a new FetchTeamQuestionBankQuestionsBySection200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInnerWithDefaults

`func NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInnerWithDefaults() *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner`

NewFetchTeamQuestionBankQuestionsBySection200ResponseDataInnerWithDefaults instantiates a new FetchTeamQuestionBankQuestionsBySection200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetSectionId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.

### HasSectionId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasSectionId() bool`

HasSectionId returns a boolean if a field has been set.

### GetUserId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetLocked

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetArchivedDate

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetArchivedDate() time.Time`

GetArchivedDate returns the ArchivedDate field if non-nil, zero value otherwise.

### GetArchivedDateOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetArchivedDateOk() (*time.Time, bool)`

GetArchivedDateOk returns a tuple with the ArchivedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedDate

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetArchivedDate(v time.Time)`

SetArchivedDate sets ArchivedDate field to given value.

### HasArchivedDate

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasArchivedDate() bool`

HasArchivedDate returns a boolean if a field has been set.

### GetForceRequired

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.

### HasForceRequired

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasForceRequired() bool`

HasForceRequired returns a boolean if a field has been set.

### GetAllowGuidanceOverride

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.

### HasAllowGuidanceOverride

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasAllowGuidanceOverride() bool`

HasAllowGuidanceOverride returns a boolean if a field has been set.

### GetIsChild

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetIsChild() bool`

GetIsChild returns the IsChild field if non-nil, zero value otherwise.

### GetIsChildOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetIsChildOk() (*bool, bool)`

GetIsChildOk returns a tuple with the IsChild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChild

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetIsChild(v bool)`

SetIsChild sets IsChild field to given value.

### HasIsChild

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasIsChild() bool`

HasIsChild returns a boolean if a field has been set.

### GetQuestionType

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.

### GetLatestVersion

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetLatestVersion() map[string]interface{}`

GetLatestVersion returns the LatestVersion field if non-nil, zero value otherwise.

### GetLatestVersionOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetLatestVersionOk() (*map[string]interface{}, bool)`

GetLatestVersionOk returns a tuple with the LatestVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestVersion

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetLatestVersion(v map[string]interface{})`

SetLatestVersion sets LatestVersion field to given value.

### HasLatestVersion

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasLatestVersion() bool`

HasLatestVersion returns a boolean if a field has been set.

### GetVersions

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetVersions() map[string]interface{}`

GetVersions returns the Versions field if non-nil, zero value otherwise.

### GetVersionsOk

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) GetVersionsOk() (*map[string]interface{}, bool)`

GetVersionsOk returns a tuple with the Versions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersions

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) SetVersions(v map[string]interface{})`

SetVersions sets Versions field to given value.

### HasVersions

`func (o *FetchTeamQuestionBankQuestionsBySection200ResponseDataInner) HasVersions() bool`

HasVersions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


