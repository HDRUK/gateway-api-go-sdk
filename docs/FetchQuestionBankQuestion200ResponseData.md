# FetchQuestionBankQuestion200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**QuestionId** | Pointer to **int32** |  | [optional] 
**Version** | Pointer to **int32** |  | [optional] 
**Default** | Pointer to **bool** |  | [optional] 
**Required** | Pointer to **bool** |  | [optional] 
**SectionId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Locked** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**ArchivedDate** | Pointer to **time.Time** |  | [optional] 
**ForceRequired** | Pointer to **bool** |  | [optional] 
**AllowGuidanceOverride** | Pointer to **bool** |  | [optional] 
**IsChild** | Pointer to **int32** |  | [optional] 
**QuestionType** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Guidance** | Pointer to **string** |  | [optional] 
**Options** | Pointer to **[]interface{}** |  | [optional] 
**Component** | Pointer to **string** |  | [optional] 
**Validations** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewFetchQuestionBankQuestion200ResponseData

`func NewFetchQuestionBankQuestion200ResponseData() *FetchQuestionBankQuestion200ResponseData`

NewFetchQuestionBankQuestion200ResponseData instantiates a new FetchQuestionBankQuestion200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchQuestionBankQuestion200ResponseDataWithDefaults

`func NewFetchQuestionBankQuestion200ResponseDataWithDefaults() *FetchQuestionBankQuestion200ResponseData`

NewFetchQuestionBankQuestion200ResponseDataWithDefaults instantiates a new FetchQuestionBankQuestion200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchQuestionBankQuestion200ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchQuestionBankQuestion200ResponseData) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchQuestionBankQuestion200ResponseData) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchQuestionBankQuestion200ResponseData) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetQuestionId

`func (o *FetchQuestionBankQuestion200ResponseData) GetQuestionId() int32`

GetQuestionId returns the QuestionId field if non-nil, zero value otherwise.

### GetQuestionIdOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetQuestionIdOk() (*int32, bool)`

GetQuestionIdOk returns a tuple with the QuestionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionId

`func (o *FetchQuestionBankQuestion200ResponseData) SetQuestionId(v int32)`

SetQuestionId sets QuestionId field to given value.

### HasQuestionId

`func (o *FetchQuestionBankQuestion200ResponseData) HasQuestionId() bool`

HasQuestionId returns a boolean if a field has been set.

### GetVersion

`func (o *FetchQuestionBankQuestion200ResponseData) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *FetchQuestionBankQuestion200ResponseData) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *FetchQuestionBankQuestion200ResponseData) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetDefault

`func (o *FetchQuestionBankQuestion200ResponseData) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *FetchQuestionBankQuestion200ResponseData) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *FetchQuestionBankQuestion200ResponseData) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetRequired

`func (o *FetchQuestionBankQuestion200ResponseData) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *FetchQuestionBankQuestion200ResponseData) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *FetchQuestionBankQuestion200ResponseData) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetSectionId

`func (o *FetchQuestionBankQuestion200ResponseData) GetSectionId() int32`

GetSectionId returns the SectionId field if non-nil, zero value otherwise.

### GetSectionIdOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetSectionIdOk() (*int32, bool)`

GetSectionIdOk returns a tuple with the SectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectionId

`func (o *FetchQuestionBankQuestion200ResponseData) SetSectionId(v int32)`

SetSectionId sets SectionId field to given value.

### HasSectionId

`func (o *FetchQuestionBankQuestion200ResponseData) HasSectionId() bool`

HasSectionId returns a boolean if a field has been set.

### GetUserId

`func (o *FetchQuestionBankQuestion200ResponseData) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *FetchQuestionBankQuestion200ResponseData) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *FetchQuestionBankQuestion200ResponseData) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetLocked

`func (o *FetchQuestionBankQuestion200ResponseData) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *FetchQuestionBankQuestion200ResponseData) SetLocked(v bool)`

SetLocked sets Locked field to given value.

### HasLocked

`func (o *FetchQuestionBankQuestion200ResponseData) HasLocked() bool`

HasLocked returns a boolean if a field has been set.

### GetArchived

`func (o *FetchQuestionBankQuestion200ResponseData) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *FetchQuestionBankQuestion200ResponseData) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *FetchQuestionBankQuestion200ResponseData) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetArchivedDate

`func (o *FetchQuestionBankQuestion200ResponseData) GetArchivedDate() time.Time`

GetArchivedDate returns the ArchivedDate field if non-nil, zero value otherwise.

### GetArchivedDateOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetArchivedDateOk() (*time.Time, bool)`

GetArchivedDateOk returns a tuple with the ArchivedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedDate

`func (o *FetchQuestionBankQuestion200ResponseData) SetArchivedDate(v time.Time)`

SetArchivedDate sets ArchivedDate field to given value.

### HasArchivedDate

`func (o *FetchQuestionBankQuestion200ResponseData) HasArchivedDate() bool`

HasArchivedDate returns a boolean if a field has been set.

### GetForceRequired

