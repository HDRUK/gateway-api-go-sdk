# FetchAllProgrammingPackages200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]ProgrammingPackage**](ProgrammingPackage.md) |  | [optional] 

## Methods

### NewFetchAllProgrammingPackages200Response

`func NewFetchAllProgrammingPackages200Response() *FetchAllProgrammingPackages200Response`

NewFetchAllProgrammingPackages200Response instantiates a new FetchAllProgrammingPackages200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllProgrammingPackages200ResponseWithDefaults

`func NewFetchAllProgrammingPackages200ResponseWithDefaults() *FetchAllProgrammingPackages200Response`

NewFetchAllProgrammingPackages200ResponseWithDefaults instantiates a new FetchAllProgrammingPackages200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllProgrammingPackages200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllProgrammingPackages200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllProgrammingPackages200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllProgrammingPackages200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllProgrammingPackages200Response) GetData() []ProgrammingPackage`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllProgrammingPackages200Response) GetDataOk() (*[]ProgrammingPackage, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllProgrammingPackages200Response) SetData(v []ProgrammingPackage)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllProgrammingPackages200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


