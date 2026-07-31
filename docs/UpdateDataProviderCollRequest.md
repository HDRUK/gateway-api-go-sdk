# UpdateDataProviderCollRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Summary** | **string** |  | 
**Enabled** | **string** |  | 
**Service** | Pointer to **string** |  | [optional] 
**TeamIds** | **[]int32** |  | 

## Methods

### NewUpdateDataProviderCollRequest

`func NewUpdateDataProviderCollRequest(name string, summary string, enabled string, teamIds []int32, ) *UpdateDataProviderCollRequest`

NewUpdateDataProviderCollRequest instantiates a new UpdateDataProviderCollRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDataProviderCollRequestWithDefaults

`func NewUpdateDataProviderCollRequestWithDefaults() *UpdateDataProviderCollRequest`

NewUpdateDataProviderCollRequestWithDefaults instantiates a new UpdateDataProviderCollRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateDataProviderCollRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateDataProviderCollRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateDataProviderCollRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSummary

`func (o *UpdateDataProviderCollRequest) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *UpdateDataProviderCollRequest) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *UpdateDataProviderCollRequest) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetEnabled

`func (o *UpdateDataProviderCollRequest) GetEnabled() string`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateDataProviderCollRequest) GetEnabledOk() (*string, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateDataProviderCollRequest) SetEnabled(v string)`

SetEnabled sets Enabled field to given value.


### GetService

`func (o *UpdateDataProviderCollRequest) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *UpdateDataProviderCollRequest) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *UpdateDataProviderCollRequest) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *UpdateDataProviderCollRequest) HasService() bool`

HasService returns a boolean if a field has been set.

### GetTeamIds

`func (o *UpdateDataProviderCollRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *UpdateDataProviderCollRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *UpdateDataProviderCollRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


