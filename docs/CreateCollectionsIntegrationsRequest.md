# CreateCollectionsIntegrationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**Datasets** | Pointer to [**[]CreateCollectionsIntegrationsRequestDatasetsInner**](CreateCollectionsIntegrationsRequestDatasetsInner.md) |  | [optional] 
**Dur** | Pointer to [**[]CreateCollectionsIntegrationsRequestDatasetsInner**](CreateCollectionsIntegrationsRequestDatasetsInner.md) |  | [optional] 
**Publications** | Pointer to [**[]CreateCollectionsIntegrationsRequestDatasetsInner**](CreateCollectionsIntegrationsRequestDatasetsInner.md) |  | [optional] 
**Public** | Pointer to **bool** |  | [optional] 

## Methods

### NewCreateCollectionsIntegrationsRequest

`func NewCreateCollectionsIntegrationsRequest() *CreateCollectionsIntegrationsRequest`

NewCreateCollectionsIntegrationsRequest instantiates a new CreateCollectionsIntegrationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCollectionsIntegrationsRequestWithDefaults

`func NewCreateCollectionsIntegrationsRequestWithDefaults() *CreateCollectionsIntegrationsRequest`

NewCreateCollectionsIntegrationsRequestWithDefaults instantiates a new CreateCollectionsIntegrationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateCollectionsIntegrationsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCollectionsIntegrationsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCollectionsIntegrationsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateCollectionsIntegrationsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *CreateCollectionsIntegrationsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCollectionsIntegrationsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCollectionsIntegrationsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateCollectionsIntegrationsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *CreateCollectionsIntegrationsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *CreateCollectionsIntegrationsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *CreateCollectionsIntegrationsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *CreateCollectionsIntegrationsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateCollectionsIntegrationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateCollectionsIntegrationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateCollectionsIntegrationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateCollectionsIntegrationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateCollectionsIntegrationsRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateCollectionsIntegrationsRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateCollectionsIntegrationsRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateCollectionsIntegrationsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *CreateCollectionsIntegrationsRequest) GetDatasets() []CreateCollectionsIntegrationsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreateCollectionsIntegrationsRequest) GetDatasetsOk() (*[]CreateCollectionsIntegrationsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreateCollectionsIntegrationsRequest) SetDatasets(v []CreateCollectionsIntegrationsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreateCollectionsIntegrationsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetDur

`func (o *CreateCollectionsIntegrationsRequest) GetDur() []CreateCollectionsIntegrationsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *CreateCollectionsIntegrationsRequest) GetDurOk() (*[]CreateCollectionsIntegrationsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *CreateCollectionsIntegrationsRequest) SetDur(v []CreateCollectionsIntegrationsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *CreateCollectionsIntegrationsRequest) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *CreateCollectionsIntegrationsRequest) GetPublications() []CreateCollectionsIntegrationsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateCollectionsIntegrationsRequest) GetPublicationsOk() (*[]CreateCollectionsIntegrationsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateCollectionsIntegrationsRequest) SetPublications(v []CreateCollectionsIntegrationsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateCollectionsIntegrationsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetPublic

`func (o *CreateCollectionsIntegrationsRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *CreateCollectionsIntegrationsRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *CreateCollectionsIntegrationsRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *CreateCollectionsIntegrationsRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


