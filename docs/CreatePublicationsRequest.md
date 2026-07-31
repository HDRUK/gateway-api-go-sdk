# CreatePublicationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PaperTitle** | Pointer to **string** |  | [optional] 
**Authors** | Pointer to **string** |  | [optional] 
**YearOfPublication** | Pointer to **string** |  | [optional] 
**PaperDoi** | Pointer to **string** |  | [optional] 
**PublicationType** | Pointer to **string** |  | [optional] 
**JournalName** | Pointer to **string** |  | [optional] 
**Abstract** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**MongoId** | Pointer to **string** |  | [optional] 
**Datasets** | Pointer to [**[]CreatePublicationsRequestDatasetsInner**](CreatePublicationsRequestDatasetsInner.md) |  | [optional] 
**Tools** | Pointer to [**[]CreatePublicationsRequestToolsInner**](CreatePublicationsRequestToolsInner.md) |  | [optional] 

## Methods

### NewCreatePublicationsRequest

`func NewCreatePublicationsRequest() *CreatePublicationsRequest`

NewCreatePublicationsRequest instantiates a new CreatePublicationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePublicationsRequestWithDefaults

`func NewCreatePublicationsRequestWithDefaults() *CreatePublicationsRequest`

NewCreatePublicationsRequestWithDefaults instantiates a new CreatePublicationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPaperTitle

`func (o *CreatePublicationsRequest) GetPaperTitle() string`

GetPaperTitle returns the PaperTitle field if non-nil, zero value otherwise.

### GetPaperTitleOk

`func (o *CreatePublicationsRequest) GetPaperTitleOk() (*string, bool)`

GetPaperTitleOk returns a tuple with the PaperTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaperTitle

`func (o *CreatePublicationsRequest) SetPaperTitle(v string)`

SetPaperTitle sets PaperTitle field to given value.

### HasPaperTitle

`func (o *CreatePublicationsRequest) HasPaperTitle() bool`

HasPaperTitle returns a boolean if a field has been set.

### GetAuthors

`func (o *CreatePublicationsRequest) GetAuthors() string`

GetAuthors returns the Authors field if non-nil, zero value otherwise.

### GetAuthorsOk

`func (o *CreatePublicationsRequest) GetAuthorsOk() (*string, bool)`

GetAuthorsOk returns a tuple with the Authors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthors

`func (o *CreatePublicationsRequest) SetAuthors(v string)`

SetAuthors sets Authors field to given value.

### HasAuthors

`func (o *CreatePublicationsRequest) HasAuthors() bool`

HasAuthors returns a boolean if a field has been set.

### GetYearOfPublication

`func (o *CreatePublicationsRequest) GetYearOfPublication() string`

GetYearOfPublication returns the YearOfPublication field if non-nil, zero value otherwise.

### GetYearOfPublicationOk

`func (o *CreatePublicationsRequest) GetYearOfPublicationOk() (*string, bool)`

GetYearOfPublicationOk returns a tuple with the YearOfPublication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearOfPublication

`func (o *CreatePublicationsRequest) SetYearOfPublication(v string)`

SetYearOfPublication sets YearOfPublication field to given value.

### HasYearOfPublication

`func (o *CreatePublicationsRequest) HasYearOfPublication() bool`

HasYearOfPublication returns a boolean if a field has been set.

### GetPaperDoi

`func (o *CreatePublicationsRequest) GetPaperDoi() string`

GetPaperDoi returns the PaperDoi field if non-nil, zero value otherwise.

### GetPaperDoiOk

`func (o *CreatePublicationsRequest) GetPaperDoiOk() (*string, bool)`

GetPaperDoiOk returns a tuple with the PaperDoi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaperDoi

`func (o *CreatePublicationsRequest) SetPaperDoi(v string)`

SetPaperDoi sets PaperDoi field to given value.

### HasPaperDoi

`func (o *CreatePublicationsRequest) HasPaperDoi() bool`

HasPaperDoi returns a boolean if a field has been set.

### GetPublicationType

`func (o *CreatePublicationsRequest) GetPublicationType() string`

GetPublicationType returns the PublicationType field if non-nil, zero value otherwise.

### GetPublicationTypeOk

`func (o *CreatePublicationsRequest) GetPublicationTypeOk() (*string, bool)`

GetPublicationTypeOk returns a tuple with the PublicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicationType

`func (o *CreatePublicationsRequest) SetPublicationType(v string)`

SetPublicationType sets PublicationType field to given value.

### HasPublicationType

`func (o *CreatePublicationsRequest) HasPublicationType() bool`

HasPublicationType returns a boolean if a field has been set.

### GetJournalName

`func (o *CreatePublicationsRequest) GetJournalName() string`

GetJournalName returns the JournalName field if non-nil, zero value otherwise.

### GetJournalNameOk

`func (o *CreatePublicationsRequest) GetJournalNameOk() (*string, bool)`

GetJournalNameOk returns a tuple with the JournalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalName

`func (o *CreatePublicationsRequest) SetJournalName(v string)`

SetJournalName sets JournalName field to given value.

### HasJournalName

`func (o *CreatePublicationsRequest) HasJournalName() bool`

HasJournalName returns a boolean if a field has been set.

### GetAbstract

`func (o *CreatePublicationsRequest) GetAbstract() string`

GetAbstract returns the Abstract field if non-nil, zero value otherwise.

### GetAbstractOk

`func (o *CreatePublicationsRequest) GetAbstractOk() (*string, bool)`

GetAbstractOk returns a tuple with the Abstract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbstract

`func (o *CreatePublicationsRequest) SetAbstract(v string)`

SetAbstract sets Abstract field to given value.

### HasAbstract

`func (o *CreatePublicationsRequest) HasAbstract() bool`

HasAbstract returns a boolean if a field has been set.

### GetUrl

`func (o *CreatePublicationsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreatePublicationsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreatePublicationsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreatePublicationsRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetMongoId

`func (o *CreatePublicationsRequest) GetMongoId() string`

GetMongoId returns the MongoId field if non-nil, zero value otherwise.

### GetMongoIdOk

`func (o *CreatePublicationsRequest) GetMongoIdOk() (*string, bool)`

GetMongoIdOk returns a tuple with the MongoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMongoId

`func (o *CreatePublicationsRequest) SetMongoId(v string)`

SetMongoId sets MongoId field to given value.

### HasMongoId

`func (o *CreatePublicationsRequest) HasMongoId() bool`

HasMongoId returns a boolean if a field has been set.

### GetDatasets

`func (o *CreatePublicationsRequest) GetDatasets() []CreatePublicationsRequestDatasetsInner`

GetDatasets returns the Datasets field if non-nil, zero value otherwise.

### GetDatasetsOk

`func (o *CreatePublicationsRequest) GetDatasetsOk() (*[]CreatePublicationsRequestDatasetsInner, bool)`

GetDatasetsOk returns a tuple with the Datasets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatasets

`func (o *CreatePublicationsRequest) SetDatasets(v []CreatePublicationsRequestDatasetsInner)`

SetDatasets sets Datasets field to given value.

### HasDatasets

`func (o *CreatePublicationsRequest) HasDatasets() bool`

HasDatasets returns a boolean if a field has been set.

### GetTools

`func (o *CreatePublicationsRequest) GetTools() []CreatePublicationsRequestToolsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *CreatePublicationsRequest) GetToolsOk() (*[]CreatePublicationsRequestToolsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *CreatePublicationsRequest) SetTools(v []CreatePublicationsRequestToolsInner)`

SetTools sets Tools field to given value.

### HasTools

`func (o *CreatePublicationsRequest) HasTools() bool`

HasTools returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


