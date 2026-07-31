# UpdateDurIntegrations200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**NonGatewayDatasets** | Pointer to **[]interface{}** |  | [optional] 
**NonGatewayApplicants** | Pointer to **[]interface{}** |  | [optional] 
**FundersAndSponsors** | Pointer to **[]interface{}** |  | [optional] 
**OtherApprovalCommittees** | Pointer to **[]interface{}** |  | [optional] 
**GatewayOutputsTools** | Pointer to **[]interface{}** |  | [optional] 
**GatewayOutputsPapers** | Pointer to **[]interface{}** |  | [optional] 
**NonGatewayOutputs** | Pointer to **[]interface{}** |  | [optional] 
**ProjectTitle** | Pointer to **string** |  | [optional] 
**ProjectIdText** | Pointer to **string** |  | [optional] 
**OrganisationName** | Pointer to **string** |  | [optional] 
**OrganisationSector** | Pointer to **string** |  | [optional] 
**LaySummary** | Pointer to **string** |  | [optional] 
**TechnicalSummary** | Pointer to **string** |  | [optional] 
**LatestApprovalDate** | Pointer to **time.Time** |  | [optional] 
**ManualUpload** | Pointer to **bool** |  | [optional] 
**RejectionReason** | Pointer to **string** |  | [optional] 
**SublicenceArrangements** | Pointer to **string** |  | [optional] 
**PublicBenefitStatement** | Pointer to **string** |  | [optional] 
**DataSensitivityLevel** | Pointer to **string** |  | [optional] 
**ProjectStartDate** | Pointer to **time.Time** |  | [optional] 
**ProjectEndDate** | Pointer to **time.Time** |  | [optional] 
**AccessDate** | Pointer to **time.Time** |  | [optional] 
**AccreditedResearcherStatus** | Pointer to **string** |  | [optional] 
**ConfidentialDataDescription** | Pointer to **string** |  | [optional] 
**DatasetLinkageDescription** | Pointer to **string** |  | [optional] 
**DutyOfConfidentiality** | Pointer to **string** |  | [optional] 
**LegalBasisForDataArticle6** | Pointer to **string** |  | [optional] 
**LegalBasisForDataArticle9** | Pointer to **string** |  | [optional] 
**NationalDataOptout** | Pointer to **string** |  | [optional] 
**OrganisationId** | Pointer to **string** |  | [optional] 
**PrivacyEnhancements** | Pointer to **string** |  | [optional] 
**RequestCategoryType** | Pointer to **string** |  | [optional] 
**RequestFrequency** | Pointer to **string** |  | [optional] 
**AccessType** | Pointer to **string** |  | [optional] 
**MongoObjectDarId** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**LastActivity** | Pointer to **time.Time** |  | [optional] 
**Counter** | Pointer to **int32** |  | [optional] 
**MongoObjectId** | Pointer to **string** |  | [optional] 
**MongoId** | Pointer to **string** |  | [optional] 
**Datasets** | Pointer to **[]interface{}** |  | [optional] 
**Keywords** | Pointer to **[]interface{}** |  | [optional] 
**Users** | Pointer to **[]interface{}** |  | [optional] 
**Applications** | Pointer to **[]interface{}** |  | [optional] 
**User** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**Application** | Pointer to **[]interface{}** |  | [optional] 
**ApplicantId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewUpdateDurIntegrations200ResponseData

`func NewUpdateDurIntegrations200ResponseData() *UpdateDurIntegrations200ResponseData`

NewUpdateDurIntegrations200ResponseData instantiates a new UpdateDurIntegrations200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDurIntegrations200ResponseDataWithDefaults

`func NewUpdateDurIntegrations200ResponseDataWithDefaults() *UpdateDurIntegrations200ResponseData`

NewUpdateDurIntegrations200ResponseDataWithDefaults instantiates a new UpdateDurIntegrations200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UpdateDurIntegrations200ResponseData) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UpdateDurIntegrations200ResponseData) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *UpdateDurIntegrations200ResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *UpdateDurIntegrations200ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UpdateDurIntegrations200ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UpdateDurIntegrations200ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *UpdateDurIntegrations200ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *UpdateDurIntegrations200ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UpdateDurIntegrations200ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UpdateDurIntegrations200ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *UpdateDurIntegrations200ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *UpdateDurIntegrations200ResponseData) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *UpdateDurIntegrations200ResponseData) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *UpdateDurIntegrations200ResponseData) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *UpdateDurIntegrations200ResponseData) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetNonGatewayDatasets

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayDatasets() []interface{}`

GetNonGatewayDatasets returns the NonGatewayDatasets field if non-nil, zero value otherwise.

### GetNonGatewayDatasetsOk

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayDatasetsOk() (*[]interface{}, bool)`

