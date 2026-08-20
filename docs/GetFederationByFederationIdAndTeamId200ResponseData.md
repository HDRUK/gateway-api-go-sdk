# GetFederationByFederationIdAndTeamId200ResponseData

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
**EnabledAt** | Pointer to **NullableTime** |  | [optional] 
**Counter** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**Tested** | Pointer to **bool** |  | [optional] 
**Notifications** | Pointer to **[]interface{}** |  | [optional] 
**IsRunning** | Pointer to **bool** |  | [optional] 

## Methods

### NewGetFederationByFederationIdAndTeamId200ResponseData

`func NewGetFederationByFederationIdAndTeamId200ResponseData() *GetFederationByFederationIdAndTeamId200ResponseData`

NewGetFederationByFederationIdAndTeamId200ResponseData instantiates a new GetFederationByFederationIdAndTeamId200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFederationByFederationIdAndTeamId200ResponseDataWithDefaults

`func NewGetFederationByFederationIdAndTeamId200ResponseDataWithDefaults() *GetFederationByFederationIdAndTeamId200ResponseData`

NewGetFederationByFederationIdAndTeamId200ResponseDataWithDefaults instantiates a new GetFederationByFederationIdAndTeamId200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFederationType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetFederationType() string`

GetFederationType returns the FederationType field if non-nil, zero value otherwise.

### GetFederationTypeOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetFederationTypeOk() (*string, bool)`

GetFederationTypeOk returns a tuple with the FederationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetFederationType(v string)`

SetFederationType sets FederationType field to given value.

### HasFederationType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasFederationType() bool`

HasFederationType returns a boolean if a field has been set.

### GetAuthType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetAuthType() string`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetAuthTypeOk() (*string, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetAuthType(v string)`

SetAuthType sets AuthType field to given value.

### HasAuthType

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasAuthType() bool`

HasAuthType returns a boolean if a field has been set.

### GetAuthSecretKey

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetAuthSecretKey() string`

GetAuthSecretKey returns the AuthSecretKey field if non-nil, zero value otherwise.

### GetAuthSecretKeyOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetAuthSecretKeyOk() (*string, bool)`

GetAuthSecretKeyOk returns a tuple with the AuthSecretKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthSecretKey

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetAuthSecretKey(v string)`

SetAuthSecretKey sets AuthSecretKey field to given value.

### HasAuthSecretKey

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasAuthSecretKey() bool`

HasAuthSecretKey returns a boolean if a field has been set.

### GetEndpointBaseurl

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointBaseurl() string`

GetEndpointBaseurl returns the EndpointBaseurl field if non-nil, zero value otherwise.

### GetEndpointBaseurlOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointBaseurlOk() (*string, bool)`

GetEndpointBaseurlOk returns a tuple with the EndpointBaseurl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointBaseurl

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEndpointBaseurl(v string)`

SetEndpointBaseurl sets EndpointBaseurl field to given value.

### HasEndpointBaseurl

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasEndpointBaseurl() bool`

HasEndpointBaseurl returns a boolean if a field has been set.

### GetEndpointDatasets

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointDatasets() string`

GetEndpointDatasets returns the EndpointDatasets field if non-nil, zero value otherwise.

### GetEndpointDatasetsOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointDatasetsOk() (*string, bool)`

GetEndpointDatasetsOk returns a tuple with the EndpointDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDatasets

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEndpointDatasets(v string)`

SetEndpointDatasets sets EndpointDatasets field to given value.

### HasEndpointDatasets

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasEndpointDatasets() bool`

HasEndpointDatasets returns a boolean if a field has been set.

### GetEndpointDataset

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointDataset() string`

GetEndpointDataset returns the EndpointDataset field if non-nil, zero value otherwise.

### GetEndpointDatasetOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEndpointDatasetOk() (*string, bool)`

GetEndpointDatasetOk returns a tuple with the EndpointDataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointDataset

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEndpointDataset(v string)`

SetEndpointDataset sets EndpointDataset field to given value.

### HasEndpointDataset

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasEndpointDataset() bool`

HasEndpointDataset returns a boolean if a field has been set.

### GetRunTimeHour

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetRunTimeHour() int32`

GetRunTimeHour returns the RunTimeHour field if non-nil, zero value otherwise.

### GetRunTimeHourOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetRunTimeHourOk() (*int32, bool)`

GetRunTimeHourOk returns a tuple with the RunTimeHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeHour

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetRunTimeHour(v int32)`

SetRunTimeHour sets RunTimeHour field to given value.

### HasRunTimeHour

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasRunTimeHour() bool`

HasRunTimeHour returns a boolean if a field has been set.

### GetRunTimeMinute

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetRunTimeMinute() string`

GetRunTimeMinute returns the RunTimeMinute field if non-nil, zero value otherwise.

### GetRunTimeMinuteOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetRunTimeMinuteOk() (*string, bool)`

GetRunTimeMinuteOk returns a tuple with the RunTimeMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunTimeMinute

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetRunTimeMinute(v string)`

SetRunTimeMinute sets RunTimeMinute field to given value.

### HasRunTimeMinute

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasRunTimeMinute() bool`

HasRunTimeMinute returns a boolean if a field has been set.

### GetEnabled

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetEnabledAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEnabledAt() time.Time`

GetEnabledAt returns the EnabledAt field if non-nil, zero value otherwise.

### GetEnabledAtOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetEnabledAtOk() (*time.Time, bool)`

GetEnabledAtOk returns a tuple with the EnabledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabledAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEnabledAt(v time.Time)`

SetEnabledAt sets EnabledAt field to given value.

### HasEnabledAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasEnabledAt() bool`

HasEnabledAt returns a boolean if a field has been set.

### SetEnabledAtNil

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetEnabledAtNil(b bool)`

 SetEnabledAtNil sets the value for EnabledAt to be an explicit nil

### UnsetEnabledAt
`func (o *GetFederationByFederationIdAndTeamId200ResponseData) UnsetEnabledAt()`

UnsetEnabledAt ensures that no value is present for EnabledAt, not even an explicit nil
### GetCounter

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetTested

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetTested() bool`

GetTested returns the Tested field if non-nil, zero value otherwise.

### GetTestedOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetTestedOk() (*bool, bool)`

GetTestedOk returns a tuple with the Tested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTested

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetTested(v bool)`

SetTested sets Tested field to given value.

### HasTested

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasTested() bool`

HasTested returns a boolean if a field has been set.

### GetNotifications

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetNotifications() []interface{}`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetNotificationsOk() (*[]interface{}, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetNotifications(v []interface{})`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetIsRunning

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetIsRunning() bool`

GetIsRunning returns the IsRunning field if non-nil, zero value otherwise.

### GetIsRunningOk

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) GetIsRunningOk() (*bool, bool)`

GetIsRunningOk returns a tuple with the IsRunning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRunning

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) SetIsRunning(v bool)`

SetIsRunning sets IsRunning field to given value.

### HasIsRunning

`func (o *GetFederationByFederationIdAndTeamId200ResponseData) HasIsRunning() bool`

HasIsRunning returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


