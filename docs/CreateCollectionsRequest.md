# CreateCollectionsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**Datasets** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Tools** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Dur** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Publications** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Collaborators** | Pointer to **[]int32** |  | [optional] 
**Public** | Pointer to **bool** |  | [optional] 

## Methods

### NewCreateCollectionsRequest

`func NewCreateCollectionsRequest() *CreateCollectionsRequest`

NewCreateCollectionsRequest instantiates a new CreateCollectionsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCollectionsRequestWithDefaults

`func NewCreateCollectionsRequestWithDefaults() *CreateCollectionsRequest`

NewCreateCollectionsRequestWithDefaults instantiates a new CreateCollectionsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateCollectionsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCollectionsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCollectionsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateCollectionsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *CreateCollectionsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCollectionsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCollectionsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateCollectionsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *CreateCollectionsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *CreateCollectionsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *CreateCollectionsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *CreateCollectionsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateCollectionsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateCollectionsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateCollectionsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateCollectionsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateCollectionsRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateCollectionsRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateCollectionsRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateCollectionsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *CreateCollectionsRequest) GetDatasets() []CreateTeamCollectionsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreateCollectionsRequest) GetDatasetsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreateCollectionsRequest) SetDatasets(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreateCollectionsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetTools

`func (o *CreateCollectionsRequest) GetTools() []CreateTeamCollectionsRequestDatasetsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *CreateCollectionsRequest) GetToolsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *CreateCollectionsRequest) SetTools(v []CreateTeamCollectionsRequestDatasetsInner)`

SetTools sets Tools field to given value.

### HasTools

`func (o *CreateCollectionsRequest) HasTools() bool`

HasTools returns a boolean if a field has been set.

### GetDur

`func (o *CreateCollectionsRequest) GetDur() []CreateTeamCollectionsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *CreateCollectionsRequest) GetDurOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *CreateCollectionsRequest) SetDur(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *CreateCollectionsRequest) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *CreateCollectionsRequest) GetPublications() []CreateTeamCollectionsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateCollectionsRequest) GetPublicationsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateCollectionsRequest) SetPublications(v []CreateTeamCollectionsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateCollectionsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetCollaborators

`func (o *CreateCollectionsRequest) GetCollaborators() []int32`

GetCollaborators returns the Collaborators field if non-nil, zero value otherwise.

### GetCollaboratorsOk

`func (o *CreateCollectionsRequest) GetCollaboratorsOk() (*[]int32, bool)`

GetCollaboratorsOk returns a tuple with the Collaborators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollaborators

`func (o *CreateCollectionsRequest) SetCollaborators(v []int32)`

SetCollaborators sets Collaborators field to given value.

### HasCollaborators

`func (o *CreateCollectionsRequest) HasCollaborators() bool`

HasCollaborators returns a boolean if a field has been set.

### GetPublic

`func (o *CreateCollectionsRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *CreateCollectionsRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *CreateCollectionsRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *CreateCollectionsRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


