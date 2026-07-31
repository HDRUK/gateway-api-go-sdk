# EditSavedSearchesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Filters** | Pointer to [**[]CreateSavedSearchesRequestFiltersInner**](CreateSavedSearchesRequestFiltersInner.md) |  | [optional] 
**Enabled** | Pointer to **string** |  | [optional] 

## Methods

### NewEditSavedSearchesRequest

`func NewEditSavedSearchesRequest() *EditSavedSearchesRequest`

NewEditSavedSearchesRequest instantiates a new EditSavedSearchesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditSavedSearchesRequestWithDefaults

`func NewEditSavedSearchesRequestWithDefaults() *EditSavedSearchesRequest`

NewEditSavedSearchesRequestWithDefaults instantiates a new EditSavedSearchesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *EditSavedSearchesRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EditSavedSearchesRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EditSavedSearchesRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EditSavedSearchesRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetFilters

`func (o *EditSavedSearchesRequest) GetFilters() []CreateSavedSearchesRequestFiltersInner`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *EditSavedSearchesRequest) GetFiltersOk() (*[]CreateSavedSearchesRequestFiltersInner, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *EditSavedSearchesRequest) SetFilters(v []CreateSavedSearchesRequestFiltersInner)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *EditSavedSearchesRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetEnabled

`func (o *EditSavedSearchesRequest) GetEnabled() string`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditSavedSearchesRequest) GetEnabledOk() (*string, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditSavedSearchesRequest) SetEnabled(v string)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditSavedSearchesRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


