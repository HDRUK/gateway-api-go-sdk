# CreateDatasetsTermExtractionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Partial** | Pointer to **bool** | Flag to determine if term extraction should be partial (true) or full (false) | [optional] [default to true]
**MinId** | Pointer to **int32** | Minimum dataset ID to include in the term extraction | [optional] [default to 1]
**MaxId** | Pointer to **int32** | Maximum dataset ID to include in the term extraction. Defaults to the maximum dataset ID available. | [optional] 
**IndexElastic** | Pointer to **bool** | Flag to determine if data should be indexed in Elasticsearch | [optional] [default to true]

## Methods

### NewCreateDatasetsTermExtractionRequest

`func NewCreateDatasetsTermExtractionRequest() *CreateDatasetsTermExtractionRequest`

NewCreateDatasetsTermExtractionRequest instantiates a new CreateDatasetsTermExtractionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDatasetsTermExtractionRequestWithDefaults

`func NewCreateDatasetsTermExtractionRequestWithDefaults() *CreateDatasetsTermExtractionRequest`

NewCreateDatasetsTermExtractionRequestWithDefaults instantiates a new CreateDatasetsTermExtractionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartial

`func (o *CreateDatasetsTermExtractionRequest) GetPartial() bool`

GetPartial returns the Partial field if non-nil, zero value otherwise.

### GetPartialOk

`func (o *CreateDatasetsTermExtractionRequest) GetPartialOk() (*bool, bool)`

GetPartialOk returns a tuple with the Partial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartial

`func (o *CreateDatasetsTermExtractionRequest) SetPartial(v bool)`

SetPartial sets Partial field to given value.

### HasPartial

`func (o *CreateDatasetsTermExtractionRequest) HasPartial() bool`

HasPartial returns a boolean if a field has been set.

### GetMinId

`func (o *CreateDatasetsTermExtractionRequest) GetMinId() int32`

GetMinId returns the MinId field if non-nil, zero value otherwise.

### GetMinIdOk

`func (o *CreateDatasetsTermExtractionRequest) GetMinIdOk() (*int32, bool)`

GetMinIdOk returns a tuple with the MinId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinId

`func (o *CreateDatasetsTermExtractionRequest) SetMinId(v int32)`

SetMinId sets MinId field to given value.

### HasMinId

`func (o *CreateDatasetsTermExtractionRequest) HasMinId() bool`

HasMinId returns a boolean if a field has been set.

### GetMaxId

`func (o *CreateDatasetsTermExtractionRequest) GetMaxId() int32`

GetMaxId returns the MaxId field if non-nil, zero value otherwise.

### GetMaxIdOk

`func (o *CreateDatasetsTermExtractionRequest) GetMaxIdOk() (*int32, bool)`

GetMaxIdOk returns a tuple with the MaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxId

`func (o *CreateDatasetsTermExtractionRequest) SetMaxId(v int32)`

SetMaxId sets MaxId field to given value.

### HasMaxId

`func (o *CreateDatasetsTermExtractionRequest) HasMaxId() bool`

HasMaxId returns a boolean if a field has been set.

### GetIndexElastic

`func (o *CreateDatasetsTermExtractionRequest) GetIndexElastic() bool`

GetIndexElastic returns the IndexElastic field if non-nil, zero value otherwise.

### GetIndexElasticOk

`func (o *CreateDatasetsTermExtractionRequest) GetIndexElasticOk() (*bool, bool)`

GetIndexElasticOk returns a tuple with the IndexElastic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndexElastic

`func (o *CreateDatasetsTermExtractionRequest) SetIndexElastic(v bool)`

SetIndexElastic sets IndexElastic field to given value.

### HasIndexElastic

`func (o *CreateDatasetsTermExtractionRequest) HasIndexElastic() bool`

HasIndexElastic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


