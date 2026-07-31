# UpdateUserDarApplicationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicantId** | **int32** |  | 
**SubmissionStatus** | **string** |  | 
**ProjectTitle** | Pointer to **string** |  | [optional] 
**ApprovalStatus** | **string** |  | 
**TeamIds** | Pointer to **[]int32** |  | [optional] 
**Answers** | Pointer to [**[]UpdateUserDarApplicationRequestAnswersInner**](UpdateUserDarApplicationRequestAnswersInner.md) |  | [optional] 

## Methods

### NewUpdateUserDarApplicationRequest

`func NewUpdateUserDarApplicationRequest(applicantId int32, submissionStatus string, approvalStatus string, ) *UpdateUserDarApplicationRequest`

NewUpdateUserDarApplicationRequest instantiates a new UpdateUserDarApplicationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserDarApplicationRequestWithDefaults

`func NewUpdateUserDarApplicationRequestWithDefaults() *UpdateUserDarApplicationRequest`

NewUpdateUserDarApplicationRequestWithDefaults instantiates a new UpdateUserDarApplicationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicantId

`func (o *UpdateUserDarApplicationRequest) GetApplicantId() int32`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *UpdateUserDarApplicationRequest) GetApplicantIdOk() (*int32, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *UpdateUserDarApplicationRequest) SetApplicantId(v int32)`

SetApplicantId sets ApplicantId field to given value.


### GetSubmissionStatus

`func (o *UpdateUserDarApplicationRequest) GetSubmissionStatus() string`

GetSubmissionStatus returns the SubmissionStatus field if non-nil, zero value otherwise.

### GetSubmissionStatusOk

`func (o *UpdateUserDarApplicationRequest) GetSubmissionStatusOk() (*string, bool)`

GetSubmissionStatusOk returns a tuple with the SubmissionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmissionStatus

`func (o *UpdateUserDarApplicationRequest) SetSubmissionStatus(v string)`

SetSubmissionStatus sets SubmissionStatus field to given value.


### GetProjectTitle

`func (o *UpdateUserDarApplicationRequest) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *UpdateUserDarApplicationRequest) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *UpdateUserDarApplicationRequest) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *UpdateUserDarApplicationRequest) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetApprovalStatus

`func (o *UpdateUserDarApplicationRequest) GetApprovalStatus() string`

GetApprovalStatus returns the ApprovalStatus field if non-nil, zero value otherwise.

### GetApprovalStatusOk

`func (o *UpdateUserDarApplicationRequest) GetApprovalStatusOk() (*string, bool)`

GetApprovalStatusOk returns a tuple with the ApprovalStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalStatus

`func (o *UpdateUserDarApplicationRequest) SetApprovalStatus(v string)`

SetApprovalStatus sets ApprovalStatus field to given value.


### GetTeamIds

`func (o *UpdateUserDarApplicationRequest) GetTeamIds() []int32`

GetTeamIds returns the TeamIds field if non-nil, zero value otherwise.

### GetTeamIdsOk

`func (o *UpdateUserDarApplicationRequest) GetTeamIdsOk() (*[]int32, bool)`

GetTeamIdsOk returns a tuple with the TeamIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamIds

`func (o *UpdateUserDarApplicationRequest) SetTeamIds(v []int32)`

SetTeamIds sets TeamIds field to given value.

### HasTeamIds

`func (o *UpdateUserDarApplicationRequest) HasTeamIds() bool`

HasTeamIds returns a boolean if a field has been set.

### GetAnswers

`func (o *UpdateUserDarApplicationRequest) GetAnswers() []UpdateUserDarApplicationRequestAnswersInner`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *UpdateUserDarApplicationRequest) GetAnswersOk() (*[]UpdateUserDarApplicationRequestAnswersInner, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *UpdateUserDarApplicationRequest) SetAnswers(v []UpdateUserDarApplicationRequestAnswersInner)`

SetAnswers sets Answers field to given value.

### HasAnswers

`func (o *UpdateUserDarApplicationRequest) HasAnswers() bool`

HasAnswers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


