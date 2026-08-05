# EditUsers200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**User**](User.md) |  | [optional] 

## Methods

### NewEditUsers200Response

`func NewEditUsers200Response() *EditUsers200Response`

NewEditUsers200Response instantiates a new EditUsers200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditUsers200ResponseWithDefaults

`func NewEditUsers200ResponseWithDefaults() *EditUsers200Response`

NewEditUsers200ResponseWithDefaults instantiates a new EditUsers200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *EditUsers200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *EditUsers200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *EditUsers200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *EditUsers200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *EditUsers200Response) GetData() User`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *EditUsers200Response) GetDataOk() (*User, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *EditUsers200Response) SetData(v User)`

SetData sets Data field to given value.

### HasData

`func (o *EditUsers200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


