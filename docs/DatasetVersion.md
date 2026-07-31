# DatasetVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**DatasetId** | Pointer to **int32** |  | [optional] 
**Version** | Pointer to **int32** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**ShortTitle** | Pointer to **NullableString** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Full GWDM-format metadata document for this version | [optional] 
**Patch** | Pointer to **[]map[string]interface{}** | RFC 6902 JSON Patch array used to reconstruct this version from the previous snapshot. Null for full snapshots (v1 and every 10th version). | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewDatasetVersion

`func NewDatasetVersion() *DatasetVersion`

NewDatasetVersion instantiates a new DatasetVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatasetVersionWithDefaults

`func NewDatasetVersionWithDefaults() *DatasetVersion`

NewDatasetVersionWithDefaults instantiates a new DatasetVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DatasetVersion) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DatasetVersion) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DatasetVersion) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DatasetVersion) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDatasetId

`func (o *DatasetVersion) GetDatasetId() int32`

GetDatasetId returns the DatasetId field if non-nil, zero value otherwise.

### GetDatasetIdOk

`func (o *DatasetVersion) GetDatasetIdOk() (*int32, bool)`

GetDatasetIdOk returns a tuple with the DatasetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetId

`func (o *DatasetVersion) SetDatasetId(v int32)`

SetDatasetId sets DatasetId field to given value.

### HasDatasetId

`func (o *DatasetVersion) HasDatasetId() bool`

HasDatasetId returns a boolean if a field has been set.

### GetVersion

`func (o *DatasetVersion) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DatasetVersion) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DatasetVersion) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *DatasetVersion) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetTitle

`func (o *DatasetVersion) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DatasetVersion) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DatasetVersion) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *DatasetVersion) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *DatasetVersion) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *DatasetVersion) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetShortTitle

`func (o *DatasetVersion) GetShortTitle() string`

GetShortTitle returns the ShortTitle field if non-nil, zero value otherwise.

### GetShortTitleOk

`func (o *DatasetVersion) GetShortTitleOk() (*string, bool)`

GetShortTitleOk returns a tuple with the ShortTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortTitle

`func (o *DatasetVersion) SetShortTitle(v string)`

SetShortTitle sets ShortTitle field to given value.

### HasShortTitle

`func (o *DatasetVersion) HasShortTitle() bool`

HasShortTitle returns a boolean if a field has been set.

### SetShortTitleNil

`func (o *DatasetVersion) SetShortTitleNil(b bool)`

 SetShortTitleNil sets the value for ShortTitle to be an explicit nil

### UnsetShortTitle
`func (o *DatasetVersion) UnsetShortTitle()`

UnsetShortTitle ensures that no value is present for ShortTitle, not even an explicit nil
### GetMetadata

`func (o *DatasetVersion) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DatasetVersion) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DatasetVersion) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DatasetVersion) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *DatasetVersion) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DatasetVersion) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetPatch

`func (o *DatasetVersion) GetPatch() []map[string]interface{}`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *DatasetVersion) GetPatchOk() (*[]map[string]interface{}, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *DatasetVersion) SetPatch(v []map[string]interface{})`

SetPatch sets Patch field to given value.

### HasPatch

`func (o *DatasetVersion) HasPatch() bool`

HasPatch returns a boolean if a field has been set.

### SetPatchNil

`func (o *DatasetVersion) SetPatchNil(b bool)`

 SetPatchNil sets the value for Patch to be an explicit nil

### UnsetPatch
`func (o *DatasetVersion) UnsetPatch()`

UnsetPatch ensures that no value is present for Patch, not even an explicit nil
### GetCreatedAt

`func (o *DatasetVersion) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DatasetVersion) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DatasetVersion) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DatasetVersion) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DatasetVersion) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DatasetVersion) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DatasetVersion) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DatasetVersion) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


