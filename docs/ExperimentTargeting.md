# ExperimentTargeting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Paths** | Pointer to **[]string** |  | [optional] 
**Audience** | Pointer to **string** |  | [optional] 
**UserIds** | Pointer to **[]int32** |  | [optional] 
**Percentage** | Pointer to **int32** |  | [optional] 

## Methods

### NewExperimentTargeting

`func NewExperimentTargeting() *ExperimentTargeting`

NewExperimentTargeting instantiates a new ExperimentTargeting object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentTargetingWithDefaults

`func NewExperimentTargetingWithDefaults() *ExperimentTargeting`

NewExperimentTargetingWithDefaults instantiates a new ExperimentTargeting object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPaths

`func (o *ExperimentTargeting) GetPaths() []string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *ExperimentTargeting) GetPathsOk() (*[]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *ExperimentTargeting) SetPaths(v []string)`

SetPaths sets Paths field to given value.

### HasPaths

`func (o *ExperimentTargeting) HasPaths() bool`

HasPaths returns a boolean if a field has been set.

### GetAudience

`func (o *ExperimentTargeting) GetAudience() string`

GetAudience returns the Audience field if non-nil, zero value otherwise.

### GetAudienceOk

`func (o *ExperimentTargeting) GetAudienceOk() (*string, bool)`

GetAudienceOk returns a tuple with the Audience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudience

`func (o *ExperimentTargeting) SetAudience(v string)`

SetAudience sets Audience field to given value.

### HasAudience

`func (o *ExperimentTargeting) HasAudience() bool`

HasAudience returns a boolean if a field has been set.

### GetUserIds

`func (o *ExperimentTargeting) GetUserIds() []int32`

GetUserIds returns the UserIds field if non-nil, zero value otherwise.

### GetUserIdsOk

`func (o *ExperimentTargeting) GetUserIdsOk() (*[]int32, bool)`

GetUserIdsOk returns a tuple with the UserIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIds

`func (o *ExperimentTargeting) SetUserIds(v []int32)`

SetUserIds sets UserIds field to given value.

### HasUserIds

`func (o *ExperimentTargeting) HasUserIds() bool`

HasUserIds returns a boolean if a field has been set.

### GetPercentage

`func (o *ExperimentTargeting) GetPercentage() int32`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *ExperimentTargeting) GetPercentageOk() (*int32, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *ExperimentTargeting) SetPercentage(v int32)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *ExperimentTargeting) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


