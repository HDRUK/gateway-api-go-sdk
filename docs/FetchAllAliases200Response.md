# FetchAllAliases200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Alias**](Alias.md) |  | [optional] 

## Methods

### NewFetchAllAliases200Response

`func NewFetchAllAliases200Response() *FetchAllAliases200Response`

NewFetchAllAliases200Response instantiates a new FetchAllAliases200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllAliases200ResponseWithDefaults

`func NewFetchAllAliases200ResponseWithDefaults() *FetchAllAliases200Response`

NewFetchAllAliases200ResponseWithDefaults instantiates a new FetchAllAliases200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllAliases200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllAliases200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllAliases200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllAliases200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllAliases200Response) GetData() []Alias`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllAliases200Response) GetDataOk() (*[]Alias, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllAliases200Response) SetData(v []Alias)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllAliases200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


