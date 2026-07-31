# License

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **NullableString** |  | [optional] 
**ValidSince** | Pointer to **NullableTime** |  | [optional] 
**ValidUntil** | Pointer to **NullableTime** |  | [optional] 
**Definition** | Pointer to **NullableString** |  | [optional] 
**Verified** | Pointer to **bool** |  | [optional] 
**Origin** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewLicense

`func NewLicense() *License`

NewLicense instantiates a new License object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseWithDefaults

`func NewLicenseWithDefaults() *License`

NewLicenseWithDefaults instantiates a new License object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *License) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *License) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *License) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *License) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCode

`func (o *License) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *License) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *License) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *License) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetLabel

`func (o *License) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *License) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *License) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *License) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *License) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *License) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetValidSince

`func (o *License) GetValidSince() time.Time`

GetValidSince returns the ValidSince field if non-nil, zero value otherwise.

### GetValidSinceOk

`func (o *License) GetValidSinceOk() (*time.Time, bool)`

GetValidSinceOk returns a tuple with the ValidSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidSince

`func (o *License) SetValidSince(v time.Time)`

SetValidSince sets ValidSince field to given value.

### HasValidSince

`func (o *License) HasValidSince() bool`

HasValidSince returns a boolean if a field has been set.

### SetValidSinceNil

`func (o *License) SetValidSinceNil(b bool)`

 SetValidSinceNil sets the value for ValidSince to be an explicit nil

### UnsetValidSince
`func (o *License) UnsetValidSince()`

UnsetValidSince ensures that no value is present for ValidSince, not even an explicit nil
### GetValidUntil

`func (o *License) GetValidUntil() time.Time`

GetValidUntil returns the ValidUntil field if non-nil, zero value otherwise.

### GetValidUntilOk

`func (o *License) GetValidUntilOk() (*time.Time, bool)`

GetValidUntilOk returns a tuple with the ValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidUntil

`func (o *License) SetValidUntil(v time.Time)`

SetValidUntil sets ValidUntil field to given value.

### HasValidUntil

`func (o *License) HasValidUntil() bool`

HasValidUntil returns a boolean if a field has been set.

### SetValidUntilNil

`func (o *License) SetValidUntilNil(b bool)`

 SetValidUntilNil sets the value for ValidUntil to be an explicit nil

### UnsetValidUntil
`func (o *License) UnsetValidUntil()`

UnsetValidUntil ensures that no value is present for ValidUntil, not even an explicit nil
### GetDefinition

`func (o *License) GetDefinition() string`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *License) GetDefinitionOk() (*string, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *License) SetDefinition(v string)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *License) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### SetDefinitionNil

`func (o *License) SetDefinitionNil(b bool)`

 SetDefinitionNil sets the value for Definition to be an explicit nil

### UnsetDefinition
`func (o *License) UnsetDefinition()`

UnsetDefinition ensures that no value is present for Definition, not even an explicit nil
### GetVerified

`func (o *License) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *License) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *License) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *License) HasVerified() bool`

HasVerified returns a boolean if a field has been set.

### GetOrigin

`func (o *License) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *License) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *License) SetOrigin(v string)`

SetOrigin sets Origin field to given value.

### HasOrigin

`func (o *License) HasOrigin() bool`

HasOrigin returns a boolean if a field has been set.

### GetCreatedAt

`func (o *License) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *License) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *License) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *License) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *License) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *License) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *License) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *License) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *License) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *License) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *License) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *License) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *License) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *License) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


