# FetchPublications200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Publication**](Publication.md) |  | [optional] 

## Methods

### NewFetchPublications200Response

`func NewFetchPublications200Response() *FetchPublications200Response`

NewFetchPublications200Response instantiates a new FetchPublications200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchPublications200ResponseWithDefaults

`func NewFetchPublications200ResponseWithDefaults() *FetchPublications200Response`

NewFetchPublications200ResponseWithDefaults instantiates a new FetchPublications200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchPublications200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchPublications200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchPublications200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchPublications200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchPublications200Response) GetData() Publication`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchPublications200Response) GetDataOk() (*Publication, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchPublications200Response) SetData(v Publication)`

SetData sets Data field to given value.

### HasData

`func (o *FetchPublications200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


