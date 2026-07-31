# FetchTeamDarApplicationHeader200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**ApplicantId** | Pointer to **int32** |  | [optional] 
**ProjectTitle** | Pointer to **string** |  | [optional] 
**ApplicationType** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**IsJoint** | Pointer to **bool** |  | [optional] 
**ApprovalStatus** | Pointer to **string** |  | [optional] 
**SubmissionStatus** | Pointer to **string** |  | [optional] 
**StatusReviewId** | Pointer to **int32** |  | [optional] 
**DaysSinceSubmission** | Pointer to **int32** |  | [optional] 
**PrimaryApplicant** | Pointer to [**[]FetchTeamDarApplicationHeader200ResponseDataPrimaryApplicantInner**](FetchTeamDarApplicationHeader200ResponseDataPrimaryApplicantInner.md) |  | [optional] 
**Datasets** | Pointer to [**[]FetchTeamDarApplicationHeader200ResponseDataDatasetsInner**](FetchTeamDarApplicationHeader200ResponseDataDatasetsInner.md) |  | [optional] 
**Teams** | Pointer to [**[]FetchTeamDarApplicationHeader200ResponseDataTeamsInner**](FetchTeamDarApplicationHeader200ResponseDataTeamsInner.md) |  | [optional] 

## Methods

### NewFetchTeamDarApplicationHeader200ResponseData

`func NewFetchTeamDarApplicationHeader200ResponseData() *FetchTeamDarApplicationHeader200ResponseData`

NewFetchTeamDarApplicationHeader200ResponseData instantiates a new FetchTeamDarApplicationHeader200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchTeamDarApplicationHeader200ResponseDataWithDefaults

`func NewFetchTeamDarApplicationHeader200ResponseDataWithDefaults() *FetchTeamDarApplicationHeader200ResponseData`

NewFetchTeamDarApplicationHeader200ResponseDataWithDefaults instantiates a new FetchTeamDarApplicationHeader200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetApplicantId

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApplicantId() int32`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApplicantIdOk() (*int32, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetApplicantId(v int32)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetProjectTitle

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetApplicationType

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApplicationType() string`

GetApplicationType returns the ApplicationType field if non-nil, zero value otherwise.

### GetApplicationTypeOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApplicationTypeOk() (*string, bool)`

GetApplicationTypeOk returns a tuple with the ApplicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationType

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetApplicationType(v string)`

SetApplicationType sets ApplicationType field to given value.

### HasApplicationType

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasApplicationType() bool`

HasApplicationType returns a boolean if a field has been set.

### GetProjectId

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetIsJoint

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetIsJoint() bool`

GetIsJoint returns the IsJoint field if non-nil, zero value otherwise.

### GetIsJointOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetIsJointOk() (*bool, bool)`

GetIsJointOk returns a tuple with the IsJoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsJoint

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetIsJoint(v bool)`

SetIsJoint sets IsJoint field to given value.

### HasIsJoint

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasIsJoint() bool`

HasIsJoint returns a boolean if a field has been set.

### GetApprovalStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApprovalStatus() string`

GetApprovalStatus returns the ApprovalStatus field if non-nil, zero value otherwise.

### GetApprovalStatusOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetApprovalStatusOk() (*string, bool)`

GetApprovalStatusOk returns a tuple with the ApprovalStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetApprovalStatus(v string)`

SetApprovalStatus sets ApprovalStatus field to given value.

### HasApprovalStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasApprovalStatus() bool`

HasApprovalStatus returns a boolean if a field has been set.

### GetSubmissionStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetSubmissionStatus() string`

GetSubmissionStatus returns the SubmissionStatus field if non-nil, zero value otherwise.

### GetSubmissionStatusOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetSubmissionStatusOk() (*string, bool)`

GetSubmissionStatusOk returns a tuple with the SubmissionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmissionStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetSubmissionStatus(v string)`

SetSubmissionStatus sets SubmissionStatus field to given value.

### HasSubmissionStatus

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasSubmissionStatus() bool`

HasSubmissionStatus returns a boolean if a field has been set.

### GetStatusReviewId

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetStatusReviewId() int32`

GetStatusReviewId returns the StatusReviewId field if non-nil, zero value otherwise.

### GetStatusReviewIdOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetStatusReviewIdOk() (*int32, bool)`

GetStatusReviewIdOk returns a tuple with the StatusReviewId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusReviewId

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetStatusReviewId(v int32)`

SetStatusReviewId sets StatusReviewId field to given value.

### HasStatusReviewId

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasStatusReviewId() bool`

HasStatusReviewId returns a boolean if a field has been set.

### GetDaysSinceSubmission

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDaysSinceSubmission() int32`

GetDaysSinceSubmission returns the DaysSinceSubmission field if non-nil, zero value otherwise.

### GetDaysSinceSubmissionOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDaysSinceSubmissionOk() (*int32, bool)`

GetDaysSinceSubmissionOk returns a tuple with the DaysSinceSubmission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysSinceSubmission

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetDaysSinceSubmission(v int32)`

SetDaysSinceSubmission sets DaysSinceSubmission field to given value.

### HasDaysSinceSubmission

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasDaysSinceSubmission() bool`

HasDaysSinceSubmission returns a boolean if a field has been set.

### GetPrimaryApplicant

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetPrimaryApplicant() []FetchTeamDarApplicationHeader200ResponseDataPrimaryApplicantInner`

GetPrimaryApplicant returns the PrimaryApplicant field if non-nil, zero value otherwise.

### GetPrimaryApplicantOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetPrimaryApplicantOk() (*[]FetchTeamDarApplicationHeader200ResponseDataPrimaryApplicantInner, bool)`

GetPrimaryApplicantOk returns a tuple with the PrimaryApplicant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryApplicant

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetPrimaryApplicant(v []FetchTeamDarApplicationHeader200ResponseDataPrimaryApplicantInner)`

SetPrimaryApplicant sets PrimaryApplicant field to given value.

### HasPrimaryApplicant

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasPrimaryApplicant() bool`

HasPrimaryApplicant returns a boolean if a field has been set.

### GetDatasets

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDatasets() []FetchTeamDarApplicationHeader200ResponseDataDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetDatasetsOk() (*[]FetchTeamDarApplicationHeader200ResponseDataDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetDatasets(v []FetchTeamDarApplicationHeader200ResponseDataDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetTeams

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetTeams() []FetchTeamDarApplicationHeader200ResponseDataTeamsInner`

GetTeams returns the Teams field if non-nil, zero value otherwise.

### GetTeamsOk

`func (o *FetchTeamDarApplicationHeader200ResponseData) GetTeamsOk() (*[]FetchTeamDarApplicationHeader200ResponseDataTeamsInner, bool)`

GetTeamsOk returns a tuple with the Teams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeams

`func (o *FetchTeamDarApplicationHeader200ResponseData) SetTeams(v []FetchTeamDarApplicationHeader200ResponseDataTeamsInner)`

SetTeams sets Teams field to given value.

### HasTeams

`func (o *FetchTeamDarApplicationHeader200ResponseData) HasTeams() bool`

HasTeams returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


