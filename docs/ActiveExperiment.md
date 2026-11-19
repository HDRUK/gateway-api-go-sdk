# ActiveExperiment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Paths** | Pointer to **[]string** |  | [optional] 
**Trigger** | Pointer to **map[string]interface{}** | See Experiment.trigger | [optional] 
**Definition** | Pointer to **map[string]interface{}** | See Experiment.definition | [optional] 
**Variant** | Pointer to **NullableString** |  | [optional] 
**EndsAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewActiveExperiment

`func NewActiveExperiment() *ActiveExperiment`

NewActiveExperiment instantiates a new ActiveExperiment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActiveExperimentWithDefaults

`func NewActiveExperimentWithDefaults() *ActiveExperiment`

NewActiveExperimentWithDefaults instantiates a new ActiveExperiment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ActiveExperiment) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ActiveExperiment) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ActiveExperiment) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ActiveExperiment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ActiveExperiment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ActiveExperiment) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ActiveExperiment) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ActiveExperiment) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPaths

`func (o *ActiveExperiment) GetPaths() []string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *ActiveExperiment) GetPathsOk() (*[]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *ActiveExperiment) SetPaths(v []string)`

SetPaths sets Paths field to given value.

### HasPaths

`func (o *ActiveExperiment) HasPaths() bool`

HasPaths returns a boolean if a field has been set.

### GetTrigger

`func (o *ActiveExperiment) GetTrigger() map[string]interface{}`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *ActiveExperiment) GetTriggerOk() (*map[string]interface{}, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *ActiveExperiment) SetTrigger(v map[string]interface{})`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *ActiveExperiment) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetDefinition

`func (o *ActiveExperiment) GetDefinition() map[string]interface{}`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *ActiveExperiment) GetDefinitionOk() (*map[string]interface{}, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *ActiveExperiment) SetDefinition(v map[string]interface{})`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *ActiveExperiment) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetVariant

`func (o *ActiveExperiment) GetVariant() string`

GetVariant returns the Variant field if non-nil, zero value otherwise.

### GetVariantOk

`func (o *ActiveExperiment) GetVariantOk() (*string, bool)`

GetVariantOk returns a tuple with the Variant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariant

`func (o *ActiveExperiment) SetVariant(v string)`

SetVariant sets Variant field to given value.

### HasVariant

`func (o *ActiveExperiment) HasVariant() bool`

HasVariant returns a boolean if a field has been set.

### SetVariantNil

`func (o *ActiveExperiment) SetVariantNil(b bool)`

 SetVariantNil sets the value for Variant to be an explicit nil

### UnsetVariant
`func (o *ActiveExperiment) UnsetVariant()`

UnsetVariant ensures that no value is present for Variant, not even an explicit nil
### GetEndsAt

`func (o *ActiveExperiment) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *ActiveExperiment) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *ActiveExperiment) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *ActiveExperiment) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.

### SetEndsAtNil

`func (o *ActiveExperiment) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *ActiveExperiment) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


