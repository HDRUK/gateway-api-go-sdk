# GetFederationHistory200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobUuid** | Pointer to **string** |  | [optional] 
**StartedAt** | Pointer to **time.Time** |  | [optional] 
**FinishedAt** | Pointer to **time.Time** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**FailedDatasets** | Pointer to [**[]GetFederationHistory200ResponseDataInnerFailedDatasetsInner**](GetFederationHistory200ResponseDataInnerFailedDatasetsInner.md) |  | [optional] 

## Methods

### NewGetFederationHistory200ResponseDataInner

`func NewGetFederationHistory200ResponseDataInner() *GetFederationHistory200ResponseDataInner`

NewGetFederationHistory200ResponseDataInner instantiates a new GetFederationHistory200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFederationHistory200ResponseDataInnerWithDefaults

`func NewGetFederationHistory200ResponseDataInnerWithDefaults() *GetFederationHistory200ResponseDataInner`

NewGetFederationHistory200ResponseDataInnerWithDefaults instantiates a new GetFederationHistory200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobUuid

`func (o *GetFederationHistory200ResponseDataInner) GetJobUuid() string`

GetJobUuid returns the JobUuid field if non-nil, zero value otherwise.

### GetJobUuidOk

`func (o *GetFederationHistory200ResponseDataInner) GetJobUuidOk() (*string, bool)`

GetJobUuidOk returns a tuple with the JobUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobUuid

`func (o *GetFederationHistory200ResponseDataInner) SetJobUuid(v string)`

SetJobUuid sets JobUuid field to given value.

### HasJobUuid

`func (o *GetFederationHistory200ResponseDataInner) HasJobUuid() bool`

HasJobUuid returns a boolean if a field has been set.

### GetStartedAt

`func (o *GetFederationHistory200ResponseDataInner) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GetFederationHistory200ResponseDataInner) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GetFederationHistory200ResponseDataInner) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *GetFederationHistory200ResponseDataInner) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### GetFinishedAt

`func (o *GetFederationHistory200ResponseDataInner) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GetFederationHistory200ResponseDataInner) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GetFederationHistory200ResponseDataInner) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *GetFederationHistory200ResponseDataInner) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### GetStatus

`func (o *GetFederationHistory200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetFederationHistory200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetFederationHistory200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetFederationHistory200ResponseDataInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetMessage

`func (o *GetFederationHistory200ResponseDataInner) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetFederationHistory200ResponseDataInner) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetFederationHistory200ResponseDataInner) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetFederationHistory200ResponseDataInner) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *GetFederationHistory200ResponseDataInner) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *GetFederationHistory200ResponseDataInner) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetFailedDatasets

`func (o *GetFederationHistory200ResponseDataInner) GetFailedDatasets() []GetFederationHistory200ResponseDataInnerFailedDatasetsInner`

GetFailedDatasets returns the FailedDatasets field if non-nil, zero value otherwise.

### GetFailedDatasetsOk

`func (o *GetFederationHistory200ResponseDataInner) GetFailedDatasetsOk() (*[]GetFederationHistory200ResponseDataInnerFailedDatasetsInner, bool)`

GetFailedDatasetsOk returns a tuple with the FailedDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedDatasets

`func (o *GetFederationHistory200ResponseDataInner) SetFailedDatasets(v []GetFederationHistory200ResponseDataInnerFailedDatasetsInner)`

SetFailedDatasets sets FailedDatasets field to given value.

### HasFailedDatasets

`func (o *GetFederationHistory200ResponseDataInner) HasFailedDatasets() bool`

HasFailedDatasets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


