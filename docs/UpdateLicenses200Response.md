# UpdateLicenses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**License**](License.md) |  | [optional] 

## Methods

### NewUpdateLicenses200Response

`func NewUpdateLicenses200Response() *UpdateLicenses200Response`

NewUpdateLicenses200Response instantiates a new UpdateLicenses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateLicenses200ResponseWithDefaults

`func NewUpdateLicenses200ResponseWithDefaults() *UpdateLicenses200Response`

NewUpdateLicenses200ResponseWithDefaults instantiates a new UpdateLicenses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UpdateLicenses200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UpdateLicenses200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UpdateLicenses200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UpdateLicenses200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *UpdateLicenses200Response) GetData() License`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UpdateLicenses200Response) GetDataOk() (*License, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UpdateLicenses200Response) SetData(v License)`

SetData sets Data field to given value.

### HasData

`func (o *UpdateLicenses200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


