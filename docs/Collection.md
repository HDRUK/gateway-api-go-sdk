# Collection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**ImageLink** | Pointer to **NullableString** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Keywords** | Pointer to **NullableString** |  | [optional] 
**Public** | Pointer to **NullableBool** |  | [optional] 
**Counter** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**TeamId** | Pointer to **NullableInt32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCollection

`func NewCollection() *Collection`

NewCollection instantiates a new Collection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionWithDefaults

`func NewCollectionWithDefaults() *Collection`

NewCollectionWithDefaults instantiates a new Collection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Collection) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Collection) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Collection) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Collection) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Collection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Collection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Collection) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Collection) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *Collection) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Collection) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Collection) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Collection) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Collection) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Collection) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetImageLink

`func (o *Collection) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *Collection) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *Collection) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *Collection) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *Collection) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *Collection) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetEnabled

`func (o *Collection) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Collection) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Collection) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Collection) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetKeywords

`func (o *Collection) GetKeywords() string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *Collection) GetKeywordsOk() (*string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *Collection) SetKeywords(v string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *Collection) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### SetKeywordsNil

`func (o *Collection) SetKeywordsNil(b bool)`

 SetKeywordsNil sets the value for Keywords to be an explicit nil

### UnsetKeywords
`func (o *Collection) UnsetKeywords()`

UnsetKeywords ensures that no value is present for Keywords, not even an explicit nil
### GetPublic

`func (o *Collection) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *Collection) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *Collection) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *Collection) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### SetPublicNil

`func (o *Collection) SetPublicNil(b bool)`

 SetPublicNil sets the value for Public to be an explicit nil

### UnsetPublic
`func (o *Collection) UnsetPublic()`

UnsetPublic ensures that no value is present for Public, not even an explicit nil
### GetCounter

`func (o *Collection) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *Collection) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *Collection) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *Collection) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### SetCounterNil

`func (o *Collection) SetCounterNil(b bool)`

 SetCounterNil sets the value for Counter to be an explicit nil

### UnsetCounter
`func (o *Collection) UnsetCounter()`

UnsetCounter ensures that no value is present for Counter, not even an explicit nil
### GetStatus

`func (o *Collection) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Collection) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Collection) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Collection) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTeamId

`func (o *Collection) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Collection) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Collection) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Collection) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### SetTeamIdNil

`func (o *Collection) SetTeamIdNil(b bool)`

 SetTeamIdNil sets the value for TeamId to be an explicit nil

### UnsetTeamId
`func (o *Collection) UnsetTeamId()`

UnsetTeamId ensures that no value is present for TeamId, not even an explicit nil
### GetCreatedAt

`func (o *Collection) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Collection) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Collection) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Collection) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Collection) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Collection) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Collection) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Collection) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


