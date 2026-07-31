# RegisterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** | Email address | [optional] 
**Password** | Pointer to **string** | Password (minimum 8 characters) | [optional] 
**Firstname** | Pointer to **string** | First name (optional) | [optional] 
**Lastname** | Pointer to **string** | Last name (optional) | [optional] 
**Provider** | Pointer to **string** | Optional. Set to &#39;cruk&#39; for CRUK registration only; otherwise ignored (service). | [optional] 

## Methods

### NewRegisterRequest

`func NewRegisterRequest() *RegisterRequest`

NewRegisterRequest instantiates a new RegisterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegisterRequestWithDefaults

`func NewRegisterRequestWithDefaults() *RegisterRequest`

NewRegisterRequestWithDefaults instantiates a new RegisterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *RegisterRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *RegisterRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *RegisterRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *RegisterRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetPassword

`func (o *RegisterRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *RegisterRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *RegisterRequest) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *RegisterRequest) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetFirstname

`func (o *RegisterRequest) GetFirstname() string`

GetFirstname returns the Firstname field if non-nil, zero value otherwise.

### GetFirstnameOk

`func (o *RegisterRequest) GetFirstnameOk() (*string, bool)`

GetFirstnameOk returns a tuple with the Firstname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstname

`func (o *RegisterRequest) SetFirstname(v string)`

SetFirstname sets Firstname field to given value.

### HasFirstname

`func (o *RegisterRequest) HasFirstname() bool`

HasFirstname returns a boolean if a field has been set.

### GetLastname

`func (o *RegisterRequest) GetLastname() string`

GetLastname returns the Lastname field if non-nil, zero value otherwise.

### GetLastnameOk

`func (o *RegisterRequest) GetLastnameOk() (*string, bool)`

GetLastnameOk returns a tuple with the Lastname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastname

`func (o *RegisterRequest) SetLastname(v string)`

SetLastname sets Lastname field to given value.

### HasLastname

`func (o *RegisterRequest) HasLastname() bool`

HasLastname returns a boolean if a field has been set.

### GetProvider

`func (o *RegisterRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *RegisterRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *RegisterRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *RegisterRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


