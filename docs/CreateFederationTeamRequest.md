# CreateFederationTeamRequest

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
**Enabled** | Pointer to **bool** |  | [optional] 
**Notifications** | Pointer to **[][]interface{}** |  | [optional] 
**Tested** | Pointer to **bool** |  | [optional] 

## Methods

### NewCreateFederationTeamRequest

`func NewCreateFederationTeamRequest() *CreateFederationTeamRequest`

NewCreateFederationTeamRequest instantiates a new CreateFederationTeamRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateFederationTeamRequestWithDefaults

`func NewCreateFederationTeamRequestWithDefaults() *CreateFederationTeamRequest`

NewCreateFederationTeamRequestWithDefaults instantiates a new CreateFederationTeamRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFederationType

`func (o *CreateFederationTeamRequest) GetFederationType() string`

GetFederationType returns the FederationType field if non-nil, zero value otherwise.

### GetFederationTypeOk

`func (o *CreateFederationTeamRequest) GetFederationTypeOk() (*string, bool)`

GetFederationTypeOk returns a tuple with the FederationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationType

`func (o *CreateFederationTeamRequest) SetFederationType(v string)`

SetFederationType sets FederationType field to given value.

### HasFederationType

`func (o *CreateFederationTeamRequest) HasFederationType() bool`

HasFederationType returns a boolean if a field has been set.

### GetAuthType

`func (o *CreateFederationTeamRequest) GetAuthType() string`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *CreateFederationTeamRequest) GetAuthTypeOk() (*string, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *CreateFederationTeamRequest) SetAuthType(v string)`

SetAuthType sets AuthType field to given value.

### HasAuthType

`func (o *CreateFederationTeamRequest) HasAuthType() bool`

HasAuthType returns a boolean if a field has been set.

### GetAuthSecretKey

`func (o *CreateFederationTeamRequest) GetAuthSecretKey() string`

GetAuthSecretKey returns the AuthSecretKey field if non-nil, zero value otherwise.

### GetAuthSecretKeyOk

`func (o *CreateFederationTeamRequest) GetAuthSecretKeyOk() (*string, bool)`

GetAuthSecretKeyOk returns a tuple with the AuthSecretKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthSecretKey

`func (o *CreateFederationTeamRequest) SetAuthSecretKey(v string)`

SetAuthSecretKey sets AuthSecretKey field to given value.

### HasAuthSecretKey

`func (o *CreateFederationTeamRequest) HasAuthSecretKey() bool`

HasAuthSecretKey returns a boolean if a field has been set.

### GetEndpointBaseurl

`func (o *CreateFederationTeamRequest) GetEndpointBaseurl() string`

GetEndpointBaseurl returns the EndpointBaseurl field if non-nil, zero value otherwise.

### GetEndpointBaseurlOk

`func (o *CreateFederationTeamRequest) GetEndpointBaseurlOk() (*string, bool)`

GetEndpointBaseurlOk returns a tuple with the EndpointBaseurl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointBaseurl

`func (o *CreateFederationTeamRequest) SetEndpointBaseurl(v string)`

SetEndpointBaseurl sets EndpointBaseurl field to given value.

### HasEndpointBaseurl

`func (o *CreateFederationTeamRequest) HasEndpointBaseurl() bool`

HasEndpointBaseurl returns a boolean if a field has been set.

### GetEndpointDatasets

`func (o *CreateFederationTeamRequest) GetEndpointDatasets() string`

GetEndpointDatasets returns the EndpointDatasets field if non-nil, zero value otherwise.

### GetEndpointDatasetsOk

`func (o *CreateFederationTeamRequest) GetEndpointDatasetsOk() (*string, bool)`

GetEndpointDatasetsOk returns a tuple with the EndpointDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDatasets

`func (o *CreateFederationTeamRequest) SetEndpointDatasets(v string)`

SetEndpointDatasets sets EndpointDatasets field to given value.

### HasEndpointDatasets

`func (o *CreateFederationTeamRequest) HasEndpointDatasets() bool`

HasEndpointDatasets returns a boolean if a field has been set.

### GetEndpointDataset

`func (o *CreateFederationTeamRequest) GetEndpointDataset() string`

GetEndpointDataset returns the EndpointDataset field if non-nil, zero value otherwise.

### GetEndpointDatasetOk

`func (o *CreateFederationTeamRequest) GetEndpointDatasetOk() (*string, bool)`

GetEndpointDatasetOk returns a tuple with the EndpointDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDataset

`func (o *CreateFederationTeamRequest) SetEndpointDataset(v string)`

SetEndpointDataset sets EndpointDataset field to given value.

### HasEndpointDataset

`func (o *CreateFederationTeamRequest) HasEndpointDataset() bool`

HasEndpointDataset returns a boolean if a field has been set.

### GetRunTimeHour

`func (o *CreateFederationTeamRequest) GetRunTimeHour() int32`

GetRunTimeHour returns the RunTimeHour field if non-nil, zero value otherwise.

### GetRunTimeHourOk

`func (o *CreateFederationTeamRequest) GetRunTimeHourOk() (*int32, bool)`

GetRunTimeHourOk returns a tuple with the RunTimeHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeHour

`func (o *CreateFederationTeamRequest) SetRunTimeHour(v int32)`

SetRunTimeHour sets RunTimeHour field to given value.

### HasRunTimeHour

`func (o *CreateFederationTeamRequest) HasRunTimeHour() bool`

HasRunTimeHour returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateFederationTeamRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateFederationTeamRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateFederationTeamRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateFederationTeamRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetNotifications

`func (o *CreateFederationTeamRequest) GetNotifications() [][]interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *CreateFederationTeamRequest) GetNotificationsOk() (*[][]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *CreateFederationTeamRequest) SetNotifications(v [][]interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *CreateFederationTeamRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetTested

`func (o *CreateFederationTeamRequest) GetTested() bool`

GetTested returns the Tested field if non-nil, zero value otherwise.

### GetTestedOk

`func (o *CreateFederationTeamRequest) GetTestedOk() (*bool, bool)`

GetTestedOk returns a tuple with the Tested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTested

`func (o *CreateFederationTeamRequest) SetTested(v bool)`

SetTested sets Tested field to given value.

### HasTested

`func (o *CreateFederationTeamRequest) HasTested() bool`

HasTested returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


