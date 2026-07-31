# FetchCollections200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Collection**](Collection.md) |  | [optional] 

## Methods

### NewFetchCollections200Response

`func NewFetchCollections200Response() *FetchCollections200Response`

NewFetchCollections200Response instantiates a new FetchCollections200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchCollections200ResponseWithDefaults

`func NewFetchCollections200ResponseWithDefaults() *FetchCollections200Response`

NewFetchCollections200ResponseWithDefaults instantiates a new FetchCollections200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchCollections200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchCollections200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchCollections200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchCollections200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchCollections200Response) GetData() Collection`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchCollections200Response) GetDataOk() (*Collection, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchCollections200Response) SetData(v Collection)`

SetData sets Data field to given value.

### HasData

`func (o *FetchCollections200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