`func (o *FetchQuestionBankQuestion200ResponseData) GetForceRequired() bool`

GetForceRequired returns the ForceRequired field if non-nil, zero value otherwise.

### GetForceRequiredOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetForceRequiredOk() (*bool, bool)`

GetForceRequiredOk returns a tuple with the ForceRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForceRequired

`func (o *FetchQuestionBankQuestion200ResponseData) SetForceRequired(v bool)`

SetForceRequired sets ForceRequired field to given value.

### HasForceRequired

`func (o *FetchQuestionBankQuestion200ResponseData) HasForceRequired() bool`

HasForceRequired returns a boolean if a field has been set.

### GetAllowGuidanceOverride

`func (o *FetchQuestionBankQuestion200ResponseData) GetAllowGuidanceOverride() bool`

GetAllowGuidanceOverride returns the AllowGuidanceOverride field if non-nil, zero value otherwise.

### GetAllowGuidanceOverrideOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetAllowGuidanceOverrideOk() (*bool, bool)`

GetAllowGuidanceOverrideOk returns a tuple with the AllowGuidanceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowGuidanceOverride

`func (o *FetchQuestionBankQuestion200ResponseData) SetAllowGuidanceOverride(v bool)`

SetAllowGuidanceOverride sets AllowGuidanceOverride field to given value.

### HasAllowGuidanceOverride

`func (o *FetchQuestionBankQuestion200ResponseData) HasAllowGuidanceOverride() bool`

HasAllowGuidanceOverride returns a boolean if a field has been set.

### GetIsChild

`func (o *FetchQuestionBankQuestion200ResponseData) GetIsChild() int32`

GetIsChild returns the IsChild field if non-nil, zero value otherwise.

### GetIsChildOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetIsChildOk() (*int32, bool)`

GetIsChildOk returns a tuple with the IsChild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsChild

`func (o *FetchQuestionBankQuestion200ResponseData) SetIsChild(v int32)`

SetIsChild sets IsChild field to given value.

### HasIsChild

`func (o *FetchQuestionBankQuestion200ResponseData) HasIsChild() bool`

HasIsChild returns a boolean if a field has been set.

### GetQuestionType

`func (o *FetchQuestionBankQuestion200ResponseData) GetQuestionType() string`

GetQuestionType returns the QuestionType field if non-nil, zero value otherwise.

### GetQuestionTypeOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetQuestionTypeOk() (*string, bool)`

GetQuestionTypeOk returns a tuple with the QuestionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionType

`func (o *FetchQuestionBankQuestion200ResponseData) SetQuestionType(v string)`

SetQuestionType sets QuestionType field to given value.

### HasQuestionType

`func (o *FetchQuestionBankQuestion200ResponseData) HasQuestionType() bool`

HasQuestionType returns a boolean if a field has been set.

### GetTitle

`func (o *FetchQuestionBankQuestion200ResponseData) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *FetchQuestionBankQuestion200ResponseData) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *FetchQuestionBankQuestion200ResponseData) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetGuidance

`func (o *FetchQuestionBankQuestion200ResponseData) GetGuidance() string`

GetGuidance returns the Guidance field if non-nil, zero value otherwise.

### GetGuidanceOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetGuidanceOk() (*string, bool)`

GetGuidanceOk returns a tuple with the Guidance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidance

`func (o *FetchQuestionBankQuestion200ResponseData) SetGuidance(v string)`

SetGuidance sets Guidance field to given value.

### HasGuidance

`func (o *FetchQuestionBankQuestion200ResponseData) HasGuidance() bool`

HasGuidance returns a boolean if a field has been set.

### GetOptions

`func (o *FetchQuestionBankQuestion200ResponseData) GetOptions() []interface{}`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetOptionsOk() (*[]interface{}, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *FetchQuestionBankQuestion200ResponseData) SetOptions(v []interface{})`

SetOptions sets Options field to given value.

### HasOptions

`func (o *FetchQuestionBankQuestion200ResponseData) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetComponent

`func (o *FetchQuestionBankQuestion200ResponseData) GetComponent() string`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetComponentOk() (*string, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *FetchQuestionBankQuestion200ResponseData) SetComponent(v string)`

SetComponent sets Component field to given value.

### HasComponent

`func (o *FetchQuestionBankQuestion200ResponseData) HasComponent() bool`

HasComponent returns a boolean if a field has been set.

### GetValidations

`func (o *FetchQuestionBankQuestion200ResponseData) GetValidations() []interface{}`

GetValidations returns the Validations field if non-nil, zero value otherwise.

### GetValidationsOk

`func (o *FetchQuestionBankQuestion200ResponseData) GetValidationsOk() (*[]interface{}, bool)`

GetValidationsOk returns a tuple with the Validations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidations

`func (o *FetchQuestionBankQuestion200ResponseData) SetValidations(v []interface{})`

SetValidations sets Validations field to given value.

### HasValidations

`func (o *FetchQuestionBankQuestion200ResponseData) HasValidations() bool`

HasValidations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


