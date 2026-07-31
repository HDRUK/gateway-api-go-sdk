# UploadDurRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | Pointer to **int32** |  | [optional] 
**TeamId** | Pointer to **int32** |  | [optional] 
**ProjectTitle** | Pointer to **string** |  | [optional] 
**ProjectIdText** | Pointer to **string** |  | [optional] 
**OrganisationName** | Pointer to **string** |  | [optional] 
**OrganisationId** | Pointer to **string** |  | [optional] 
**OrganisationSector** | Pointer to **string** |  | [optional] 
**NonGatewayApplicants** | Pointer to **string** |  | [optional] 
**ApplicantId** | Pointer to **int32** |  | [optional] 
**FundersAndSponsors** | Pointer to **string** |  | [optional] 
**AccreditedResearcherStatus** | Pointer to **string** |  | [optional] 
**SublicenceArrangements** | Pointer to **string** |  | [optional] 
**LaySummary** | Pointer to **string** |  | [optional] 
**PublicBenefitStatement** | Pointer to **string** |  | [optional] 
**RequestCategoryType** | Pointer to **string** |  | [optional] 
**TechnicalSummary** | Pointer to **string** |  | [optional] 
**OtherApprovalCommittees** | Pointer to **string** |  | [optional] 
**ProjectStartDate** | Pointer to **string** |  | [optional] 
**ProjectEndDate** | Pointer to **string** |  | [optional] 
**LatestApprovalDate** | Pointer to **string** |  | [optional] 
**DataSensitivityLevel** | Pointer to **string** |  | [optional] 
**LegalBasisForDataArticle6** | Pointer to **string** |  | [optional] 
**LegalBasisForDataArticle9** | Pointer to **string** |  | [optional] 
**DutyOfConfidentiality** | Pointer to **string** |  | [optional] 
**NationalDataOptout** | Pointer to **string** |  | [optional] 
**RequestFrequency** | Pointer to **string** |  | [optional] 
**DatasetLinkageDescription** | Pointer to **string** |  | [optional] 
**ConfidentialDataDescription** | Pointer to **string** |  | [optional] 
**AccessDate** | Pointer to **string** |  | [optional] 
**AccessType** | Pointer to **string** |  | [optional] 
**PrivacyEnhancements** | Pointer to **string** |  | [optional] 
**Datasets** | Pointer to [**[]CreateDurRequestDatasetsInner**](CreateDurRequestDatasetsInner.md) |  | [optional] 

## Methods

### NewUploadDurRequest

`func NewUploadDurRequest() *UploadDurRequest`

NewUploadDurRequest instantiates a new UploadDurRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadDurRequestWithDefaults

`func NewUploadDurRequestWithDefaults() *UploadDurRequest`

NewUploadDurRequestWithDefaults instantiates a new UploadDurRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *UploadDurRequest) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UploadDurRequest) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UploadDurRequest) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UploadDurRequest) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetTeamId

`func (o *UploadDurRequest) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *UploadDurRequest) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *UploadDurRequest) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *UploadDurRequest) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### GetProjectTitle

`func (o *UploadDurRequest) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *UploadDurRequest) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *UploadDurRequest) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *UploadDurRequest) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetProjectIdText

`func (o *UploadDurRequest) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *UploadDurRequest) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *UploadDurRequest) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *UploadDurRequest) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### GetOrganisationName

`func (o *UploadDurRequest) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *UploadDurRequest) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *UploadDurRequest) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *UploadDurRequest) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetOrganisationId

`func (o *UploadDurRequest) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *UploadDurRequest) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *UploadDurRequest) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *UploadDurRequest) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetOrganisationSector

`func (o *UploadDurRequest) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *UploadDurRequest) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *UploadDurRequest) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *UploadDurRequest) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### GetNonGatewayApplicants

