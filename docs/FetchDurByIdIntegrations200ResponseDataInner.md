# FetchDurByIdIntegrations200ResponseDataInner

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
**Publications** | Pointer to **[]interface{}** |  | [optional] 
**Tools** | Pointer to **[]interface{}** |  | [optional] 
**Keywords** | Pointer to **[]interface{}** |  | [optional] 
**Users** | Pointer to **[]interface{}** |  | [optional] 
**Applications** | Pointer to **[]interface{}** |  | [optional] 
**User** | Pointer to **[]interface{}** |  | [optional] 
**Team** | Pointer to **[]interface{}** |  | [optional] 
**Application** | Pointer to **[]interface{}** |  | [optional] 
**Applicantions** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewFetchDurByIdIntegrations200ResponseDataInner

`func NewFetchDurByIdIntegrations200ResponseDataInner() *FetchDurByIdIntegrations200ResponseDataInner`

NewFetchDurByIdIntegrations200ResponseDataInner instantiates a new FetchDurByIdIntegrations200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchDurByIdIntegrations200ResponseDataInnerWithDefaults

`func NewFetchDurByIdIntegrations200ResponseDataInnerWithDefaults() *FetchDurByIdIntegrations200ResponseDataInner`

NewFetchDurByIdIntegrations200ResponseDataInnerWithDefaults instantiates a new FetchDurByIdIntegrations200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetNonGatewayDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayDatasets() []interface{}`

GetNonGatewayDatasets returns the NonGatewayDatasets field if non-nil, zero value otherwise.

### GetNonGatewayDatasetsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayDatasetsOk() (*[]interface{}, bool)`

GetNonGatewayDatasetsOk returns a tuple with the NonGatewayDatasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetNonGatewayDatasets(v []interface{})`

SetNonGatewayDatasets sets NonGatewayDatasets field to given value.

### HasNonGatewayDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasNonGatewayDatasets() bool`

HasNonGatewayDatasets returns a boolean if a field has been set.

### GetNonGatewayApplicants

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayApplicants() []interface{}`

GetNonGatewayApplicants returns the NonGatewayApplicants field if non-nil, zero value otherwise.

### GetNonGatewayApplicantsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayApplicantsOk() (*[]interface{}, bool)`

GetNonGatewayApplicantsOk returns a tuple with the NonGatewayApplicants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayApplicants

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetNonGatewayApplicants(v []interface{})`

SetNonGatewayApplicants sets NonGatewayApplicants field to given value.

### HasNonGatewayApplicants

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasNonGatewayApplicants() bool`

HasNonGatewayApplicants returns a boolean if a field has been set.

### GetFundersAndSponsors

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetFundersAndSponsors() []interface{}`

GetFundersAndSponsors returns the FundersAndSponsors field if non-nil, zero value otherwise.

### GetFundersAndSponsorsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetFundersAndSponsorsOk() (*[]interface{}, bool)`

GetFundersAndSponsorsOk returns a tuple with the FundersAndSponsors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundersAndSponsors

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetFundersAndSponsors(v []interface{})`

SetFundersAndSponsors sets FundersAndSponsors field to given value.

### HasFundersAndSponsors

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasFundersAndSponsors() bool`

HasFundersAndSponsors returns a boolean if a field has been set.

### GetOtherApprovalCommittees

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOtherApprovalCommittees() []interface{}`

GetOtherApprovalCommittees returns the OtherApprovalCommittees field if non-nil, zero value otherwise.

### GetOtherApprovalCommitteesOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOtherApprovalCommitteesOk() (*[]interface{}, bool)`

GetOtherApprovalCommitteesOk returns a tuple with the OtherApprovalCommittees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherApprovalCommittees

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetOtherApprovalCommittees(v []interface{})`

SetOtherApprovalCommittees sets OtherApprovalCommittees field to given value.

### HasOtherApprovalCommittees

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasOtherApprovalCommittees() bool`

HasOtherApprovalCommittees returns a boolean if a field has been set.

### GetGatewayOutputsTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetGatewayOutputsTools() []interface{}`

GetGatewayOutputsTools returns the GatewayOutputsTools field if non-nil, zero value otherwise.

### GetGatewayOutputsToolsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetGatewayOutputsToolsOk() (*[]interface{}, bool)`

