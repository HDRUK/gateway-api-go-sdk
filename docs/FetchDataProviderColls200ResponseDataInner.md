# FetchDataProviderColls200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Summary** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Service** | Pointer to **string** |  | [optional] 

## Methods

### NewFetchDataProviderColls200ResponseDataInner

`func NewFetchDataProviderColls200ResponseDataInner() *FetchDataProviderColls200ResponseDataInner`

NewFetchDataProviderColls200ResponseDataInner instantiates a new FetchDataProviderColls200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchDataProviderColls200ResponseDataInnerWithDefaults

`func NewFetchDataProviderColls200ResponseDataInnerWithDefaults() *FetchDataProviderColls200ResponseDataInner`

NewFetchDataProviderColls200ResponseDataInnerWithDefaults instantiates a new FetchDataProviderColls200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchDataProviderColls200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchDataProviderColls200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchDataProviderColls200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchDataProviderColls200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchDataProviderColls200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchDataProviderColls200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchDataProviderColls200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetName

`func (o *FetchDataProviderColls200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FetchDataProviderColls200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FetchDataProviderColls200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSummary

`func (o *FetchDataProviderColls200ResponseDataInner) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *FetchDataProviderColls200ResponseDataInner) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *FetchDataProviderColls200ResponseDataInner) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetEnabled

`func (o *FetchDataProviderColls200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FetchDataProviderColls200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *FetchDataProviderColls200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetService

`func (o *FetchDataProviderColls200ResponseDataInner) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *FetchDataProviderColls200ResponseDataInner) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *FetchDataProviderColls200ResponseDataInner) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *FetchDataProviderColls200ResponseDataInner) HasService() bool`

HasService returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


