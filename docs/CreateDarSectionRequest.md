# CreateDarSectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | **string** |  | 
**ParentSection** | Pointer to **int32** |  | [optional] 
**Order** | **int32** |  | 

## Methods

### NewCreateDarSectionRequest

`func NewCreateDarSectionRequest(name string, description string, order int32, ) *CreateDarSectionRequest`

NewCreateDarSectionRequest instantiates a new CreateDarSectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDarSectionRequestWithDefaults

`func NewCreateDarSectionRequestWithDefaults() *CreateDarSectionRequest`

NewCreateDarSectionRequestWithDefaults instantiates a new CreateDarSectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateDarSectionRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateDarSectionRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateDarSectionRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateDarSectionRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateDarSectionRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateDarSectionRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetParentSection

`func (o *CreateDarSectionRequest) GetParentSection() int32`

GetParentSection returns the ParentSection field if non-nil, zero value otherwise.

### GetParentSectionOk

`func (o *CreateDarSectionRequest) GetParentSectionOk() (*int32, bool)`

GetParentSectionOk returns a tuple with the ParentSection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSection

`func (o *CreateDarSectionRequest) SetParentSection(v int32)`

SetParentSection sets ParentSection field to given value.

### HasParentSection

`func (o *CreateDarSectionRequest) HasParentSection() bool`

HasParentSection returns a boolean if a field has been set.

### GetOrder

`func (o *CreateDarSectionRequest) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *CreateDarSectionRequest) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *CreateDarSectionRequest) SetOrder(v int32)`

SetOrder sets Order field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


