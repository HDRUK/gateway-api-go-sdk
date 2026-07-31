# FetchDatasets200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Dataset**](Dataset.md) |  | [optional] 

## Methods

### NewFetchDatasets200Response

`func NewFetchDatasets200Response() *FetchDatasets200Response`

NewFetchDatasets200Response instantiates a new FetchDatasets200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchDatasets200ResponseWithDefaults

`func NewFetchDatasets200ResponseWithDefaults() *FetchDatasets200Response`

NewFetchDatasets200ResponseWithDefaults instantiates a new FetchDatasets200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchDatasets200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchDatasets200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchDatasets200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchDatasets200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchDatasets200Response) GetData() Dataset`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchDatasets200Response) GetDataOk() (*Dataset, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchDatasets200Response) SetData(v Dataset)`

SetData sets Data field to given value.

### HasData

`func (o *FetchDatasets200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


