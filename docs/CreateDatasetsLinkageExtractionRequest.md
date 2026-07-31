# CreateDatasetsLinkageExtractionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinId** | Pointer to **int32** | Minimum dataset ID to include in the term extraction | [optional] [default to 1]
**MaxId** | Pointer to **int32** | Maximum dataset ID to include in the term extraction. Defaults to the maximum dataset ID available. | [optional] 

## Methods

### NewCreateDatasetsLinkageExtractionRequest

`func NewCreateDatasetsLinkageExtractionRequest() *CreateDatasetsLinkageExtractionRequest`

NewCreateDatasetsLinkageExtractionRequest instantiates a new CreateDatasetsLinkageExtractionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDatasetsLinkageExtractionRequestWithDefaults

`func NewCreateDatasetsLinkageExtractionRequestWithDefaults() *CreateDatasetsLinkageExtractionRequest`

NewCreateDatasetsLinkageExtractionRequestWithDefaults instantiates a new CreateDatasetsLinkageExtractionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMinId

`func (o *CreateDatasetsLinkageExtractionRequest) GetMinId() int32`

GetMinId returns the MinId field if non-nil, zero value otherwise.

### GetMinIdOk

`func (o *CreateDatasetsLinkageExtractionRequest) GetMinIdOk() (*int32, bool)`

GetMinIdOk returns a tuple with the MinId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinId

`func (o *CreateDatasetsLinkageExtractionRequest) SetMinId(v int32)`

SetMinId sets MinId field to given value.

### HasMinId

`func (o *CreateDatasetsLinkageExtractionRequest) HasMinId() bool`

HasMinId returns a boolean if a field has been set.

### GetMaxId

`func (o *CreateDatasetsLinkageExtractionRequest) GetMaxId() int32`

GetMaxId returns the MaxId field if non-nil, zero value otherwise.

### GetMaxIdOk

`func (o *CreateDatasetsLinkageExtractionRequest) GetMaxIdOk() (*int32, bool)`

GetMaxIdOk returns a tuple with the MaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxId

`func (o *CreateDatasetsLinkageExtractionRequest) SetMaxId(v int32)`

SetMaxId sets MaxId field to given value.

### HasMaxId

`func (o *CreateDatasetsLinkageExtractionRequest) HasMaxId() bool`

HasMaxId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


