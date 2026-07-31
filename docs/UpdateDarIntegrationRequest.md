# UpdateDarIntegrationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **int32** |  | 
**NotificationEmail** | **string** |  | 
**OutboundAuthType** | **string** |  | 
**OutboundAuthKey** | **string** |  | 
**OutboundEndpointsBaseUrl** | **string** |  | 
**OutboundEndpointsEnquiry** | **string** |  | 
**OutboundEndpoints5safes** | **string** |  | 
**OutboundEndpoints5safesFiles** | **string** |  | 
**InboundServiceAccountId** | **string** |  | 

## Methods

### NewUpdateDarIntegrationRequest

`func NewUpdateDarIntegrationRequest(enabled int32, notificationEmail string, outboundAuthType string, outboundAuthKey string, outboundEndpointsBaseUrl string, outboundEndpointsEnquiry string, outboundEndpoints5safes string, outboundEndpoints5safesFiles string, inboundServiceAccountId string, ) *UpdateDarIntegrationRequest`

NewUpdateDarIntegrationRequest instantiates a new UpdateDarIntegrationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDarIntegrationRequestWithDefaults

`func NewUpdateDarIntegrationRequestWithDefaults() *UpdateDarIntegrationRequest`

NewUpdateDarIntegrationRequestWithDefaults instantiates a new UpdateDarIntegrationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *UpdateDarIntegrationRequest) GetEnabled() int32`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateDarIntegrationRequest) GetEnabledOk() (*int32, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateDarIntegrationRequest) SetEnabled(v int32)`

SetEnabled sets Enabled field to given value.


### GetNotificationEmail

`func (o *UpdateDarIntegrationRequest) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *UpdateDarIntegrationRequest) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *UpdateDarIntegrationRequest) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.


### GetOutboundAuthType

`func (o *UpdateDarIntegrationRequest) GetOutboundAuthType() string`

GetOutboundAuthType returns the OutboundAuthType field if non-nil, zero value otherwise.

### GetOutboundAuthTypeOk

`func (o *UpdateDarIntegrationRequest) GetOutboundAuthTypeOk() (*string, bool)`

GetOutboundAuthTypeOk returns a tuple with the OutboundAuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthType

`func (o *UpdateDarIntegrationRequest) SetOutboundAuthType(v string)`

SetOutboundAuthType sets OutboundAuthType field to given value.


### GetOutboundAuthKey

`func (o *UpdateDarIntegrationRequest) GetOutboundAuthKey() string`

GetOutboundAuthKey returns the OutboundAuthKey field if non-nil, zero value otherwise.

### GetOutboundAuthKeyOk

`func (o *UpdateDarIntegrationRequest) GetOutboundAuthKeyOk() (*string, bool)`

GetOutboundAuthKeyOk returns a tuple with the OutboundAuthKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundAuthKey

`func (o *UpdateDarIntegrationRequest) SetOutboundAuthKey(v string)`

SetOutboundAuthKey sets OutboundAuthKey field to given value.


### GetOutboundEndpointsBaseUrl

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpointsBaseUrl() string`

GetOutboundEndpointsBaseUrl returns the OutboundEndpointsBaseUrl field if non-nil, zero value otherwise.

### GetOutboundEndpointsBaseUrlOk

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpointsBaseUrlOk() (*string, bool)`

GetOutboundEndpointsBaseUrlOk returns a tuple with the OutboundEndpointsBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsBaseUrl

`func (o *UpdateDarIntegrationRequest) SetOutboundEndpointsBaseUrl(v string)`

SetOutboundEndpointsBaseUrl sets OutboundEndpointsBaseUrl field to given value.


### GetOutboundEndpointsEnquiry

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpointsEnquiry() string`

GetOutboundEndpointsEnquiry returns the OutboundEndpointsEnquiry field if non-nil, zero value otherwise.

### GetOutboundEndpointsEnquiryOk

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpointsEnquiryOk() (*string, bool)`

GetOutboundEndpointsEnquiryOk returns a tuple with the OutboundEndpointsEnquiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpointsEnquiry

`func (o *UpdateDarIntegrationRequest) SetOutboundEndpointsEnquiry(v string)`

SetOutboundEndpointsEnquiry sets OutboundEndpointsEnquiry field to given value.


### GetOutboundEndpoints5safes

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpoints5safes() string`

GetOutboundEndpoints5safes returns the OutboundEndpoints5safes field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesOk

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpoints5safesOk() (*string, bool)`

GetOutboundEndpoints5safesOk returns a tuple with the OutboundEndpoints5safes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safes

`func (o *UpdateDarIntegrationRequest) SetOutboundEndpoints5safes(v string)`

SetOutboundEndpoints5safes sets OutboundEndpoints5safes field to given value.


### GetOutboundEndpoints5safesFiles

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpoints5safesFiles() string`

GetOutboundEndpoints5safesFiles returns the OutboundEndpoints5safesFiles field if non-nil, zero value otherwise.

### GetOutboundEndpoints5safesFilesOk

`func (o *UpdateDarIntegrationRequest) GetOutboundEndpoints5safesFilesOk() (*string, bool)`

GetOutboundEndpoints5safesFilesOk returns a tuple with the OutboundEndpoints5safesFiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundEndpoints5safesFiles

`func (o *UpdateDarIntegrationRequest) SetOutboundEndpoints5safesFiles(v string)`

SetOutboundEndpoints5safesFiles sets OutboundEndpoints5safesFiles field to given value.


### GetInboundServiceAccountId

`func (o *UpdateDarIntegrationRequest) GetInboundServiceAccountId() string`

GetInboundServiceAccountId returns the InboundServiceAccountId field if non-nil, zero value otherwise.

### GetInboundServiceAccountIdOk

`func (o *UpdateDarIntegrationRequest) GetInboundServiceAccountIdOk() (*string, bool)`

GetInboundServiceAccountIdOk returns a tuple with the InboundServiceAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundServiceAccountId

`func (o *UpdateDarIntegrationRequest) SetInboundServiceAccountId(v string)`

SetInboundServiceAccountId sets InboundServiceAccountId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


