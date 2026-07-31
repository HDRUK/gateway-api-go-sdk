# DataAccessApplication

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ApplicantId** | Pointer to **int32** |  | [optional] 
**ProjectTitle** | Pointer to **NullableString** |  | [optional] 
**ProjectId** | Pointer to **NullableString** |  | [optional] 
**ApplicationType** | Pointer to **string** |  | [optional] 
**SubmissionStatus** | Pointer to **string** |  | [optional] 
**ApprovalStatus** | Pointer to **NullableString** |  | [optional] 
**IsJoint** | Pointer to **bool** |  | [optional] 
**StatusReviewId** | Pointer to **NullableInt32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewDataAccessApplication

`func NewDataAccessApplication() *DataAccessApplication`

NewDataAccessApplication instantiates a new DataAccessApplication object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataAccessApplicationWithDefaults

`func NewDataAccessApplicationWithDefaults() *DataAccessApplication`

NewDataAccessApplicationWithDefaults instantiates a new DataAccessApplication object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DataAccessApplication) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DataAccessApplication) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DataAccessApplication) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DataAccessApplication) HasId() bool`

HasId returns a boolean if a field has been set.

### GetApplicantId

`func (o *DataAccessApplication) GetApplicantId() int32`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *DataAccessApplication) GetApplicantIdOk() (*int32, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *DataAccessApplication) SetApplicantId(v int32)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *DataAccessApplication) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetProjectTitle

`func (o *DataAccessApplication) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *DataAccessApplication) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *DataAccessApplication) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *DataAccessApplication) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### SetProjectTitleNil

`func (o *DataAccessApplication) SetProjectTitleNil(b bool)`

 SetProjectTitleNil sets the value for ProjectTitle to be an explicit nil

### UnsetProjectTitle
`func (o *DataAccessApplication) UnsetProjectTitle()`

UnsetProjectTitle ensures that no value is present for ProjectTitle, not even an explicit nil
### GetProjectId

`func (o *DataAccessApplication) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *DataAccessApplication) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *DataAccessApplication) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *DataAccessApplication) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *DataAccessApplication) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *DataAccessApplication) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetApplicationType

`func (o *DataAccessApplication) GetApplicationType() string`

GetApplicationType returns the ApplicationType field if non-nil, zero value otherwise.

### GetApplicationTypeOk

`func (o *DataAccessApplication) GetApplicationTypeOk() (*string, bool)`

GetApplicationTypeOk returns a tuple with the ApplicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationType

`func (o *DataAccessApplication) SetApplicationType(v string)`

SetApplicationType sets ApplicationType field to given value.

### HasApplicationType

`func (o *DataAccessApplication) HasApplicationType() bool`

HasApplicationType returns a boolean if a field has been set.

### GetSubmissionStatus

`func (o *DataAccessApplication) GetSubmissionStatus() string`

GetSubmissionStatus returns the SubmissionStatus field if non-nil, zero value otherwise.

### GetSubmissionStatusOk

`func (o *DataAccessApplication) GetSubmissionStatusOk() (*string, bool)`

GetSubmissionStatusOk returns a tuple with the SubmissionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmissionStatus

`func (o *DataAccessApplication) SetSubmissionStatus(v string)`

SetSubmissionStatus sets SubmissionStatus field to given value.

### HasSubmissionStatus

`func (o *DataAccessApplication) HasSubmissionStatus() bool`

HasSubmissionStatus returns a boolean if a field has been set.

### GetApprovalStatus

`func (o *DataAccessApplication) GetApprovalStatus() string`

GetApprovalStatus returns the ApprovalStatus field if non-nil, zero value otherwise.

### GetApprovalStatusOk

`func (o *DataAccessApplication) GetApprovalStatusOk() (*string, bool)`

GetApprovalStatusOk returns a tuple with the ApprovalStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalStatus

`func (o *DataAccessApplication) SetApprovalStatus(v string)`

SetApprovalStatus sets ApprovalStatus field to given value.

### HasApprovalStatus

`func (o *DataAccessApplication) HasApprovalStatus() bool`

HasApprovalStatus returns a boolean if a field has been set.

### SetApprovalStatusNil

`func (o *DataAccessApplication) SetApprovalStatusNil(b bool)`

 SetApprovalStatusNil sets the value for ApprovalStatus to be an explicit nil

### UnsetApprovalStatus
`func (o *DataAccessApplication) UnsetApprovalStatus()`

UnsetApprovalStatus ensures that no value is present for ApprovalStatus, not even an explicit nil
### GetIsJoint

`func (o *DataAccessApplication) GetIsJoint() bool`

GetIsJoint returns the IsJoint field if non-nil, zero value otherwise.

### GetIsJointOk

`func (o *DataAccessApplication) GetIsJointOk() (*bool, bool)`

GetIsJointOk returns a tuple with the IsJoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsJoint

`func (o *DataAccessApplication) SetIsJoint(v bool)`

SetIsJoint sets IsJoint field to given value.

### HasIsJoint

`func (o *DataAccessApplication) HasIsJoint() bool`

HasIsJoint returns a boolean if a field has been set.

### GetStatusReviewId

`func (o *DataAccessApplication) GetStatusReviewId() int32`

GetStatusReviewId returns the StatusReviewId field if non-nil, zero value otherwise.

### GetStatusReviewIdOk

`func (o *DataAccessApplication) GetStatusReviewIdOk() (*int32, bool)`

GetStatusReviewIdOk returns a tuple with the StatusReviewId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusReviewId

`func (o *DataAccessApplication) SetStatusReviewId(v int32)`

SetStatusReviewId sets StatusReviewId field to given value.

### HasStatusReviewId

`func (o *DataAccessApplication) HasStatusReviewId() bool`

HasStatusReviewId returns a boolean if a field has been set.

### SetStatusReviewIdNil

`func (o *DataAccessApplication) SetStatusReviewIdNil(b bool)`

 SetStatusReviewIdNil sets the value for StatusReviewId to be an explicit nil

### UnsetStatusReviewId
`func (o *DataAccessApplication) UnsetStatusReviewId()`

UnsetStatusReviewId ensures that no value is present for StatusReviewId, not even an explicit nil
### GetCreatedAt

`func (o *DataAccessApplication) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DataAccessApplication) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DataAccessApplication) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DataAccessApplication) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DataAccessApplication) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DataAccessApplication) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DataAccessApplication) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DataAccessApplication) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *DataAccessApplication) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *DataAccessApplication) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *DataAccessApplication) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *DataAccessApplication) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *DataAccessApplication) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *DataAccessApplication) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


