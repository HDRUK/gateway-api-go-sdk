# Tool

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**ResultsInsights** | Pointer to **NullableString** |  | [optional] 
**License** | Pointer to **NullableInt32** | Foreign key to licenses table | [optional] 
**TechStack** | Pointer to **NullableString** |  | [optional] 
**CategoryId** | Pointer to **NullableInt32** |  | [optional] 
**UserId** | Pointer to **NullableInt32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**AssociatedAuthors** | Pointer to **NullableString** |  | [optional] 
**ContactAddress** | Pointer to **NullableString** |  | [optional] 
**AnyDataset** | Pointer to **bool** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **NullableInt32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewTool

`func NewTool() *Tool`

NewTool instantiates a new Tool object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolWithDefaults

`func NewToolWithDefaults() *Tool`

NewToolWithDefaults instantiates a new Tool object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Tool) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Tool) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Tool) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Tool) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Tool) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Tool) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Tool) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Tool) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrl

`func (o *Tool) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Tool) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Tool) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *Tool) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *Tool) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *Tool) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetDescription

`func (o *Tool) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Tool) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Tool) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Tool) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Tool) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Tool) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetResultsInsights

`func (o *Tool) GetResultsInsights() string`

GetResultsInsights returns the ResultsInsights field if non-nil, zero value otherwise.

### GetResultsInsightsOk

`func (o *Tool) GetResultsInsightsOk() (*string, bool)`

GetResultsInsightsOk returns a tuple with the ResultsInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsInsights

`func (o *Tool) SetResultsInsights(v string)`

SetResultsInsights sets ResultsInsights field to given value.

### HasResultsInsights

`func (o *Tool) HasResultsInsights() bool`

HasResultsInsights returns a boolean if a field has been set.

### SetResultsInsightsNil

`func (o *Tool) SetResultsInsightsNil(b bool)`

 SetResultsInsightsNil sets the value for ResultsInsights to be an explicit nil

### UnsetResultsInsights
`func (o *Tool) UnsetResultsInsights()`

UnsetResultsInsights ensures that no value is present for ResultsInsights, not even an explicit nil
### GetLicense

`func (o *Tool) GetLicense() int32`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *Tool) GetLicenseOk() (*int32, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *Tool) SetLicense(v int32)`

SetLicense sets License field to given value.

### HasLicense

`func (o *Tool) HasLicense() bool`

HasLicense returns a boolean if a field has been set.

### SetLicenseNil

`func (o *Tool) SetLicenseNil(b bool)`

 SetLicenseNil sets the value for License to be an explicit nil

### UnsetLicense
`func (o *Tool) UnsetLicense()`

UnsetLicense ensures that no value is present for License, not even an explicit nil
### GetTechStack

`func (o *Tool) GetTechStack() string`

GetTechStack returns the TechStack field if non-nil, zero value otherwise.

### GetTechStackOk

`func (o *Tool) GetTechStackOk() (*string, bool)`

GetTechStackOk returns a tuple with the TechStack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechStack

`func (o *Tool) SetTechStack(v string)`

SetTechStack sets TechStack field to given value.

### HasTechStack

`func (o *Tool) HasTechStack() bool`

HasTechStack returns a boolean if a field has been set.

### SetTechStackNil

`func (o *Tool) SetTechStackNil(b bool)`

 SetTechStackNil sets the value for TechStack to be an explicit nil

### UnsetTechStack
`func (o *Tool) UnsetTechStack()`

UnsetTechStack ensures that no value is present for TechStack, not even an explicit nil
### GetCategoryId

`func (o *Tool) GetCategoryId() int32`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *Tool) GetCategoryIdOk() (*int32, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *Tool) SetCategoryId(v int32)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *Tool) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *Tool) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *Tool) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetUserId

`func (o *Tool) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Tool) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Tool) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Tool) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *Tool) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *Tool) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetEnabled

`func (o *Tool) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Tool) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Tool) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Tool) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetAssociatedAuthors

`func (o *Tool) GetAssociatedAuthors() string`

GetAssociatedAuthors returns the AssociatedAuthors field if non-nil, zero value otherwise.

### GetAssociatedAuthorsOk

`func (o *Tool) GetAssociatedAuthorsOk() (*string, bool)`

GetAssociatedAuthorsOk returns a tuple with the AssociatedAuthors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedAuthors

`func (o *Tool) SetAssociatedAuthors(v string)`

SetAssociatedAuthors sets AssociatedAuthors field to given value.

### HasAssociatedAuthors

`func (o *Tool) HasAssociatedAuthors() bool`

HasAssociatedAuthors returns a boolean if a field has been set.

### SetAssociatedAuthorsNil

`func (o *Tool) SetAssociatedAuthorsNil(b bool)`

 SetAssociatedAuthorsNil sets the value for AssociatedAuthors to be an explicit nil

### UnsetAssociatedAuthors
`func (o *Tool) UnsetAssociatedAuthors()`

UnsetAssociatedAuthors ensures that no value is present for AssociatedAuthors, not even an explicit nil
### GetContactAddress

`func (o *Tool) GetContactAddress() string`

GetContactAddress returns the ContactAddress field if non-nil, zero value otherwise.

### GetContactAddressOk

`func (o *Tool) GetContactAddressOk() (*string, bool)`

GetContactAddressOk returns a tuple with the ContactAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactAddress

`func (o *Tool) SetContactAddress(v string)`

SetContactAddress sets ContactAddress field to given value.

### HasContactAddress

`func (o *Tool) HasContactAddress() bool`

HasContactAddress returns a boolean if a field has been set.

### SetContactAddressNil

`func (o *Tool) SetContactAddressNil(b bool)`

 SetContactAddressNil sets the value for ContactAddress to be an explicit nil

### UnsetContactAddress
`func (o *Tool) UnsetContactAddress()`

UnsetContactAddress ensures that no value is present for ContactAddress, not even an explicit nil
### GetAnyDataset

`func (o *Tool) GetAnyDataset() bool`

GetAnyDataset returns the AnyDataset field if non-nil, zero value otherwise.

### GetAnyDatasetOk

`func (o *Tool) GetAnyDatasetOk() (*bool, bool)`

GetAnyDatasetOk returns a tuple with the AnyDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnyDataset

`func (o *Tool) SetAnyDataset(v bool)`

SetAnyDataset sets AnyDataset field to given value.

### HasAnyDataset

`func (o *Tool) HasAnyDataset() bool`

HasAnyDataset returns a boolean if a field has been set.

### GetStatus

`func (o *Tool) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Tool) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Tool) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Tool) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTeamId

`func (o *Tool) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Tool) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Tool) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Tool) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### SetTeamIdNil

`func (o *Tool) SetTeamIdNil(b bool)`

 SetTeamIdNil sets the value for TeamId to be an explicit nil

### UnsetTeamId
`func (o *Tool) UnsetTeamId()`

UnsetTeamId ensures that no value is present for TeamId, not even an explicit nil
### GetCreatedAt

`func (o *Tool) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Tool) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Tool) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Tool) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Tool) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Tool) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Tool) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Tool) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