GetGatewayOutputsToolsOk returns a tuple with the GatewayOutputsTools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetGatewayOutputsTools(v []interface{})`

SetGatewayOutputsTools sets GatewayOutputsTools field to given value.

### HasGatewayOutputsTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasGatewayOutputsTools() bool`

HasGatewayOutputsTools returns a boolean if a field has been set.

### GetGatewayOutputsPapers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetGatewayOutputsPapers() []interface{}`

GetGatewayOutputsPapers returns the GatewayOutputsPapers field if non-nil, zero value otherwise.

### GetGatewayOutputsPapersOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetGatewayOutputsPapersOk() (*[]interface{}, bool)`

GetGatewayOutputsPapersOk returns a tuple with the GatewayOutputsPapers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOutputsPapers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetGatewayOutputsPapers(v []interface{})`

SetGatewayOutputsPapers sets GatewayOutputsPapers field to given value.

### HasGatewayOutputsPapers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasGatewayOutputsPapers() bool`

HasGatewayOutputsPapers returns a boolean if a field has been set.

### GetNonGatewayOutputs

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayOutputs() []interface{}`

GetNonGatewayOutputs returns the NonGatewayOutputs field if non-nil, zero value otherwise.

### GetNonGatewayOutputsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNonGatewayOutputsOk() (*[]interface{}, bool)`

GetNonGatewayOutputsOk returns a tuple with the NonGatewayOutputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonGatewayOutputs

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetNonGatewayOutputs(v []interface{})`

SetNonGatewayOutputs sets NonGatewayOutputs field to given value.

### HasNonGatewayOutputs

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasNonGatewayOutputs() bool`

HasNonGatewayOutputs returns a boolean if a field has been set.

### GetProjectTitle

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectTitle() string`

GetProjectTitle returns the ProjectTitle field if non-nil, zero value otherwise.

### GetProjectTitleOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectTitleOk() (*string, bool)`

GetProjectTitleOk returns a tuple with the ProjectTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectTitle

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetProjectTitle(v string)`

SetProjectTitle sets ProjectTitle field to given value.

### HasProjectTitle

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasProjectTitle() bool`

HasProjectTitle returns a boolean if a field has been set.

### GetProjectIdText

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectIdText() string`

GetProjectIdText returns the ProjectIdText field if non-nil, zero value otherwise.

### GetProjectIdTextOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectIdTextOk() (*string, bool)`

GetProjectIdTextOk returns a tuple with the ProjectIdText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIdText

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetProjectIdText(v string)`

SetProjectIdText sets ProjectIdText field to given value.

### HasProjectIdText

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasProjectIdText() bool`

HasProjectIdText returns a boolean if a field has been set.

### GetOrganisationName

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationName() string`

GetOrganisationName returns the OrganisationName field if non-nil, zero value otherwise.

### GetOrganisationNameOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationNameOk() (*string, bool)`

GetOrganisationNameOk returns a tuple with the OrganisationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationName

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetOrganisationName(v string)`

SetOrganisationName sets OrganisationName field to given value.

### HasOrganisationName

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasOrganisationName() bool`

HasOrganisationName returns a boolean if a field has been set.

### GetOrganisationSector

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationSector() string`

GetOrganisationSector returns the OrganisationSector field if non-nil, zero value otherwise.

### GetOrganisationSectorOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationSectorOk() (*string, bool)`

GetOrganisationSectorOk returns a tuple with the OrganisationSector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationSector

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetOrganisationSector(v string)`

SetOrganisationSector sets OrganisationSector field to given value.

### HasOrganisationSector

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasOrganisationSector() bool`

HasOrganisationSector returns a boolean if a field has been set.

### GetLaySummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLaySummary() string`

GetLaySummary returns the LaySummary field if non-nil, zero value otherwise.

### GetLaySummaryOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLaySummaryOk() (*string, bool)`

GetLaySummaryOk returns a tuple with the LaySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaySummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetLaySummary(v string)`

SetLaySummary sets LaySummary field to given value.

### HasLaySummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasLaySummary() bool`

HasLaySummary returns a boolean if a field has been set.

### GetTechnicalSummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetTechnicalSummary() string`

GetTechnicalSummary returns the TechnicalSummary field if non-nil, zero value otherwise.

### GetTechnicalSummaryOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetTechnicalSummaryOk() (*string, bool)`

GetTechnicalSummaryOk returns a tuple with the TechnicalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechnicalSummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetTechnicalSummary(v string)`

SetTechnicalSummary sets TechnicalSummary field to given value.

### HasTechnicalSummary

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasTechnicalSummary() bool`

HasTechnicalSummary returns a boolean if a field has been set.

### GetLatestApprovalDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLatestApprovalDate() time.Time`

GetLatestApprovalDate returns the LatestApprovalDate field if non-nil, zero value otherwise.

### GetLatestApprovalDateOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLatestApprovalDateOk() (*time.Time, bool)`

GetLatestApprovalDateOk returns a tuple with the LatestApprovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestApprovalDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetLatestApprovalDate(v time.Time)`

SetLatestApprovalDate sets LatestApprovalDate field to given value.

### HasLatestApprovalDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasLatestApprovalDate() bool`

HasLatestApprovalDate returns a boolean if a field has been set.

### GetManualUpload

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetManualUpload() bool`

GetManualUpload returns the ManualUpload field if non-nil, zero value otherwise.

### GetManualUploadOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetManualUploadOk() (*bool, bool)`

GetManualUploadOk returns a tuple with the ManualUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualUpload

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetManualUpload(v bool)`

SetManualUpload sets ManualUpload field to given value.

### HasManualUpload

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasManualUpload() bool`

HasManualUpload returns a boolean if a field has been set.

### GetRejectionReason

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### GetSublicenceArrangements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetSublicenceArrangements() string`

GetSublicenceArrangements returns the SublicenceArrangements field if non-nil, zero value otherwise.

### GetSublicenceArrangementsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetSublicenceArrangementsOk() (*string, bool)`

GetSublicenceArrangementsOk returns a tuple with the SublicenceArrangements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSublicenceArrangements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetSublicenceArrangements(v string)`

SetSublicenceArrangements sets SublicenceArrangements field to given value.

### HasSublicenceArrangements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasSublicenceArrangements() bool`

HasSublicenceArrangements returns a boolean if a field has been set.

### GetPublicBenefitStatement

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPublicBenefitStatement() string`

GetPublicBenefitStatement returns the PublicBenefitStatement field if non-nil, zero value otherwise.

### GetPublicBenefitStatementOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPublicBenefitStatementOk() (*string, bool)`

GetPublicBenefitStatementOk returns a tuple with the PublicBenefitStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBenefitStatement

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetPublicBenefitStatement(v string)`

SetPublicBenefitStatement sets PublicBenefitStatement field to given value.

### HasPublicBenefitStatement

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasPublicBenefitStatement() bool`

HasPublicBenefitStatement returns a boolean if a field has been set.

### GetDataSensitivityLevel

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDataSensitivityLevel() string`

GetDataSensitivityLevel returns the DataSensitivityLevel field if non-nil, zero value otherwise.

### GetDataSensitivityLevelOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDataSensitivityLevelOk() (*string, bool)`

GetDataSensitivityLevelOk returns a tuple with the DataSensitivityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSensitivityLevel

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetDataSensitivityLevel(v string)`

SetDataSensitivityLevel sets DataSensitivityLevel field to given value.

### HasDataSensitivityLevel

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasDataSensitivityLevel() bool`

HasDataSensitivityLevel returns a boolean if a field has been set.

### GetProjectStartDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectStartDate() time.Time`

GetProjectStartDate returns the ProjectStartDate field if non-nil, zero value otherwise.

### GetProjectStartDateOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectStartDateOk() (*time.Time, bool)`

GetProjectStartDateOk returns a tuple with the ProjectStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStartDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetProjectStartDate(v time.Time)`

SetProjectStartDate sets ProjectStartDate field to given value.

### HasProjectStartDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasProjectStartDate() bool`

HasProjectStartDate returns a boolean if a field has been set.

### GetProjectEndDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectEndDate() time.Time`

GetProjectEndDate returns the ProjectEndDate field if non-nil, zero value otherwise.

### GetProjectEndDateOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetProjectEndDateOk() (*time.Time, bool)`

GetProjectEndDateOk returns a tuple with the ProjectEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectEndDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetProjectEndDate(v time.Time)`

SetProjectEndDate sets ProjectEndDate field to given value.

### HasProjectEndDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasProjectEndDate() bool`

