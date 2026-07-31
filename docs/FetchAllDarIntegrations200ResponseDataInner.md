# FetchAllDarIntegrations200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**NotificationEmail** | Pointer to **string** |  | [optional] 
**OutboundAuthType** | Pointer to **string** |  | [optional] 
**OutboundAuthKey** | Pointer to **string** |  | [optional] 
**OutboundEndpointsBaseUrl** | Pointer to **string** |  | [optional] 
**OutboundEndpointsEnquiry** | Pointer to **string** |  | [optional] 
**OutboundEndpoints5safes** | Pointer to **string** |  | [optional] 
**OutboundEndpoints5safesFiles** | Pointer to **string** |  | [optional] 
**InboundServiceAccountId** | Pointer to **string** |  | [optional] 

## Methods

### NewFetchAllDarIntegrations200ResponseDataInner

`func NewFetchAllDarIntegrations200ResponseDataInner() *FetchAllDarIntegrations200ResponseDataInner`

NewFetchAllDarIntegrations200ResponseDataInner instantiates a new FetchAllDarIntegrations200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllDarIntegrations200ResponseDataInnerWithDefaults

`func NewFetchAllDarIntegrations200ResponseDataInnerWithDefaults() *FetchAllDarIntegrations200ResponseDataInner`

NewFetchAllDarIntegrations200ResponseDataInnerWithDefaults instantiates a new FetchAllDarIntegrations200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetEnabled

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetNotificationEmail

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### GetOutboundAuthType

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundAuthType() string`

GetOutboundAuthType returns the OutboundAuthType field if non-nil, zero value otherwise.

### GetOutboundAuthTypeOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundAuthTypeOk() (*string, bool)`

GetOutboundAuthTypeOk returns a tuple with the OutboundAuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthType

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundAuthType(v string)`

SetOutboundAuthType sets OutboundAuthType field to given value.

### HasOutboundAuthType

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundAuthType() bool`

HasOutboundAuthType returns a boolean if a field has been set.

### GetOutboundAuthKey

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundAuthKey() string`

GetOutboundAuthKey returns the OutboundAuthKey field if non-nil, zero value otherwise.

### GetOutboundAuthKeyOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundAuthKeyOk() (*string, bool)`

GetOutboundAuthKeyOk returns a tuple with the OutboundAuthKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthKey

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundAuthKey(v string)`

SetOutboundAuthKey sets OutboundAuthKey field to given value.

### HasOutboundAuthKey

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundAuthKey() bool`

HasOutboundAuthKey returns a boolean if a field has been set.

### GetOutboundEndpointsBaseUrl

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpointsBaseUrl() string`

GetOutboundEndpointsBaseUrl returns the OutboundEndpointsBaseUrl field if non-nil, zero value otherwise.

### GetOutboundEndpointsBaseUrlOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpointsBaseUrlOk() (*string, bool)`

GetOutboundEndpointsBaseUrlOk returns a tuple with the OutboundEndpointsBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsBaseUrl

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundEndpointsBaseUrl(v string)`

SetOutboundEndpointsBaseUrl sets OutboundEndpointsBaseUrl field to given value.

### HasOutboundEndpointsBaseUrl

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundEndpointsBaseUrl() bool`

HasOutboundEndpointsBaseUrl returns a boolean if a field has been set.

### GetOutboundEndpointsEnquiry

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpointsEnquiry() string`

GetOutboundEndpointsEnquiry returns the OutboundEndpointsEnquiry field if non-nil, zero value otherwise.

### GetOutboundEndpointsEnquiryOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpointsEnquiryOk() (*string, bool)`

GetOutboundEndpointsEnquiryOk returns a tuple with the OutboundEndpointsEnquiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsEnquiry

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundEndpointsEnquiry(v string)`

SetOutboundEndpointsEnquiry sets OutboundEndpointsEnquiry field to given value.

### HasOutboundEndpointsEnquiry

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundEndpointsEnquiry() bool`

HasOutboundEndpointsEnquiry returns a boolean if a field has been set.

### GetOutboundEndpoints5safes

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpoints5safes() string`

GetOutboundEndpoints5safes returns the OutboundEndpoints5safes field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpoints5safesOk() (*string, bool)`

GetOutboundEndpoints5safesOk returns a tuple with the OutboundEndpoints5safes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safes

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundEndpoints5safes(v string)`

SetOutboundEndpoints5safes sets OutboundEndpoints5safes field to given value.

### HasOutboundEndpoints5safes

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundEndpoints5safes() bool`

HasOutboundEndpoints5safes returns a boolean if a field has been set.

### GetOutboundEndpoints5safesFiles

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpoints5safesFiles() string`

GetOutboundEndpoints5safesFiles returns the OutboundEndpoints5safesFiles field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesFilesOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetOutboundEndpoints5safesFilesOk() (*string, bool)`

GetOutboundEndpoints5safesFilesOk returns a tuple with the OutboundEndpoints5safesFiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safesFiles

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetOutboundEndpoints5safesFiles(v string)`

SetOutboundEndpoints5safesFiles sets OutboundEndpoints5safesFiles field to given value.

### HasOutboundEndpoints5safesFiles

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasOutboundEndpoints5safesFiles() bool`

HasOutboundEndpoints5safesFiles returns a boolean if a field has been set.

### GetInboundServiceAccountId

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetInboundServiceAccountId() string`

GetInboundServiceAccountId returns the InboundServiceAccountId field if non-nil, zero value otherwise.

### GetInboundServiceAccountIdOk

`func (o *FetchAllDarIntegrations200ResponseDataInner) GetInboundServiceAccountIdOk() (*string, bool)`

GetInboundServiceAccountIdOk returns a tuple with the InboundServiceAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundServiceAccountId

`func (o *FetchAllDarIntegrations200ResponseDataInner) SetInboundServiceAccountId(v string)`

SetInboundServiceAccountId sets InboundServiceAccountId field to given value.

### HasInboundServiceAccountId

`func (o *FetchAllDarIntegrations200ResponseDataInner) HasInboundServiceAccountId() bool`

HasInboundServiceAccountId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


