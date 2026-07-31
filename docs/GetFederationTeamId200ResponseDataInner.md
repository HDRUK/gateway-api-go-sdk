# GetFederationTeamId200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**FederationType** | Pointer to **string** |  | [optional] 
**AuthType** | Pointer to **string** |  | [optional] 
**AuthSecretKey** | Pointer to **string** |  | [optional] 
**EndpointBaseurl** | Pointer to **string** |  | [optional] 
**EndpointDatasets** | Pointer to **string** |  | [optional] 
**EndpointDataset** | Pointer to **string** |  | [optional] 
**RunTimeHour** | Pointer to **int32** |  | [optional] 
**RunTimeMinute** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**Tested** | Pointer to **bool** |  | [optional] 
**IsRunning** | Pointer to **bool** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 
**LastRunAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewGetFederationTeamId200ResponseDataInner

`func NewGetFederationTeamId200ResponseDataInner() *GetFederationTeamId200ResponseDataInner`

NewGetFederationTeamId200ResponseDataInner instantiates a new GetFederationTeamId200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFederationTeamId200ResponseDataInnerWithDefaults

`func NewGetFederationTeamId200ResponseDataInnerWithDefaults() *GetFederationTeamId200ResponseDataInner`

NewGetFederationTeamId200ResponseDataInnerWithDefaults instantiates a new GetFederationTeamId200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetFederationTeamId200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetFederationTeamId200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetFederationTeamId200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GetFederationTeamId200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFederationType

`func (o *GetFederationTeamId200ResponseDataInner) GetFederationType() string`

GetFederationType returns the FederationType field if non-nil, zero value otherwise.

### GetFederationTypeOk

`func (o *GetFederationTeamId200ResponseDataInner) GetFederationTypeOk() (*string, bool)`

GetFederationTypeOk returns a tuple with the FederationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationType

`func (o *GetFederationTeamId200ResponseDataInner) SetFederationType(v string)`

SetFederationType sets FederationType field to given value.

### HasFederationType

`func (o *GetFederationTeamId200ResponseDataInner) HasFederationType() bool`

HasFederationType returns a boolean if a field has been set.

### GetAuthType

`func (o *GetFederationTeamId200ResponseDataInner) GetAuthType() string`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *GetFederationTeamId200ResponseDataInner) GetAuthTypeOk() (*string, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *GetFederationTeamId200ResponseDataInner) SetAuthType(v string)`

SetAuthType sets AuthType field to given value.

### HasAuthType

`func (o *GetFederationTeamId200ResponseDataInner) HasAuthType() bool`

HasAuthType returns a boolean if a field has been set.

### GetAuthSecretKey

`func (o *GetFederationTeamId200ResponseDataInner) GetAuthSecretKey() string`

GetAuthSecretKey returns the AuthSecretKey field if non-nil, zero value otherwise.

### GetAuthSecretKeyOk

`func (o *GetFederationTeamId200ResponseDataInner) GetAuthSecretKeyOk() (*string, bool)`

GetAuthSecretKeyOk returns a tuple with the AuthSecretKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthSecretKey

`func (o *GetFederationTeamId200ResponseDataInner) SetAuthSecretKey(v string)`

SetAuthSecretKey sets AuthSecretKey field to given value.

### HasAuthSecretKey

`func (o *GetFederationTeamId200ResponseDataInner) HasAuthSecretKey() bool`

HasAuthSecretKey returns a boolean if a field has been set.

### GetEndpointBaseurl

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointBaseurl() string`

GetEndpointBaseurl returns the EndpointBaseurl field if non-nil, zero value otherwise.

### GetEndpointBaseurlOk

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointBaseurlOk() (*string, bool)`

GetEndpointBaseurlOk returns a tuple with the EndpointBaseurl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointBaseurl

`func (o *GetFederationTeamId200ResponseDataInner) SetEndpointBaseurl(v string)`

SetEndpointBaseurl sets EndpointBaseurl field to given value.

### HasEndpointBaseurl

`func (o *GetFederationTeamId200ResponseDataInner) HasEndpointBaseurl() bool`

HasEndpointBaseurl returns a boolean if a field has been set.

### GetEndpointDatasets

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointDatasets() string`

GetEndpointDatasets returns the EndpointDatasets field if non-nil, zero value otherwise.

### GetEndpointDatasetsOk

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointDatasetsOk() (*string, bool)`

GetEndpointDatasetsOk returns a tuple with the EndpointDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDatasets

`func (o *GetFederationTeamId200ResponseDataInner) SetEndpointDatasets(v string)`

SetEndpointDatasets sets EndpointDatasets field to given value.

### HasEndpointDatasets

`func (o *GetFederationTeamId200ResponseDataInner) HasEndpointDatasets() bool`

HasEndpointDatasets returns a boolean if a field has been set.

### GetEndpointDataset

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointDataset() string`

GetEndpointDataset returns the EndpointDataset field if non-nil, zero value otherwise.

### GetEndpointDatasetOk

`func (o *GetFederationTeamId200ResponseDataInner) GetEndpointDatasetOk() (*string, bool)`