GetNonGatewayDatasetsOk returns a tuple with the NonGatewayDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayDatasets

`func (o *UpdateDurIntegrations200ResponseData) SetNonGatewayDatasets(v []interface{})`

SetNonGatewayDatasets sets NonGatewayDatasets field to given value.

### HasNonGatewayDatasets

`func (o *UpdateDurIntegrations200ResponseData) HasNonGatewayDatasets() bool`

HasNonGatewayDatasets returns a boolean if a field has been set.

### GetNonGatewayApplicants

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayApplicants() []interface{}`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayApplicantsOk() (*[]interface{}, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *UpdateDurIntegrations200ResponseData) SetNonGatewayApplicants(v []interface{})`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *UpdateDurIntegrations200ResponseData) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *UpdateDurIntegrations200ResponseData) GetFundersAndSponsors() []interface{}`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *UpdateDurIntegrations200ResponseData) GetFundersAndSponsorsOk() (*[]interface{}, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *UpdateDurIntegrations200ResponseData) SetFundersAndSponsors(v []interface{})`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *UpdateDurIntegrations200ResponseData) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *UpdateDurIntegrations200ResponseData) GetOtherApprovalCommittees() []interface{}`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *UpdateDurIntegrations200ResponseData) GetOtherApprovalCommitteesOk() (*[]interface{}, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *UpdateDurIntegrations200ResponseData) SetOtherApprovalCommittees(v []interface{})`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *UpdateDurIntegrations200ResponseData) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetGatewayOutputsTools

`func (o *UpdateDurIntegrations200ResponseData) GetGatewayOutputsTools() []interface{}`

GetGatewayOutputsTools returns the GatewayOutputsTools field if non-nil, zero value otherwise.

### GetGatewayOutputsToolsOk

`func (o *UpdateDurIntegrations200ResponseData) GetGatewayOutputsToolsOk() (*[]interface{}, bool)`

GetGatewayOutputsToolsOk returns a tuple with the GatewayOutputsTools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsTools

`func (o *UpdateDurIntegrations200ResponseData) SetGatewayOutputsTools(v []interface{})`

SetGatewayOutputsTools sets GatewayOutputsTools field to given value.

### HasGatewayOutputsTools

`func (o *UpdateDurIntegrations200ResponseData) HasGatewayOutputsTools() bool`

HasGatewayOutputsTools returns a boolean if a field has been set.

### GetGatewayOutputsPapers

`func (o *UpdateDurIntegrations200ResponseData) GetGatewayOutputsPapers() []interface{}`

GetGatewayOutputsPapers returns the GatewayOutputsPapers field if non-nil, zero value otherwise.

### GetGatewayOutputsPapersOk

`func (o *UpdateDurIntegrations200ResponseData) GetGatewayOutputsPapersOk() (*[]interface{}, bool)`

GetGatewayOutputsPapersOk returns a tuple with the GatewayOutputsPapers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsPapers

`func (o *UpdateDurIntegrations200ResponseData) SetGatewayOutputsPapers(v []interface{})`

SetGatewayOutputsPapers sets GatewayOutputsPapers field to given value.

### HasGatewayOutputsPapers

`func (o *UpdateDurIntegrations200ResponseData) HasGatewayOutputsPapers() bool`

HasGatewayOutputsPapers returns a boolean if a field has been set.

### GetNonGatewayOutputs

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayOutputs() []interface{}`

GetNonGatewayOutputs returns the NonGatewayOutputs field if non-nil, zero value otherwise.

### GetNonGatewayOutputsOk

`func (o *UpdateDurIntegrations200ResponseData) GetNonGatewayOutputsOk() (*[]interface{}, bool)`

GetNonGatewayOutputsOk returns a tuple with the NonGatewayOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayOutputs

`func (o *UpdateDurIntegrations200ResponseData) SetNonGatewayOutputs(v []interface{})`

SetNonGatewayOutputs sets NonGatewayOutputs field to given value.

### HasNonGatewayOutputs

`func (o *UpdateDurIntegrations200ResponseData) HasNonGatewayOutputs() bool`

HasNonGatewayOutputs returns a boolean if a field has been set.

### GetProjectTitle

`func (o *UpdateDurIntegrations200ResponseData) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *UpdateDurIntegrations200ResponseData) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *UpdateDurIntegrations200ResponseData) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *UpdateDurIntegrations200ResponseData) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetProjectIdText

