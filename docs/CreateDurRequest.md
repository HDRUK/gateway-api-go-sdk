# CreateDurRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NonGatewayDatasets** | Pointer to **[]string** |  | [optional] 
**NonGatewayApplicants** | Pointer to **[]string** |  | [optional] 
**FundersAndSponsors** | Pointer to **[]string** |  | [optional] 
**OtherApprovalCommittees** | Pointer to **[]string** |  | [optional] 
**GatewayOutputsTools** | Pointer to **[]string** |  | [optional] 
**GatewayOutputsPapers** | Pointer to **[]string** |  | [optional] 
**NonGatewayOutputs** | Pointer to **[]string** |  | [optional] 
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
**Datasets** | Pointer to [**[]CreateDurRequestDatasetsInner**](CreateDurRequestDatasetsInner.md) |  | [optional] 
**Publications** | Pointer to [**[]CreateDurRequestPublicationsInner**](CreateDurRequestPublicationsInner.md) |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**Users** | Pointer to [**[]CreateDurRequestUsersInner**](CreateDurRequestUsersInner.md) |  | [optional] 
**User** | Pointer to [**[]CreateDurRequestUsersInner**](CreateDurRequestUsersInner.md) |  | [optional] 
**Team** | Pointer to [**[]CreateDurRequestTeamInner**](CreateDurRequestTeamInner.md) |  | [optional] 
**ApplicantId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateDurRequest

`func NewCreateDurRequest() *CreateDurRequest`

NewCreateDurRequest instantiates a new CreateDurRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDurRequestWithDefaults

`func NewCreateDurRequestWithDefaults() *CreateDurRequest`

NewCreateDurRequestWithDefaults instantiates a new CreateDurRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNonGatewayDatasets

`func (o *CreateDurRequest) GetNonGatewayDatasets() []string`

GetNonGatewayDatasets returns the NonGatewayDatasets field if non-nil, zero value otherwise.

### GetNonGatewayDatasetsOk

`func (o *CreateDurRequest) GetNonGatewayDatasetsOk() (*[]string, bool)`

GetNonGatewayDatasetsOk returns a tuple with the NonGatewayDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayDatasets

`func (o *CreateDurRequest) SetNonGatewayDatasets(v []string)`

SetNonGatewayDatasets sets NonGatewayDatasets field to given value.

### HasNonGatewayDatasets

`func (o *CreateDurRequest) HasNonGatewayDatasets() bool`

HasNonGatewayDatasets returns a boolean if a field has been set.

### GetNonGatewayApplicants

`func (o *CreateDurRequest) GetNonGatewayApplicants() []string`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *CreateDurRequest) GetNonGatewayApplicantsOk() (*[]string, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *CreateDurRequest) SetNonGatewayApplicants(v []string)`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *CreateDurRequest) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *CreateDurRequest) GetFundersAndSponsors() []string`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *CreateDurRequest) GetFundersAndSponsorsOk() (*[]string, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *CreateDurRequest) SetFundersAndSponsors(v []string)`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *CreateDurRequest) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *CreateDurRequest) GetOtherApprovalCommittees() []string`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *CreateDurRequest) GetOtherApprovalCommitteesOk() (*[]string, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *CreateDurRequest) SetOtherApprovalCommittees(v []string)`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *CreateDurRequest) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetGatewayOutputsTools

`func (o *CreateDurRequest) GetGatewayOutputsTools() []string`

GetGatewayOutputsTools returns the GatewayOutputsTools field if non-nil, zero value otherwise.

### GetGatewayOutputsToolsOk

`func (o *CreateDurRequest) GetGatewayOutputsToolsOk() (*[]string, bool)`

GetGatewayOutputsToolsOk returns a tuple with the GatewayOutputsTools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsTools

`func (o *CreateDurRequest) SetGatewayOutputsTools(v []string)`

SetGatewayOutputsTools sets GatewayOutputsTools field to given value.

### HasGatewayOutputsTools

`func (o *CreateDurRequest) HasGatewayOutputsTools() bool`

HasGatewayOutputsTools returns a boolean if a field has been set.

### GetGatewayOutputsPapers

`func (o *CreateDurRequest) GetGatewayOutputsPapers() []string`

GetGatewayOutputsPapers returns the GatewayOutputsPapers field if non-nil, zero value otherwise.

### GetGatewayOutputsPapersOk

`func (o *CreateDurRequest) GetGatewayOutputsPapersOk() (*[]string, bool)`

GetGatewayOutputsPapersOk returns a tuple with the GatewayOutputsPapers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsPapers

`func (o *CreateDurRequest) SetGatewayOutputsPapers(v []string)`

SetGatewayOutputsPapers sets GatewayOutputsPapers field to given value.

### HasGatewayOutputsPapers

`func (o *CreateDurRequest) HasGatewayOutputsPapers() bool`

HasGatewayOutputsPapers returns a boolean if a field has been set.

### GetNonGatewayOutputs

`func (o *CreateDurRequest) GetNonGatewayOutputs() []string`

GetNonGatewayOutputs returns the NonGatewayOutputs field if non-nil, zero value otherwise.

### GetNonGatewayOutputsOk

`func (o *CreateDurRequest) GetNonGatewayOutputsOk() (*[]string, bool)`

GetNonGatewayOutputsOk returns a tuple with the NonGatewayOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayOutputs

`func (o *CreateDurRequest) SetNonGatewayOutputs(v []string)`

SetNonGatewayOutputs sets NonGatewayOutputs field to given value.

### HasNonGatewayOutputs

`func (o *CreateDurRequest) HasNonGatewayOutputs() bool`

HasNonGatewayOutputs returns a boolean if a field has been set.

### GetProjectTitle

`func (o *CreateDurRequest) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *CreateDurRequest) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *CreateDurRequest) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *CreateDurRequest) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetProjectIdText

`func (o *CreateDurRequest) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *CreateDurRequest) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *CreateDurRequest) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *CreateDurRequest) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### GetOrganisationName

`func (o *CreateDurRequest) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *CreateDurRequest) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *CreateDurRequest) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *CreateDurRequest) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetOrganisationSector

`func (o *CreateDurRequest) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *CreateDurRequest) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *CreateDurRequest) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *CreateDurRequest) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### GetLaySummary

`func (o *CreateDurRequest) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *CreateDurRequest) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *CreateDurRequest) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *CreateDurRequest) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *CreateDurRequest) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *CreateDurRequest) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *CreateDurRequest) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *CreateDurRequest) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetLatestApprovalDate

`func (o *CreateDurRequest) GetLatestApprovalDate() time.Time`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *CreateDurRequest) GetLatestApprovalDateOk() (*time.Time, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *CreateDurRequest) SetLatestApprovalDate(v time.Time)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *CreateDurRequest) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### GetManualUpload

`func (o *CreateDurRequest) GetManualUpload() bool`

GetManualUpload returns the ManualUpload field if non-nil, zero value otherwise.

### GetManualUploadOk

`func (o *CreateDurRequest) GetManualUploadOk() (*bool, bool)`

GetManualUploadOk returns a tuple with the ManualUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualUpload

`func (o *CreateDurRequest) SetManualUpload(v bool)`

SetManualUpload sets ManualUpload field to given value.

### HasManualUpload

`func (o *CreateDurRequest) HasManualUpload() bool`

HasManualUpload returns a boolean if a field has been set.

### GetRejectionReason

`func (o *CreateDurRequest) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *CreateDurRequest) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *CreateDurRequest) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *CreateDurRequest) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### GetSublicenceArrangements

`func (o *CreateDurRequest) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *CreateDurRequest) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *CreateDurRequest) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *CreateDurRequest) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### GetPublicBenefitStatement

`func (o *CreateDurRequest) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *CreateDurRequest) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *CreateDurRequest) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *CreateDurRequest) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *CreateDurRequest) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *CreateDurRequest) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *CreateDurRequest) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *CreateDurRequest) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetProjectStartDate

`func (o *CreateDurRequest) GetProjectStartDate() time.Time`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *CreateDurRequest) GetProjectStartDateOk() (*time.Time, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *CreateDurRequest) SetProjectStartDate(v time.Time)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *CreateDurRequest) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### GetProjectEndDate

`func (o *CreateDurRequest) GetProjectEndDate() time.Time`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *CreateDurRequest) GetProjectEndDateOk() (*time.Time, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *CreateDurRequest) SetProjectEndDate(v time.Time)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *CreateDurRequest) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### GetAccessDate

`func (o *CreateDurRequest) GetAccessDate() time.Time`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *CreateDurRequest) GetAccessDateOk() (*time.Time, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *CreateDurRequest) SetAccessDate(v time.Time)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *CreateDurRequest) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccreditedResearcherStatus

`func (o *CreateDurRequest) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *CreateDurRequest) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *CreateDurRequest) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *CreateDurRequest) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### GetConfidentialDataDescription

`func (o *CreateDurRequest) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *CreateDurRequest) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *CreateDurRequest) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *CreateDurRequest) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *CreateDurRequest) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *CreateDurRequest) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *CreateDurRequest) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *CreateDurRequest) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *CreateDurRequest) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *CreateDurRequest) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *CreateDurRequest) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *CreateDurRequest) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *CreateDurRequest) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *CreateDurRequest) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *CreateDurRequest) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *CreateDurRequest) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetLegalBasisForDataArticle9

`func (o *CreateDurRequest) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *CreateDurRequest) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *CreateDurRequest) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *CreateDurRequest) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *CreateDurRequest) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *CreateDurRequest) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *CreateDurRequest) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *CreateDurRequest) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetOrganisationId

`func (o *CreateDurRequest) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *CreateDurRequest) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *CreateDurRequest) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *CreateDurRequest) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetPrivacyEnhancements

`func (o *CreateDurRequest) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *CreateDurRequest) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *CreateDurRequest) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *CreateDurRequest) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *CreateDurRequest) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *CreateDurRequest) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *CreateDurRequest) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *CreateDurRequest) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *CreateDurRequest) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *CreateDurRequest) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *CreateDurRequest) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *CreateDurRequest) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetAccessType

`func (o *CreateDurRequest) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *CreateDurRequest) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *CreateDurRequest) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *CreateDurRequest) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetMongoObjectDarId

`func (o *CreateDurRequest) GetMongoObjectDarId() string`

GetMongoObjectDarId returns the MongoObjectDarId field if non-nil, zero value otherwise.

### GetMongoObjectDarIdOk

`func (o *CreateDurRequest) GetMongoObjectDarIdOk() (*string, bool)`

GetMongoObjectDarIdOk returns a tuple with the MongoObjectDarId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectDarId

`func (o *CreateDurRequest) SetMongoObjectDarId(v string)`

SetMongoObjectDarId sets MongoObjectDarId field to given value.

### HasMongoObjectDarId

`func (o *CreateDurRequest) HasMongoObjectDarId() bool`

HasMongoObjectDarId returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateDurRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDurRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDurRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateDurRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLastActivity

`func (o *CreateDurRequest) GetLastActivity() time.Time`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *CreateDurRequest) GetLastActivityOk() (*time.Time, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *CreateDurRequest) SetLastActivity(v time.Time)`

SetLastActivity sets LastActivity field to given value.

### HasLastActivity

`func (o *CreateDurRequest) HasLastActivity() bool`

HasLastActivity returns a boolean if a field has been set.

### GetCounter

`func (o *CreateDurRequest) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *CreateDurRequest) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *CreateDurRequest) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *CreateDurRequest) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### GetMongoObjectId

`func (o *CreateDurRequest) GetMongoObjectId() string`

GetMongoObjectId returns the MongoObjectId field if non-nil, zero value otherwise.

### GetMongoObjectIdOk

`func (o *CreateDurRequest) GetMongoObjectIdOk() (*string, bool)`

GetMongoObjectIdOk returns a tuple with the MongoObjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectId

`func (o *CreateDurRequest) SetMongoObjectId(v string)`

SetMongoObjectId sets MongoObjectId field to given value.

### HasMongoObjectId

`func (o *CreateDurRequest) HasMongoObjectId() bool`

HasMongoObjectId returns a boolean if a field has been set.

### GetMongoId

`func (o *CreateDurRequest) GetMongoId() string`

GetMongoId returns the MongoId field if non-nil, zero value otherwise.

### GetMongoIdOk

`func (o *CreateDurRequest) GetMongoIdOk() (*string, bool)`

GetMongoIdOk returns a tuple with the MongoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoId

`func (o *CreateDurRequest) SetMongoId(v string)`

SetMongoId sets MongoId field to given value.

### HasMongoId

`func (o *CreateDurRequest) HasMongoId() bool`

HasMongoId returns a boolean if a field has been set.

### GetDatasets

`func (o *CreateDurRequest) GetDatasets() []CreateDurRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreateDurRequest) GetDatasetsOk() (*[]CreateDurRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreateDurRequest) SetDatasets(v []CreateDurRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreateDurRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetPublications

`func (o *CreateDurRequest) GetPublications() []CreateDurRequestPublicationsInner`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *CreateDurRequest) GetPublicationsOk() (*[]CreateDurRequestPublicationsInner, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *CreateDurRequest) SetPublications(v []CreateDurRequestPublicationsInner)`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *CreateDurRequest) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateDurRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateDurRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateDurRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateDurRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetUsers

`func (o *CreateDurRequest) GetUsers() []CreateDurRequestUsersInner`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *CreateDurRequest) GetUsersOk() (*[]CreateDurRequestUsersInner, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *CreateDurRequest) SetUsers(v []CreateDurRequestUsersInner)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *CreateDurRequest) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetUser

`func (o *CreateDurRequest) GetUser() []CreateDurRequestUsersInner`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CreateDurRequest) GetUserOk() (*[]CreateDurRequestUsersInner, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CreateDurRequest) SetUser(v []CreateDurRequestUsersInner)`

SetUser sets User field to given value.

### HasUser

`func (o *CreateDurRequest) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetTeam

`func (o *CreateDurRequest) GetTeam() []CreateDurRequestTeamInner`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *CreateDurRequest) GetTeamOk() (*[]CreateDurRequestTeamInner, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *CreateDurRequest) SetTeam(v []CreateDurRequestTeamInner)`

SetTeam sets Team field to given value.

### HasTeam

`func (o *CreateDurRequest) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetApplicantId

`func (o *CreateDurRequest) GetApplicantId() string`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *CreateDurRequest) GetApplicantIdOk() (*string, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *CreateDurRequest) SetApplicantId(v string)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *CreateDurRequest) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetStatus

`func (o *CreateDurRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateDurRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateDurRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateDurRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


