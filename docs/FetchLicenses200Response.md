# FetchLicenses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**License**](License.md) |  | [optional] 

## Methods

### NewFetchLicenses200Response

`func NewFetchLicenses200Response() *FetchLicenses200Response`

NewFetchLicenses200Response instantiates a new FetchLicenses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchLicenses200ResponseWithDefaults

`func NewFetchLicenses200ResponseWithDefaults() *FetchLicenses200Response`

NewFetchLicenses200ResponseWithDefaults instantiates a new FetchLicenses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchLicenses200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchLicenses200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchLicenses200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchLicenses200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchLicenses200Response) GetData() License`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchLicenses200Response) GetDataOk() (*License, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchLicenses200Response) SetData(v License)`

SetData sets Data field to given value.

### HasData

`func (o *FetchLicenses200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


