# Widget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**DataCustodianEntitiesIds** | Pointer to **NullableString** |  | [optional] 
**IncludedDatasets** | Pointer to **NullableString** |  | [optional] 
**IncludedDataUses** | Pointer to **NullableString** |  | [optional] 
**IncludedScripts** | Pointer to **NullableString** |  | [optional] 
**IncludedCollections** | Pointer to **NullableString** |  | [optional] 
**IncludeSearchBar** | Pointer to **bool** |  | [optional] 
**IncludeCohortLink** | Pointer to **bool** |  | [optional] 
**SizeWidth** | Pointer to **NullableInt32** |  | [optional] 
**SizeHeight** | Pointer to **NullableInt32** |  | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**KeepProportions** | Pointer to **bool** |  | [optional] 
**WidgetName** | Pointer to **string** |  | [optional] 
**PermittedDomains** | Pointer to **NullableString** |  | [optional] 
**BrandingPrimary** | Pointer to **NullableString** |  | [optional] 
**BrandingSecondary** | Pointer to **NullableString** |  | [optional] 
**BrandingNeutral** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWidget

`func NewWidget() *Widget`

NewWidget instantiates a new Widget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWidgetWithDefaults

`func NewWidgetWithDefaults() *Widget`

NewWidgetWithDefaults instantiates a new Widget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Widget) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Widget) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Widget) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Widget) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTeamId

`func (o *Widget) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Widget) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Widget) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Widget) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetDataCustodianEntitiesIds

`func (o *Widget) GetDataCustodianEntitiesIds() string`

GetDataCustodianEntitiesIds returns the DataCustodianEntitiesIds field if non-nil, zero value otherwise.

### GetDataCustodianEntitiesIdsOk

`func (o *Widget) GetDataCustodianEntitiesIdsOk() (*string, bool)`

GetDataCustodianEntitiesIdsOk returns a tuple with the DataCustodianEntitiesIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCustodianEntitiesIds

`func (o *Widget) SetDataCustodianEntitiesIds(v string)`

SetDataCustodianEntitiesIds sets DataCustodianEntitiesIds field to given value.

### HasDataCustodianEntitiesIds

`func (o *Widget) HasDataCustodianEntitiesIds() bool`

HasDataCustodianEntitiesIds returns a boolean if a field has been set.

### SetDataCustodianEntitiesIdsNil

`func (o *Widget) SetDataCustodianEntitiesIdsNil(b bool)`

 SetDataCustodianEntitiesIdsNil sets the value for DataCustodianEntitiesIds to be an explicit nil

### UnsetDataCustodianEntitiesIds
`func (o *Widget) UnsetDataCustodianEntitiesIds()`

UnsetDataCustodianEntitiesIds ensures that no value is present for DataCustodianEntitiesIds, not even an explicit nil
### GetIncludedDatasets

`func (o *Widget) GetIncludedDatasets() string`

GetIncludedDatasets returns the IncludedDatasets field if non-nil, zero value otherwise.

### GetIncludedDatasetsOk

`func (o *Widget) GetIncludedDatasetsOk() (*string, bool)`

GetIncludedDatasetsOk returns a tuple with the IncludedDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedDatasets

`func (o *Widget) SetIncludedDatasets(v string)`

SetIncludedDatasets sets IncludedDatasets field to given value.

### HasIncludedDatasets

`func (o *Widget) HasIncludedDatasets() bool`

HasIncludedDatasets returns a boolean if a field has been set.

### SetIncludedDatasetsNil

`func (o *Widget) SetIncludedDatasetsNil(b bool)`

 SetIncludedDatasetsNil sets the value for IncludedDatasets to be an explicit nil

### UnsetIncludedDatasets
`func (o *Widget) UnsetIncludedDatasets()`

UnsetIncludedDatasets ensures that no value is present for IncludedDatasets, not even an explicit nil
### GetIncludedDataUses

`func (o *Widget) GetIncludedDataUses() string`

GetIncludedDataUses returns the IncludedDataUses field if non-nil, zero value otherwise.

### GetIncludedDataUsesOk

`func (o *Widget) GetIncludedDataUsesOk() (*string, bool)`

GetIncludedDataUsesOk returns a tuple with the IncludedDataUses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedDataUses

`func (o *Widget) SetIncludedDataUses(v string)`

SetIncludedDataUses sets IncludedDataUses field to given value.

### HasIncludedDataUses

`func (o *Widget) HasIncludedDataUses() bool`

HasIncludedDataUses returns a boolean if a field has been set.

### SetIncludedDataUsesNil

`func (o *Widget) SetIncludedDataUsesNil(b bool)`

 SetIncludedDataUsesNil sets the value for IncludedDataUses to be an explicit nil

### UnsetIncludedDataUses
`func (o *Widget) UnsetIncludedDataUses()`

UnsetIncludedDataUses ensures that no value is present for IncludedDataUses, not even an explicit nil
### GetIncludedScripts

`func (o *Widget) GetIncludedScripts() string`

GetIncludedScripts returns the IncludedScripts field if non-nil, zero value otherwise.

### GetIncludedScriptsOk

`func (o *Widget) GetIncludedScriptsOk() (*string, bool)`

GetIncludedScriptsOk returns a tuple with the IncludedScripts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedScripts

`func (o *Widget) SetIncludedScripts(v string)`

SetIncludedScripts sets IncludedScripts field to given value.

### HasIncludedScripts

`func (o *Widget) HasIncludedScripts() bool`

HasIncludedScripts returns a boolean if a field has been set.

### SetIncludedScriptsNil

`func (o *Widget) SetIncludedScriptsNil(b bool)`

 SetIncludedScriptsNil sets the value for IncludedScripts to be an explicit nil

### UnsetIncludedScripts
`func (o *Widget) UnsetIncludedScripts()`

UnsetIncludedScripts ensures that no value is present for IncludedScripts, not even an explicit nil
### GetIncludedCollections

`func (o *Widget) GetIncludedCollections() string`

GetIncludedCollections returns the IncludedCollections field if non-nil, zero value otherwise.

### GetIncludedCollectionsOk

`func (o *Widget) GetIncludedCollectionsOk() (*string, bool)`

GetIncludedCollectionsOk returns a tuple with the IncludedCollections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedCollections

`func (o *Widget) SetIncludedCollections(v string)`

SetIncludedCollections sets IncludedCollections field to given value.

### HasIncludedCollections

`func (o *Widget) HasIncludedCollections() bool`

HasIncludedCollections returns a boolean if a field has been set.

### SetIncludedCollectionsNil

`func (o *Widget) SetIncludedCollectionsNil(b bool)`

 SetIncludedCollectionsNil sets the value for IncludedCollections to be an explicit nil

### UnsetIncludedCollections
`func (o *Widget) UnsetIncludedCollections()`

UnsetIncludedCollections ensures that no value is present for IncludedCollections, not even an explicit nil
### GetIncludeSearchBar

`func (o *Widget) GetIncludeSearchBar() bool`

GetIncludeSearchBar returns the IncludeSearchBar field if non-nil, zero value otherwise.

### GetIncludeSearchBarOk

`func (o *Widget) GetIncludeSearchBarOk() (*bool, bool)`

GetIncludeSearchBarOk returns a tuple with the IncludeSearchBar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSearchBar

`func (o *Widget) SetIncludeSearchBar(v bool)`

SetIncludeSearchBar sets IncludeSearchBar field to given value.

### HasIncludeSearchBar

`func (o *Widget) HasIncludeSearchBar() bool`

HasIncludeSearchBar returns a boolean if a field has been set.

### GetIncludeCohortLink

`func (o *Widget) GetIncludeCohortLink() bool`

GetIncludeCohortLink returns the IncludeCohortLink field if non-nil, zero value otherwise.

### GetIncludeCohortLinkOk

`func (o *Widget) GetIncludeCohortLinkOk() (*bool, bool)`

GetIncludeCohortLinkOk returns a tuple with the IncludeCohortLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeCohortLink

`func (o *Widget) SetIncludeCohortLink(v bool)`

SetIncludeCohortLink sets IncludeCohortLink field to given value.

### HasIncludeCohortLink

`func (o *Widget) HasIncludeCohortLink() bool`

HasIncludeCohortLink returns a boolean if a field has been set.

### GetSizeWidth

`func (o *Widget) GetSizeWidth() int32`

GetSizeWidth returns the SizeWidth field if non-nil, zero value otherwise.

### GetSizeWidthOk

`func (o *Widget) GetSizeWidthOk() (*int32, bool)`

GetSizeWidthOk returns a tuple with the SizeWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeWidth

`func (o *Widget) SetSizeWidth(v int32)`

SetSizeWidth sets SizeWidth field to given value.

### HasSizeWidth

`func (o *Widget) HasSizeWidth() bool`

HasSizeWidth returns a boolean if a field has been set.

### SetSizeWidthNil

`func (o *Widget) SetSizeWidthNil(b bool)`

 SetSizeWidthNil sets the value for SizeWidth to be an explicit nil

### UnsetSizeWidth
`func (o *Widget) UnsetSizeWidth()`

UnsetSizeWidth ensures that no value is present for SizeWidth, not even an explicit nil
### GetSizeHeight

`func (o *Widget) GetSizeHeight() int32`

GetSizeHeight returns the SizeHeight field if non-nil, zero value otherwise.

### GetSizeHeightOk

`func (o *Widget) GetSizeHeightOk() (*int32, bool)`

GetSizeHeightOk returns a tuple with the SizeHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeHeight

`func (o *Widget) SetSizeHeight(v int32)`

SetSizeHeight sets SizeHeight field to given value.

### HasSizeHeight

`func (o *Widget) HasSizeHeight() bool`

HasSizeHeight returns a boolean if a field has been set.

### SetSizeHeightNil

`func (o *Widget) SetSizeHeightNil(b bool)`

 SetSizeHeightNil sets the value for SizeHeight to be an explicit nil

### UnsetSizeHeight
`func (o *Widget) UnsetSizeHeight()`

UnsetSizeHeight ensures that no value is present for SizeHeight, not even an explicit nil
### GetUnit

`func (o *Widget) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *Widget) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *Widget) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *Widget) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetKeepProportions

`func (o *Widget) GetKeepProportions() bool`

GetKeepProportions returns the KeepProportions field if non-nil, zero value otherwise.

### GetKeepProportionsOk

`func (o *Widget) GetKeepProportionsOk() (*bool, bool)`

GetKeepProportionsOk returns a tuple with the KeepProportions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepProportions

`func (o *Widget) SetKeepProportions(v bool)`

SetKeepProportions sets KeepProportions field to given value.

### HasKeepProportions

`func (o *Widget) HasKeepProportions() bool`

HasKeepProportions returns a boolean if a field has been set.

### GetWidgetName

`func (o *Widget) GetWidgetName() string`

GetWidgetName returns the WidgetName field if non-nil, zero value otherwise.

### GetWidgetNameOk

`func (o *Widget) GetWidgetNameOk() (*string, bool)`

GetWidgetNameOk returns a tuple with the WidgetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetName

`func (o *Widget) SetWidgetName(v string)`

SetWidgetName sets WidgetName field to given value.

### HasWidgetName

`func (o *Widget) HasWidgetName() bool`

HasWidgetName returns a boolean if a field has been set.

### GetPermittedDomains

`func (o *Widget) GetPermittedDomains() string`

GetPermittedDomains returns the PermittedDomains field if non-nil, zero value otherwise.

### GetPermittedDomainsOk

`func (o *Widget) GetPermittedDomainsOk() (*string, bool)`

GetPermittedDomainsOk returns a tuple with the PermittedDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermittedDomains

`func (o *Widget) SetPermittedDomains(v string)`

SetPermittedDomains sets PermittedDomains field to given value.

### HasPermittedDomains

`func (o *Widget) HasPermittedDomains() bool`

HasPermittedDomains returns a boolean if a field has been set.

### SetPermittedDomainsNil

`func (o *Widget) SetPermittedDomainsNil(b bool)`

 SetPermittedDomainsNil sets the value for PermittedDomains to be an explicit nil

### UnsetPermittedDomains
`func (o *Widget) UnsetPermittedDomains()`

UnsetPermittedDomains ensures that no value is present for PermittedDomains, not even an explicit nil
### GetBrandingPrimary

`func (o *Widget) GetBrandingPrimary() string`

GetBrandingPrimary returns the BrandingPrimary field if non-nil, zero value otherwise.

### GetBrandingPrimaryOk

`func (o *Widget) GetBrandingPrimaryOk() (*string, bool)`

GetBrandingPrimaryOk returns a tuple with the BrandingPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandingPrimary

`func (o *Widget) SetBrandingPrimary(v string)`

SetBrandingPrimary sets BrandingPrimary field to given value.

### HasBrandingPrimary

`func (o *Widget) HasBrandingPrimary() bool`

HasBrandingPrimary returns a boolean if a field has been set.

### SetBrandingPrimaryNil

`func (o *Widget) SetBrandingPrimaryNil(b bool)`

 SetBrandingPrimaryNil sets the value for BrandingPrimary to be an explicit nil

### UnsetBrandingPrimary
`func (o *Widget) UnsetBrandingPrimary()`

UnsetBrandingPrimary ensures that no value is present for BrandingPrimary, not even an explicit nil
### GetBrandingSecondary

`func (o *Widget) GetBrandingSecondary() string`

GetBrandingSecondary returns the BrandingSecondary field if non-nil, zero value otherwise.

### GetBrandingSecondaryOk

`func (o *Widget) GetBrandingSecondaryOk() (*string, bool)`

GetBrandingSecondaryOk returns a tuple with the BrandingSecondary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandingSecondary

`func (o *Widget) SetBrandingSecondary(v string)`

SetBrandingSecondary sets BrandingSecondary field to given value.

### HasBrandingSecondary

`func (o *Widget) HasBrandingSecondary() bool`

HasBrandingSecondary returns a boolean if a field has been set.

### SetBrandingSecondaryNil

`func (o *Widget) SetBrandingSecondaryNil(b bool)`

 SetBrandingSecondaryNil sets the value for BrandingSecondary to be an explicit nil

### UnsetBrandingSecondary
`func (o *Widget) UnsetBrandingSecondary()`

UnsetBrandingSecondary ensures that no value is present for BrandingSecondary, not even an explicit nil
### GetBrandingNeutral

`func (o *Widget) GetBrandingNeutral() string`

GetBrandingNeutral returns the BrandingNeutral field if non-nil, zero value otherwise.

### GetBrandingNeutralOk

`func (o *Widget) GetBrandingNeutralOk() (*string, bool)`

GetBrandingNeutralOk returns a tuple with the BrandingNeutral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandingNeutral

`func (o *Widget) SetBrandingNeutral(v string)`

SetBrandingNeutral sets BrandingNeutral field to given value.

### HasBrandingNeutral

`func (o *Widget) HasBrandingNeutral() bool`

HasBrandingNeutral returns a boolean if a field has been set.

### SetBrandingNeutralNil

`func (o *Widget) SetBrandingNeutralNil(b bool)`

 SetBrandingNeutralNil sets the value for BrandingNeutral to be an explicit nil

### UnsetBrandingNeutral
`func (o *Widget) UnsetBrandingNeutral()`

UnsetBrandingNeutral ensures that no value is present for BrandingNeutral, not even an explicit nil
### GetCreatedAt

`func (o *Widget) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Widget) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Widget) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Widget) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Widget) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Widget) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Widget) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Widget) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


