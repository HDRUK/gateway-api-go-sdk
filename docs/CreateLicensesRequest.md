# CreateLicensesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Label** | **string** |  | 
**ValidSince** | **time.Time** |  | 
**ValidUntil** | Pointer to **time.Time** |  | [optional] 
**Definition** | **string** |  | 
**Origin** | **string** |  | 

## Methods

### NewCreateLicensesRequest

`func NewCreateLicensesRequest(code string, label string, validSince time.Time, definition string, origin string, ) *CreateLicensesRequest`

NewCreateLicensesRequest instantiates a new CreateLicensesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLicensesRequestWithDefaults

`func NewCreateLicensesRequestWithDefaults() *CreateLicensesRequest`

NewCreateLicensesRequestWithDefaults instantiates a new CreateLicensesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *CreateLicensesRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CreateLicensesRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CreateLicensesRequest) SetCode(v string)`

SetCode sets Code field to given value.


### GetLabel

`func (o *CreateLicensesRequest) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateLicensesRequest) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateLicensesRequest) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetValidSince

`func (o *CreateLicensesRequest) GetValidSince() time.Time`

GetValidSince returns the ValidSince field if non-nil, zero value otherwise.

### GetValidSinceOk

`func (o *CreateLicensesRequest) GetValidSinceOk() (*time.Time, bool)`

GetValidSinceOk returns a tuple with the ValidSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidSince

`func (o *CreateLicensesRequest) SetValidSince(v time.Time)`

SetValidSince sets ValidSince field to given value.


### GetValidUntil

`func (o *CreateLicensesRequest) GetValidUntil() time.Time`

GetValidUntil returns the ValidUntil field if non-nil, zero value otherwise.

### GetValidUntilOk

`func (o *CreateLicensesRequest) GetValidUntilOk() (*time.Time, bool)`

GetValidUntilOk returns a tuple with the ValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidUntil

`func (o *CreateLicensesRequest) SetValidUntil(v time.Time)`

SetValidUntil sets ValidUntil field to given value.

### HasValidUntil

`func (o *CreateLicensesRequest) HasValidUntil() bool`

HasValidUntil returns a boolean if a field has been set.

### GetDefinition

`func (o *CreateLicensesRequest) GetDefinition() string`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *CreateLicensesRequest) GetDefinitionOk() (*string, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *CreateLicensesRequest) SetDefinition(v string)`

SetDefinition sets Definition field to given value.


### GetOrigin

`func (o *CreateLicensesRequest) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *CreateLicensesRequest) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *CreateLicensesRequest) SetOrigin(v string)`

SetOrigin sets Origin field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


