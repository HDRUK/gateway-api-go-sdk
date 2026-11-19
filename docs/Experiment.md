# Experiment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Definition** | Pointer to [**ExperimentDefinition**](ExperimentDefinition.md) |  | [optional] 
**Targeting** | Pointer to [**ExperimentTargeting**](ExperimentTargeting.md) |  | [optional] 
**Trigger** | Pointer to [**ExperimentTrigger**](ExperimentTrigger.md) |  | [optional] 
**StartsAt** | Pointer to **NullableString** |  | [optional] 
**EndsAt** | Pointer to **NullableString** |  | [optional] 
**CreatedBy** | Pointer to **NullableInt32** |  | [optional] 
**ResponsesCount** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewExperiment

`func NewExperiment() *Experiment`

NewExperiment instantiates a new Experiment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentWithDefaults

`func NewExperimentWithDefaults() *Experiment`

NewExperimentWithDefaults instantiates a new Experiment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Experiment) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Experiment) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Experiment) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Experiment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Experiment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Experiment) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Experiment) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Experiment) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *Experiment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Experiment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Experiment) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Experiment) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDefinition

`func (o *Experiment) GetDefinition() ExperimentDefinition`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *Experiment) GetDefinitionOk() (*ExperimentDefinition, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *Experiment) SetDefinition(v ExperimentDefinition)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *Experiment) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetTargeting

`func (o *Experiment) GetTargeting() ExperimentTargeting`

GetTargeting returns the Targeting field if non-nil, zero value otherwise.

### GetTargetingOk

`func (o *Experiment) GetTargetingOk() (*ExperimentTargeting, bool)`

GetTargetingOk returns a tuple with the Targeting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargeting

`func (o *Experiment) SetTargeting(v ExperimentTargeting)`

SetTargeting sets Targeting field to given value.

### HasTargeting

`func (o *Experiment) HasTargeting() bool`

HasTargeting returns a boolean if a field has been set.

### GetTrigger

`func (o *Experiment) GetTrigger() ExperimentTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *Experiment) GetTriggerOk() (*ExperimentTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *Experiment) SetTrigger(v ExperimentTrigger)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *Experiment) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetStartsAt

`func (o *Experiment) GetStartsAt() string`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *Experiment) GetStartsAtOk() (*string, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *Experiment) SetStartsAt(v string)`

SetStartsAt sets StartsAt field to given value.

### HasStartsAt

`func (o *Experiment) HasStartsAt() bool`

HasStartsAt returns a boolean if a field has been set.

### SetStartsAtNil

`func (o *Experiment) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *Experiment) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil
### GetEndsAt

`func (o *Experiment) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *Experiment) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *Experiment) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *Experiment) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.

### SetEndsAtNil

`func (o *Experiment) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *Experiment) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil
### GetCreatedBy

`func (o *Experiment) GetCreatedBy() int32`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *Experiment) GetCreatedByOk() (*int32, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *Experiment) SetCreatedBy(v int32)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *Experiment) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *Experiment) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *Experiment) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetResponsesCount

`func (o *Experiment) GetResponsesCount() int32`

GetResponsesCount returns the ResponsesCount field if non-nil, zero value otherwise.

### GetResponsesCountOk

`func (o *Experiment) GetResponsesCountOk() (*int32, bool)`

GetResponsesCountOk returns a tuple with the ResponsesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsesCount

`func (o *Experiment) SetResponsesCount(v int32)`

SetResponsesCount sets ResponsesCount field to given value.

### HasResponsesCount

`func (o *Experiment) HasResponsesCount() bool`

HasResponsesCount returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Experiment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Experiment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Experiment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Experiment) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Experiment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Experiment) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Experiment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Experiment) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *Experiment) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *Experiment) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *Experiment) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *Experiment) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *Experiment) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *Experiment) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