`func (o *UploadDurRequest) GetNonGatewayApplicants() string`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *UploadDurRequest) GetNonGatewayApplicantsOk() (*string, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *UploadDurRequest) SetNonGatewayApplicants(v string)`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *UploadDurRequest) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### GetApplicantId

`func (o *UploadDurRequest) GetApplicantId() int32`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *UploadDurRequest) GetApplicantIdOk() (*int32, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *UploadDurRequest) SetApplicantId(v int32)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *UploadDurRequest) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *UploadDurRequest) GetFundersAndSponsors() string`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *UploadDurRequest) GetFundersAndSponsorsOk() (*string, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *UploadDurRequest) SetFundersAndSponsors(v string)`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *UploadDurRequest) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetAccreditedResearcherStatus

`func (o *UploadDurRequest) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *UploadDurRequest) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *UploadDurRequest) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *UploadDurRequest) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### GetSublicenceArrangements

`func (o *UploadDurRequest) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *UploadDurRequest) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *UploadDurRequest) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *UploadDurRequest) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### GetLaySummary

`func (o *UploadDurRequest) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *UploadDurRequest) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *UploadDurRequest) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *UploadDurRequest) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetPublicBenefitStatement

`func (o *UploadDurRequest) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *UploadDurRequest) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *UploadDurRequest) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *UploadDurRequest) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *UploadDurRequest) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *UploadDurRequest) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *UploadDurRequest) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *UploadDurRequest) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *UploadDurRequest) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *UploadDurRequest) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *UploadDurRequest) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *UploadDurRequest) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *UploadDurRequest) GetOtherApprovalCommittees() string`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *UploadDurRequest) GetOtherApprovalCommitteesOk() (*string, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *UploadDurRequest) SetOtherApprovalCommittees(v string)`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *UploadDurRequest) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetProjectStartDate

`func (o *UploadDurRequest) GetProjectStartDate() string`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *UploadDurRequest) GetProjectStartDateOk() (*string, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *UploadDurRequest) SetProjectStartDate(v string)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *UploadDurRequest) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### GetProjectEndDate

`func (o *UploadDurRequest) GetProjectEndDate() string`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *UploadDurRequest) GetProjectEndDateOk() (*string, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *UploadDurRequest) SetProjectEndDate(v string)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *UploadDurRequest) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### GetLatestApprovalDate

`func (o *UploadDurRequest) GetLatestApprovalDate() string`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *UploadDurRequest) GetLatestApprovalDateOk() (*string, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *UploadDurRequest) SetLatestApprovalDate(v string)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *UploadDurRequest) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *UploadDurRequest) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *UploadDurRequest) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *UploadDurRequest) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *UploadDurRequest) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *UploadDurRequest) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *UploadDurRequest) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *UploadDurRequest) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *UploadDurRequest) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetLegalBasisForDataArticle9

`func (o *UploadDurRequest) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *UploadDurRequest) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *UploadDurRequest) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *UploadDurRequest) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *UploadDurRequest) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *UploadDurRequest) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *UploadDurRequest) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *UploadDurRequest) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *UploadDurRequest) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *UploadDurRequest) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *UploadDurRequest) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *UploadDurRequest) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *UploadDurRequest) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *UploadDurRequest) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *UploadDurRequest) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *UploadDurRequest) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *UploadDurRequest) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *UploadDurRequest) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *UploadDurRequest) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *UploadDurRequest) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetConfidentialDataDescription

`func (o *UploadDurRequest) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *UploadDurRequest) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *UploadDurRequest) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *UploadDurRequest) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### GetAccessDate

`func (o *UploadDurRequest) GetAccessDate() string`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *UploadDurRequest) GetAccessDateOk() (*string, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *UploadDurRequest) SetAccessDate(v string)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *UploadDurRequest) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccessType

`func (o *UploadDurRequest) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *UploadDurRequest) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *UploadDurRequest) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *UploadDurRequest) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetPrivacyEnhancements

`func (o *UploadDurRequest) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *UploadDurRequest) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *UploadDurRequest) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *UploadDurRequest) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### GetDatasets

`func (o *UploadDurRequest) GetDatasets() []CreateDurRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *UploadDurRequest) GetDatasetsOk() (*[]CreateDurRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *UploadDurRequest) SetDatasets(v []CreateDurRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *UploadDurRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


