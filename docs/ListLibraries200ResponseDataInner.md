# ListLibraries200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**DatasetId** | Pointer to **string** |  | [optional] 
**DatasetStatus** | Pointer to **string** |  | [optional] 
**DataProviderId** | Pointer to **string** |  | [optional] 
**DataProviderDarStatus** | Pointer to **bool** |  | [optional] 
**DataProviderName** | Pointer to **string** |  | [optional] 

## Methods

### NewListLibraries200ResponseDataInner

`func NewListLibraries200ResponseDataInner() *ListLibraries200ResponseDataInner`

NewListLibraries200ResponseDataInner instantiates a new ListLibraries200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListLibraries200ResponseDataInnerWithDefaults

`func NewListLibraries200ResponseDataInnerWithDefaults() *ListLibraries200ResponseDataInner`

NewListLibraries200ResponseDataInnerWithDefaults instantiates a new ListLibraries200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListLibraries200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListLibraries200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListLibraries200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ListLibraries200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ListLibraries200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListLibraries200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListLibraries200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ListLibraries200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ListLibraries200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListLibraries200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListLibraries200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ListLibraries200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetUserId

`func (o *ListLibraries200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ListLibraries200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ListLibraries200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *ListLibraries200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetDatasetId

`func (o *ListLibraries200ResponseDataInner) GetDatasetId() string`

GetDatasetId returns the DatasetId field if non-nil, zero value otherwise.

### GetDatasetIdOk

`func (o *ListLibraries200ResponseDataInner) GetDatasetIdOk() (*string, bool)`

GetDatasetIdOk returns a tuple with the DatasetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetId

`func (o *ListLibraries200ResponseDataInner) SetDatasetId(v string)`

SetDatasetId sets DatasetId field to given value.

### HasDatasetId

`func (o *ListLibraries200ResponseDataInner) HasDatasetId() bool`

HasDatasetId returns a boolean if a field has been set.

### GetDatasetStatus

`func (o *ListLibraries200ResponseDataInner) GetDatasetStatus() string`

GetDatasetStatus returns the DatasetStatus field if non-nil, zero value otherwise.

### GetDatasetStatusOk

`func (o *ListLibraries200ResponseDataInner) GetDatasetStatusOk() (*string, bool)`

GetDatasetStatusOk returns a tuple with the DatasetStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetStatus

`func (o *ListLibraries200ResponseDataInner) SetDatasetStatus(v string)`

SetDatasetStatus sets DatasetStatus field to given value.

### HasDatasetStatus

`func (o *ListLibraries200ResponseDataInner) HasDatasetStatus() bool`

HasDatasetStatus returns a boolean if a field has been set.

### GetDataProviderId

`func (o *ListLibraries200ResponseDataInner) GetDataProviderId() string`

GetDataProviderId returns the DataProviderId field if non-nil, zero value otherwise.

### GetDataProviderIdOk

`func (o *ListLibraries200ResponseDataInner) GetDataProviderIdOk() (*string, bool)`

GetDataProviderIdOk returns a tuple with the DataProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataProviderId

`func (o *ListLibraries200ResponseDataInner) SetDataProviderId(v string)`

SetDataProviderId sets DataProviderId field to given value.

### HasDataProviderId

`func (o *ListLibraries200ResponseDataInner) HasDataProviderId() bool`

HasDataProviderId returns a boolean if a field has been set.

### GetDataProviderDarStatus

`func (o *ListLibraries200ResponseDataInner) GetDataProviderDarStatus() bool`

GetDataProviderDarStatus returns the DataProviderDarStatus field if non-nil, zero value otherwise.

### GetDataProviderDarStatusOk

`func (o *ListLibraries200ResponseDataInner) GetDataProviderDarStatusOk() (*bool, bool)`

GetDataProviderDarStatusOk returns a tuple with the DataProviderDarStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataProviderDarStatus

`func (o *ListLibraries200ResponseDataInner) SetDataProviderDarStatus(v bool)`

SetDataProviderDarStatus sets DataProviderDarStatus field to given value.

### HasDataProviderDarStatus

`func (o *ListLibraries200ResponseDataInner) HasDataProviderDarStatus() bool`

HasDataProviderDarStatus returns a boolean if a field has been set.

### GetDataProviderName

`func (o *ListLibraries200ResponseDataInner) GetDataProviderName() string`

GetDataProviderName returns the DataProviderName field if non-nil, zero value otherwise.

### GetDataProviderNameOk

`func (o *ListLibraries200ResponseDataInner) GetDataProviderNameOk() (*string, bool)`

GetDataProviderNameOk returns a tuple with the DataProviderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataProviderName

`func (o *ListLibraries200ResponseDataInner) SetDataProviderName(v string)`

SetDataProviderName sets DataProviderName field to given value.

### HasDataProviderName

`func (o *ListLibraries200ResponseDataInner) HasDataProviderName() bool`

HasDataProviderName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