HasProjectEndDate returns a boolean if a field has been set.

### GetAccessDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccessDate() time.Time`

GetAccessDate returns the AccessDate field if non-nil, zero value otherwise.

### GetAccessDateOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccessDateOk() (*time.Time, bool)`

GetAccessDateOk returns a tuple with the AccessDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetAccessDate(v time.Time)`

SetAccessDate sets AccessDate field to given value.

### HasAccessDate

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasAccessDate() bool`

HasAccessDate returns a boolean if a field has been set.

### GetAccreditedResearcherStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccreditedResearcherStatus() string`

GetAccreditedResearcherStatus returns the AccreditedResearcherStatus field if non-nil, zero value otherwise.

### GetAccreditedResearcherStatusOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccreditedResearcherStatusOk() (*string, bool)`

GetAccreditedResearcherStatusOk returns a tuple with the AccreditedResearcherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccreditedResearcherStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetAccreditedResearcherStatus(v string)`

SetAccreditedResearcherStatus sets AccreditedResearcherStatus field to given value.

### HasAccreditedResearcherStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasAccreditedResearcherStatus() bool`

HasAccreditedResearcherStatus returns a boolean if a field has been set.

### GetConfidentialDataDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetConfidentialDataDescription() string`

GetConfidentialDataDescription returns the ConfidentialDataDescription field if non-nil, zero value otherwise.

### GetConfidentialDataDescriptionOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetConfidentialDataDescriptionOk() (*string, bool)`

GetConfidentialDataDescriptionOk returns a tuple with the ConfidentialDataDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentialDataDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetConfidentialDataDescription(v string)`

SetConfidentialDataDescription sets ConfidentialDataDescription field to given value.

### HasConfidentialDataDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasConfidentialDataDescription() bool`

HasConfidentialDataDescription returns a boolean if a field has been set.

### GetDatasetLinkageDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDatasetLinkageDescription() string`

GetDatasetLinkageDescription returns the DatasetLinkageDescription field if non-nil, zero value otherwise.

### GetDatasetLinkageDescriptionOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDatasetLinkageDescriptionOk() (*string, bool)`

GetDatasetLinkageDescriptionOk returns a tuple with the DatasetLinkageDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasetLinkageDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetDatasetLinkageDescription(v string)`

SetDatasetLinkageDescription sets DatasetLinkageDescription field to given value.

### HasDatasetLinkageDescription

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasDatasetLinkageDescription() bool`

HasDatasetLinkageDescription returns a boolean if a field has been set.

### GetDutyOfConfidentiality

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDutyOfConfidentiality() string`

GetDutyOfConfidentiality returns the DutyOfConfidentiality field if non-nil, zero value otherwise.

### GetDutyOfConfidentialityOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDutyOfConfidentialityOk() (*string, bool)`

GetDutyOfConfidentialityOk returns a tuple with the DutyOfConfidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDutyOfConfidentiality

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetDutyOfConfidentiality(v string)`

SetDutyOfConfidentiality sets DutyOfConfidentiality field to given value.

### HasDutyOfConfidentiality

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasDutyOfConfidentiality() bool`

HasDutyOfConfidentiality returns a boolean if a field has been set.

### GetLegalBasisForDataArticle6

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLegalBasisForDataArticle6() string`

GetLegalBasisForDataArticle6 returns the LegalBasisForDataArticle6 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle6Ok

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLegalBasisForDataArticle6Ok() (*string, bool)`

GetLegalBasisForDataArticle6Ok returns a tuple with the LegalBasisForDataArticle6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle6

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetLegalBasisForDataArticle6(v string)`

SetLegalBasisForDataArticle6 sets LegalBasisForDataArticle6 field to given value.

### HasLegalBasisForDataArticle6

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasLegalBasisForDataArticle6() bool`

HasLegalBasisForDataArticle6 returns a boolean if a field has been set.

### GetLegalBasisForDataArticle9

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLegalBasisForDataArticle9() string`

GetLegalBasisForDataArticle9 returns the LegalBasisForDataArticle9 field if non-nil, zero value otherwise.

### GetLegalBasisForDataArticle9Ok

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLegalBasisForDataArticle9Ok() (*string, bool)`

