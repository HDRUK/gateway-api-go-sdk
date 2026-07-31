# CreateDurIntegrationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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
**User** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**ApplicantId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateDurIntegrationsRequest

`func NewCreateDurIntegrationsRequest() *CreateDurIntegrationsRequest`

NewCreateDurIntegrationsRequest instantiates a new CreateDurIntegrationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDurIntegrationsRequestWithDefaults

`func NewCreateDurIntegrationsRequestWithDefaults() *CreateDurIntegrationsRequest`

NewCreateDurIntegrationsRequestWithDefaults instantiates a new CreateDurIntegrationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNonGatewayDatasets

`func (o *CreateDurIntegrationsRequest) GetNonGatewayDatasets() []interface{}`

GetNonGatewayDatasets returns the NonGatewayDatasets field if non-nil, zero value otherwise.

### GetNonGatewayDatasetsOk

`func (o *CreateDurIntegrationsRequest) GetNonGatewayDatasetsOk() (*[]interface{}, bool)`

GetNonGatewayDatasetsOk returns a tuple with the NonGatewayDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayDatasets

`func (o *CreateDurIntegrationsRequest) SetNonGatewayDatasets(v []interface{})`

SetNonGatewayDatasets sets NonGatewayDatasets field to given value.

### HasNonGatewayDatasets

`func (o *CreateDurIntegrationsRequest) HasNonGatewayDatasets() bool`

HasNonGatewayDatasets returns a boolean if a field has been set.

### GetNonGatewayApplicants

`func (o *CreateDurIntegrationsRequest) GetNonGatewayApplicants() []interface{}`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *CreateDurIntegrationsRequest) GetNonGatewayApplicantsOk() (*[]interface{}, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *CreateDurIntegrationsRequest) SetNonGatewayApplicants(v []interface{})`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *CreateDurIntegrationsRequest) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *CreateDurIntegrationsRequest) GetFundersAndSponsors() []interface{}`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *CreateDurIntegrationsRequest) GetFundersAndSponsorsOk() (*[]interface{}, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *CreateDurIntegrationsRequest) SetFundersAndSponsors(v []interface{})`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *CreateDurIntegrationsRequest) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *CreateDurIntegrationsRequest) GetOtherApprovalCommittees() []interface{}`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *CreateDurIntegrationsRequest) GetOtherApprovalCommitteesOk() (*[]interface{}, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *CreateDurIntegrationsRequest) SetOtherApprovalCommittees(v []interface{})`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *CreateDurIntegrationsRequest) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetGatewayOutputsTools

`func (o *CreateDurIntegrationsRequest) GetGatewayOutputsTools() []interface{}`

GetGatewayOutputsTools returns the GatewayOutputsTools field if non-nil, zero value otherwise.

### GetGatewayOutputsToolsOk

`func (o *CreateDurIntegrationsRequest) GetGatewayOutputsToolsOk() (*[]interface{}, bool)`

GetGatewayOutputsToolsOk returns a tuple with the GatewayOutputsTools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsTools

`func (o *CreateDurIntegrationsRequest) SetGatewayOutputsTools(v []interface{})`

SetGatewayOutputsTools sets GatewayOutputsTools field to given value.

### HasGatewayOutputsTools

`func (o *CreateDurIntegrationsRequest) HasGatewayOutputsTools() bool`

HasGatewayOutputsTools returns a boolean if a field has been set.

### GetGatewayOutputsPapers

`func (o *CreateDurIntegrationsRequest) GetGatewayOutputsPapers() []interface{}`

GetGatewayOutputsPapers returns the GatewayOutputsPapers field if non-nil, zero value otherwise.

### GetGatewayOutputsPapersOk

`func (o *CreateDurIntegrationsRequest) GetGatewayOutputsPapersOk() (*[]interface{}, bool)`

GetGatewayOutputsPapersOk returns a tuple with the GatewayOutputsPapers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsPapers

`func (o *CreateDurIntegrationsRequest) SetGatewayOutputsPapers(v []interface{})`

SetGatewayOutputsPapers sets GatewayOutputsPapers field to given value.

### HasGatewayOutputsPapers

`func (o *CreateDurIntegrationsRequest) HasGatewayOutputsPapers() bool`

HasGatewayOutputsPapers returns a boolean if a field has been set.

### GetNonGatewayOutputs

`func (o *CreateDurIntegrationsRequest) GetNonGatewayOutputs() []interface{}`

GetNonGatewayOutputs returns the NonGatewayOutputs field if non-nil, zero value otherwise.

### GetNonGatewayOutputsOk

`func (o *CreateDurIntegrationsRequest) GetNonGatewayOutputsOk() (*[]interface{}, bool)`

GetNonGatewayOutputsOk returns a tuple with the NonGatewayOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayOutputs

`func (o *CreateDurIntegrationsRequest) SetNonGatewayOutputs(v []interface{})`

SetNonGatewayOutputs sets NonGatewayOutputs field to given value.

### HasNonGatewayOutputs

`func (o *CreateDurIntegrationsRequest) HasNonGatewayOutputs() bool`

HasNonGatewayOutputs returns a boolean if a field has been set.

### GetProjectTitle

`func (o *CreateDurIntegrationsRequest) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *CreateDurIntegrationsRequest) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *CreateDurIntegrationsRequest) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *CreateDurIntegrationsRequest) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetProjectIdText

`func (o *CreateDurIntegrationsRequest) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *CreateDurIntegrationsRequest) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *CreateDurIntegrationsRequest) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *CreateDurIntegrationsRequest) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### GetOrganisationName

`func (o *CreateDurIntegrationsRequest) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *CreateDurIntegrationsRequest) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *CreateDurIntegrationsRequest) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *CreateDurIntegrationsRequest) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetOrganisationSector

`func (o *CreateDurIntegrationsRequest) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *CreateDurIntegrationsRequest) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *CreateDurIntegrationsRequest) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *CreateDurIntegrationsRequest) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### GetLaySummary

`func (o *CreateDurIntegrationsRequest) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *CreateDurIntegrationsRequest) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *CreateDurIntegrationsRequest) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *CreateDurIntegrationsRequest) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *CreateDurIntegrationsRequest) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *CreateDurIntegrationsRequest) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *CreateDurIntegrationsRequest) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *CreateDurIntegrationsRequest) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetLatestApprovalDate

`func (o *CreateDurIntegrationsRequest) GetLatestApprovalDate() time.Time`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *CreateDurIntegrationsRequest) GetLatestApprovalDateOk() (*time.Time, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *CreateDurIntegrationsRequest) SetLatestApprovalDate(v time.Time)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *CreateDurIntegrationsRequest) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### GetManualUpload

`func (o *CreateDurIntegrationsRequest) GetManualUpload() bool`

GetManualUpload returns the ManualUpload field if non-nil, zero value otherwise.

### GetManualUploadOk

`func (o *CreateDurIntegrationsRequest) GetManualUploadOk() (*bool, bool)`

GetManualUploadOk returns a tuple with the ManualUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualUpload

`func (o *CreateDurIntegrationsRequest) SetManualUpload(v bool)`

SetManualUpload sets ManualUpload field to given value.

### HasManualUpload

`func (o *CreateDurIntegrationsRequest) HasManualUpload() bool`

HasManualUpload returns a boolean if a field has been set.

### GetRejectionReason

`func (o *CreateDurIntegrationsRequest) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *CreateDurIntegrationsRequest) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *CreateDurIntegrationsRequest) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *CreateDurIntegrationsRequest) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### GetSublicenceArrangements

`func (o *CreateDurIntegrationsRequest) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *CreateDurIntegrationsRequest) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *CreateDurIntegrationsRequest) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *CreateDurIntegrationsRequest) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### GetPublicBenefitStatement

