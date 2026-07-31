# Dur

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ProjectTitle** | Pointer to **NullableString** |  | [optional] 
**ProjectIdText** | Pointer to **NullableString** |  | [optional] 
**OrganisationName** | Pointer to **NullableString** |  | [optional] 
**OrganisationSector** | Pointer to **NullableString** |  | [optional] 
**SectorId** | Pointer to **NullableInt32** |  | [optional] 
**LaySummary** | Pointer to **NullableString** |  | [optional] 
**TechnicalSummary** | Pointer to **NullableString** |  | [optional] 
**LatestApprovalDate** | Pointer to **NullableString** |  | [optional] 
**ManualUpload** | Pointer to **bool** |  | [optional] 
**RejectionReason** | Pointer to **NullableString** |  | [optional] 
**SublicenceArrangements** | Pointer to **NullableString** |  | [optional] 
**PublicBenefitStatement** | Pointer to **NullableString** |  | [optional] 
**DataSensitivityLevel** | Pointer to **NullableString** |  | [optional] 
**ProjectStartDate** | Pointer to **NullableString** |  | [optional] 
**ProjectEndDate** | Pointer to **NullableString** |  | [optional] 
**AccessDate** | Pointer to **NullableString** |  | [optional] 
**AccreditedResearcherStatus** | Pointer to **NullableString** |  | [optional] 
**ConfidentialDataDescription** | Pointer to **NullableString** |  | [optional] 
**DatasetLinkageDescription** | Pointer to **NullableString** |  | [optional] 
**DutyOfConfidentiality** | Pointer to **NullableString** |  | [optional] 
**LegalBasisForDataArticle6** | Pointer to **NullableString** |  | [optional] 
**LegalBasisForDataArticle9** | Pointer to **NullableString** |  | [optional] 
**NationalDataOptout** | Pointer to **NullableString** |  | [optional] 
**OrganisationId** | Pointer to **NullableString** |  | [optional] 
**PrivacyEnhancements** | Pointer to **NullableString** |  | [optional] 
**RequestCategoryType** | Pointer to **NullableString** |  | [optional] 
**RequestFrequency** | Pointer to **NullableString** |  | [optional] 
**AccessType** | Pointer to **NullableString** |  | [optional] 
**NonGatewayDatasets** | Pointer to **[]string** |  | [optional] 
**NonGatewayApplicants** | Pointer to **[]string** |  | [optional] 
**FundersAndSponsors** | Pointer to **[]string** |  | [optional] 
**OtherApprovalCommittees** | Pointer to **[]string** |  | [optional] 
**GatewayOutputsTools** | Pointer to **[]string** |  | [optional] 
**GatewayOutputsPapers** | Pointer to **[]string** |  | [optional] 
**NonGatewayOutputs** | Pointer to **[]string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**LastActivity** | Pointer to **NullableTime** |  | [optional] 
**Counter** | Pointer to **NullableInt32** |  | [optional] 
**UserId** | Pointer to **NullableInt32** |  | [optional] 
**TeamId** | Pointer to **NullableInt32** |  | [optional] 
**ApplicantId** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewDur

`func NewDur() *Dur`

NewDur instantiates a new Dur object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDurWithDefaults

`func NewDurWithDefaults() *Dur`

NewDurWithDefaults instantiates a new Dur object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Dur) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Dur) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Dur) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Dur) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectTitle

`func (o *Dur) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *Dur) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *Dur) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *Dur) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### SetProjectTitleNil

`func (o *Dur) SetProjectTitleNil(b bool)`

 SetProjectTitleNil sets the value for ProjectTitle to be an explicit nil

### UnsetProjectTitle
`func (o *Dur) UnsetProjectTitle()`

UnsetProjectTitle ensures that no value is present for ProjectTitle, not even an explicit nil
### GetProjectIdText

`func (o *Dur) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *Dur) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *Dur) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *Dur) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### SetProjectIdTextNil

