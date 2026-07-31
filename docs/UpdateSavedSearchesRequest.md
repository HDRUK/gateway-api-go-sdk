# UpdateSavedSearchesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**SearchEndpoint** | Pointer to **string** |  | [optional] 
**Filters** | Pointer to [**[]CreateSavedSearchesRequestFiltersInner**](CreateSavedSearchesRequestFiltersInner.md) |  | [optional] 
**Enabled** | **string** |  | 

## Methods

### NewUpdateSavedSearchesRequest

`func NewUpdateSavedSearchesRequest(name string, enabled string, ) *UpdateSavedSearchesRequest`

NewUpdateSavedSearchesRequest instantiates a new UpdateSavedSearchesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateSavedSearchesRequestWithDefaults

`func NewUpdateSavedSearchesRequestWithDefaults() *UpdateSavedSearchesRequest`

NewUpdateSavedSearchesRequestWithDefaults instantiates a new UpdateSavedSearchesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateSavedSearchesRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateSavedSearchesRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateSavedSearchesRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSearchEndpoint

`func (o *UpdateSavedSearchesRequest) GetSearchEndpoint() string`

GetSearchEndpoint returns the SearchEndpoint field if non-nil, zero value otherwise.

### GetSearchEndpointOk

`func (o *UpdateSavedSearchesRequest) GetSearchEndpointOk() (*string, bool)`

GetSearchEndpointOk returns a tuple with the SearchEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchEndpoint

`func (o *UpdateSavedSearchesRequest) SetSearchEndpoint(v string)`

SetSearchEndpoint sets SearchEndpoint field to given value.

### HasSearchEndpoint

`func (o *UpdateSavedSearchesRequest) HasSearchEndpoint() bool`

HasSearchEndpoint returns a boolean if a field has been set.

### GetFilters

`func (o *UpdateSavedSearchesRequest) GetFilters() []CreateSavedSearchesRequestFiltersInner`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *UpdateSavedSearchesRequest) GetFiltersOk() (*[]CreateSavedSearchesRequestFiltersInner, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *UpdateSavedSearchesRequest) SetFilters(v []CreateSavedSearchesRequestFiltersInner)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *UpdateSavedSearchesRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateSavedSearchesRequest) GetEnabled() string`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateSavedSearchesRequest) GetEnabledOk() (*string, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateSavedSearchesRequest) SetEnabled(v string)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