GetLegalBasisForDataArticle9Ok returns a tuple with the LegalBasisForDataArticle9 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalBasisForDataArticle9

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetLegalBasisForDataArticle9(v string)`

SetLegalBasisForDataArticle9 sets LegalBasisForDataArticle9 field to given value.

### HasLegalBasisForDataArticle9

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasLegalBasisForDataArticle9() bool`

HasLegalBasisForDataArticle9 returns a boolean if a field has been set.

### GetNationalDataOptout

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNationalDataOptout() string`

GetNationalDataOptout returns the NationalDataOptout field if non-nil, zero value otherwise.

### GetNationalDataOptoutOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetNationalDataOptoutOk() (*string, bool)`

GetNationalDataOptoutOk returns a tuple with the NationalDataOptout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNationalDataOptout

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetNationalDataOptout(v string)`

SetNationalDataOptout sets NationalDataOptout field to given value.

### HasNationalDataOptout

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasNationalDataOptout() bool`

HasNationalDataOptout returns a boolean if a field has been set.

### GetOrganisationId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationId() string`

GetOrganisationId returns the OrganisationId field if non-nil, zero value otherwise.

### GetOrganisationIdOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetOrganisationIdOk() (*string, bool)`

GetOrganisationIdOk returns a tuple with the OrganisationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisationId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetOrganisationId(v string)`

SetOrganisationId sets OrganisationId field to given value.

### HasOrganisationId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasOrganisationId() bool`

HasOrganisationId returns a boolean if a field has been set.

### GetPrivacyEnhancements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPrivacyEnhancements() string`

GetPrivacyEnhancements returns the PrivacyEnhancements field if non-nil, zero value otherwise.

### GetPrivacyEnhancementsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPrivacyEnhancementsOk() (*string, bool)`

GetPrivacyEnhancementsOk returns a tuple with the PrivacyEnhancements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyEnhancements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetPrivacyEnhancements(v string)`

SetPrivacyEnhancements sets PrivacyEnhancements field to given value.

### HasPrivacyEnhancements

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasPrivacyEnhancements() bool`

HasPrivacyEnhancements returns a boolean if a field has been set.

### GetRequestCategoryType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRequestCategoryType() string`

GetRequestCategoryType returns the RequestCategoryType field if non-nil, zero value otherwise.

### GetRequestCategoryTypeOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRequestCategoryTypeOk() (*string, bool)`

GetRequestCategoryTypeOk returns a tuple with the RequestCategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCategoryType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetRequestCategoryType(v string)`

SetRequestCategoryType sets RequestCategoryType field to given value.

### HasRequestCategoryType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasRequestCategoryType() bool`

HasRequestCategoryType returns a boolean if a field has been set.

### GetRequestFrequency

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRequestFrequency() string`

GetRequestFrequency returns the RequestFrequency field if non-nil, zero value otherwise.

### GetRequestFrequencyOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetRequestFrequencyOk() (*string, bool)`

GetRequestFrequencyOk returns a tuple with the RequestFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestFrequency

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetRequestFrequency(v string)`

SetRequestFrequency sets RequestFrequency field to given value.

### HasRequestFrequency

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasRequestFrequency() bool`

HasRequestFrequency returns a boolean if a field has been set.

### GetAccessType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccessType() string`

GetAccessType returns the AccessType field if non-nil, zero value otherwise.

### GetAccessTypeOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetAccessTypeOk() (*string, bool)`

GetAccessTypeOk returns a tuple with the AccessType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetAccessType(v string)`

SetAccessType sets AccessType field to given value.

### HasAccessType

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasAccessType() bool`

HasAccessType returns a boolean if a field has been set.

### GetMongoObjectDarId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoObjectDarId() string`

GetMongoObjectDarId returns the MongoObjectDarId field if non-nil, zero value otherwise.

### GetMongoObjectDarIdOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoObjectDarIdOk() (*string, bool)`

GetMongoObjectDarIdOk returns a tuple with the MongoObjectDarId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectDarId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetMongoObjectDarId(v string)`

SetMongoObjectDarId sets MongoObjectDarId field to given value.

### HasMongoObjectDarId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasMongoObjectDarId() bool`

HasMongoObjectDarId returns a boolean if a field has been set.

### GetEnabled

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLastActivity

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLastActivity() time.Time`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetLastActivityOk() (*time.Time, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetLastActivity(v time.Time)`

