# CreateNotificationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationType** | **string** |  | 
**Message** | **string** |  | 
**OptIn** | **bool** |  | 
**Enabled** | **bool** |  | 
**Email** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateNotificationsRequest

`func NewCreateNotificationsRequest(notificationType string, message string, optIn bool, enabled bool, ) *CreateNotificationsRequest`

NewCreateNotificationsRequest instantiates a new CreateNotificationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateNotificationsRequestWithDefaults

`func NewCreateNotificationsRequestWithDefaults() *CreateNotificationsRequest`

NewCreateNotificationsRequestWithDefaults instantiates a new CreateNotificationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationType

`func (o *CreateNotificationsRequest) GetNotificationType() string`

GetNotificationType returns the NotificationType field if non-nil, zero value otherwise.

### GetNotificationTypeOk

`func (o *CreateNotificationsRequest) GetNotificationTypeOk() (*string, bool)`

GetNotificationTypeOk returns a tuple with the NotificationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationType

`func (o *CreateNotificationsRequest) SetNotificationType(v string)`

SetNotificationType sets NotificationType field to given value.


### GetMessage

`func (o *CreateNotificationsRequest) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateNotificationsRequest) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateNotificationsRequest) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetOptIn

`func (o *CreateNotificationsRequest) GetOptIn() bool`

GetOptIn returns the OptIn field if non-nil, zero value otherwise.

### GetOptInOk

`func (o *CreateNotificationsRequest) GetOptInOk() (*bool, bool)`

GetOptInOk returns a tuple with the OptIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptIn

`func (o *CreateNotificationsRequest) SetOptIn(v bool)`

SetOptIn sets OptIn field to given value.


### GetEnabled

`func (o *CreateNotificationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateNotificationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateNotificationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetEmail

`func (o *CreateNotificationsRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateNotificationsRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateNotificationsRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateNotificationsRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


