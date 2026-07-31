# FetchAllSavedSearches200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]SavedSearch**](SavedSearch.md) |  | [optional] 

## Methods

### NewFetchAllSavedSearches200Response

`func NewFetchAllSavedSearches200Response() *FetchAllSavedSearches200Response`

NewFetchAllSavedSearches200Response instantiates a new FetchAllSavedSearches200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllSavedSearches200ResponseWithDefaults

`func NewFetchAllSavedSearches200ResponseWithDefaults() *FetchAllSavedSearches200Response`

NewFetchAllSavedSearches200ResponseWithDefaults instantiates a new FetchAllSavedSearches200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllSavedSearches200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllSavedSearches200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllSavedSearches200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllSavedSearches200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllSavedSearches200Response) GetData() []SavedSearch`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllSavedSearches200Response) GetDataOk() (*[]SavedSearch, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllSavedSearches200Response) SetData(v []SavedSearch)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllSavedSearches200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