`func (o *UpdateDurIntegrations200ResponseData) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *UpdateDurIntegrations200ResponseData) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *UpdateDurIntegrations200ResponseData) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *UpdateDurIntegrations200ResponseData) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### GetOrganisationName

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *UpdateDurIntegrations200ResponseData) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *UpdateDurIntegrations200ResponseData) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetOrganisationSector

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *UpdateDurIntegrations200ResponseData) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *UpdateDurIntegrations200ResponseData) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### GetLaySummary

`func (o *UpdateDurIntegrations200ResponseData) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *UpdateDurIntegrations200ResponseData) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *UpdateDurIntegrations200ResponseData) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *UpdateDurIntegrations200ResponseData) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *UpdateDurIntegrations200ResponseData) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *UpdateDurIntegrations200ResponseData) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *UpdateDurIntegrations200ResponseData) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *UpdateDurIntegrations200ResponseData) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetLatestApprovalDate

`func (o *UpdateDurIntegrations200ResponseData) GetLatestApprovalDate() time.Time`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *UpdateDurIntegrations200ResponseData) GetLatestApprovalDateOk() (*time.Time, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *UpdateDurIntegrations200ResponseData) SetLatestApprovalDate(v time.Time)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *UpdateDurIntegrations200ResponseData) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### GetManualUpload

`func (o *UpdateDurIntegrations200ResponseData) GetManualUpload() bool`

GetManualUpload returns the ManualUpload field if non-nil, zero value otherwise.

### GetManualUploadOk

`func (o *UpdateDurIntegrations200ResponseData) GetManualUploadOk() (*bool, bool)`

GetManualUploadOk returns a tuple with the ManualUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualUpload

`func (o *UpdateDurIntegrations200ResponseData) SetManualUpload(v bool)`

SetManualUpload sets ManualUpload field to given value.

### HasManualUpload

`func (o *UpdateDurIntegrations200ResponseData) HasManualUpload() bool`

HasManualUpload returns a boolean if a field has been set.

### GetRejectionReason

`func (o *UpdateDurIntegrations200ResponseData) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *UpdateDurIntegrations200ResponseData) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *UpdateDurIntegrations200ResponseData) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *UpdateDurIntegrations200ResponseData) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### GetSublicenceArrangements

`func (o *UpdateDurIntegrations200ResponseData) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *UpdateDurIntegrations200ResponseData) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *UpdateDurIntegrations200ResponseData) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *UpdateDurIntegrations200ResponseData) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### GetPublicBenefitStatement

`func (o *UpdateDurIntegrations200ResponseData) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *UpdateDurIntegrations200ResponseData) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *UpdateDurIntegrations200ResponseData) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *UpdateDurIntegrations200ResponseData) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *UpdateDurIntegrations200ResponseData) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *UpdateDurIntegrations200ResponseData) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *UpdateDurIntegrations200ResponseData) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *UpdateDurIntegrations200ResponseData) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetProjectStartDate

`func (o *UpdateDurIntegrations200ResponseData) GetProjectStartDate() time.Time`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *UpdateDurIntegrations200ResponseData) GetProjectStartDateOk() (*time.Time, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *UpdateDurIntegrations200ResponseData) SetProjectStartDate(v time.Time)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *UpdateDurIntegrations200ResponseData) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### GetProjectEndDate

`func (o *UpdateDurIntegrations200ResponseData) GetProjectEndDate() time.Time`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *UpdateDurIntegrations200ResponseData) GetProjectEndDateOk() (*time.Time, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *UpdateDurIntegrations200ResponseData) SetProjectEndDate(v time.Time)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *UpdateDurIntegrations200ResponseData) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### GetAccessDate

`func (o *UpdateDurIntegrations200ResponseData) GetAccessDate() time.Time`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *UpdateDurIntegrations200ResponseData) GetAccessDateOk() (*time.Time, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *UpdateDurIntegrations200ResponseData) SetAccessDate(v time.Time)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *UpdateDurIntegrations200ResponseData) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccreditedResearcherStatus

`func (o *UpdateDurIntegrations200ResponseData) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *UpdateDurIntegrations200ResponseData) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *UpdateDurIntegrations200ResponseData) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *UpdateDurIntegrations200ResponseData) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### GetConfidentialDataDescription

