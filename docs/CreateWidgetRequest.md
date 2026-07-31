# CreateWidgetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WidgetName** | **string** |  | 
**SizeWidth** | Pointer to **int32** |  | [optional] 
**SizeHeight** | Pointer to **int32** |  | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**IncludeSearchBar** | Pointer to **bool** |  | [optional] 
**IncludeCohortLink** | Pointer to **bool** |  | [optional] 
**KeepProportions** | Pointer to **bool** |  | [optional] 
**PermittedDomains** | Pointer to **[]string** |  | [optional] 
**IncludedDatasets** | Pointer to **[]int32** |  | [optional] 
**IncludedDataUses** | Pointer to **[]int32** |  | [optional] 
**IncludedScripts** | Pointer to **[]int32** |  | [optional] 
**IncludedCollections** | Pointer to **[]int32** |  | [optional] 
**DataCustodianEntitiesIds** | Pointer to **[]int32** |  | [optional] 

## Methods

### NewCreateWidgetRequest

`func NewCreateWidgetRequest(widgetName string, ) *CreateWidgetRequest`

NewCreateWidgetRequest instantiates a new CreateWidgetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWidgetRequestWithDefaults

`func NewCreateWidgetRequestWithDefaults() *CreateWidgetRequest`

NewCreateWidgetRequestWithDefaults instantiates a new CreateWidgetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidgetName

`func (o *CreateWidgetRequest) GetWidgetName() string`

GetWidgetName returns the WidgetName field if non-nil, zero value otherwise.

### GetWidgetNameOk

`func (o *CreateWidgetRequest) GetWidgetNameOk() (*string, bool)`

GetWidgetNameOk returns a tuple with the WidgetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetName

`func (o *CreateWidgetRequest) SetWidgetName(v string)`

SetWidgetName sets WidgetName field to given value.


### GetSizeWidth

`func (o *CreateWidgetRequest) GetSizeWidth() int32`

GetSizeWidth returns the SizeWidth field if non-nil, zero value otherwise.

### GetSizeWidthOk

`func (o *CreateWidgetRequest) GetSizeWidthOk() (*int32, bool)`

GetSizeWidthOk returns a tuple with the SizeWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeWidth

`func (o *CreateWidgetRequest) SetSizeWidth(v int32)`

SetSizeWidth sets SizeWidth field to given value.

### HasSizeWidth

`func (o *CreateWidgetRequest) HasSizeWidth() bool`

HasSizeWidth returns a boolean if a field has been set.

### GetSizeHeight

`func (o *CreateWidgetRequest) GetSizeHeight() int32`

GetSizeHeight returns the SizeHeight field if non-nil, zero value otherwise.

### GetSizeHeightOk

`func (o *CreateWidgetRequest) GetSizeHeightOk() (*int32, bool)`

GetSizeHeightOk returns a tuple with the SizeHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeHeight

`func (o *CreateWidgetRequest) SetSizeHeight(v int32)`

SetSizeHeight sets SizeHeight field to given value.

### HasSizeHeight

`func (o *CreateWidgetRequest) HasSizeHeight() bool`

HasSizeHeight returns a boolean if a field has been set.

### GetUnit

