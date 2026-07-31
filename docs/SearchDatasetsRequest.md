# SearchDatasetsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** |  | [optional] 
**Sort** | Pointer to **string** |  | [optional] 
**Direction** | Pointer to **string** |  | [optional] 
**Filters** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 

## Methods

### NewSearchDatasetsRequest

`func NewSearchDatasetsRequest() *SearchDatasetsRequest`

NewSearchDatasetsRequest instantiates a new SearchDatasetsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchDatasetsRequestWithDefaults

`func NewSearchDatasetsRequestWithDefaults() *SearchDatasetsRequest`

NewSearchDatasetsRequestWithDefaults instantiates a new SearchDatasetsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchDatasetsRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchDatasetsRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchDatasetsRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SearchDatasetsRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetSort

`func (o *SearchDatasetsRequest) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *SearchDatasetsRequest) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *SearchDatasetsRequest) SetSort(v string)`

SetSort sets Sort field to given value.

### HasSort

`func (o *SearchDatasetsRequest) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetDirection

`func (o *SearchDatasetsRequest) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *SearchDatasetsRequest) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *SearchDatasetsRequest) SetDirection(v string)`

SetDirection sets Direction field to given value.

### HasDirection

`func (o *SearchDatasetsRequest) HasDirection() bool`

HasDirection returns a boolean if a field has been set.

### GetFilters

`func (o *SearchDatasetsRequest) GetFilters() string`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *SearchDatasetsRequest) GetFiltersOk() (*string, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *SearchDatasetsRequest) SetFilters(v string)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *SearchDatasetsRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetPerPage

`func (o *SearchDatasetsRequest) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SearchDatasetsRequest) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SearchDatasetsRequest) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *SearchDatasetsRequest) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