`func (o *UpdateDurIntegrations200ResponseData) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *UpdateDurIntegrations200ResponseData) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *UpdateDurIntegrations200ResponseData) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *UpdateDurIntegrations200ResponseData) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *UpdateDurIntegrations200ResponseData) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *UpdateDurIntegrations200ResponseData) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *UpdateDurIntegrations200ResponseData) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *UpdateDurIntegrations200ResponseData) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *UpdateDurIntegrations200ResponseData) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *UpdateDurIntegrations200ResponseData) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *UpdateDurIntegrations200ResponseData) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *UpdateDurIntegrations200ResponseData) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *UpdateDurIntegrations200ResponseData) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *UpdateDurIntegrations200ResponseData) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *UpdateDurIntegrations200ResponseData) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *UpdateDurIntegrations200ResponseData) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetLegalBasisForDataArticle9

`func (o *UpdateDurIntegrations200ResponseData) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *UpdateDurIntegrations200ResponseData) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *UpdateDurIntegrations200ResponseData) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *UpdateDurIntegrations200ResponseData) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *UpdateDurIntegrations200ResponseData) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *UpdateDurIntegrations200ResponseData) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *UpdateDurIntegrations200ResponseData) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *UpdateDurIntegrations200ResponseData) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetOrganisationId

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *UpdateDurIntegrations200ResponseData) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *UpdateDurIntegrations200ResponseData) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetPrivacyEnhancements

`func (o *UpdateDurIntegrations200ResponseData) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *UpdateDurIntegrations200ResponseData) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *UpdateDurIntegrations200ResponseData) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *UpdateDurIntegrations200ResponseData) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *UpdateDurIntegrations200ResponseData) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *UpdateDurIntegrations200ResponseData) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *UpdateDurIntegrations200ResponseData) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *UpdateDurIntegrations200ResponseData) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *UpdateDurIntegrations200ResponseData) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *UpdateDurIntegrations200ResponseData) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *UpdateDurIntegrations200ResponseData) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *UpdateDurIntegrations200ResponseData) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetAccessType

`func (o *UpdateDurIntegrations200ResponseData) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *UpdateDurIntegrations200ResponseData) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *UpdateDurIntegrations200ResponseData) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *UpdateDurIntegrations200ResponseData) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetMongoObjectDarId

`func (o *UpdateDurIntegrations200ResponseData) GetMongoObjectDarId() string`

GetMongoObjectDarId returns the MongoObjectDarId field if non-nil, zero value otherwise.

### GetMongoObjectDarIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetMongoObjectDarIdOk() (*string, bool)`

GetMongoObjectDarIdOk returns a tuple with the MongoObjectDarId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectDarId

`func (o *UpdateDurIntegrations200ResponseData) SetMongoObjectDarId(v string)`

SetMongoObjectDarId sets MongoObjectDarId field to given value.

### HasMongoObjectDarId

`func (o *UpdateDurIntegrations200ResponseData) HasMongoObjectDarId() bool`

HasMongoObjectDarId returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateDurIntegrations200ResponseData) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateDurIntegrations200ResponseData) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateDurIntegrations200ResponseData) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateDurIntegrations200ResponseData) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLastActivity

`func (o *UpdateDurIntegrations200ResponseData) GetLastActivity() time.Time`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *UpdateDurIntegrations200ResponseData) GetLastActivityOk() (*time.Time, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *UpdateDurIntegrations200ResponseData) SetLastActivity(v time.Time)`

SetLastActivity sets LastActivity field to given value.

### HasLastActivity

`func (o *UpdateDurIntegrations200ResponseData) HasLastActivity() bool`

HasLastActivity returns a boolean if a field has been set.

### GetCounter

`func (o *UpdateDurIntegrations200ResponseData) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *UpdateDurIntegrations200ResponseData) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *UpdateDurIntegrations200ResponseData) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *UpdateDurIntegrations200ResponseData) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### GetMongoObjectId

`func (o *UpdateDurIntegrations200ResponseData) GetMongoObjectId() string`

GetMongoObjectId returns the MongoObjectId field if non-nil, zero value otherwise.

### GetMongoObjectIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetMongoObjectIdOk() (*string, bool)`

GetMongoObjectIdOk returns a tuple with the MongoObjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectId

`func (o *UpdateDurIntegrations200ResponseData) SetMongoObjectId(v string)`

SetMongoObjectId sets MongoObjectId field to given value.

### HasMongoObjectId

`func (o *UpdateDurIntegrations200ResponseData) HasMongoObjectId() bool`

HasMongoObjectId returns a boolean if a field has been set.

### GetMongoId

`func (o *UpdateDurIntegrations200ResponseData) GetMongoId() string`

GetMongoId returns the MongoId field if non-nil, zero value otherwise.

### GetMongoIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetMongoIdOk() (*string, bool)`

GetMongoIdOk returns a tuple with the MongoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoId

`func (o *UpdateDurIntegrations200ResponseData) SetMongoId(v string)`

SetMongoId sets MongoId field to given value.

### HasMongoId

`func (o *UpdateDurIntegrations200ResponseData) HasMongoId() bool`

HasMongoId returns a boolean if a field has been set.

### GetDatasets

`func (o *UpdateDurIntegrations200ResponseData) GetDatasets() []interface{}`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *UpdateDurIntegrations200ResponseData) GetDatasetsOk() (*[]interface{}, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *UpdateDurIntegrations200ResponseData) SetDatasets(v []interface{})`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *UpdateDurIntegrations200ResponseData) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetKeywords

`func (o *UpdateDurIntegrations200ResponseData) GetKeywords() []interface{}`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *UpdateDurIntegrations200ResponseData) GetKeywordsOk() (*[]interface{}, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *UpdateDurIntegrations200ResponseData) SetKeywords(v []interface{})`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *UpdateDurIntegrations200ResponseData) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetUsers

`func (o *UpdateDurIntegrations200ResponseData) GetUsers() []interface{}`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *UpdateDurIntegrations200ResponseData) GetUsersOk() (*[]interface{}, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *UpdateDurIntegrations200ResponseData) SetUsers(v []interface{})`

SetUsers sets Users field to given value.

### HasUsers

`func (o *UpdateDurIntegrations200ResponseData) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetApplications

`func (o *UpdateDurIntegrations200ResponseData) GetApplications() []interface{}`

GetApplications returns the Applications field if non-nil, zero value otherwise.

### GetApplicationsOk

`func (o *UpdateDurIntegrations200ResponseData) GetApplicationsOk() (*[]interface{}, bool)`

GetApplicationsOk returns a tuple with the Applications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplications

`func (o *UpdateDurIntegrations200ResponseData) SetApplications(v []interface{})`

SetApplications sets Applications field to given value.

### HasApplications

`func (o *UpdateDurIntegrations200ResponseData) HasApplications() bool`

HasApplications returns a boolean if a field has been set.

### GetUser

`func (o *UpdateDurIntegrations200ResponseData) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *UpdateDurIntegrations200ResponseData) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *UpdateDurIntegrations200ResponseData) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *UpdateDurIntegrations200ResponseData) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetTeam

`func (o *UpdateDurIntegrations200ResponseData) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *UpdateDurIntegrations200ResponseData) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *UpdateDurIntegrations200ResponseData) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *UpdateDurIntegrations200ResponseData) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetApplication

`func (o *UpdateDurIntegrations200ResponseData) GetApplication() []interface{}`

GetApplication returns the Application field if non-nil, zero value otherwise.

### GetApplicationOk

`func (o *UpdateDurIntegrations200ResponseData) GetApplicationOk() (*[]interface{}, bool)`

GetApplicationOk returns a tuple with the Application field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplication

`func (o *UpdateDurIntegrations200ResponseData) SetApplication(v []interface{})`

SetApplication sets Application field to given value.

### HasApplication

`func (o *UpdateDurIntegrations200ResponseData) HasApplication() bool`

HasApplication returns a boolean if a field has been set.

### GetApplicantId

`func (o *UpdateDurIntegrations200ResponseData) GetApplicantId() string`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *UpdateDurIntegrations200ResponseData) GetApplicantIdOk() (*string, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *UpdateDurIntegrations200ResponseData) SetApplicantId(v string)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *UpdateDurIntegrations200ResponseData) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateDurIntegrations200ResponseData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateDurIntegrations200ResponseData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateDurIntegrations200ResponseData) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateDurIntegrations200ResponseData) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