`func (o *CreateDurIntegrationsRequest) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *CreateDurIntegrationsRequest) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *CreateDurIntegrationsRequest) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *CreateDurIntegrationsRequest) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *CreateDurIntegrationsRequest) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *CreateDurIntegrationsRequest) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *CreateDurIntegrationsRequest) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *CreateDurIntegrationsRequest) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetProjectStartDate

`func (o *CreateDurIntegrationsRequest) GetProjectStartDate() time.Time`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *CreateDurIntegrationsRequest) GetProjectStartDateOk() (*time.Time, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *CreateDurIntegrationsRequest) SetProjectStartDate(v time.Time)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *CreateDurIntegrationsRequest) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### GetProjectEndDate

`func (o *CreateDurIntegrationsRequest) GetProjectEndDate() time.Time`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *CreateDurIntegrationsRequest) GetProjectEndDateOk() (*time.Time, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *CreateDurIntegrationsRequest) SetProjectEndDate(v time.Time)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *CreateDurIntegrationsRequest) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### GetAccessDate

`func (o *CreateDurIntegrationsRequest) GetAccessDate() time.Time`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *CreateDurIntegrationsRequest) GetAccessDateOk() (*time.Time, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *CreateDurIntegrationsRequest) SetAccessDate(v time.Time)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *CreateDurIntegrationsRequest) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccreditedResearcherStatus

`func (o *CreateDurIntegrationsRequest) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *CreateDurIntegrationsRequest) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *CreateDurIntegrationsRequest) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *CreateDurIntegrationsRequest) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### GetConfidentialDataDescription

`func (o *CreateDurIntegrationsRequest) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *CreateDurIntegrationsRequest) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *CreateDurIntegrationsRequest) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *CreateDurIntegrationsRequest) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *CreateDurIntegrationsRequest) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *CreateDurIntegrationsRequest) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *CreateDurIntegrationsRequest) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *CreateDurIntegrationsRequest) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *CreateDurIntegrationsRequest) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *CreateDurIntegrationsRequest) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *CreateDurIntegrationsRequest) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *CreateDurIntegrationsRequest) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *CreateDurIntegrationsRequest) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *CreateDurIntegrationsRequest) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *CreateDurIntegrationsRequest) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *CreateDurIntegrationsRequest) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetLegalBasisForDataArticle9

`func (o *CreateDurIntegrationsRequest) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *CreateDurIntegrationsRequest) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *CreateDurIntegrationsRequest) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *CreateDurIntegrationsRequest) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *CreateDurIntegrationsRequest) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *CreateDurIntegrationsRequest) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *CreateDurIntegrationsRequest) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *CreateDurIntegrationsRequest) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetOrganisationId

`func (o *CreateDurIntegrationsRequest) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *CreateDurIntegrationsRequest) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *CreateDurIntegrationsRequest) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *CreateDurIntegrationsRequest) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetPrivacyEnhancements

`func (o *CreateDurIntegrationsRequest) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *CreateDurIntegrationsRequest) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *CreateDurIntegrationsRequest) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *CreateDurIntegrationsRequest) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *CreateDurIntegrationsRequest) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *CreateDurIntegrationsRequest) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *CreateDurIntegrationsRequest) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *CreateDurIntegrationsRequest) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *CreateDurIntegrationsRequest) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *CreateDurIntegrationsRequest) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *CreateDurIntegrationsRequest) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *CreateDurIntegrationsRequest) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetAccessType

`func (o *CreateDurIntegrationsRequest) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *CreateDurIntegrationsRequest) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *CreateDurIntegrationsRequest) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *CreateDurIntegrationsRequest) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetMongoObjectDarId

`func (o *CreateDurIntegrationsRequest) GetMongoObjectDarId() string`

GetMongoObjectDarId returns the MongoObjectDarId field if non-nil, zero value otherwise.

### GetMongoObjectDarIdOk

`func (o *CreateDurIntegrationsRequest) GetMongoObjectDarIdOk() (*string, bool)`

GetMongoObjectDarIdOk returns a tuple with the MongoObjectDarId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectDarId

`func (o *CreateDurIntegrationsRequest) SetMongoObjectDarId(v string)`

SetMongoObjectDarId sets MongoObjectDarId field to given value.

### HasMongoObjectDarId

`func (o *CreateDurIntegrationsRequest) HasMongoObjectDarId() bool`

HasMongoObjectDarId returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateDurIntegrationsRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDurIntegrationsRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDurIntegrationsRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateDurIntegrationsRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLastActivity

`func (o *CreateDurIntegrationsRequest) GetLastActivity() time.Time`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *CreateDurIntegrationsRequest) GetLastActivityOk() (*time.Time, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *CreateDurIntegrationsRequest) SetLastActivity(v time.Time)`

