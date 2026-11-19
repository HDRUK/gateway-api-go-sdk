# ExperimentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Status** | **string** |  | 
**Definition** | **map[string]interface{}** | See Experiment.definition | 
**Targeting** | **map[string]interface{}** | See Experiment.targeting | 
**Trigger** | **map[string]interface{}** | See Experiment.trigger | 
**StartsAt** | Pointer to **NullableString** |  | [optional] 
**EndsAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewExperimentInput

`func NewExperimentInput(name string, status string, definition map[string]interface{}, targeting map[string]interface{}, trigger map[string]interface{}, ) *ExperimentInput`

NewExperimentInput instantiates a new ExperimentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentInputWithDefaults

`func NewExperimentInputWithDefaults() *ExperimentInput`

NewExperimentInputWithDefaults instantiates a new ExperimentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ExperimentInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ExperimentInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ExperimentInput) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *ExperimentInput) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ExperimentInput) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ExperimentInput) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDefinition

`func (o *ExperimentInput) GetDefinition() map[string]interface{}`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *ExperimentInput) GetDefinitionOk() (*map[string]interface{}, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *ExperimentInput) SetDefinition(v map[string]interface{})`

SetDefinition sets Definition field to given value.


### GetTargeting

`func (o *ExperimentInput) GetTargeting() map[string]interface{}`

GetTargeting returns the Targeting field if non-nil, zero value otherwise.

### GetTargetingOk

`func (o *ExperimentInput) GetTargetingOk() (*map[string]interface{}, bool)`

GetTargetingOk returns a tuple with the Targeting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargeting

`func (o *ExperimentInput) SetTargeting(v map[string]interface{})`

SetTargeting sets Targeting field to given value.


### GetTrigger

`func (o *ExperimentInput) GetTrigger() map[string]interface{}`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *ExperimentInput) GetTriggerOk() (*map[string]interface{}, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *ExperimentInput) SetTrigger(v map[string]interface{})`

SetTrigger sets Trigger field to given value.


### GetStartsAt

`func (o *ExperimentInput) GetStartsAt() string`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *ExperimentInput) GetStartsAtOk() (*string, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *ExperimentInput) SetStartsAt(v string)`

SetStartsAt sets StartsAt field to given value.

### HasStartsAt

`func (o *ExperimentInput) HasStartsAt() bool`

HasStartsAt returns a boolean if a field has been set.

### SetStartsAtNil

`func (o *ExperimentInput) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *ExperimentInput) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil
### GetEndsAt

`func (o *ExperimentInput) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *ExperimentInput) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *ExperimentInput) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *ExperimentInput) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.

### SetEndsAtNil

`func (o *ExperimentInput) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *ExperimentInput) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