`func (o *Dur) SetProjectIdTextNil(b bool)`

 SetProjectIdTextNil sets the value for ProjectIdText to be an explicit nil

### UnsetProjectIdText
`func (o *Dur) UnsetProjectIdText()`

UnsetProjectIdText ensures that no value is present for ProjectIdText, not even an explicit nil
### GetOrganisationName

`func (o *Dur) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *Dur) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *Dur) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *Dur) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### SetOrganisationNameNil

`func (o *Dur) SetOrganisationNameNil(b bool)`

 SetOrganisationNameNil sets the value for OrganisationName to be an explicit nil

### UnsetOrganisationName
`func (o *Dur) UnsetOrganisationName()`

UnsetOrganisationName ensures that no value is present for OrganisationName, not even an explicit nil
### GetOrganisationSector

`func (o *Dur) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *Dur) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *Dur) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *Dur) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### SetOrganisationSectorNil

`func (o *Dur) SetOrganisationSectorNil(b bool)`

 SetOrganisationSectorNil sets the value for OrganisationSector to be an explicit nil

### UnsetOrganisationSector
`func (o *Dur) UnsetOrganisationSector()`

UnsetOrganisationSector ensures that no value is present for OrganisationSector, not even an explicit nil
### GetSectorId

`func (o *Dur) GetSectorId() int32`

GetSectorId returns the SectorId field if non-nil, zero value otherwise.

### GetSectorIdOk

`func (o *Dur) GetSectorIdOk() (*int32, bool)`

GetSectorIdOk returns a tuple with the SectorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectorId

`func (o *Dur) SetSectorId(v int32)`

SetSectorId sets SectorId field to given value.

### HasSectorId

`func (o *Dur) HasSectorId() bool`

HasSectorId returns a boolean if a field has been set.

### SetSectorIdNil

`func (o *Dur) SetSectorIdNil(b bool)`

 SetSectorIdNil sets the value for SectorId to be an explicit nil

### UnsetSectorId
`func (o *Dur) UnsetSectorId()`

UnsetSectorId ensures that no value is present for SectorId, not even an explicit nil
### GetLaySummary

`func (o *Dur) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *Dur) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *Dur) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *Dur) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### SetLaySummaryNil

`func (o *Dur) SetLaySummaryNil(b bool)`

 SetLaySummaryNil sets the value for LaySummary to be an explicit nil

### UnsetLaySummary
`func (o *Dur) UnsetLaySummary()`

UnsetLaySummary ensures that no value is present for LaySummary, not even an explicit nil
### GetTechnicalSummary

`func (o *Dur) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *Dur) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *Dur) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *Dur) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### SetTechnicalSummaryNil

`func (o *Dur) SetTechnicalSummaryNil(b bool)`

 SetTechnicalSummaryNil sets the value for TechnicalSummary to be an explicit nil

### UnsetTechnicalSummary
`func (o *Dur) UnsetTechnicalSummary()`

UnsetTechnicalSummary ensures that no value is present for TechnicalSummary, not even an explicit nil
### GetLatestApprovalDate

`func (o *Dur) GetLatestApprovalDate() string`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *Dur) GetLatestApprovalDateOk() (*string, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *Dur) SetLatestApprovalDate(v string)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *Dur) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### SetLatestApprovalDateNil

`func (o *Dur) SetLatestApprovalDateNil(b bool)`

 SetLatestApprovalDateNil sets the value for LatestApprovalDate to be an explicit nil

### UnsetLatestApprovalDate
`func (o *Dur) UnsetLatestApprovalDate()`

UnsetLatestApprovalDate ensures that no value is present for LatestApprovalDate, not even an explicit nil
### GetManualUpload

`func (o *Dur) GetManualUpload() bool`

GetManualUpload returns the ManualUpload field if non-nil, zero value otherwise.

### GetManualUploadOk

`func (o *Dur) GetManualUploadOk() (*bool, bool)`

GetManualUploadOk returns a tuple with the ManualUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualUpload

`func (o *Dur) SetManualUpload(v bool)`

