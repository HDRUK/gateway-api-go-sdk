# FetchAllReviews200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]FetchAllReviews200ResponseDataInner**](FetchAllReviews200ResponseDataInner.md) |  | [optional] 

## Methods

### NewFetchAllReviews200Response

`func NewFetchAllReviews200Response() *FetchAllReviews200Response`

NewFetchAllReviews200Response instantiates a new FetchAllReviews200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllReviews200ResponseWithDefaults

`func NewFetchAllReviews200ResponseWithDefaults() *FetchAllReviews200Response`

NewFetchAllReviews200ResponseWithDefaults instantiates a new FetchAllReviews200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllReviews200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllReviews200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllReviews200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllReviews200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllReviews200Response) GetData() []FetchAllReviews200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllReviews200Response) GetDataOk() (*[]FetchAllReviews200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllReviews200Response) SetData(v []FetchAllReviews200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllReviews200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


