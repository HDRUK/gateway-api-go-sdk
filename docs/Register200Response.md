# Register200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | Pointer to **string** |  | [optional] 
**TokenType** | Pointer to **string** |  | [optional] 
**User** | Pointer to [**Register200ResponseUser**](Register200ResponseUser.md) |  | [optional] 

## Methods

### NewRegister200Response

`func NewRegister200Response() *Register200Response`

NewRegister200Response instantiates a new Register200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegister200ResponseWithDefaults

`func NewRegister200ResponseWithDefaults() *Register200Response`

NewRegister200ResponseWithDefaults instantiates a new Register200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *Register200Response) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *Register200Response) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *Register200Response) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.

### HasAccessToken

`func (o *Register200Response) HasAccessToken() bool`

HasAccessToken returns a boolean if a field has been set.

### GetTokenType

`func (o *Register200Response) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *Register200Response) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *Register200Response) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.

### HasTokenType

`func (o *Register200Response) HasTokenType() bool`

HasTokenType returns a boolean if a field has been set.

### GetUser

`func (o *Register200Response) GetUser() Register200ResponseUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *Register200Response) GetUserOk() (*Register200ResponseUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *Register200Response) SetUser(v Register200ResponseUser)`

SetUser sets User field to given value.

### HasUser

`func (o *Register200Response) HasUser() bool`

HasUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


