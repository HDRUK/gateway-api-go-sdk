# FetchApplications200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]FetchApplications200ResponseDataInner**](FetchApplications200ResponseDataInner.md) |  | [optional] 

## Methods

### NewFetchApplications200Response

`func NewFetchApplications200Response() *FetchApplications200Response`

NewFetchApplications200Response instantiates a new FetchApplications200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchApplications200ResponseWithDefaults

`func NewFetchApplications200ResponseWithDefaults() *FetchApplications200Response`

NewFetchApplications200ResponseWithDefaults instantiates a new FetchApplications200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchApplications200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchApplications200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchApplications200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchApplications200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchApplications200Response) GetData() []FetchApplications200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchApplications200Response) GetDataOk() (*[]FetchApplications200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchApplications200Response) SetData(v []FetchApplications200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *FetchApplications200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


