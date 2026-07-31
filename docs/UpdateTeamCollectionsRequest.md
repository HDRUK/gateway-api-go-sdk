# UpdateTeamCollectionsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**ImageLink** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**Datasets** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Dur** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Publications** | Pointer to [**[]CreateTeamCollectionsRequestDatasetsInner**](CreateTeamCollectionsRequestDatasetsInner.md) |  | [optional] 
**Public** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateTeamCollectionsRequest

`func NewUpdateTeamCollectionsRequest() *UpdateTeamCollectionsRequest`

NewUpdateTeamCollectionsRequest instantiates a new UpdateTeamCollectionsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTeamCollectionsRequestWithDefaults

`func NewUpdateTeamCollectionsRequestWithDefaults() *UpdateTeamCollectionsRequest`

NewUpdateTeamCollectionsRequestWithDefaults instantiates a new UpdateTeamCollectionsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateTeamCollectionsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateTeamCollectionsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateTeamCollectionsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateTeamCollectionsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateTeamCollectionsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateTeamCollectionsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateTeamCollectionsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateTeamCollectionsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *UpdateTeamCollectionsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *UpdateTeamCollectionsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *UpdateTeamCollectionsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *UpdateTeamCollectionsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateTeamCollectionsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateTeamCollectionsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateTeamCollectionsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateTeamCollectionsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *UpdateTeamCollectionsRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *UpdateTeamCollectionsRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *UpdateTeamCollectionsRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *UpdateTeamCollectionsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *UpdateTeamCollectionsRequest) GetDatasets() []CreateTeamCollectionsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *UpdateTeamCollectionsRequest) GetDatasetsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *UpdateTeamCollectionsRequest) SetDatasets(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *UpdateTeamCollectionsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetDur

`func (o *UpdateTeamCollectionsRequest) GetDur() []CreateTeamCollectionsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *UpdateTeamCollectionsRequest) GetDurOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *UpdateTeamCollectionsRequest) SetDur(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *UpdateTeamCollectionsRequest) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *UpdateTeamCollectionsRequest) GetPublications() []CreateTeamCollectionsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *UpdateTeamCollectionsRequest) GetPublicationsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *UpdateTeamCollectionsRequest) SetPublications(v []CreateTeamCollectionsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *UpdateTeamCollectionsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetPublic

`func (o *UpdateTeamCollectionsRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *UpdateTeamCollectionsRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *UpdateTeamCollectionsRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *UpdateTeamCollectionsRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