SetManualUpload sets ManualUpload field to given value.

### HasManualUpload

`func (o *Dur) HasManualUpload() bool`

HasManualUpload returns a boolean if a field has been set.

### GetRejectionReason

`func (o *Dur) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *Dur) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *Dur) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *Dur) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### SetRejectionReasonNil

`func (o *Dur) SetRejectionReasonNil(b bool)`

 SetRejectionReasonNil sets the value for RejectionReason to be an explicit nil

### UnsetRejectionReason
`func (o *Dur) UnsetRejectionReason()`

UnsetRejectionReason ensures that no value is present for RejectionReason, not even an explicit nil
### GetSublicenceArrangements

`func (o *Dur) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *Dur) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *Dur) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *Dur) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### SetSublicenceArrangementsNil

`func (o *Dur) SetSublicenceArrangementsNil(b bool)`

 SetSublicenceArrangementsNil sets the value for SublicenceArrangements to be an explicit nil

### UnsetSublicenceArrangements
`func (o *Dur) UnsetSublicenceArrangements()`

UnsetSublicenceArrangements ensures that no value is present for SublicenceArrangements, not even an explicit nil
### GetPublicBenefitStatement

`func (o *Dur) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *Dur) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *Dur) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *Dur) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### SetPublicBenefitStatementNil

`func (o *Dur) SetPublicBenefitStatementNil(b bool)`

 SetPublicBenefitStatementNil sets the value for PublicBenefitStatement to be an explicit nil

### UnsetPublicBenefitStatement
`func (o *Dur) UnsetPublicBenefitStatement()`

UnsetPublicBenefitStatement ensures that no value is present for PublicBenefitStatement, not even an explicit nil
### GetDataSensitivityLevel

`func (o *Dur) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *Dur) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *Dur) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *Dur) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### SetDataSensitivityLevelNil

`func (o *Dur) SetDataSensitivityLevelNil(b bool)`

 SetDataSensitivityLevelNil sets the value for DataSensitivityLevel to be an explicit nil

### UnsetDataSensitivityLevel
`func (o *Dur) UnsetDataSensitivityLevel()`

UnsetDataSensitivityLevel ensures that no value is present for DataSensitivityLevel, not even an explicit nil
### GetProjectStartDate

`func (o *Dur) GetProjectStartDate() string`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *Dur) GetProjectStartDateOk() (*string, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *Dur) SetProjectStartDate(v string)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *Dur) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### SetProjectStartDateNil

`func (o *Dur) SetProjectStartDateNil(b bool)`

 SetProjectStartDateNil sets the value for ProjectStartDate to be an explicit nil

### UnsetProjectStartDate
`func (o *Dur) UnsetProjectStartDate()`

UnsetProjectStartDate ensures that no value is present for ProjectStartDate, not even an explicit nil
### GetProjectEndDate

`func (o *Dur) GetProjectEndDate() string`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *Dur) GetProjectEndDateOk() (*string, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *Dur) SetProjectEndDate(v string)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *Dur) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### SetProjectEndDateNil

`func (o *Dur) SetProjectEndDateNil(b bool)`

 SetProjectEndDateNil sets the value for ProjectEndDate to be an explicit nil

### UnsetProjectEndDate
`func (o *Dur) UnsetProjectEndDate()`

UnsetProjectEndDate ensures that no value is present for ProjectEndDate, not even an explicit nil
### GetAccessDate

`func (o *Dur) GetAccessDate() string`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *Dur) GetAccessDateOk() (*string, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *Dur) SetAccessDate(v string)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *Dur) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### SetAccessDateNil

`func (o *Dur) SetAccessDateNil(b bool)`

 SetAccessDateNil sets the value for AccessDate to be an explicit nil

### UnsetAccessDate
`func (o *Dur) UnsetAccessDate()`

UnsetAccessDate ensures that no value is present for AccessDate, not even an explicit nil
### GetAccreditedResearcherStatus

