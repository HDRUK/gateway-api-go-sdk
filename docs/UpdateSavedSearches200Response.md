# UpdateSavedSearches200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**SavedSearch**](SavedSearch.md) |  | [optional] 

## Methods

### NewUpdateSavedSearches200Response

`func NewUpdateSavedSearches200Response() *UpdateSavedSearches200Response`

NewUpdateSavedSearches200Response instantiates a new UpdateSavedSearches200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateSavedSearches200ResponseWithDefaults

`func NewUpdateSavedSearches200ResponseWithDefaults() *UpdateSavedSearches200Response`

NewUpdateSavedSearches200ResponseWithDefaults instantiates a new UpdateSavedSearches200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UpdateSavedSearches200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UpdateSavedSearches200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UpdateSavedSearches200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UpdateSavedSearches200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *UpdateSavedSearches200Response) GetData() SavedSearch`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UpdateSavedSearches200Response) GetDataOk() (*SavedSearch, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UpdateSavedSearches200Response) SetData(v SavedSearch)`

SetData sets Data field to given value.

### HasData

`func (o *UpdateSavedSearches200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