GetEndpointDatasetOk returns a tuple with the EndpointDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDataset

`func (o *GetFederationTeamId200ResponseDataInner) SetEndpointDataset(v string)`

SetEndpointDataset sets EndpointDataset field to given value.

### HasEndpointDataset

`func (o *GetFederationTeamId200ResponseDataInner) HasEndpointDataset() bool`

HasEndpointDataset returns a boolean if a field has been set.

### GetRunTimeHour

`func (o *GetFederationTeamId200ResponseDataInner) GetRunTimeHour() int32`

GetRunTimeHour returns the RunTimeHour field if non-nil, zero value otherwise.

### GetRunTimeHourOk

`func (o *GetFederationTeamId200ResponseDataInner) GetRunTimeHourOk() (*int32, bool)`

GetRunTimeHourOk returns a tuple with the RunTimeHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeHour

`func (o *GetFederationTeamId200ResponseDataInner) SetRunTimeHour(v int32)`

SetRunTimeHour sets RunTimeHour field to given value.

### HasRunTimeHour

`func (o *GetFederationTeamId200ResponseDataInner) HasRunTimeHour() bool`

HasRunTimeHour returns a boolean if a field has been set.

### GetRunTimeMinute

`func (o *GetFederationTeamId200ResponseDataInner) GetRunTimeMinute() string`

GetRunTimeMinute returns the RunTimeMinute field if non-nil, zero value otherwise.

### GetRunTimeMinuteOk

`func (o *GetFederationTeamId200ResponseDataInner) GetRunTimeMinuteOk() (*string, bool)`

GetRunTimeMinuteOk returns a tuple with the RunTimeMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeMinute

`func (o *GetFederationTeamId200ResponseDataInner) SetRunTimeMinute(v string)`

SetRunTimeMinute sets RunTimeMinute field to given value.

### HasRunTimeMinute

`func (o *GetFederationTeamId200ResponseDataInner) HasRunTimeMinute() bool`

HasRunTimeMinute returns a boolean if a field has been set.

### GetEnabled

`func (o *GetFederationTeamId200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetFederationTeamId200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetFederationTeamId200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *GetFederationTeamId200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetFederationTeamId200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetFederationTeamId200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetFederationTeamId200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetFederationTeamId200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetFederationTeamId200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetFederationTeamId200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetFederationTeamId200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetFederationTeamId200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *GetFederationTeamId200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *GetFederationTeamId200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *GetFederationTeamId200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *GetFederationTeamId200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetTested

`func (o *GetFederationTeamId200ResponseDataInner) GetTested() bool`

GetTested returns the Tested field if non-nil, zero value otherwise.

### GetTestedOk

`func (o *GetFederationTeamId200ResponseDataInner) GetTestedOk() (*bool, bool)`

GetTestedOk returns a tuple with the Tested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTested

`func (o *GetFederationTeamId200ResponseDataInner) SetTested(v bool)`

SetTested sets Tested field to given value.

### HasTested

`func (o *GetFederationTeamId200ResponseDataInner) HasTested() bool`

HasTested returns a boolean if a field has been set.

### GetIsRunning

`func (o *GetFederationTeamId200ResponseDataInner) GetIsRunning() bool`

GetIsRunning returns the IsRunning field if non-nil, zero value otherwise.

### GetIsRunningOk

`func (o *GetFederationTeamId200ResponseDataInner) GetIsRunningOk() (*bool, bool)`

GetIsRunningOk returns a tuple with the IsRunning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRunning

`func (o *GetFederationTeamId200ResponseDataInner) SetIsRunning(v bool)`

SetIsRunning sets IsRunning field to given value.

### HasIsRunning

`func (o *GetFederationTeamId200ResponseDataInner) HasIsRunning() bool`

HasIsRunning returns a boolean if a field has been set.

### GetNotifications

`func (o *GetFederationTeamId200ResponseDataInner) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *GetFederationTeamId200ResponseDataInner) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *GetFederationTeamId200ResponseDataInner) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *GetFederationTeamId200ResponseDataInner) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetLastRunAt

`func (o *GetFederationTeamId200ResponseDataInner) GetLastRunAt() time.Time`

GetLastRunAt returns the LastRunAt field if non-nil, zero value otherwise.

### GetLastRunAtOk

`func (o *GetFederationTeamId200ResponseDataInner) GetLastRunAtOk() (*time.Time, bool)`

GetLastRunAtOk returns a tuple with the LastRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunAt

`func (o *GetFederationTeamId200ResponseDataInner) SetLastRunAt(v time.Time)`

SetLastRunAt sets LastRunAt field to given value.

### HasLastRunAt

`func (o *GetFederationTeamId200ResponseDataInner) HasLastRunAt() bool`

HasLastRunAt returns a boolean if a field has been set.

### SetLastRunAtNil

`func (o *GetFederationTeamId200ResponseDataInner) SetLastRunAtNil(b bool)`

 SetLastRunAtNil sets the value for LastRunAt to be an explicit nil

### UnsetLastRunAt
`func (o *GetFederationTeamId200ResponseDataInner) UnsetLastRunAt()`

UnsetLastRunAt ensures that no value is present for LastRunAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


