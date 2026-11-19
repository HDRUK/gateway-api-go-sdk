# ExperimentDefinition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Steps** | Pointer to [**[]ExperimentDefinitionStepsInner**](ExperimentDefinitionStepsInner.md) |  | [optional] 
**ThankYou** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewExperimentDefinition

`func NewExperimentDefinition() *ExperimentDefinition`

NewExperimentDefinition instantiates a new ExperimentDefinition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentDefinitionWithDefaults

`func NewExperimentDefinitionWithDefaults() *ExperimentDefinition`

NewExperimentDefinitionWithDefaults instantiates a new ExperimentDefinition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSteps

`func (o *ExperimentDefinition) GetSteps() []ExperimentDefinitionStepsInner`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *ExperimentDefinition) GetStepsOk() (*[]ExperimentDefinitionStepsInner, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *ExperimentDefinition) SetSteps(v []ExperimentDefinitionStepsInner)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *ExperimentDefinition) HasSteps() bool`

HasSteps returns a boolean if a field has been set.

### GetThankYou

`func (o *ExperimentDefinition) GetThankYou() string`

GetThankYou returns the ThankYou field if non-nil, zero value otherwise.

### GetThankYouOk

`func (o *ExperimentDefinition) GetThankYouOk() (*string, bool)`

GetThankYouOk returns a tuple with the ThankYou field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThankYou

`func (o *ExperimentDefinition) SetThankYou(v string)`

SetThankYou sets ThankYou field to given value.

### HasThankYou

`func (o *ExperimentDefinition) HasThankYou() bool`

HasThankYou returns a boolean if a field has been set.

### SetThankYouNil

`func (o *ExperimentDefinition) SetThankYouNil(b bool)`

 SetThankYouNil sets the value for ThankYou to be an explicit nil

### UnsetThankYou
`func (o *ExperimentDefinition) UnsetThankYou()`

UnsetThankYou ensures that no value is present for ThankYou, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