`func (o *Dur) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *Dur) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *Dur) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *Dur) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### SetAccreditedResearcherStatusNil

`func (o *Dur) SetAccreditedResearcherStatusNil(b bool)`

 SetAccreditedResearcherStatusNil sets the value for AccreditedResearcherStatus to be an explicit nil

### UnsetAccreditedResearcherStatus
`func (o *Dur) UnsetAccreditedResearcherStatus()`

UnsetAccreditedResearcherStatus ensures that no value is present for AccreditedResearcherStatus, not even an explicit nil
### GetConfidentialDataDescription

`func (o *Dur) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *Dur) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *Dur) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *Dur) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### SetConfidentialDataDescriptionNil

`func (o *Dur) SetConfidentialDataDescriptionNil(b bool)`

 SetConfidentialDataDescriptionNil sets the value for ConfidentialDataDescription to be an explicit nil

### UnsetConfidentialDataDescription
`func (o *Dur) UnsetConfidentialDataDescription()`

UnsetConfidentialDataDescription ensures that no value is present for ConfidentialDataDescription, not even an explicit nil
### GetDatasetLinkageDescription

`func (o *Dur) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *Dur) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *Dur) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *Dur) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### SetDatasetLinkageDescriptionNil

`func (o *Dur) SetDatasetLinkageDescriptionNil(b bool)`

 SetDatasetLinkageDescriptionNil sets the value for DatasetLinkageDescription to be an explicit nil

### UnsetDatasetLinkageDescription
`func (o *Dur) UnsetDatasetLinkageDescription()`

UnsetDatasetLinkageDescription ensures that no value is present for DatasetLinkageDescription, not even an explicit nil
### GetDutyOfConfidentiality

`func (o *Dur) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *Dur) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *Dur) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *Dur) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### SetDutyOfConfidentialityNil

`func (o *Dur) SetDutyOfConfidentialityNil(b bool)`

 SetDutyOfConfidentialityNil sets the value for DutyOfConfidentiality to be an explicit nil

### UnsetDutyOfConfidentiality
`func (o *Dur) UnsetDutyOfConfidentiality()`

UnsetDutyOfConfidentiality ensures that no value is present for DutyOfConfidentiality, not even an explicit nil
### GetLegalBasisForDataArticle6

`func (o *Dur) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *Dur) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *Dur) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *Dur) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### SetLegalBasisForDataArticle6Nil

`func (o *Dur) SetLegalBasisForDataArticle6Nil(b bool)`

 SetLegalBasisForDataArticle6Nil sets the value for LegalBasisForDataArticle6 to be an explicit nil

### UnsetLegalBasisForDataArticle6
`func (o *Dur) UnsetLegalBasisForDataArticle6()`

UnsetLegalBasisForDataArticle6 ensures that no value is present for LegalBasisForDataArticle6, not even an explicit nil
### GetLegalBasisForDataArticle9

`func (o *Dur) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *Dur) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *Dur) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *Dur) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### SetLegalBasisForDataArticle9Nil

`func (o *Dur) SetLegalBasisForDataArticle9Nil(b bool)`

 SetLegalBasisForDataArticle9Nil sets the value for LegalBasisForDataArticle9 to be an explicit nil

### UnsetLegalBasisForDataArticle9
`func (o *Dur) UnsetLegalBasisForDataArticle9()`

UnsetLegalBasisForDataArticle9 ensures that no value is present for LegalBasisForDataArticle9, not even an explicit nil
### GetNationalDataOptout

`func (o *Dur) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *Dur) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *Dur) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *Dur) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### SetNationalDataOptoutNil

`func (o *Dur) SetNationalDataOptoutNil(b bool)`

 SetNationalDataOptoutNil sets the value for NationalDataOptout to be an explicit nil

### UnsetNationalDataOptout
`func (o *Dur) UnsetNationalDataOptout()`

UnsetNationalDataOptout ensures that no value is present for NationalDataOptout, not even an explicit nil
### GetOrganisationId

`func (o *Dur) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *Dur) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *Dur) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *Dur) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### SetOrganisationIdNil

