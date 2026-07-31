# CreateToolsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**ResultsInsights** | Pointer to **string** |  | [optional] 
**License** | Pointer to **int32** |  | [optional] 
**TechStack** | Pointer to **string** |  | [optional] 
**CategoryId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**Tags** | Pointer to **[]int64** |  | [optional] 
**Dataset** | Pointer to [**[]CreateToolsIntegrationsRequestDatasetInner**](CreateToolsIntegrationsRequestDatasetInner.md) |  | [optional] 
**Enabled** | Pointer to **int32** |  | [optional] 
**ProgrammingLanguage** | Pointer to **[]int64** |  | [optional] 
**ProgrammingPackage** | Pointer to **[]int64** |  | [optional] 
**TypeCategory** | Pointer to **[]int64** |  | [optional] 
**AssociatedAuthors** | Pointer to **string** |  | [optional] 
**ContactAddress** | Pointer to **string** |  | [optional] 
**Publications** | Pointer to [**[]CreateToolsIntegrationsRequestPublicationsInner**](CreateToolsIntegrationsRequestPublicationsInner.md) |  | [optional] 
**Durs** | Pointer to **[]int64** |  | [optional] 
**Collections** | Pointer to [**[]CreateToolsRequestCollectionsInner**](CreateToolsRequestCollectionsInner.md) |  | [optional] 
**AnyDataset** | Pointer to **bool** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateToolsRequest

`func NewCreateToolsRequest() *CreateToolsRequest`

NewCreateToolsRequest instantiates a new CreateToolsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateToolsRequestWithDefaults

`func NewCreateToolsRequestWithDefaults() *CreateToolsRequest`

NewCreateToolsRequestWithDefaults instantiates a new CreateToolsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateToolsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateToolsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateToolsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateToolsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrl

`func (o *CreateToolsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateToolsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateToolsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreateToolsRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetDescription

`func (o *CreateToolsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateToolsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateToolsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateToolsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetResultsInsights

`func (o *CreateToolsRequest) GetResultsInsights() string`

GetResultsInsights returns the ResultsInsights field if non-nil, zero value otherwise.

### GetResultsInsightsOk

`func (o *CreateToolsRequest) GetResultsInsightsOk() (*string, bool)`

GetResultsInsightsOk returns a tuple with the ResultsInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsInsights

`func (o *CreateToolsRequest) SetResultsInsights(v string)`

SetResultsInsights sets ResultsInsights field to given value.

### HasResultsInsights

`func (o *CreateToolsRequest) HasResultsInsights() bool`

HasResultsInsights returns a boolean if a field has been set.

### GetLicense

`func (o *CreateToolsRequest) GetLicense() int32`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *CreateToolsRequest) GetLicenseOk() (*int32, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *CreateToolsRequest) SetLicense(v int32)`

SetLicense sets License field to given value.

### HasLicense

`func (o *CreateToolsRequest) HasLicense() bool`

HasLicense returns a boolean if a field has been set.

### GetTechStack

`func (o *CreateToolsRequest) GetTechStack() string`

GetTechStack returns the TechStack field if non-nil, zero value otherwise.

### GetTechStackOk

`func (o *CreateToolsRequest) GetTechStackOk() (*string, bool)`

GetTechStackOk returns a tuple with the TechStack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechStack

`func (o *CreateToolsRequest) SetTechStack(v string)`

SetTechStack sets TechStack field to given value.

### HasTechStack

`func (o *CreateToolsRequest) HasTechStack() bool`

HasTechStack returns a boolean if a field has been set.

### GetCategoryId

`func (o *CreateToolsRequest) GetCategoryId() int32`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *CreateToolsRequest) GetCategoryIdOk() (*int32, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *CreateToolsRequest) SetCategoryId(v int32)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *CreateToolsRequest) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateToolsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateToolsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateToolsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateToolsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamId

`func (o *CreateToolsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateToolsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateToolsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *CreateToolsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetTags

`func (o *CreateToolsRequest) GetTags() []int64`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreateToolsRequest) GetTagsOk() (*[]int64, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreateToolsRequest) SetTags(v []int64)`

SetTags sets Tags field to given value.

### HasTags

`func (o *CreateToolsRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDataset

`func (o *CreateToolsRequest) GetDataset() []CreateToolsIntegrationsRequestDatasetInner`

GetDataset returns the Dataset field if non-nil, zero value otherwise.

### GetDatasetOk

`func (o *CreateToolsRequest) GetDatasetOk() (*[]CreateToolsIntegrationsRequestDatasetInner, bool)`

GetDatasetOk returns a tuple with the Dataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataset

`func (o *CreateToolsRequest) SetDataset(v []CreateToolsIntegrationsRequestDatasetInner)`

SetDataset sets Dataset field to given value.

### HasDataset

`func (o *CreateToolsRequest) HasDataset() bool`

HasDataset returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateToolsRequest) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateToolsRequest) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateToolsRequest) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateToolsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetProgrammingLanguage

`func (o *CreateToolsRequest) GetProgrammingLanguage() []int64`

GetProgrammingLanguage returns the ProgrammingLanguage field if non-nil, zero value otherwise.

### GetProgrammingLanguageOk

`func (o *CreateToolsRequest) GetProgrammingLanguageOk() (*[]int64, bool)`

GetProgrammingLanguageOk returns a tuple with the ProgrammingLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingLanguage

`func (o *CreateToolsRequest) SetProgrammingLanguage(v []int64)`

SetProgrammingLanguage sets ProgrammingLanguage field to given value.

### HasProgrammingLanguage

`func (o *CreateToolsRequest) HasProgrammingLanguage() bool`

HasProgrammingLanguage returns a boolean if a field has been set.

### GetProgrammingPackage

`func (o *CreateToolsRequest) GetProgrammingPackage() []int64`

GetProgrammingPackage returns the ProgrammingPackage field if non-nil, zero value otherwise.

### GetProgrammingPackageOk

`func (o *CreateToolsRequest) GetProgrammingPackageOk() (*[]int64, bool)`

GetProgrammingPackageOk returns a tuple with the ProgrammingPackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingPackage

`func (o *CreateToolsRequest) SetProgrammingPackage(v []int64)`

SetProgrammingPackage sets ProgrammingPackage field to given value.

### HasProgrammingPackage

`func (o *CreateToolsRequest) HasProgrammingPackage() bool`

HasProgrammingPackage returns a boolean if a field has been set.

### GetTypeCategory

`func (o *CreateToolsRequest) GetTypeCategory() []int64`

GetTypeCategory returns the TypeCategory field if non-nil, zero value otherwise.

### GetTypeCategoryOk

`func (o *CreateToolsRequest) GetTypeCategoryOk() (*[]int64, bool)`

GetTypeCategoryOk returns a tuple with the TypeCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeCategory

`func (o *CreateToolsRequest) SetTypeCategory(v []int64)`

SetTypeCategory sets TypeCategory field to given value.

### HasTypeCategory

`func (o *CreateToolsRequest) HasTypeCategory() bool`

HasTypeCategory returns a boolean if a field has been set.

### GetAssociatedAuthors

`func (o *CreateToolsRequest) GetAssociatedAuthors() string`

GetAssociatedAuthors returns the AssociatedAuthors field if non-nil, zero value otherwise.

### GetAssociatedAuthorsOk

`func (o *CreateToolsRequest) GetAssociatedAuthorsOk() (*string, bool)`

GetAssociatedAuthorsOk returns a tuple with the AssociatedAuthors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedAuthors

`func (o *CreateToolsRequest) SetAssociatedAuthors(v string)`

SetAssociatedAuthors sets AssociatedAuthors field to given value.

### HasAssociatedAuthors

`func (o *CreateToolsRequest) HasAssociatedAuthors() bool`

HasAssociatedAuthors returns a boolean if a field has been set.

### GetContactAddress

`func (o *CreateToolsRequest) GetContactAddress() string`

GetContactAddress returns the ContactAddress field if non-nil, zero value otherwise.

### GetContactAddressOk

`func (o *CreateToolsRequest) GetContactAddressOk() (*string, bool)`

GetContactAddressOk returns a tuple with the ContactAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactAddress

`func (o *CreateToolsRequest) SetContactAddress(v string)`

SetContactAddress sets ContactAddress field to given value.

### HasContactAddress

`func (o *CreateToolsRequest) HasContactAddress() bool`

HasContactAddress returns a boolean if a field has been set.

### GetPublications

`func (o *CreateToolsRequest) GetPublications() []CreateToolsIntegrationsRequestPublicationsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateToolsRequest) GetPublicationsOk() (*[]CreateToolsIntegrationsRequestPublicationsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateToolsRequest) SetPublications(v []CreateToolsIntegrationsRequestPublicationsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateToolsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetDurs

`func (o *CreateToolsRequest) GetDurs() []int64`

GetDurs returns the Durs field if non-nil, zero value otherwise.

### GetDursOk

`func (o *CreateToolsRequest) GetDursOk() (*[]int64, bool)`

GetDursOk returns a tuple with the Durs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurs

`func (o *CreateToolsRequest) SetDurs(v []int64)`

SetDurs sets Durs field to given value.

### HasDurs

`func (o *CreateToolsRequest) HasDurs() bool`

HasDurs returns a boolean if a field has been set.

### GetCollections

`func (o *CreateToolsRequest) GetCollections() []CreateToolsRequestCollectionsInner`

GetCollections returns the Collections field if non-nil, zero value otherwise.

### GetCollectionsOk

`func (o *CreateToolsRequest) GetCollectionsOk() (*[]CreateToolsRequestCollectionsInner, bool)`

GetCollectionsOk returns a tuple with the Collections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollections

`func (o *CreateToolsRequest) SetCollections(v []CreateToolsRequestCollectionsInner)`

SetCollections sets Collections field to given value.

### HasCollections

`func (o *CreateToolsRequest) HasCollections() bool`

HasCollections returns a boolean if a field has been set.

### GetAnyDataset

`func (o *CreateToolsRequest) GetAnyDataset() bool`

GetAnyDataset returns the AnyDataset field if non-nil, zero value otherwise.

### GetAnyDatasetOk

`func (o *CreateToolsRequest) GetAnyDatasetOk() (*bool, bool)`

GetAnyDatasetOk returns a tuple with the AnyDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnyDataset

`func (o *CreateToolsRequest) SetAnyDataset(v bool)`

SetAnyDataset sets AnyDataset field to given value.

### HasAnyDataset

`func (o *CreateToolsRequest) HasAnyDataset() bool`

HasAnyDataset returns a boolean if a field has been set.

### GetStatus

`func (o *CreateToolsRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateToolsRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateToolsRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateToolsRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


