# GetCancerTypeFilters200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**FilterId** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**PrimaryGroup** | Pointer to **string** |  | [optional] 
**Count** | Pointer to **string** |  | [optional] 
**ParentId** | Pointer to **NullableInt32** |  | [optional] 
**Level** | Pointer to **int32** |  | [optional] 
**Children** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewGetCancerTypeFilters200ResponseDataInner

`func NewGetCancerTypeFilters200ResponseDataInner() *GetCancerTypeFilters200ResponseDataInner`

NewGetCancerTypeFilters200ResponseDataInner instantiates a new GetCancerTypeFilters200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCancerTypeFilters200ResponseDataInnerWithDefaults

`func NewGetCancerTypeFilters200ResponseDataInnerWithDefaults() *GetCancerTypeFilters200ResponseDataInner`

NewGetCancerTypeFilters200ResponseDataInnerWithDefaults instantiates a new GetCancerTypeFilters200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetCancerTypeFilters200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetCancerTypeFilters200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GetCancerTypeFilters200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFilterId

`func (o *GetCancerTypeFilters200ResponseDataInner) GetFilterId() string`

GetFilterId returns the FilterId field if non-nil, zero value otherwise.

### GetFilterIdOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetFilterIdOk() (*string, bool)`

GetFilterIdOk returns a tuple with the FilterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterId

`func (o *GetCancerTypeFilters200ResponseDataInner) SetFilterId(v string)`

SetFilterId sets FilterId field to given value.

### HasFilterId

`func (o *GetCancerTypeFilters200ResponseDataInner) HasFilterId() bool`

HasFilterId returns a boolean if a field has been set.

### GetLabel

`func (o *GetCancerTypeFilters200ResponseDataInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *GetCancerTypeFilters200ResponseDataInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *GetCancerTypeFilters200ResponseDataInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetDescription

`func (o *GetCancerTypeFilters200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GetCancerTypeFilters200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GetCancerTypeFilters200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *GetCancerTypeFilters200ResponseDataInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *GetCancerTypeFilters200ResponseDataInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCategory

`func (o *GetCancerTypeFilters200ResponseDataInner) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *GetCancerTypeFilters200ResponseDataInner) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *GetCancerTypeFilters200ResponseDataInner) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetPrimaryGroup

`func (o *GetCancerTypeFilters200ResponseDataInner) GetPrimaryGroup() string`

GetPrimaryGroup returns the PrimaryGroup field if non-nil, zero value otherwise.

### GetPrimaryGroupOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetPrimaryGroupOk() (*string, bool)`

GetPrimaryGroupOk returns a tuple with the PrimaryGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryGroup

`func (o *GetCancerTypeFilters200ResponseDataInner) SetPrimaryGroup(v string)`

SetPrimaryGroup sets PrimaryGroup field to given value.

### HasPrimaryGroup

`func (o *GetCancerTypeFilters200ResponseDataInner) HasPrimaryGroup() bool`

HasPrimaryGroup returns a boolean if a field has been set.

### GetCount

`func (o *GetCancerTypeFilters200ResponseDataInner) GetCount() string`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetCountOk() (*string, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *GetCancerTypeFilters200ResponseDataInner) SetCount(v string)`

SetCount sets Count field to given value.

### HasCount

`func (o *GetCancerTypeFilters200ResponseDataInner) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetParentId

`func (o *GetCancerTypeFilters200ResponseDataInner) GetParentId() int32`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetParentIdOk() (*int32, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *GetCancerTypeFilters200ResponseDataInner) SetParentId(v int32)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *GetCancerTypeFilters200ResponseDataInner) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### SetParentIdNil

`func (o *GetCancerTypeFilters200ResponseDataInner) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *GetCancerTypeFilters200ResponseDataInner) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil
### GetLevel

`func (o *GetCancerTypeFilters200ResponseDataInner) GetLevel() int32`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetLevelOk() (*int32, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *GetCancerTypeFilters200ResponseDataInner) SetLevel(v int32)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *GetCancerTypeFilters200ResponseDataInner) HasLevel() bool`

HasLevel returns a boolean if a field has been set.

### GetChildren

`func (o *GetCancerTypeFilters200ResponseDataInner) GetChildren() []map[string]interface{}`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *GetCancerTypeFilters200ResponseDataInner) GetChildrenOk() (*[]map[string]interface{}, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *GetCancerTypeFilters200ResponseDataInner) SetChildren(v []map[string]interface{})`

SetChildren sets Children field to given value.

### HasChildren

`func (o *GetCancerTypeFilters200ResponseDataInner) HasChildren() bool`

HasChildren returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