`func (o *Dur) SetOrganisationIdNil(b bool)`

 SetOrganisationIdNil sets the value for OrganisationId to be an explicit nil

### UnsetOrganisationId
`func (o *Dur) UnsetOrganisationId()`

UnsetOrganisationId ensures that no value is present for OrganisationId, not even an explicit nil
### GetPrivacyEnhancements

`func (o *Dur) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *Dur) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *Dur) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *Dur) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### SetPrivacyEnhancementsNil

`func (o *Dur) SetPrivacyEnhancementsNil(b bool)`

 SetPrivacyEnhancementsNil sets the value for PrivacyEnhancements to be an explicit nil

### UnsetPrivacyEnhancements
`func (o *Dur) UnsetPrivacyEnhancements()`

UnsetPrivacyEnhancements ensures that no value is present for PrivacyEnhancements, not even an explicit nil
### GetRequestCategoryType

`func (o *Dur) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *Dur) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *Dur) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *Dur) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### SetRequestCategoryTypeNil

`func (o *Dur) SetRequestCategoryTypeNil(b bool)`

 SetRequestCategoryTypeNil sets the value for RequestCategoryType to be an explicit nil

### UnsetRequestCategoryType
`func (o *Dur) UnsetRequestCategoryType()`

UnsetRequestCategoryType ensures that no value is present for RequestCategoryType, not even an explicit nil
### GetRequestFrequency

`func (o *Dur) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *Dur) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *Dur) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *Dur) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### SetRequestFrequencyNil

`func (o *Dur) SetRequestFrequencyNil(b bool)`

 SetRequestFrequencyNil sets the value for RequestFrequency to be an explicit nil

### UnsetRequestFrequency
`func (o *Dur) UnsetRequestFrequency()`

UnsetRequestFrequency ensures that no value is present for RequestFrequency, not even an explicit nil
### GetAccessType

`func (o *Dur) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *Dur) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *Dur) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *Dur) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### SetAccessTypeNil

`func (o *Dur) SetAccessTypeNil(b bool)`

 SetAccessTypeNil sets the value for AccessType to be an explicit nil

### UnsetAccessType
`func (o *Dur) UnsetAccessType()`

UnsetAccessType ensures that no value is present for AccessType, not even an explicit nil
### GetNonGatewayDatasets

`func (o *Dur) GetNonGatewayDatasets() []string`

GetNonGatewayDatasets returns the NonGatewayDatasets field if non-nil, zero value otherwise.

### GetNonGatewayDatasetsOk

`func (o *Dur) GetNonGatewayDatasetsOk() (*[]string, bool)`

GetNonGatewayDatasetsOk returns a tuple with the NonGatewayDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayDatasets

`func (o *Dur) SetNonGatewayDatasets(v []string)`

SetNonGatewayDatasets sets NonGatewayDatasets field to given value.

### HasNonGatewayDatasets

`func (o *Dur) HasNonGatewayDatasets() bool`

HasNonGatewayDatasets returns a boolean if a field has been set.

### SetNonGatewayDatasetsNil

`func (o *Dur) SetNonGatewayDatasetsNil(b bool)`

 SetNonGatewayDatasetsNil sets the value for NonGatewayDatasets to be an explicit nil

### UnsetNonGatewayDatasets
`func (o *Dur) UnsetNonGatewayDatasets()`

UnsetNonGatewayDatasets ensures that no value is present for NonGatewayDatasets, not even an explicit nil
### GetNonGatewayApplicants

