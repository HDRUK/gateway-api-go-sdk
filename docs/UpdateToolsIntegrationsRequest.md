# UpdateToolsIntegrationsRequest

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
**Tags** | Pointer to **[]int64** |  | [optional] 
**ProgrammingLanguage** | Pointer to **[]int64** |  | [optional] 
**ProgrammingPackage** | Pointer to **[]int64** |  | [optional] 
**Dataset** | Pointer to [**[]CreateToolsIntegrationsRequestDatasetInner**](CreateToolsIntegrationsRequestDatasetInner.md) |  | [optional] 
**TypeCategory** | Pointer to **[]int64** |  | [optional] 
**Enabled** | Pointer to **int32** |  | [optional] 
**Publications** | Pointer to [**[]CreateToolsIntegrationsRequestPublicationsInner**](CreateToolsIntegrationsRequestPublicationsInner.md) |  | [optional] 

## Methods

### NewUpdateToolsIntegrationsRequest

`func NewUpdateToolsIntegrationsRequest() *UpdateToolsIntegrationsRequest`

NewUpdateToolsIntegrationsRequest instantiates a new UpdateToolsIntegrationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateToolsIntegrationsRequestWithDefaults

`func NewUpdateToolsIntegrationsRequestWithDefaults() *UpdateToolsIntegrationsRequest`

NewUpdateToolsIntegrationsRequestWithDefaults instantiates a new UpdateToolsIntegrationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateToolsIntegrationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateToolsIntegrationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateToolsIntegrationsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateToolsIntegrationsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrl

`func (o *UpdateToolsIntegrationsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *UpdateToolsIntegrationsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *UpdateToolsIntegrationsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *UpdateToolsIntegrationsRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateToolsIntegrationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateToolsIntegrationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateToolsIntegrationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateToolsIntegrationsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLicense

`func (o *UpdateToolsIntegrationsRequest) GetLicense() string`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *UpdateToolsIntegrationsRequest) GetLicenseOk() (*string, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *UpdateToolsIntegrationsRequest) SetLicense(v string)`

SetLicense sets License field to given value.

### HasLicense

`func (o *UpdateToolsIntegrationsRequest) HasLicense() bool`

HasLicense returns a boolean if a field has been set.

### GetTechStack

`func (o *UpdateToolsIntegrationsRequest) GetTechStack() string`

GetTechStack returns the TechStack field if non-nil, zero value otherwise.

### GetTechStackOk

`func (o *UpdateToolsIntegrationsRequest) GetTechStackOk() (*string, bool)`

GetTechStackOk returns a tuple with the TechStack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechStack

`func (o *UpdateToolsIntegrationsRequest) SetTechStack(v string)`

SetTechStack sets TechStack field to given value.

### HasTechStack

`func (o *UpdateToolsIntegrationsRequest) HasTechStack() bool`

HasTechStack returns a boolean if a field has been set.

### GetCategoryId

`func (o *UpdateToolsIntegrationsRequest) GetCategoryId() int32`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *UpdateToolsIntegrationsRequest) GetCategoryIdOk() (*int32, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *UpdateToolsIntegrationsRequest) SetCategoryId(v int32)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *UpdateToolsIntegrationsRequest) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### GetUserId

`func (o *UpdateToolsIntegrationsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateToolsIntegrationsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateToolsIntegrationsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UpdateToolsIntegrationsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTags

`func (o *UpdateToolsIntegrationsRequest) GetTags() []int64`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdateToolsIntegrationsRequest) GetTagsOk() (*[]int64, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdateToolsIntegrationsRequest) SetTags(v []int64)`

SetTags sets Tags field to given value.

### HasTags

`func (o *UpdateToolsIntegrationsRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetProgrammingLanguage

`func (o *UpdateToolsIntegrationsRequest) GetProgrammingLanguage() []int64`

GetProgrammingLanguage returns the ProgrammingLanguage field if non-nil, zero value otherwise.

### GetProgrammingLanguageOk

`func (o *UpdateToolsIntegrationsRequest) GetProgrammingLanguageOk() (*[]int64, bool)`

GetProgrammingLanguageOk returns a tuple with the ProgrammingLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingLanguage

`func (o *UpdateToolsIntegrationsRequest) SetProgrammingLanguage(v []int64)`

SetProgrammingLanguage sets ProgrammingLanguage field to given value.

### HasProgrammingLanguage

`func (o *UpdateToolsIntegrationsRequest) HasProgrammingLanguage() bool`

HasProgrammingLanguage returns a boolean if a field has been set.

### GetProgrammingPackage

`func (o *UpdateToolsIntegrationsRequest) GetProgrammingPackage() []int64`

GetProgrammingPackage returns the ProgrammingPackage field if non-nil, zero value otherwise.

### GetProgrammingPackageOk

`func (o *UpdateToolsIntegrationsRequest) GetProgrammingPackageOk() (*[]int64, bool)`

GetProgrammingPackageOk returns a tuple with the ProgrammingPackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgrammingPackage

`func (o *UpdateToolsIntegrationsRequest) SetProgrammingPackage(v []int64)`

SetProgrammingPackage sets ProgrammingPackage field to given value.

### HasProgrammingPackage

`func (o *UpdateToolsIntegrationsRequest) HasProgrammingPackage() bool`

HasProgrammingPackage returns a boolean if a field has been set.

### GetDataset

`func (o *UpdateToolsIntegrationsRequest) GetDataset() []CreateToolsIntegrationsRequestDatasetInner`

GetDataset returns the Dataset field if non-nil, zero value otherwise.

### GetDatasetOk

`func (o *UpdateToolsIntegrationsRequest) GetDatasetOk() (*[]CreateToolsIntegrationsRequestDatasetInner, bool)`

GetDatasetOk returns a tuple with the Dataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataset

`func (o *UpdateToolsIntegrationsRequest) SetDataset(v []CreateToolsIntegrationsRequestDatasetInner)`

SetDataset sets Dataset field to given value.

### HasDataset

`func (o *UpdateToolsIntegrationsRequest) HasDataset() bool`

HasDataset returns a boolean if a field has been set.

### GetTypeCategory

`func (o *UpdateToolsIntegrationsRequest) GetTypeCategory() []int64`

GetTypeCategory returns the TypeCategory field if non-nil, zero value otherwise.

### GetTypeCategoryOk

`func (o *UpdateToolsIntegrationsRequest) GetTypeCategoryOk() (*[]int64, bool)`

GetTypeCategoryOk returns a tuple with the TypeCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeCategory

`func (o *UpdateToolsIntegrationsRequest) SetTypeCategory(v []int64)`

SetTypeCategory sets TypeCategory field to given value.

### HasTypeCategory

`func (o *UpdateToolsIntegrationsRequest) HasTypeCategory() bool`

HasTypeCategory returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateToolsIntegrationsRequest) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateToolsIntegrationsRequest) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateToolsIntegrationsRequest) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateToolsIntegrationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPublications

`func (o *UpdateToolsIntegrationsRequest) GetPublications() []CreateToolsIntegrationsRequestPublicationsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *UpdateToolsIntegrationsRequest) GetPublicationsOk() (*[]CreateToolsIntegrationsRequestPublicationsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *UpdateToolsIntegrationsRequest) SetPublications(v []CreateToolsIntegrationsRequestPublicationsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *UpdateToolsIntegrationsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


