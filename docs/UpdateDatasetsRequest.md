# UpdateDatasetsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TeamId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**CreateOrigin** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewUpdateDatasetsRequest

`func NewUpdateDatasetsRequest() *UpdateDatasetsRequest`

NewUpdateDatasetsRequest instantiates a new UpdateDatasetsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDatasetsRequestWithDefaults

`func NewUpdateDatasetsRequestWithDefaults() *UpdateDatasetsRequest`

NewUpdateDatasetsRequestWithDefaults instantiates a new UpdateDatasetsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTeamId

`func (o *UpdateDatasetsRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *UpdateDatasetsRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *UpdateDatasetsRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *UpdateDatasetsRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetUserId

`func (o *UpdateDatasetsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UpdateDatasetsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UpdateDatasetsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UpdateDatasetsRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetCreateOrigin

`func (o *UpdateDatasetsRequest) GetCreateOrigin() string`

GetCreateOrigin returns the CreateOrigin field if non-nil, zero value otherwise.

### GetCreateOriginOk

`func (o *UpdateDatasetsRequest) GetCreateOriginOk() (*string, bool)`

GetCreateOriginOk returns a tuple with the CreateOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateOrigin

`func (o *UpdateDatasetsRequest) SetCreateOrigin(v string)`

SetCreateOrigin sets CreateOrigin field to given value.

### HasCreateOrigin

`func (o *UpdateDatasetsRequest) HasCreateOrigin() bool`

HasCreateOrigin returns a boolean if a field has been set.

### GetMetadata

`func (o *UpdateDatasetsRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UpdateDatasetsRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UpdateDatasetsRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UpdateDatasetsRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


