# UpdateCollectionsV2Request

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
**Collaborators** | Pointer to **[]int32** |  | [optional] 
**Public** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateCollectionsV2Request

`func NewUpdateCollectionsV2Request() *UpdateCollectionsV2Request`

NewUpdateCollectionsV2Request instantiates a new UpdateCollectionsV2Request object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCollectionsV2RequestWithDefaults

`func NewUpdateCollectionsV2RequestWithDefaults() *UpdateCollectionsV2Request`

NewUpdateCollectionsV2RequestWithDefaults instantiates a new UpdateCollectionsV2Request object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateCollectionsV2Request) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateCollectionsV2Request) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateCollectionsV2Request) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateCollectionsV2Request) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateCollectionsV2Request) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateCollectionsV2Request) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateCollectionsV2Request) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateCollectionsV2Request) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageLink

`func (o *UpdateCollectionsV2Request) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *UpdateCollectionsV2Request) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *UpdateCollectionsV2Request) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *UpdateCollectionsV2Request) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateCollectionsV2Request) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateCollectionsV2Request) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateCollectionsV2Request) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateCollectionsV2Request) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *UpdateCollectionsV2Request) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *UpdateCollectionsV2Request) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *UpdateCollectionsV2Request) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *UpdateCollectionsV2Request) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetDatasets

`func (o *UpdateCollectionsV2Request) GetDatasets() []CreateTeamCollectionsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *UpdateCollectionsV2Request) GetDatasetsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *UpdateCollectionsV2Request) SetDatasets(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *UpdateCollectionsV2Request) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetDur

`func (o *UpdateCollectionsV2Request) GetDur() []CreateTeamCollectionsRequestDatasetsInner`

GetDur returns the Dur field if non-nil, zero value otherwise.

### GetDurOk

`func (o *UpdateCollectionsV2Request) GetDurOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetDurOk returns a tuple with the Dur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDur

`func (o *UpdateCollectionsV2Request) SetDur(v []CreateTeamCollectionsRequestDatasetsInner)`

SetDur sets Dur field to given value.

### HasDur

`func (o *UpdateCollectionsV2Request) HasDur() bool`

HasDur returns a boolean if a field has been set.

### GetPublications

`func (o *UpdateCollectionsV2Request) GetPublications() []CreateTeamCollectionsRequestDatasetsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *UpdateCollectionsV2Request) GetPublicationsOk() (*[]CreateTeamCollectionsRequestDatasetsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *UpdateCollectionsV2Request) SetPublications(v []CreateTeamCollectionsRequestDatasetsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *UpdateCollectionsV2Request) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetCollaborators

`func (o *UpdateCollectionsV2Request) GetCollaborators() []int32`

GetCollaborators returns the Collaborators field if non-nil, zero value otherwise.

### GetCollaboratorsOk

`func (o *UpdateCollectionsV2Request) GetCollaboratorsOk() (*[]int32, bool)`

GetCollaboratorsOk returns a tuple with the Collaborators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollaborators

`func (o *UpdateCollectionsV2Request) SetCollaborators(v []int32)`

SetCollaborators sets Collaborators field to given value.

### HasCollaborators

`func (o *UpdateCollectionsV2Request) HasCollaborators() bool`

HasCollaborators returns a boolean if a field has been set.

### GetPublic

`func (o *UpdateCollectionsV2Request) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *UpdateCollectionsV2Request) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *UpdateCollectionsV2Request) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *UpdateCollectionsV2Request) HasPublic() bool`

HasPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


