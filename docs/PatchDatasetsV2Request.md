# PatchDatasetsV2Request

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreateOrigin** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewPatchDatasetsV2Request

`func NewPatchDatasetsV2Request() *PatchDatasetsV2Request`

NewPatchDatasetsV2Request instantiates a new PatchDatasetsV2Request object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchDatasetsV2RequestWithDefaults

`func NewPatchDatasetsV2RequestWithDefaults() *PatchDatasetsV2Request`

NewPatchDatasetsV2RequestWithDefaults instantiates a new PatchDatasetsV2Request object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreateOrigin

`func (o *PatchDatasetsV2Request) GetCreateOrigin() string`

GetCreateOrigin returns the CreateOrigin field if non-nil, zero value otherwise.

### GetCreateOriginOk

`func (o *PatchDatasetsV2Request) GetCreateOriginOk() (*string, bool)`

GetCreateOriginOk returns a tuple with the CreateOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateOrigin

`func (o *PatchDatasetsV2Request) SetCreateOrigin(v string)`

SetCreateOrigin sets CreateOrigin field to given value.

### HasCreateOrigin

`func (o *PatchDatasetsV2Request) HasCreateOrigin() bool`

HasCreateOrigin returns a boolean if a field has been set.

### GetMetadata

`func (o *PatchDatasetsV2Request) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PatchDatasetsV2Request) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PatchDatasetsV2Request) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *PatchDatasetsV2Request) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


