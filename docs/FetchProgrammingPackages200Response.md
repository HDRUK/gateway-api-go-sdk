# FetchProgrammingPackages200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**ProgrammingPackage**](ProgrammingPackage.md) |  | [optional] 

## Methods

### NewFetchProgrammingPackages200Response

`func NewFetchProgrammingPackages200Response() *FetchProgrammingPackages200Response`

NewFetchProgrammingPackages200Response instantiates a new FetchProgrammingPackages200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchProgrammingPackages200ResponseWithDefaults

`func NewFetchProgrammingPackages200ResponseWithDefaults() *FetchProgrammingPackages200Response`

NewFetchProgrammingPackages200ResponseWithDefaults instantiates a new FetchProgrammingPackages200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchProgrammingPackages200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchProgrammingPackages200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchProgrammingPackages200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchProgrammingPackages200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchProgrammingPackages200Response) GetData() ProgrammingPackage`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchProgrammingPackages200Response) GetDataOk() (*ProgrammingPackage, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchProgrammingPackages200Response) SetData(v ProgrammingPackage)`

SetData sets Data field to given value.

### HasData

`func (o *FetchProgrammingPackages200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


