# LoginRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** | Email address | [optional] 
**Password** | Pointer to **string** | Password | [optional] 
**Provider** | Pointer to **string** | Optional. Set to &#39;cruk&#39; for CRUK login only; otherwise ignored (service). | [optional] 

## Methods

### NewLoginRequest

`func NewLoginRequest() *LoginRequest`

NewLoginRequest instantiates a new LoginRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginRequestWithDefaults

`func NewLoginRequestWithDefaults() *LoginRequest`

NewLoginRequestWithDefaults instantiates a new LoginRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *LoginRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *LoginRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *LoginRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *LoginRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetPassword

`func (o *LoginRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *LoginRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *LoginRequest) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *LoginRequest) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetProvider

`func (o *LoginRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *LoginRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *LoginRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *LoginRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


