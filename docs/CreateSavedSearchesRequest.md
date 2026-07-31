# CreateSavedSearchesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**SearchEndpoint** | Pointer to **string** |  | [optional] 
**Filters** | Pointer to [**[]CreateSavedSearchesRequestFiltersInner**](CreateSavedSearchesRequestFiltersInner.md) |  | [optional] 
**Enabled** | **bool** |  | 

## Methods

### NewCreateSavedSearchesRequest

`func NewCreateSavedSearchesRequest(name string, enabled bool, ) *CreateSavedSearchesRequest`

NewCreateSavedSearchesRequest instantiates a new CreateSavedSearchesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSavedSearchesRequestWithDefaults

`func NewCreateSavedSearchesRequestWithDefaults() *CreateSavedSearchesRequest`

NewCreateSavedSearchesRequestWithDefaults instantiates a new CreateSavedSearchesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateSavedSearchesRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateSavedSearchesRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateSavedSearchesRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSearchEndpoint

`func (o *CreateSavedSearchesRequest) GetSearchEndpoint() string`

GetSearchEndpoint returns the SearchEndpoint field if non-nil, zero value otherwise.

### GetSearchEndpointOk

`func (o *CreateSavedSearchesRequest) GetSearchEndpointOk() (*string, bool)`

GetSearchEndpointOk returns a tuple with the SearchEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchEndpoint

`func (o *CreateSavedSearchesRequest) SetSearchEndpoint(v string)`

SetSearchEndpoint sets SearchEndpoint field to given value.

### HasSearchEndpoint

`func (o *CreateSavedSearchesRequest) HasSearchEndpoint() bool`

HasSearchEndpoint returns a boolean if a field has been set.

### GetFilters

`func (o *CreateSavedSearchesRequest) GetFilters() []CreateSavedSearchesRequestFiltersInner`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *CreateSavedSearchesRequest) GetFiltersOk() (*[]CreateSavedSearchesRequestFiltersInner, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *CreateSavedSearchesRequest) SetFilters(v []CreateSavedSearchesRequestFiltersInner)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *CreateSavedSearchesRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateSavedSearchesRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateSavedSearchesRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateSavedSearchesRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


