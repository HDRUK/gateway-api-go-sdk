# UpdateWidget200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**Widget**](Widget.md) |  | [optional] 

## Methods

### NewUpdateWidget200Response

`func NewUpdateWidget200Response() *UpdateWidget200Response`

NewUpdateWidget200Response instantiates a new UpdateWidget200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateWidget200ResponseWithDefaults

`func NewUpdateWidget200ResponseWithDefaults() *UpdateWidget200Response`

NewUpdateWidget200ResponseWithDefaults instantiates a new UpdateWidget200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UpdateWidget200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UpdateWidget200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UpdateWidget200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UpdateWidget200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *UpdateWidget200Response) GetData() Widget`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UpdateWidget200Response) GetDataOk() (*Widget, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UpdateWidget200Response) SetData(v Widget)`

SetData sets Data field to given value.

### HasData

`func (o *UpdateWidget200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


