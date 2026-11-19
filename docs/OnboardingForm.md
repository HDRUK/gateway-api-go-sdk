# OnboardingForm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Schemas** | Pointer to [**[]OnboardingFormSchemasInner**](OnboardingFormSchemasInner.md) |  | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 
**Schema** | Pointer to **map[string]interface{}** | JSON Schema of the selected input schema | [optional] 
**DefaultValues** | Pointer to **map[string]interface{}** | Team defaults in the selected schema | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Only with dataset_id | [optional] 

## Methods

### NewOnboardingForm

`func NewOnboardingForm() *OnboardingForm`

NewOnboardingForm instantiates a new OnboardingForm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOnboardingFormWithDefaults

`func NewOnboardingFormWithDefaults() *OnboardingForm`

NewOnboardingFormWithDefaults instantiates a new OnboardingForm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSchemas

`func (o *OnboardingForm) GetSchemas() []OnboardingFormSchemasInner`

GetSchemas returns the Schemas field if non-nil, zero value otherwise.

### GetSchemasOk

`func (o *OnboardingForm) GetSchemasOk() (*[]OnboardingFormSchemasInner, bool)`

GetSchemasOk returns a tuple with the Schemas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemas

`func (o *OnboardingForm) SetSchemas(v []OnboardingFormSchemasInner)`

SetSchemas sets Schemas field to given value.

### HasSchemas

`func (o *OnboardingForm) HasSchemas() bool`

HasSchemas returns a boolean if a field has been set.

### GetModel

`func (o *OnboardingForm) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *OnboardingForm) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *OnboardingForm) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *OnboardingForm) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetVersion

`func (o *OnboardingForm) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *OnboardingForm) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *OnboardingForm) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *OnboardingForm) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetSchema

`func (o *OnboardingForm) GetSchema() map[string]interface{}`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *OnboardingForm) GetSchemaOk() (*map[string]interface{}, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *OnboardingForm) SetSchema(v map[string]interface{})`

SetSchema sets Schema field to given value.

### HasSchema

`func (o *OnboardingForm) HasSchema() bool`

HasSchema returns a boolean if a field has been set.

### GetDefaultValues

`func (o *OnboardingForm) GetDefaultValues() map[string]interface{}`

GetDefaultValues returns the DefaultValues field if non-nil, zero value otherwise.

### GetDefaultValuesOk

`func (o *OnboardingForm) GetDefaultValuesOk() (*map[string]interface{}, bool)`

GetDefaultValuesOk returns a tuple with the DefaultValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultValues

`func (o *OnboardingForm) SetDefaultValues(v map[string]interface{})`

SetDefaultValues sets DefaultValues field to given value.

### HasDefaultValues

`func (o *OnboardingForm) HasDefaultValues() bool`

HasDefaultValues returns a boolean if a field has been set.

### GetMetadata

`func (o *OnboardingForm) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OnboardingForm) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OnboardingForm) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OnboardingForm) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *OnboardingForm) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *OnboardingForm) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