`func (o *Dur) GetNonGatewayApplicants() []string`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *Dur) GetNonGatewayApplicantsOk() (*[]string, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *Dur) SetNonGatewayApplicants(v []string)`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *Dur) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### SetNonGatewayApplicantsNil

`func (o *Dur) SetNonGatewayApplicantsNil(b bool)`

 SetNonGatewayApplicantsNil sets the value for NonGatewayApplicants to be an explicit nil

### UnsetNonGatewayApplicants
`func (o *Dur) UnsetNonGatewayApplicants()`

UnsetNonGatewayApplicants ensures that no value is present for NonGatewayApplicants, not even an explicit nil
### GetFundersAndSponsors

`func (o *Dur) GetFundersAndSponsors() []string`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *Dur) GetFundersAndSponsorsOk() (*[]string, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *Dur) SetFundersAndSponsors(v []string)`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *Dur) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### SetFundersAndSponsorsNil

`func (o *Dur) SetFundersAndSponsorsNil(b bool)`

 SetFundersAndSponsorsNil sets the value for FundersAndSponsors to be an explicit nil

### UnsetFundersAndSponsors
`func (o *Dur) UnsetFundersAndSponsors()`

UnsetFundersAndSponsors ensures that no value is present for FundersAndSponsors, not even an explicit nil
### GetOtherApprovalCommittees

`func (o *Dur) GetOtherApprovalCommittees() []string`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *Dur) GetOtherApprovalCommitteesOk() (*[]string, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *Dur) SetOtherApprovalCommittees(v []string)`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *Dur) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### SetOtherApprovalCommitteesNil

`func (o *Dur) SetOtherApprovalCommitteesNil(b bool)`

 SetOtherApprovalCommitteesNil sets the value for OtherApprovalCommittees to be an explicit nil

### UnsetOtherApprovalCommittees
`func (o *Dur) UnsetOtherApprovalCommittees()`

UnsetOtherApprovalCommittees ensures that no value is present for OtherApprovalCommittees, not even an explicit nil
### GetGatewayOutputsTools

`func (o *Dur) GetGatewayOutputsTools() []string`

GetGatewayOutputsTools returns the GatewayOutputsTools field if non-nil, zero value otherwise.

### GetGatewayOutputsToolsOk

`func (o *Dur) GetGatewayOutputsToolsOk() (*[]string, bool)`

GetGatewayOutputsToolsOk returns a tuple with the GatewayOutputsTools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsTools

`func (o *Dur) SetGatewayOutputsTools(v []string)`

SetGatewayOutputsTools sets GatewayOutputsTools field to given value.

### HasGatewayOutputsTools

`func (o *Dur) HasGatewayOutputsTools() bool`

HasGatewayOutputsTools returns a boolean if a field has been set.

### SetGatewayOutputsToolsNil

`func (o *Dur) SetGatewayOutputsToolsNil(b bool)`

 SetGatewayOutputsToolsNil sets the value for GatewayOutputsTools to be an explicit nil

### UnsetGatewayOutputsTools
`func (o *Dur) UnsetGatewayOutputsTools()`

UnsetGatewayOutputsTools ensures that no value is present for GatewayOutputsTools, not even an explicit nil
### GetGatewayOutputsPapers

`func (o *Dur) GetGatewayOutputsPapers() []string`

GetGatewayOutputsPapers returns the GatewayOutputsPapers field if non-nil, zero value otherwise.

### GetGatewayOutputsPapersOk

`func (o *Dur) GetGatewayOutputsPapersOk() (*[]string, bool)`

GetGatewayOutputsPapersOk returns a tuple with the GatewayOutputsPapers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsPapers

`func (o *Dur) SetGatewayOutputsPapers(v []string)`

SetGatewayOutputsPapers sets GatewayOutputsPapers field to given value.

### HasGatewayOutputsPapers

`func (o *Dur) HasGatewayOutputsPapers() bool`

HasGatewayOutputsPapers returns a boolean if a field has been set.

### SetGatewayOutputsPapersNil

`func (o *Dur) SetGatewayOutputsPapersNil(b bool)`

 SetGatewayOutputsPapersNil sets the value for GatewayOutputsPapers to be an explicit nil

### UnsetGatewayOutputsPapers
`func (o *Dur) UnsetGatewayOutputsPapers()`

UnsetGatewayOutputsPapers ensures that no value is present for GatewayOutputsPapers, not even an explicit nil
### GetNonGatewayOutputs

`func (o *Dur) GetNonGatewayOutputs() []string`

GetNonGatewayOutputs returns the NonGatewayOutputs field if non-nil, zero value otherwise.

### GetNonGatewayOutputsOk

`func (o *Dur) GetNonGatewayOutputsOk() (*[]string, bool)`

GetNonGatewayOutputsOk returns a tuple with the NonGatewayOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayOutputs

`func (o *Dur) SetNonGatewayOutputs(v []string)`

SetNonGatewayOutputs sets NonGatewayOutputs field to given value.

### HasNonGatewayOutputs

`func (o *Dur) HasNonGatewayOutputs() bool`

HasNonGatewayOutputs returns a boolean if a field has been set.

### SetNonGatewayOutputsNil

`func (o *Dur) SetNonGatewayOutputsNil(b bool)`

 SetNonGatewayOutputsNil sets the value for NonGatewayOutputs to be an explicit nil

### UnsetNonGatewayOutputs
`func (o *Dur) UnsetNonGatewayOutputs()`

UnsetNonGatewayOutputs ensures that no value is present for NonGatewayOutputs, not even an explicit nil
### GetEnabled

`func (o *Dur) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Dur) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Dur) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Dur) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLastActivity

