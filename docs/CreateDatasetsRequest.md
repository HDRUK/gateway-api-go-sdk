# CreateDatasetsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**CreateOrigin** | Pointer to **string** |  | [optional] 
**Datasetid** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateDatasetsRequest

`func NewCreateDatasetsRequest() *CreateDatasetsRequest`

NewCreateDatasetsRequest instantiates a new CreateDatasetsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDatasetsRequestWithDefaults

`func NewCreateDatasetsRequestWithDefaults() *CreateDatasetsRequest`

NewCreateDatasetsRequestWithDefaults instantiates a new CreateDatasetsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTeamId

`func (o *CreateDatasetsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *CreateDatasetsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *CreateDatasetsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *CreateDatasetsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateDatasetsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateDatasetsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateDatasetsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateDatasetsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetCreateOrigin

`func (o *CreateDatasetsRequest) GetCreateOrigin() string`

GetCreateOrigin returns the CreateOrigin field if non-nil, zero value otherwise.

### GetCreateOriginOk

`func (o *CreateDatasetsRequest) GetCreateOriginOk() (*string, bool)`

GetCreateOriginOk returns a tuple with the CreateOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateOrigin

`func (o *CreateDatasetsRequest) SetCreateOrigin(v string)`

SetCreateOrigin sets CreateOrigin field to given value.

### HasCreateOrigin

`func (o *CreateDatasetsRequest) HasCreateOrigin() bool`

HasCreateOrigin returns a boolean if a field has been set.

### GetDatasetid

`func (o *CreateDatasetsRequest) GetDatasetid() string`

GetDatasetid returns the Datasetid field if non-nil, zero value otherwise.

### GetDatasetidOk

`func (o *CreateDatasetsRequest) GetDatasetidOk() (*string, bool)`

GetDatasetidOk returns a tuple with the Datasetid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetid

`func (o *CreateDatasetsRequest) SetDatasetid(v string)`

SetDatasetid sets Datasetid field to given value.

### HasDatasetid

`func (o *CreateDatasetsRequest) HasDatasetid() bool`

HasDatasetid returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateDatasetsRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateDatasetsRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateDatasetsRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateDatasetsRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


