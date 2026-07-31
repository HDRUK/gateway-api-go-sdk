# DataCustodianNetwork

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Summary** | Pointer to **NullableString** |  | [optional] 
**ImgUrl** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Service** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewDataCustodianNetwork

`func NewDataCustodianNetwork() *DataCustodianNetwork`

NewDataCustodianNetwork instantiates a new DataCustodianNetwork object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataCustodianNetworkWithDefaults

`func NewDataCustodianNetworkWithDefaults() *DataCustodianNetwork`

NewDataCustodianNetworkWithDefaults instantiates a new DataCustodianNetwork object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DataCustodianNetwork) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DataCustodianNetwork) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DataCustodianNetwork) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DataCustodianNetwork) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEnabled

`func (o *DataCustodianNetwork) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DataCustodianNetwork) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DataCustodianNetwork) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *DataCustodianNetwork) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetName

`func (o *DataCustodianNetwork) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DataCustodianNetwork) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DataCustodianNetwork) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DataCustodianNetwork) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSummary

`func (o *DataCustodianNetwork) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DataCustodianNetwork) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DataCustodianNetwork) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *DataCustodianNetwork) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *DataCustodianNetwork) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *DataCustodianNetwork) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetImgUrl

`func (o *DataCustodianNetwork) GetImgUrl() string`

GetImgUrl returns the ImgUrl field if non-nil, zero value otherwise.

### GetImgUrlOk

`func (o *DataCustodianNetwork) GetImgUrlOk() (*string, bool)`

GetImgUrlOk returns a tuple with the ImgUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImgUrl

`func (o *DataCustodianNetwork) SetImgUrl(v string)`

SetImgUrl sets ImgUrl field to given value.

### HasImgUrl

`func (o *DataCustodianNetwork) HasImgUrl() bool`

HasImgUrl returns a boolean if a field has been set.

### SetImgUrlNil

`func (o *DataCustodianNetwork) SetImgUrlNil(b bool)`

 SetImgUrlNil sets the value for ImgUrl to be an explicit nil

### UnsetImgUrl
`func (o *DataCustodianNetwork) UnsetImgUrl()`

UnsetImgUrl ensures that no value is present for ImgUrl, not even an explicit nil
### GetUrl

`func (o *DataCustodianNetwork) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *DataCustodianNetwork) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *DataCustodianNetwork) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *DataCustodianNetwork) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *DataCustodianNetwork) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *DataCustodianNetwork) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetService

`func (o *DataCustodianNetwork) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *DataCustodianNetwork) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *DataCustodianNetwork) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *DataCustodianNetwork) HasService() bool`

HasService returns a boolean if a field has been set.

### SetServiceNil

`func (o *DataCustodianNetwork) SetServiceNil(b bool)`

 SetServiceNil sets the value for Service to be an explicit nil

### UnsetService
`func (o *DataCustodianNetwork) UnsetService()`

UnsetService ensures that no value is present for Service, not even an explicit nil
### GetCreatedAt

`func (o *DataCustodianNetwork) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DataCustodianNetwork) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DataCustodianNetwork) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DataCustodianNetwork) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DataCustodianNetwork) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DataCustodianNetwork) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DataCustodianNetwork) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DataCustodianNetwork) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


