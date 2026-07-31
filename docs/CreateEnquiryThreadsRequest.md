# CreateEnquiryThreadsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **int32** |  | 
**ProjectTitle** | **string** |  | 
**IsDarDialogue** | Pointer to **bool** |  | [optional] 
**IsDarStatus** | Pointer to **bool** |  | [optional] 
**IsFeasibilityEnquiry** | Pointer to **bool** |  | [optional] 
**IsGeneralEnquiry** | Pointer to **bool** |  | [optional] 
**IsDarReview** | Pointer to **bool** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 

## Methods

### NewCreateEnquiryThreadsRequest

`func NewCreateEnquiryThreadsRequest(userId int32, projectTitle string, ) *CreateEnquiryThreadsRequest`

NewCreateEnquiryThreadsRequest instantiates a new CreateEnquiryThreadsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateEnquiryThreadsRequestWithDefaults

`func NewCreateEnquiryThreadsRequestWithDefaults() *CreateEnquiryThreadsRequest`

NewCreateEnquiryThreadsRequestWithDefaults instantiates a new CreateEnquiryThreadsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *CreateEnquiryThreadsRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateEnquiryThreadsRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateEnquiryThreadsRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.


### GetProjectTitle

`func (o *CreateEnquiryThreadsRequest) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *CreateEnquiryThreadsRequest) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *CreateEnquiryThreadsRequest) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.


### GetIsDarDialogue

`func (o *CreateEnquiryThreadsRequest) GetIsDarDialogue() bool`

GetIsDarDialogue returns the IsDarDialogue field if non-nil, zero value otherwise.

### GetIsDarDialogueOk

`func (o *CreateEnquiryThreadsRequest) GetIsDarDialogueOk() (*bool, bool)`

GetIsDarDialogueOk returns a tuple with the IsDarDialogue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDarDialogue

`func (o *CreateEnquiryThreadsRequest) SetIsDarDialogue(v bool)`

SetIsDarDialogue sets IsDarDialogue field to given value.

### HasIsDarDialogue

`func (o *CreateEnquiryThreadsRequest) HasIsDarDialogue() bool`

HasIsDarDialogue returns a boolean if a field has been set.

### GetIsDarStatus

`func (o *CreateEnquiryThreadsRequest) GetIsDarStatus() bool`

GetIsDarStatus returns the IsDarStatus field if non-nil, zero value otherwise.

### GetIsDarStatusOk

`func (o *CreateEnquiryThreadsRequest) GetIsDarStatusOk() (*bool, bool)`

GetIsDarStatusOk returns a tuple with the IsDarStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDarStatus

`func (o *CreateEnquiryThreadsRequest) SetIsDarStatus(v bool)`

SetIsDarStatus sets IsDarStatus field to given value.

### HasIsDarStatus

`func (o *CreateEnquiryThreadsRequest) HasIsDarStatus() bool`

HasIsDarStatus returns a boolean if a field has been set.

### GetIsFeasibilityEnquiry

`func (o *CreateEnquiryThreadsRequest) GetIsFeasibilityEnquiry() bool`

GetIsFeasibilityEnquiry returns the IsFeasibilityEnquiry field if non-nil, zero value otherwise.

### GetIsFeasibilityEnquiryOk

`func (o *CreateEnquiryThreadsRequest) GetIsFeasibilityEnquiryOk() (*bool, bool)`

GetIsFeasibilityEnquiryOk returns a tuple with the IsFeasibilityEnquiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFeasibilityEnquiry

`func (o *CreateEnquiryThreadsRequest) SetIsFeasibilityEnquiry(v bool)`

SetIsFeasibilityEnquiry sets IsFeasibilityEnquiry field to given value.

### HasIsFeasibilityEnquiry

`func (o *CreateEnquiryThreadsRequest) HasIsFeasibilityEnquiry() bool`

HasIsFeasibilityEnquiry returns a boolean if a field has been set.

### GetIsGeneralEnquiry

`func (o *CreateEnquiryThreadsRequest) GetIsGeneralEnquiry() bool`

GetIsGeneralEnquiry returns the IsGeneralEnquiry field if non-nil, zero value otherwise.

### GetIsGeneralEnquiryOk

`func (o *CreateEnquiryThreadsRequest) GetIsGeneralEnquiryOk() (*bool, bool)`

GetIsGeneralEnquiryOk returns a tuple with the IsGeneralEnquiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGeneralEnquiry

`func (o *CreateEnquiryThreadsRequest) SetIsGeneralEnquiry(v bool)`

SetIsGeneralEnquiry sets IsGeneralEnquiry field to given value.

### HasIsGeneralEnquiry

`func (o *CreateEnquiryThreadsRequest) HasIsGeneralEnquiry() bool`

HasIsGeneralEnquiry returns a boolean if a field has been set.

### GetIsDarReview

`func (o *CreateEnquiryThreadsRequest) GetIsDarReview() bool`

GetIsDarReview returns the IsDarReview field if non-nil, zero value otherwise.

### GetIsDarReviewOk

`func (o *CreateEnquiryThreadsRequest) GetIsDarReviewOk() (*bool, bool)`

GetIsDarReviewOk returns a tuple with the IsDarReview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDarReview

`func (o *CreateEnquiryThreadsRequest) SetIsDarReview(v bool)`

SetIsDarReview sets IsDarReview field to given value.

### HasIsDarReview

`func (o *CreateEnquiryThreadsRequest) HasIsDarReview() bool`

HasIsDarReview returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateEnquiryThreadsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateEnquiryThreadsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateEnquiryThreadsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateEnquiryThreadsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


