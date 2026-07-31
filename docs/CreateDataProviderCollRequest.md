# CreateDataProviderCollRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Summary** | **string** |  | 
**Enabled** | **bool** |  | 
**Service** | Pointer to **string** |  | [optional] 
**TeamIds** | **[]int32** |  | 

## Methods

### NewCreateDataProviderCollRequest

`func NewCreateDataProviderCollRequest(name string, summary string, enabled bool, teamIds []int32, ) *CreateDataProviderCollRequest`

NewCreateDataProviderCollRequest instantiates a new CreateDataProviderCollRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDataProviderCollRequestWithDefaults

`func NewCreateDataProviderCollRequestWithDefaults() *CreateDataProviderCollRequest`

NewCreateDataProviderCollRequestWithDefaults instantiates a new CreateDataProviderCollRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateDataProviderCollRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateDataProviderCollRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateDataProviderCollRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSummary

`func (o *CreateDataProviderCollRequest) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *CreateDataProviderCollRequest) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *CreateDataProviderCollRequest) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetEnabled

`func (o *CreateDataProviderCollRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDataProviderCollRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDataProviderCollRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetService

`func (o *CreateDataProviderCollRequest) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *CreateDataProviderCollRequest) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *CreateDataProviderCollRequest) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *CreateDataProviderCollRequest) HasService() bool`

HasService returns a boolean if a field has been set.

### GetTeamIds

`func (o *CreateDataProviderCollRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *CreateDataProviderCollRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *CreateDataProviderCollRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


