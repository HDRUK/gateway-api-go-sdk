# CreateToolsIntegrationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**License** | Pointer to **string** |  | [optional] 
**TechStack** | Pointer to **string** |  | [optional] 
**CategoryId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**Tags** | Pointer to **[]int64** |  | [optional] 
**ProgrammingLanguage** | Pointer to **[]int64** |  | [optional] 
**ProgrammingPackage** | Pointer to **[]int64** |  | [optional] 
**Dataset** | Pointer to [**[]CreateToolsIntegrationsRequestDatasetInner**](CreateToolsIntegrationsRequestDatasetInner.md) |  | [optional] 
**TypeCategory** | Pointer to **[]int64** |  | [optional] 
**Enabled** | Pointer to **int32** |  | [optional] 
**Publications** | Pointer to [**[]CreateToolsIntegrationsRequestPublicationsInner**](CreateToolsIntegrationsRequestPublicationsInner.md) |  | [optional] 

## Methods

### NewCreateToolsIntegrationsRequest

`func NewCreateToolsIntegrationsRequest() *CreateToolsIntegrationsRequest`

NewCreateToolsIntegrationsRequest instantiates a new CreateToolsIntegrationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateToolsIntegrationsRequestWithDefaults

`func NewCreateToolsIntegrationsRequestWithDefaults() *CreateToolsIntegrationsRequest`

NewCreateToolsIntegrationsRequestWithDefaults instantiates a new CreateToolsIntegrationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateToolsIntegrationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateToolsIntegrationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateToolsIntegrationsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateToolsIntegrationsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrl

`func (o *CreateToolsIntegrationsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateToolsIntegrationsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateToolsIntegrationsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreateToolsIntegrationsRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetDescription

`func (o *CreateToolsIntegrationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateToolsIntegrationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateToolsIntegrationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateToolsIntegrationsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLicense

`func (o *CreateToolsIntegrationsRequest) GetLicense() string`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *CreateToolsIntegrationsRequest) GetLicenseOk() (*string, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *CreateToolsIntegrationsRequest) SetLicense(v string)`

SetLicense sets License field to given value.

### HasLicense

`func (o *CreateToolsIntegrationsRequest) HasLicense() bool`

HasLicense returns a boolean if a field has been set.

### GetTechStack

`func (o *CreateToolsIntegrationsRequest) GetTechStack() string`

GetTechStack returns the TechStack field if non-nil, zero value otherwise.

### GetTechStackOk

`func (o *CreateToolsIntegrationsRequest) GetTechStackOk() (*string, bool)`

GetTechStackOk returns a tuple with the TechStack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechStack

`func (o *CreateToolsIntegrationsRequest) SetTechStack(v string)`

SetTechStack sets TechStack field to given value.

### HasTechStack

`func (o *CreateToolsIntegrationsRequest) HasTechStack() bool`

HasTechStack returns a boolean if a field has been set.

### GetCategoryId

`func (o *CreateToolsIntegrationsRequest) GetCategoryId() int32`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *CreateToolsIntegrationsRequest) GetCategoryIdOk() (*int32, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *CreateToolsIntegrationsRequest) SetCategoryId(v int32)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *CreateToolsIntegrationsRequest) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateToolsIntegrationsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateToolsIntegrationsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateToolsIntegrationsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateToolsIntegrationsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamId

`func (o *CreateToolsIntegrationsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateToolsIntegrationsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateToolsIntegrationsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *CreateToolsIntegrationsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetTags

`func (o *CreateToolsIntegrationsRequest) GetTags() []int64`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreateToolsIntegrationsRequest) GetTagsOk() (*[]int64, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreateToolsIntegrationsRequest) SetTags(v []int64)`

SetTags sets Tags field to given value.

### HasTags

`func (o *CreateToolsIntegrationsRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetProgrammingLanguage

`func (o *CreateToolsIntegrationsRequest) GetProgrammingLanguage() []int64`

GetProgrammingLanguage returns the ProgrammingLanguage field if non-nil, zero value otherwise.

### GetProgrammingLanguageOk

`func (o *CreateToolsIntegrationsRequest) GetProgrammingLanguageOk() (*[]int64, bool)`

GetProgrammingLanguageOk returns a tuple with the ProgrammingLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingLanguage

`func (o *CreateToolsIntegrationsRequest) SetProgrammingLanguage(v []int64)`

SetProgrammingLanguage sets ProgrammingLanguage field to given value.

### HasProgrammingLanguage

`func (o *CreateToolsIntegrationsRequest) HasProgrammingLanguage() bool`

HasProgrammingLanguage returns a boolean if a field has been set.

### GetProgrammingPackage

`func (o *CreateToolsIntegrationsRequest) GetProgrammingPackage() []int64`

GetProgrammingPackage returns the ProgrammingPackage field if non-nil, zero value otherwise.

### GetProgrammingPackageOk

`func (o *CreateToolsIntegrationsRequest) GetProgrammingPackageOk() (*[]int64, bool)`

GetProgrammingPackageOk returns a tuple with the ProgrammingPackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingPackage

`func (o *CreateToolsIntegrationsRequest) SetProgrammingPackage(v []int64)`

SetProgrammingPackage sets ProgrammingPackage field to given value.

### HasProgrammingPackage

`func (o *CreateToolsIntegrationsRequest) HasProgrammingPackage() bool`

HasProgrammingPackage returns a boolean if a field has been set.

### GetDataset

`func (o *CreateToolsIntegrationsRequest) GetDataset() []CreateToolsIntegrationsRequestDatasetInner`

GetDataset returns the Dataset field if non-nil, zero value otherwise.

### GetDatasetOk

`func (o *CreateToolsIntegrationsRequest) GetDatasetOk() (*[]CreateToolsIntegrationsRequestDatasetInner, bool)`

GetDatasetOk returns a tuple with the Dataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataset

`func (o *CreateToolsIntegrationsRequest) SetDataset(v []CreateToolsIntegrationsRequestDatasetInner)`

SetDataset sets Dataset field to given value.

### HasDataset

`func (o *CreateToolsIntegrationsRequest) HasDataset() bool`

HasDataset returns a boolean if a field has been set.

### GetTypeCategory

`func (o *CreateToolsIntegrationsRequest) GetTypeCategory() []int64`

GetTypeCategory returns the TypeCategory field if non-nil, zero value otherwise.

### GetTypeCategoryOk

`func (o *CreateToolsIntegrationsRequest) GetTypeCategoryOk() (*[]int64, bool)`

GetTypeCategoryOk returns a tuple with the TypeCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeCategory

`func (o *CreateToolsIntegrationsRequest) SetTypeCategory(v []int64)`

SetTypeCategory sets TypeCategory field to given value.

### HasTypeCategory

`func (o *CreateToolsIntegrationsRequest) HasTypeCategory() bool`

HasTypeCategory returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateToolsIntegrationsRequest) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateToolsIntegrationsRequest) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateToolsIntegrationsRequest) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateToolsIntegrationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPublications

`func (o *CreateToolsIntegrationsRequest) GetPublications() []CreateToolsIntegrationsRequestPublicationsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateToolsIntegrationsRequest) GetPublicationsOk() (*[]CreateToolsIntegrationsRequestPublicationsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateToolsIntegrationsRequest) SetPublications(v []CreateToolsIntegrationsRequestPublicationsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateToolsIntegrationsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