SetLastActivity sets LastActivity field to given value.

### HasLastActivity

`func (o *CreateDurIntegrationsRequest) HasLastActivity() bool`

HasLastActivity returns a boolean if a field has been set.

### GetCounter

`func (o *CreateDurIntegrationsRequest) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *CreateDurIntegrationsRequest) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *CreateDurIntegrationsRequest) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *CreateDurIntegrationsRequest) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### GetMongoObjectId

`func (o *CreateDurIntegrationsRequest) GetMongoObjectId() string`

GetMongoObjectId returns the MongoObjectId field if non-nil, zero value otherwise.

### GetMongoObjectIdOk

`func (o *CreateDurIntegrationsRequest) GetMongoObjectIdOk() (*string, bool)`

GetMongoObjectIdOk returns a tuple with the MongoObjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectId

`func (o *CreateDurIntegrationsRequest) SetMongoObjectId(v string)`

SetMongoObjectId sets MongoObjectId field to given value.

### HasMongoObjectId

`func (o *CreateDurIntegrationsRequest) HasMongoObjectId() bool`

HasMongoObjectId returns a boolean if a field has been set.

### GetMongoId

`func (o *CreateDurIntegrationsRequest) GetMongoId() string`

GetMongoId returns the MongoId field if non-nil, zero value otherwise.

### GetMongoIdOk

`func (o *CreateDurIntegrationsRequest) GetMongoIdOk() (*string, bool)`

GetMongoIdOk returns a tuple with the MongoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoId

`func (o *CreateDurIntegrationsRequest) SetMongoId(v string)`

SetMongoId sets MongoId field to given value.

### HasMongoId

`func (o *CreateDurIntegrationsRequest) HasMongoId() bool`

HasMongoId returns a boolean if a field has been set.

### GetDatasets

`func (o *CreateDurIntegrationsRequest) GetDatasets() []interface{}`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreateDurIntegrationsRequest) GetDatasetsOk() (*[]interface{}, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreateDurIntegrationsRequest) SetDatasets(v []interface{})`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreateDurIntegrationsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateDurIntegrationsRequest) GetKeywords() []interface{}`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateDurIntegrationsRequest) GetKeywordsOk() (*[]interface{}, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateDurIntegrationsRequest) SetKeywords(v []interface{})`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateDurIntegrationsRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetUsers

`func (o *CreateDurIntegrationsRequest) GetUsers() []interface{}`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *CreateDurIntegrationsRequest) GetUsersOk() (*[]interface{}, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *CreateDurIntegrationsRequest) SetUsers(v []interface{})`

SetUsers sets Users field to given value.

### HasUsers

`func (o *CreateDurIntegrationsRequest) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetUser

`func (o *CreateDurIntegrationsRequest) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CreateDurIntegrationsRequest) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CreateDurIntegrationsRequest) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *CreateDurIntegrationsRequest) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetTeam

`func (o *CreateDurIntegrationsRequest) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *CreateDurIntegrationsRequest) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *CreateDurIntegrationsRequest) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *CreateDurIntegrationsRequest) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetApplicantId

`func (o *CreateDurIntegrationsRequest) GetApplicantId() string`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *CreateDurIntegrationsRequest) GetApplicantIdOk() (*string, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *CreateDurIntegrationsRequest) SetApplicantId(v string)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *CreateDurIntegrationsRequest) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetStatus

`func (o *CreateDurIntegrationsRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateDurIntegrationsRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateDurIntegrationsRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateDurIntegrationsRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