`func (o *Dur) GetLastActivity() time.Time`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *Dur) GetLastActivityOk() (*time.Time, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *Dur) SetLastActivity(v time.Time)`

SetLastActivity sets LastActivity field to given value.

### HasLastActivity

`func (o *Dur) HasLastActivity() bool`

HasLastActivity returns a boolean if a field has been set.

### SetLastActivityNil

`func (o *Dur) SetLastActivityNil(b bool)`

 SetLastActivityNil sets the value for LastActivity to be an explicit nil

### UnsetLastActivity
`func (o *Dur) UnsetLastActivity()`

UnsetLastActivity ensures that no value is present for LastActivity, not even an explicit nil
### GetCounter

`func (o *Dur) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *Dur) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *Dur) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *Dur) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### SetCounterNil

`func (o *Dur) SetCounterNil(b bool)`

 SetCounterNil sets the value for Counter to be an explicit nil

### UnsetCounter
`func (o *Dur) UnsetCounter()`

UnsetCounter ensures that no value is present for Counter, not even an explicit nil
### GetUserId

`func (o *Dur) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Dur) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Dur) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Dur) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *Dur) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *Dur) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetTeamId

`func (o *Dur) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Dur) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Dur) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Dur) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### SetTeamIdNil

`func (o *Dur) SetTeamIdNil(b bool)`

 SetTeamIdNil sets the value for TeamId to be an explicit nil

### UnsetTeamId
`func (o *Dur) UnsetTeamId()`

UnsetTeamId ensures that no value is present for TeamId, not even an explicit nil
### GetApplicantId

`func (o *Dur) GetApplicantId() int32`

GetApplicantId returns the ApplicantId field if non-nil, zero value otherwise.

### GetApplicantIdOk

`func (o *Dur) GetApplicantIdOk() (*int32, bool)`

GetApplicantIdOk returns a tuple with the ApplicantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantId

`func (o *Dur) SetApplicantId(v int32)`

SetApplicantId sets ApplicantId field to given value.

### HasApplicantId

`func (o *Dur) HasApplicantId() bool`

HasApplicantId returns a boolean if a field has been set.

### SetApplicantIdNil

`func (o *Dur) SetApplicantIdNil(b bool)`

 SetApplicantIdNil sets the value for ApplicantId to be an explicit nil

### UnsetApplicantId
`func (o *Dur) UnsetApplicantId()`

UnsetApplicantId ensures that no value is present for ApplicantId, not even an explicit nil
### GetStatus

`func (o *Dur) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Dur) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Dur) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Dur) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Dur) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Dur) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Dur) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Dur) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Dur) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Dur) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Dur) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Dur) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


