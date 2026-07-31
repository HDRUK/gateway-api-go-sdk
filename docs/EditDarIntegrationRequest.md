# EditDarIntegrationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **int32** |  | [optional] 
**NotificationEmail** | Pointer to **string** |  | [optional] 
**OutboundAuthType** | Pointer to **string** |  | [optional] 
**OutboundAuthKey** | Pointer to **string** |  | [optional] 
**OutboundEndpointsBaseUrl** | Pointer to **string** |  | [optional] 
**OutboundEndpointsEnquiry** | Pointer to **string** |  | [optional] 
**OutboundEndpoints5safes** | Pointer to **string** |  | [optional] 
**OutboundEndpoints5safesFiles** | Pointer to **string** |  | [optional] 
**InboundServiceAccountId** | Pointer to **string** |  | [optional] 

## Methods

### NewEditDarIntegrationRequest

`func NewEditDarIntegrationRequest() *EditDarIntegrationRequest`

NewEditDarIntegrationRequest instantiates a new EditDarIntegrationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditDarIntegrationRequestWithDefaults

`func NewEditDarIntegrationRequestWithDefaults() *EditDarIntegrationRequest`

NewEditDarIntegrationRequestWithDefaults instantiates a new EditDarIntegrationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *EditDarIntegrationRequest) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditDarIntegrationRequest) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditDarIntegrationRequest) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditDarIntegrationRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetNotificationEmail

`func (o *EditDarIntegrationRequest) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *EditDarIntegrationRequest) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *EditDarIntegrationRequest) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *EditDarIntegrationRequest) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### GetOutboundAuthType

`func (o *EditDarIntegrationRequest) GetOutboundAuthType() string`

GetOutboundAuthType returns the OutboundAuthType field if non-nil, zero value otherwise.

### GetOutboundAuthTypeOk

`func (o *EditDarIntegrationRequest) GetOutboundAuthTypeOk() (*string, bool)`

GetOutboundAuthTypeOk returns a tuple with the OutboundAuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthType

`func (o *EditDarIntegrationRequest) SetOutboundAuthType(v string)`

SetOutboundAuthType sets OutboundAuthType field to given value.

### HasOutboundAuthType

`func (o *EditDarIntegrationRequest) HasOutboundAuthType() bool`

HasOutboundAuthType returns a boolean if a field has been set.

### GetOutboundAuthKey

`func (o *EditDarIntegrationRequest) GetOutboundAuthKey() string`

GetOutboundAuthKey returns the OutboundAuthKey field if non-nil, zero value otherwise.

### GetOutboundAuthKeyOk

`func (o *EditDarIntegrationRequest) GetOutboundAuthKeyOk() (*string, bool)`

GetOutboundAuthKeyOk returns a tuple with the OutboundAuthKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthKey

`func (o *EditDarIntegrationRequest) SetOutboundAuthKey(v string)`

SetOutboundAuthKey sets OutboundAuthKey field to given value.

### HasOutboundAuthKey

`func (o *EditDarIntegrationRequest) HasOutboundAuthKey() bool`

HasOutboundAuthKey returns a boolean if a field has been set.

### GetOutboundEndpointsBaseUrl

`func (o *EditDarIntegrationRequest) GetOutboundEndpointsBaseUrl() string`

GetOutboundEndpointsBaseUrl returns the OutboundEndpointsBaseUrl field if non-nil, zero value otherwise.

### GetOutboundEndpointsBaseUrlOk

`func (o *EditDarIntegrationRequest) GetOutboundEndpointsBaseUrlOk() (*string, bool)`

GetOutboundEndpointsBaseUrlOk returns a tuple with the OutboundEndpointsBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsBaseUrl

`func (o *EditDarIntegrationRequest) SetOutboundEndpointsBaseUrl(v string)`

SetOutboundEndpointsBaseUrl sets OutboundEndpointsBaseUrl field to given value.

### HasOutboundEndpointsBaseUrl

`func (o *EditDarIntegrationRequest) HasOutboundEndpointsBaseUrl() bool`

HasOutboundEndpointsBaseUrl returns a boolean if a field has been set.

### GetOutboundEndpointsEnquiry

`func (o *EditDarIntegrationRequest) GetOutboundEndpointsEnquiry() string`

GetOutboundEndpointsEnquiry returns the OutboundEndpointsEnquiry field if non-nil, zero value otherwise.

### GetOutboundEndpointsEnquiryOk

`func (o *EditDarIntegrationRequest) GetOutboundEndpointsEnquiryOk() (*string, bool)`

GetOutboundEndpointsEnquiryOk returns a tuple with the OutboundEndpointsEnquiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsEnquiry

`func (o *EditDarIntegrationRequest) SetOutboundEndpointsEnquiry(v string)`

SetOutboundEndpointsEnquiry sets OutboundEndpointsEnquiry field to given value.

### HasOutboundEndpointsEnquiry

`func (o *EditDarIntegrationRequest) HasOutboundEndpointsEnquiry() bool`

HasOutboundEndpointsEnquiry returns a boolean if a field has been set.

### GetOutboundEndpoints5safes

`func (o *EditDarIntegrationRequest) GetOutboundEndpoints5safes() string`

GetOutboundEndpoints5safes returns the OutboundEndpoints5safes field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesOk

`func (o *EditDarIntegrationRequest) GetOutboundEndpoints5safesOk() (*string, bool)`

GetOutboundEndpoints5safesOk returns a tuple with the OutboundEndpoints5safes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safes

`func (o *EditDarIntegrationRequest) SetOutboundEndpoints5safes(v string)`

SetOutboundEndpoints5safes sets OutboundEndpoints5safes field to given value.

### HasOutboundEndpoints5safes

`func (o *EditDarIntegrationRequest) HasOutboundEndpoints5safes() bool`

HasOutboundEndpoints5safes returns a boolean if a field has been set.

### GetOutboundEndpoints5safesFiles

`func (o *EditDarIntegrationRequest) GetOutboundEndpoints5safesFiles() string`

GetOutboundEndpoints5safesFiles returns the OutboundEndpoints5safesFiles field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesFilesOk

`func (o *EditDarIntegrationRequest) GetOutboundEndpoints5safesFilesOk() (*string, bool)`

GetOutboundEndpoints5safesFilesOk returns a tuple with the OutboundEndpoints5safesFiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safesFiles

`func (o *EditDarIntegrationRequest) SetOutboundEndpoints5safesFiles(v string)`

SetOutboundEndpoints5safesFiles sets OutboundEndpoints5safesFiles field to given value.

### HasOutboundEndpoints5safesFiles

`func (o *EditDarIntegrationRequest) HasOutboundEndpoints5safesFiles() bool`

HasOutboundEndpoints5safesFiles returns a boolean if a field has been set.

### GetInboundServiceAccountId

`func (o *EditDarIntegrationRequest) GetInboundServiceAccountId() string`

GetInboundServiceAccountId returns the InboundServiceAccountId field if non-nil, zero value otherwise.

### GetInboundServiceAccountIdOk

`func (o *EditDarIntegrationRequest) GetInboundServiceAccountIdOk() (*string, bool)`

GetInboundServiceAccountIdOk returns a tuple with the InboundServiceAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundServiceAccountId

`func (o *EditDarIntegrationRequest) SetInboundServiceAccountId(v string)`

SetInboundServiceAccountId sets InboundServiceAccountId field to given value.

### HasInboundServiceAccountId

`func (o *EditDarIntegrationRequest) HasInboundServiceAccountId() bool`

HasInboundServiceAccountId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


