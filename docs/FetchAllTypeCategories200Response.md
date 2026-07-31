# FetchAllTypeCategories200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]TypeCategory**](TypeCategory.md) |  | [optional] 

## Methods

### NewFetchAllTypeCategories200Response

`func NewFetchAllTypeCategories200Response() *FetchAllTypeCategories200Response`

NewFetchAllTypeCategories200Response instantiates a new FetchAllTypeCategories200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllTypeCategories200ResponseWithDefaults

`func NewFetchAllTypeCategories200ResponseWithDefaults() *FetchAllTypeCategories200Response`

NewFetchAllTypeCategories200ResponseWithDefaults instantiates a new FetchAllTypeCategories200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllTypeCategories200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllTypeCategories200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllTypeCategories200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllTypeCategories200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllTypeCategories200Response) GetData() []TypeCategory`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllTypeCategories200Response) GetDataOk() (*[]TypeCategory, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllTypeCategories200Response) SetData(v []TypeCategory)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllTypeCategories200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