SetLastActivity sets LastActivity field to given value.

### HasLastActivity

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasLastActivity() bool`

HasLastActivity returns a boolean if a field has been set.

### GetCounter

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetCounter() int32`

GetCounter returns the Counter field if non-nil, zero value otherwise.

### GetCounterOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetCounterOk() (*int32, bool)`

GetCounterOk returns a tuple with the Counter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounter

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetCounter(v int32)`

SetCounter sets Counter field to given value.

### HasCounter

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasCounter() bool`

HasCounter returns a boolean if a field has been set.

### GetMongoObjectId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoObjectId() string`

GetMongoObjectId returns the MongoObjectId field if non-nil, zero value otherwise.

### GetMongoObjectIdOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoObjectIdOk() (*string, bool)`

GetMongoObjectIdOk returns a tuple with the MongoObjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoObjectId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetMongoObjectId(v string)`

SetMongoObjectId sets MongoObjectId field to given value.

### HasMongoObjectId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasMongoObjectId() bool`

HasMongoObjectId returns a boolean if a field has been set.

### GetMongoId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoId() string`

GetMongoId returns the MongoId field if non-nil, zero value otherwise.

### GetMongoIdOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetMongoIdOk() (*string, bool)`

GetMongoIdOk returns a tuple with the MongoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetMongoId(v string)`

SetMongoId sets MongoId field to given value.

### HasMongoId

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasMongoId() bool`

HasMongoId returns a boolean if a field has been set.

### GetDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDatasets() []interface{}`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetDatasetsOk() (*[]interface{}, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetDatasets(v []interface{})`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetPublications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPublications() []interface{}`

GetPublications returns the Publications field if non-nil, zero value otherwise.

### GetPublicationsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetPublicationsOk() (*[]interface{}, bool)`

GetPublicationsOk returns a tuple with the Publications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetPublications(v []interface{})`

SetPublications sets Publications field to given value.

### HasPublications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasPublications() bool`

HasPublications returns a boolean if a field has been set.

### GetTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetTools() []interface{}`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetToolsOk() (*[]interface{}, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetTools(v []interface{})`

SetTools sets Tools field to given value.

### HasTools

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasTools() bool`

HasTools returns a boolean if a field has been set.

### GetKeywords

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetKeywords() []interface{}`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetKeywordsOk() (*[]interface{}, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetKeywords(v []interface{})`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetUsers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUsers() []interface{}`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUsersOk() (*[]interface{}, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetUsers(v []interface{})`

SetUsers sets Users field to given value.

### HasUsers

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### GetApplications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplications() []interface{}`

GetApplications returns the Applications field if non-nil, zero value otherwise.

### GetApplicationsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplicationsOk() (*[]interface{}, bool)`

GetApplicationsOk returns a tuple with the Applications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetApplications(v []interface{})`

SetApplications sets Applications field to given value.

### HasApplications

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasApplications() bool`

HasApplications returns a boolean if a field has been set.

### GetUser

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUser() []interface{}`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetUserOk() (*[]interface{}, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetUser(v []interface{})`

SetUser sets User field to given value.

### HasUser

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetTeam

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetTeam() []interface{}`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetTeamOk() (*[]interface{}, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetTeam(v []interface{})`

SetTeam sets Team field to given value.

### HasTeam

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### GetApplication

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplication() []interface{}`

GetApplication returns the Application field if non-nil, zero value otherwise.

### GetApplicationOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplicationOk() (*[]interface{}, bool)`

GetApplicationOk returns a tuple with the Application field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplication

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetApplication(v []interface{})`

SetApplication sets Application field to given value.

### HasApplication

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasApplication() bool`

HasApplication returns a boolean if a field has been set.

### GetApplicantions

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplicantions() string`

GetApplicantions returns the Applicantions field if non-nil, zero value otherwise.

### GetApplicantionsOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetApplicantionsOk() (*string, bool)`

GetApplicantionsOk returns a tuple with the Applicantions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicantions

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetApplicantions(v string)`

SetApplicantions sets Applicantions field to given value.

### HasApplicantions

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasApplicantions() bool`

HasApplicantions returns a boolean if a field has been set.

### GetStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FetchDurByIdIntegrations200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *FetchDurByIdIntegrations200ResponseDataInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


