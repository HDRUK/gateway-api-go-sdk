# SavedSearch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **NullableInt32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SearchTerm** | Pointer to **NullableString** |  | [optional] 
**SearchEndpoint** | Pointer to **NullableString** |  | [optional] 
**SortOrder** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewSavedSearch

`func NewSavedSearch() *SavedSearch`

NewSavedSearch instantiates a new SavedSearch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSavedSearchWithDefaults

`func NewSavedSearchWithDefaults() *SavedSearch`

NewSavedSearchWithDefaults instantiates a new SavedSearch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SavedSearch) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SavedSearch) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SavedSearch) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SavedSearch) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUserId

`func (o *SavedSearch) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SavedSearch) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SavedSearch) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *SavedSearch) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *SavedSearch) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *SavedSearch) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetName

`func (o *SavedSearch) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SavedSearch) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SavedSearch) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SavedSearch) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSearchTerm

`func (o *SavedSearch) GetSearchTerm() string`

GetSearchTerm returns the SearchTerm field if non-nil, zero value otherwise.

### GetSearchTermOk

`func (o *SavedSearch) GetSearchTermOk() (*string, bool)`

GetSearchTermOk returns a tuple with the SearchTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchTerm

`func (o *SavedSearch) SetSearchTerm(v string)`

SetSearchTerm sets SearchTerm field to given value.

### HasSearchTerm

`func (o *SavedSearch) HasSearchTerm() bool`

HasSearchTerm returns a boolean if a field has been set.

### SetSearchTermNil

`func (o *SavedSearch) SetSearchTermNil(b bool)`

 SetSearchTermNil sets the value for SearchTerm to be an explicit nil

### UnsetSearchTerm
`func (o *SavedSearch) UnsetSearchTerm()`

UnsetSearchTerm ensures that no value is present for SearchTerm, not even an explicit nil
### GetSearchEndpoint

`func (o *SavedSearch) GetSearchEndpoint() string`

GetSearchEndpoint returns the SearchEndpoint field if non-nil, zero value otherwise.

### GetSearchEndpointOk

`func (o *SavedSearch) GetSearchEndpointOk() (*string, bool)`

GetSearchEndpointOk returns a tuple with the SearchEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchEndpoint

`func (o *SavedSearch) SetSearchEndpoint(v string)`

SetSearchEndpoint sets SearchEndpoint field to given value.

### HasSearchEndpoint

`func (o *SavedSearch) HasSearchEndpoint() bool`

HasSearchEndpoint returns a boolean if a field has been set.

### SetSearchEndpointNil

`func (o *SavedSearch) SetSearchEndpointNil(b bool)`

 SetSearchEndpointNil sets the value for SearchEndpoint to be an explicit nil

### UnsetSearchEndpoint
`func (o *SavedSearch) UnsetSearchEndpoint()`

UnsetSearchEndpoint ensures that no value is present for SearchEndpoint, not even an explicit nil
### GetSortOrder

`func (o *SavedSearch) GetSortOrder() string`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *SavedSearch) GetSortOrderOk() (*string, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *SavedSearch) SetSortOrder(v string)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *SavedSearch) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### GetEnabled

`func (o *SavedSearch) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SavedSearch) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SavedSearch) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *SavedSearch) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SavedSearch) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SavedSearch) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SavedSearch) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SavedSearch) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *SavedSearch) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SavedSearch) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SavedSearch) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SavedSearch) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *SavedSearch) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SavedSearch) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SavedSearch) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *SavedSearch) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *SavedSearch) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SavedSearch) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


