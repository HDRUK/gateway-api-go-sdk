# UpdateFederationTeamRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FederationType** | Pointer to **string** |  | [optional] 
**AuthType** | Pointer to **string** |  | [optional] 
**AuthSecretKey** | Pointer to **string** |  | [optional] 
**EndpointBaseurl** | Pointer to **string** |  | [optional] 
**EndpointDatasets** | Pointer to **string** |  | [optional] 
**EndpointDataset** | Pointer to **string** |  | [optional] 
**RunTimeHour** | Pointer to **int32** |  | [optional] 
**RunTimeMinute** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Notifications** | Pointer to **[][]interface{}** |  | [optional] 
**Tested** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateFederationTeamRequest

`func NewUpdateFederationTeamRequest() *UpdateFederationTeamRequest`

NewUpdateFederationTeamRequest instantiates a new UpdateFederationTeamRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFederationTeamRequestWithDefaults

`func NewUpdateFederationTeamRequestWithDefaults() *UpdateFederationTeamRequest`

NewUpdateFederationTeamRequestWithDefaults instantiates a new UpdateFederationTeamRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFederationType

`func (o *UpdateFederationTeamRequest) GetFederationType() string`

GetFederationType returns the FederationType field if non-nil, zero value otherwise.

### GetFederationTypeOk

`func (o *UpdateFederationTeamRequest) GetFederationTypeOk() (*string, bool)`

GetFederationTypeOk returns a tuple with the FederationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationType

`func (o *UpdateFederationTeamRequest) SetFederationType(v string)`

SetFederationType sets FederationType field to given value.

### HasFederationType

`func (o *UpdateFederationTeamRequest) HasFederationType() bool`

HasFederationType returns a boolean if a field has been set.

### GetAuthType

`func (o *UpdateFederationTeamRequest) GetAuthType() string`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *UpdateFederationTeamRequest) GetAuthTypeOk() (*string, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *UpdateFederationTeamRequest) SetAuthType(v string)`

SetAuthType sets AuthType field to given value.

### HasAuthType

`func (o *UpdateFederationTeamRequest) HasAuthType() bool`

HasAuthType returns a boolean if a field has been set.

### GetAuthSecretKey

`func (o *UpdateFederationTeamRequest) GetAuthSecretKey() string`

GetAuthSecretKey returns the AuthSecretKey field if non-nil, zero value otherwise.

### GetAuthSecretKeyOk

`func (o *UpdateFederationTeamRequest) GetAuthSecretKeyOk() (*string, bool)`

GetAuthSecretKeyOk returns a tuple with the AuthSecretKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthSecretKey

`func (o *UpdateFederationTeamRequest) SetAuthSecretKey(v string)`

SetAuthSecretKey sets AuthSecretKey field to given value.

### HasAuthSecretKey

`func (o *UpdateFederationTeamRequest) HasAuthSecretKey() bool`

HasAuthSecretKey returns a boolean if a field has been set.

### GetEndpointBaseurl

`func (o *UpdateFederationTeamRequest) GetEndpointBaseurl() string`

GetEndpointBaseurl returns the EndpointBaseurl field if non-nil, zero value otherwise.

### GetEndpointBaseurlOk

`func (o *UpdateFederationTeamRequest) GetEndpointBaseurlOk() (*string, bool)`

GetEndpointBaseurlOk returns a tuple with the EndpointBaseurl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointBaseurl

`func (o *UpdateFederationTeamRequest) SetEndpointBaseurl(v string)`

SetEndpointBaseurl sets EndpointBaseurl field to given value.

### HasEndpointBaseurl

`func (o *UpdateFederationTeamRequest) HasEndpointBaseurl() bool`

HasEndpointBaseurl returns a boolean if a field has been set.

### GetEndpointDatasets

`func (o *UpdateFederationTeamRequest) GetEndpointDatasets() string`

GetEndpointDatasets returns the EndpointDatasets field if non-nil, zero value otherwise.

### GetEndpointDatasetsOk

`func (o *UpdateFederationTeamRequest) GetEndpointDatasetsOk() (*string, bool)`

GetEndpointDatasetsOk returns a tuple with the EndpointDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDatasets

`func (o *UpdateFederationTeamRequest) SetEndpointDatasets(v string)`

SetEndpointDatasets sets EndpointDatasets field to given value.

### HasEndpointDatasets

`func (o *UpdateFederationTeamRequest) HasEndpointDatasets() bool`

HasEndpointDatasets returns a boolean if a field has been set.

### GetEndpointDataset

`func (o *UpdateFederationTeamRequest) GetEndpointDataset() string`

GetEndpointDataset returns the EndpointDataset field if non-nil, zero value otherwise.

### GetEndpointDatasetOk

`func (o *UpdateFederationTeamRequest) GetEndpointDatasetOk() (*string, bool)`

GetEndpointDatasetOk returns a tuple with the EndpointDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDataset

`func (o *UpdateFederationTeamRequest) SetEndpointDataset(v string)`

SetEndpointDataset sets EndpointDataset field to given value.

### HasEndpointDataset

`func (o *UpdateFederationTeamRequest) HasEndpointDataset() bool`

HasEndpointDataset returns a boolean if a field has been set.

### GetRunTimeHour

`func (o *UpdateFederationTeamRequest) GetRunTimeHour() int32`

GetRunTimeHour returns the RunTimeHour field if non-nil, zero value otherwise.

### GetRunTimeHourOk

`func (o *UpdateFederationTeamRequest) GetRunTimeHourOk() (*int32, bool)`

GetRunTimeHourOk returns a tuple with the RunTimeHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeHour

`func (o *UpdateFederationTeamRequest) SetRunTimeHour(v int32)`

SetRunTimeHour sets RunTimeHour field to given value.

### HasRunTimeHour

`func (o *UpdateFederationTeamRequest) HasRunTimeHour() bool`

HasRunTimeHour returns a boolean if a field has been set.

### GetRunTimeMinute

`func (o *UpdateFederationTeamRequest) GetRunTimeMinute() string`

GetRunTimeMinute returns the RunTimeMinute field if non-nil, zero value otherwise.

### GetRunTimeMinuteOk

`func (o *UpdateFederationTeamRequest) GetRunTimeMinuteOk() (*string, bool)`

GetRunTimeMinuteOk returns a tuple with the RunTimeMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeMinute

`func (o *UpdateFederationTeamRequest) SetRunTimeMinute(v string)`

SetRunTimeMinute sets RunTimeMinute field to given value.

### HasRunTimeMinute

`func (o *UpdateFederationTeamRequest) HasRunTimeMinute() bool`

HasRunTimeMinute returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateFederationTeamRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateFederationTeamRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateFederationTeamRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateFederationTeamRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetNotifications

`func (o *UpdateFederationTeamRequest) GetNotifications() [][]interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *UpdateFederationTeamRequest) GetNotificationsOk() (*[][]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *UpdateFederationTeamRequest) SetNotifications(v [][]interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *UpdateFederationTeamRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetTested

`func (o *UpdateFederationTeamRequest) GetTested() bool`

GetTested returns the Tested field if non-nil, zero value otherwise.

### GetTestedOk

`func (o *UpdateFederationTeamRequest) GetTestedOk() (*bool, bool)`

GetTestedOk returns a tuple with the Tested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTested

`func (o *UpdateFederationTeamRequest) SetTested(v bool)`

SetTested sets Tested field to given value.

### HasTested

`func (o *UpdateFederationTeamRequest) HasTested() bool`

HasTested returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


