# Dataset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **NullableInt32** |  | [optional] 
**TeamId** | Pointer to **NullableInt32** |  | [optional] 
**Pid** | Pointer to **NullableString** |  | [optional] 
**Datasetid** | Pointer to **NullableString** |  | [optional] 
**Version** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**CreateOrigin** | Pointer to **NullableString** |  | [optional] 
**IsCohortDiscovery** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewDataset

`func NewDataset() *Dataset`

NewDataset instantiates a new Dataset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatasetWithDefaults

`func NewDatasetWithDefaults() *Dataset`

NewDatasetWithDefaults instantiates a new Dataset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Dataset) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Dataset) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Dataset) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Dataset) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUserId

`func (o *Dataset) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Dataset) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Dataset) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Dataset) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *Dataset) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *Dataset) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetTeamId

`func (o *Dataset) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Dataset) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Dataset) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Dataset) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### SetTeamIdNil

`func (o *Dataset) SetTeamIdNil(b bool)`

 SetTeamIdNil sets the value for TeamId to be an explicit nil

### UnsetTeamId
`func (o *Dataset) UnsetTeamId()`

UnsetTeamId ensures that no value is present for TeamId, not even an explicit nil
### GetPid

`func (o *Dataset) GetPid() string`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *Dataset) GetPidOk() (*string, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *Dataset) SetPid(v string)`

SetPid sets Pid field to given value.

### HasPid

`func (o *Dataset) HasPid() bool`

HasPid returns a boolean if a field has been set.

### SetPidNil

`func (o *Dataset) SetPidNil(b bool)`

 SetPidNil sets the value for Pid to be an explicit nil

### UnsetPid
`func (o *Dataset) UnsetPid()`

UnsetPid ensures that no value is present for Pid, not even an explicit nil
### GetDatasetid

`func (o *Dataset) GetDatasetid() string`

GetDatasetid returns the Datasetid field if non-nil, zero value otherwise.

### GetDatasetidOk

`func (o *Dataset) GetDatasetidOk() (*string, bool)`

GetDatasetidOk returns a tuple with the Datasetid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetid

`func (o *Dataset) SetDatasetid(v string)`

SetDatasetid sets Datasetid field to given value.

### HasDatasetid

`func (o *Dataset) HasDatasetid() bool`

HasDatasetid returns a boolean if a field has been set.

### SetDatasetidNil

`func (o *Dataset) SetDatasetidNil(b bool)`

 SetDatasetidNil sets the value for Datasetid to be an explicit nil

### UnsetDatasetid
`func (o *Dataset) UnsetDatasetid()`

UnsetDatasetid ensures that no value is present for Datasetid, not even an explicit nil
### GetVersion

`func (o *Dataset) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *Dataset) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *Dataset) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *Dataset) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *Dataset) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *Dataset) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetStatus

`func (o *Dataset) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Dataset) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Dataset) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Dataset) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreateOrigin

`func (o *Dataset) GetCreateOrigin() string`

GetCreateOrigin returns the CreateOrigin field if non-nil, zero value otherwise.

### GetCreateOriginOk

`func (o *Dataset) GetCreateOriginOk() (*string, bool)`

GetCreateOriginOk returns a tuple with the CreateOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateOrigin

`func (o *Dataset) SetCreateOrigin(v string)`

SetCreateOrigin sets CreateOrigin field to given value.

### HasCreateOrigin

`func (o *Dataset) HasCreateOrigin() bool`

HasCreateOrigin returns a boolean if a field has been set.

### SetCreateOriginNil

`func (o *Dataset) SetCreateOriginNil(b bool)`

 SetCreateOriginNil sets the value for CreateOrigin to be an explicit nil

### UnsetCreateOrigin
`func (o *Dataset) UnsetCreateOrigin()`

UnsetCreateOrigin ensures that no value is present for CreateOrigin, not even an explicit nil
### GetIsCohortDiscovery

`func (o *Dataset) GetIsCohortDiscovery() bool`

GetIsCohortDiscovery returns the IsCohortDiscovery field if non-nil, zero value otherwise.

### GetIsCohortDiscoveryOk

`func (o *Dataset) GetIsCohortDiscoveryOk() (*bool, bool)`

GetIsCohortDiscoveryOk returns a tuple with the IsCohortDiscovery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCohortDiscovery

`func (o *Dataset) SetIsCohortDiscovery(v bool)`

SetIsCohortDiscovery sets IsCohortDiscovery field to given value.

### HasIsCohortDiscovery

`func (o *Dataset) HasIsCohortDiscovery() bool`

HasIsCohortDiscovery returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Dataset) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Dataset) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Dataset) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Dataset) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Dataset) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Dataset) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Dataset) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Dataset) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


