# ExperimentTrigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**On** | Pointer to **string** |  | [optional] 
**DelaySeconds** | Pointer to **int32** |  | [optional] 
**Frequency** | Pointer to **string** |  | [optional] 

## Methods

### NewExperimentTrigger

`func NewExperimentTrigger() *ExperimentTrigger`

NewExperimentTrigger instantiates a new ExperimentTrigger object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentTriggerWithDefaults

`func NewExperimentTriggerWithDefaults() *ExperimentTrigger`

NewExperimentTriggerWithDefaults instantiates a new ExperimentTrigger object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOn

`func (o *ExperimentTrigger) GetOn() string`

GetOn returns the On field if non-nil, zero value otherwise.

### GetOnOk

`func (o *ExperimentTrigger) GetOnOk() (*string, bool)`

GetOnOk returns a tuple with the On field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOn

`func (o *ExperimentTrigger) SetOn(v string)`

SetOn sets On field to given value.

### HasOn

`func (o *ExperimentTrigger) HasOn() bool`

HasOn returns a boolean if a field has been set.

### GetDelaySeconds

`func (o *ExperimentTrigger) GetDelaySeconds() int32`

GetDelaySeconds returns the DelaySeconds field if non-nil, zero value otherwise.

### GetDelaySecondsOk

`func (o *ExperimentTrigger) GetDelaySecondsOk() (*int32, bool)`

GetDelaySecondsOk returns a tuple with the DelaySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelaySeconds

`func (o *ExperimentTrigger) SetDelaySeconds(v int32)`

SetDelaySeconds sets DelaySeconds field to given value.

### HasDelaySeconds

`func (o *ExperimentTrigger) HasDelaySeconds() bool`

HasDelaySeconds returns a boolean if a field has been set.

### GetFrequency

`func (o *ExperimentTrigger) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *ExperimentTrigger) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *ExperimentTrigger) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.

### HasFrequency

`func (o *ExperimentTrigger) HasFrequency() bool`

HasFrequency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


