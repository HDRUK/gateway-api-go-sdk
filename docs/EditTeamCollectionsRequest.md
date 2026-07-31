# EditTeamCollectionsRequest

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
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewEditTeamCollectionsRequest

`func NewEditTeamCollectionsRequest() *EditTeamCollectionsRequest`

NewEditTeamCollectionsRequest instantiates a new EditTeamCollectionsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditTeamCollectionsRequestWithDefaults

`func NewEditTeamCollectionsRequestWithDefaults() *EditTeamCollectionsRequest`

NewEditTeamCollectionsRequestWithDefaults instantiates a new EditTeamCollectionsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *EditTeamCollectionsRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EditTeamCollectionsRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EditTeamCollectionsRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EditTeamCollectionsRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *EditTeamCollectionsRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EditTeamCollectionsRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EditTeamCollectionsRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *EditTeamCollectionsRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *EditTeamCollectionsRequest) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *EditTeamCollectionsRequest) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *EditTeamCollectionsRequest) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *EditTeamCollectionsRequest) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *EditTeamCollectionsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditTeamCollectionsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditTeamCollectionsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditTeamCollectionsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *EditTeamCollectionsRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *EditTeamCollectionsRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *EditTeamCollectionsRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *EditTeamCollectionsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *EditTeamCollectionsRequest) GetDatasets() []CreateTeamCollectionsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *EditTeamCollectionsRequest) GetDatasetsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *EditTeamCollectionsRequest) SetDatasets(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *EditTeamCollectionsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetDur

`func (o *EditTeamCollectionsRequest) GetDur() []CreateTeamCollectionsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *EditTeamCollectionsRequest) GetDurOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *EditTeamCollectionsRequest) SetDur(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *EditTeamCollectionsRequest) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *EditTeamCollectionsRequest) GetPublications() []CreateTeamCollectionsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *EditTeamCollectionsRequest) GetPublicationsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *EditTeamCollectionsRequest) SetPublications(v []CreateTeamCollectionsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *EditTeamCollectionsRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetPublic

`func (o *EditTeamCollectionsRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *EditTeamCollectionsRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *EditTeamCollectionsRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *EditTeamCollectionsRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### GetStatus

`func (o *EditTeamCollectionsRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EditTeamCollectionsRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EditTeamCollectionsRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EditTeamCollectionsRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


