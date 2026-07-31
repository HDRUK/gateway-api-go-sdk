# EditNotificationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationType** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**OptIn** | Pointer to **bool** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 

## Methods

### NewEditNotificationsRequest

`func NewEditNotificationsRequest() *EditNotificationsRequest`

NewEditNotificationsRequest instantiates a new EditNotificationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditNotificationsRequestWithDefaults

`func NewEditNotificationsRequestWithDefaults() *EditNotificationsRequest`

NewEditNotificationsRequestWithDefaults instantiates a new EditNotificationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationType

`func (o *EditNotificationsRequest) GetNotificationType() string`

GetNotificationType returns the NotificationType field if non-nil, zero value otherwise.

### GetNotificationTypeOk

`func (o *EditNotificationsRequest) GetNotificationTypeOk() (*string, bool)`

GetNotificationTypeOk returns a tuple with the NotificationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationType

`func (o *EditNotificationsRequest) SetNotificationType(v string)`

SetNotificationType sets NotificationType field to given value.

### HasNotificationType

`func (o *EditNotificationsRequest) HasNotificationType() bool`

HasNotificationType returns a boolean if a field has been set.

### GetMessage

`func (o *EditNotificationsRequest) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *EditNotificationsRequest) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *EditNotificationsRequest) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *EditNotificationsRequest) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetOptIn

`func (o *EditNotificationsRequest) GetOptIn() bool`

GetOptIn returns the OptIn field if non-nil, zero value otherwise.

### GetOptInOk

`func (o *EditNotificationsRequest) GetOptInOk() (*bool, bool)`

GetOptInOk returns a tuple with the OptIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptIn

`func (o *EditNotificationsRequest) SetOptIn(v bool)`

SetOptIn sets OptIn field to given value.

### HasOptIn

`func (o *EditNotificationsRequest) HasOptIn() bool`

HasOptIn returns a boolean if a field has been set.

### GetEnabled

`func (o *EditNotificationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditNotificationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditNotificationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditNotificationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetEmail

`func (o *EditNotificationsRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EditNotificationsRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EditNotificationsRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EditNotificationsRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


