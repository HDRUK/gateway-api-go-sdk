# ExperimentResponseInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Answers** | **map[string]interface{}** | Answers keyed by question block id; unknown ids are dropped | 
**Path** | **string** |  | 
**Variant** | Pointer to **NullableString** |  | [optional] 
**Contact** | Pointer to **bool** |  | [optional] 
**Email** | Pointer to **NullableString** | Required when contact is true and not signed in | [optional] 
**Recaptcha** | **string** | reCAPTCHA v3 token for the experiment_response action | 

## Methods

### NewExperimentResponseInput

`func NewExperimentResponseInput(answers map[string]interface{}, path string, recaptcha string, ) *ExperimentResponseInput`

NewExperimentResponseInput instantiates a new ExperimentResponseInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExperimentResponseInputWithDefaults

`func NewExperimentResponseInputWithDefaults() *ExperimentResponseInput`

NewExperimentResponseInputWithDefaults instantiates a new ExperimentResponseInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswers

`func (o *ExperimentResponseInput) GetAnswers() map[string]interface{}`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *ExperimentResponseInput) GetAnswersOk() (*map[string]interface{}, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *ExperimentResponseInput) SetAnswers(v map[string]interface{})`

SetAnswers sets Answers field to given value.


### GetPath

`func (o *ExperimentResponseInput) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ExperimentResponseInput) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ExperimentResponseInput) SetPath(v string)`

SetPath sets Path field to given value.


### GetVariant

`func (o *ExperimentResponseInput) GetVariant() string`

GetVariant returns the Variant field if non-nil, zero value otherwise.

### GetVariantOk

`func (o *ExperimentResponseInput) GetVariantOk() (*string, bool)`

GetVariantOk returns a tuple with the Variant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariant

`func (o *ExperimentResponseInput) SetVariant(v string)`

SetVariant sets Variant field to given value.

### HasVariant

`func (o *ExperimentResponseInput) HasVariant() bool`

HasVariant returns a boolean if a field has been set.

### SetVariantNil

`func (o *ExperimentResponseInput) SetVariantNil(b bool)`

 SetVariantNil sets the value for Variant to be an explicit nil

### UnsetVariant
`func (o *ExperimentResponseInput) UnsetVariant()`

UnsetVariant ensures that no value is present for Variant, not even an explicit nil
### GetContact

`func (o *ExperimentResponseInput) GetContact() bool`

GetContact returns the Contact field if non-nil, zero value otherwise.

### GetContactOk

`func (o *ExperimentResponseInput) GetContactOk() (*bool, bool)`

GetContactOk returns a tuple with the Contact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContact

`func (o *ExperimentResponseInput) SetContact(v bool)`

SetContact sets Contact field to given value.

### HasContact

`func (o *ExperimentResponseInput) HasContact() bool`

HasContact returns a boolean if a field has been set.

### GetEmail

`func (o *ExperimentResponseInput) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ExperimentResponseInput) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ExperimentResponseInput) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ExperimentResponseInput) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *ExperimentResponseInput) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *ExperimentResponseInput) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetRecaptcha

`func (o *ExperimentResponseInput) GetRecaptcha() string`

GetRecaptcha returns the Recaptcha field if non-nil, zero value otherwise.

### GetRecaptchaOk

`func (o *ExperimentResponseInput) GetRecaptchaOk() (*string, bool)`

GetRecaptchaOk returns a tuple with the Recaptcha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecaptcha

`func (o *ExperimentResponseInput) SetRecaptcha(v string)`

SetRecaptcha sets Recaptcha field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


