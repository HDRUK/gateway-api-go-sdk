# CreateApplications200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]CreateApplications200ResponseDataInner**](CreateApplications200ResponseDataInner.md) |  | [optional] 

## Methods

### NewCreateApplications200Response

`func NewCreateApplications200Response() *CreateApplications200Response`

NewCreateApplications200Response instantiates a new CreateApplications200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApplications200ResponseWithDefaults

`func NewCreateApplications200ResponseWithDefaults() *CreateApplications200Response`

NewCreateApplications200ResponseWithDefaults instantiates a new CreateApplications200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CreateApplications200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateApplications200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateApplications200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CreateApplications200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *CreateApplications200Response) GetData() []CreateApplications200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateApplications200Response) GetDataOk() (*[]CreateApplications200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateApplications200Response) SetData(v []CreateApplications200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *CreateApplications200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


