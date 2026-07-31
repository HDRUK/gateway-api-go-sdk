# CreateTeamCollectionsRequest

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
**Public** | Pointer to **bool** |  | [optional] 

## Methods

### NewCreateTeamCollectionsRequest

`func NewCreateTeamCollectionsRequest() *CreateTeamCollectionsRequest`

NewCreateTeamCollectionsRequest instantiates a new CreateTeamCollectionsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTeamCollectionsRequestWithDefaults

`func NewCreateTeamCollectionsRequestWithDefaults() *CreateTeamCollectionsRequest`

NewCreateTeamCollectionsRequestWithDefaults instantiates a new CreateTeamCollectionsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateTeamCollectionsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateTeamCollectionsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateTeamCollectionsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateTeamCollectionsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *CreateTeamCollectionsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateTeamCollectionsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateTeamCollectionsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateTeamCollectionsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *CreateTeamCollectionsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *CreateTeamCollectionsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *CreateTeamCollectionsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *CreateTeamCollectionsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateTeamCollectionsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateTeamCollectionsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateTeamCollectionsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateTeamCollectionsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateTeamCollectionsRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateTeamCollectionsRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateTeamCollectionsRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateTeamCollectionsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *CreateTeamCollectionsRequest) GetDatasets() []CreateTeamCollectionsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreateTeamCollectionsRequest) GetDatasetsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreateTeamCollectionsRequest) SetDatasets(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreateTeamCollectionsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetTools

`func (o *CreateTeamCollectionsRequest) GetTools() []CreateTeamCollectionsRequestDatasetsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *CreateTeamCollectionsRequest) GetToolsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *CreateTeamCollectionsRequest) SetTools(v []CreateTeamCollectionsRequestDatasetsInner)`

SetTools sets Tools field to given value.

### HasTools

`func (o *CreateTeamCollectionsRequest) HasTools() bool`

HasTools returns a boolean if a field has been set.

### GetDur

`func (o *CreateTeamCollectionsRequest) GetDur() []CreateTeamCollectionsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *CreateTeamCollectionsRequest) GetDurOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *CreateTeamCollectionsRequest) SetDur(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *CreateTeamCollectionsRequest) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *CreateTeamCollectionsRequest) GetPublications() []CreateTeamCollectionsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateTeamCollectionsRequest) GetPublicationsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateTeamCollectionsRequest) SetPublications(v []CreateTeamCollectionsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateTeamCollectionsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetPublic

`func (o *CreateTeamCollectionsRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *CreateTeamCollectionsRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *CreateTeamCollectionsRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *CreateTeamCollectionsRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