`func (o *CreateWidgetRequest) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *CreateWidgetRequest) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *CreateWidgetRequest) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *CreateWidgetRequest) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetIncludeSearchBar

`func (o *CreateWidgetRequest) GetIncludeSearchBar() bool`

GetIncludeSearchBar returns the IncludeSearchBar field if non-nil, zero value otherwise.

### GetIncludeSearchBarOk

`func (o *CreateWidgetRequest) GetIncludeSearchBarOk() (*bool, bool)`

GetIncludeSearchBarOk returns a tuple with the IncludeSearchBar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSearchBar

`func (o *CreateWidgetRequest) SetIncludeSearchBar(v bool)`

SetIncludeSearchBar sets IncludeSearchBar field to given value.

### HasIncludeSearchBar

`func (o *CreateWidgetRequest) HasIncludeSearchBar() bool`

HasIncludeSearchBar returns a boolean if a field has been set.

### GetIncludeCohortLink

`func (o *CreateWidgetRequest) GetIncludeCohortLink() bool`

GetIncludeCohortLink returns the IncludeCohortLink field if non-nil, zero value otherwise.

### GetIncludeCohortLinkOk

`func (o *CreateWidgetRequest) GetIncludeCohortLinkOk() (*bool, bool)`

GetIncludeCohortLinkOk returns a tuple with the IncludeCohortLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeCohortLink

`func (o *CreateWidgetRequest) SetIncludeCohortLink(v bool)`

SetIncludeCohortLink sets IncludeCohortLink field to given value.

### HasIncludeCohortLink

`func (o *CreateWidgetRequest) HasIncludeCohortLink() bool`

HasIncludeCohortLink returns a boolean if a field has been set.

### GetKeepProportions

`func (o *CreateWidgetRequest) GetKeepProportions() bool`

GetKeepProportions returns the KeepProportions field if non-nil, zero value otherwise.

### GetKeepProportionsOk

`func (o *CreateWidgetRequest) GetKeepProportionsOk() (*bool, bool)`

GetKeepProportionsOk returns a tuple with the KeepProportions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepProportions

`func (o *CreateWidgetRequest) SetKeepProportions(v bool)`

SetKeepProportions sets KeepProportions field to given value.

### HasKeepProportions

`func (o *CreateWidgetRequest) HasKeepProportions() bool`

HasKeepProportions returns a boolean if a field has been set.

### GetPermittedDomains

`func (o *CreateWidgetRequest) GetPermittedDomains() []string`

GetPermittedDomains returns the PermittedDomains field if non-nil, zero value otherwise.

### GetPermittedDomainsOk

`func (o *CreateWidgetRequest) GetPermittedDomainsOk() (*[]string, bool)`

GetPermittedDomainsOk returns a tuple with the PermittedDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermittedDomains

`func (o *CreateWidgetRequest) SetPermittedDomains(v []string)`

SetPermittedDomains sets PermittedDomains field to given value.

### HasPermittedDomains

`func (o *CreateWidgetRequest) HasPermittedDomains() bool`

HasPermittedDomains returns a boolean if a field has been set.

### GetIncludedDatasets

`func (o *CreateWidgetRequest) GetIncludedDatasets() []int32`

GetIncludedDatasets returns the IncludedDatasets field if non-nil, zero value otherwise.

### GetIncludedDatasetsOk

`func (o *CreateWidgetRequest) GetIncludedDatasetsOk() (*[]int32, bool)`

GetIncludedDatasetsOk returns a tuple with the IncludedDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedDatasets

`func (o *CreateWidgetRequest) SetIncludedDatasets(v []int32)`

SetIncludedDatasets sets IncludedDatasets field to given value.

### HasIncludedDatasets

`func (o *CreateWidgetRequest) HasIncludedDatasets() bool`

HasIncludedDatasets returns a boolean if a field has been set.

### GetIncludedDataUses

`func (o *CreateWidgetRequest) GetIncludedDataUses() []int32`

GetIncludedDataUses returns the IncludedDataUses field if non-nil, zero value otherwise.

### GetIncludedDataUsesOk

`func (o *CreateWidgetRequest) GetIncludedDataUsesOk() (*[]int32, bool)`

GetIncludedDataUsesOk returns a tuple with the IncludedDataUses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedDataUses

`func (o *CreateWidgetRequest) SetIncludedDataUses(v []int32)`

SetIncludedDataUses sets IncludedDataUses field to given value.

### HasIncludedDataUses

`func (o *CreateWidgetRequest) HasIncludedDataUses() bool`

HasIncludedDataUses returns a boolean if a field has been set.

### GetIncludedScripts

`func (o *CreateWidgetRequest) GetIncludedScripts() []int32`

GetIncludedScripts returns the IncludedScripts field if non-nil, zero value otherwise.

### GetIncludedScriptsOk

`func (o *CreateWidgetRequest) GetIncludedScriptsOk() (*[]int32, bool)`

GetIncludedScriptsOk returns a tuple with the IncludedScripts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedScripts

`func (o *CreateWidgetRequest) SetIncludedScripts(v []int32)`

SetIncludedScripts sets IncludedScripts field to given value.

### HasIncludedScripts

`func (o *CreateWidgetRequest) HasIncludedScripts() bool`

HasIncludedScripts returns a boolean if a field has been set.

### GetIncludedCollections

`func (o *CreateWidgetRequest) GetIncludedCollections() []int32`

GetIncludedCollections returns the IncludedCollections field if non-nil, zero value otherwise.

### GetIncludedCollectionsOk

`func (o *CreateWidgetRequest) GetIncludedCollectionsOk() (*[]int32, bool)`

GetIncludedCollectionsOk returns a tuple with the IncludedCollections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludedCollections

`func (o *CreateWidgetRequest) SetIncludedCollections(v []int32)`

SetIncludedCollections sets IncludedCollections field to given value.

### HasIncludedCollections

`func (o *CreateWidgetRequest) HasIncludedCollections() bool`

HasIncludedCollections returns a boolean if a field has been set.

### GetDataCustodianEntitiesIds

`func (o *CreateWidgetRequest) GetDataCustodianEntitiesIds() []int32`

GetDataCustodianEntitiesIds returns the DataCustodianEntitiesIds field if non-nil, zero value otherwise.

### GetDataCustodianEntitiesIdsOk

`func (o *CreateWidgetRequest) GetDataCustodianEntitiesIdsOk() (*[]int32, bool)`

GetDataCustodianEntitiesIdsOk returns a tuple with the DataCustodianEntitiesIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCustodianEntitiesIds

`func (o *CreateWidgetRequest) SetDataCustodianEntitiesIds(v []int32)`

SetDataCustodianEntitiesIds sets DataCustodianEntitiesIds field to given value.

### HasDataCustodianEntitiesIds

`func (o *CreateWidgetRequest) HasDataCustodianEntitiesIds() bool`

HasDataCustodianEntitiesIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


