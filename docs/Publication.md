# Publication

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**PaperTitle** | Pointer to **string** |  | [optional] 
**Authors** | Pointer to **NullableString** |  | [optional] 
**YearOfPublication** | Pointer to **NullableInt32** |  | [optional] 
**PaperDoi** | Pointer to **NullableString** |  | [optional] 
**PublicationType** | Pointer to **NullableString** |  | [optional] 
**JournalName** | Pointer to **NullableString** |  | [optional] 
**Abstract** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**OwnerId** | Pointer to **NullableInt32** |  | [optional] 
**TeamId** | Pointer to **NullableInt32** |  | [optional] 
**FirstPublicationDate** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewPublication

`func NewPublication() *Publication`

NewPublication instantiates a new Publication object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicationWithDefaults

`func NewPublicationWithDefaults() *Publication`

NewPublicationWithDefaults instantiates a new Publication object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Publication) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Publication) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Publication) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Publication) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPaperTitle

`func (o *Publication) GetPaperTitle() string`

GetPaperTitle returns the PaperTitle field if non-nil, zero value otherwise.

### GetPaperTitleOk

`func (o *Publication) GetPaperTitleOk() (*string, bool)`

GetPaperTitleOk returns a tuple with the PaperTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaperTitle

`func (o *Publication) SetPaperTitle(v string)`

SetPaperTitle sets PaperTitle field to given value.

### HasPaperTitle

`func (o *Publication) HasPaperTitle() bool`

HasPaperTitle returns a boolean if a field has been set.

### GetAuthors

`func (o *Publication) GetAuthors() string`

GetAuthors returns the Authors field if non-nil, zero value otherwise.

### GetAuthorsOk

`func (o *Publication) GetAuthorsOk() (*string, bool)`

GetAuthorsOk returns a tuple with the Authors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthors

`func (o *Publication) SetAuthors(v string)`

SetAuthors sets Authors field to given value.

### HasAuthors

`func (o *Publication) HasAuthors() bool`

HasAuthors returns a boolean if a field has been set.

### SetAuthorsNil

`func (o *Publication) SetAuthorsNil(b bool)`

 SetAuthorsNil sets the value for Authors to be an explicit nil

### UnsetAuthors
`func (o *Publication) UnsetAuthors()`

UnsetAuthors ensures that no value is present for Authors, not even an explicit nil
### GetYearOfPublication

`func (o *Publication) GetYearOfPublication() int32`

GetYearOfPublication returns the YearOfPublication field if non-nil, zero value otherwise.

### GetYearOfPublicationOk

`func (o *Publication) GetYearOfPublicationOk() (*int32, bool)`

GetYearOfPublicationOk returns a tuple with the YearOfPublication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearOfPublication

`func (o *Publication) SetYearOfPublication(v int32)`

SetYearOfPublication sets YearOfPublication field to given value.

### HasYearOfPublication

`func (o *Publication) HasYearOfPublication() bool`

HasYearOfPublication returns a boolean if a field has been set.

### SetYearOfPublicationNil

`func (o *Publication) SetYearOfPublicationNil(b bool)`

 SetYearOfPublicationNil sets the value for YearOfPublication to be an explicit nil

### UnsetYearOfPublication
`func (o *Publication) UnsetYearOfPublication()`

UnsetYearOfPublication ensures that no value is present for YearOfPublication, not even an explicit nil
### GetPaperDoi

`func (o *Publication) GetPaperDoi() string`

GetPaperDoi returns the PaperDoi field if non-nil, zero value otherwise.

### GetPaperDoiOk

`func (o *Publication) GetPaperDoiOk() (*string, bool)`

GetPaperDoiOk returns a tuple with the PaperDoi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaperDoi

`func (o *Publication) SetPaperDoi(v string)`

SetPaperDoi sets PaperDoi field to given value.

### HasPaperDoi

`func (o *Publication) HasPaperDoi() bool`

HasPaperDoi returns a boolean if a field has been set.

### SetPaperDoiNil

`func (o *Publication) SetPaperDoiNil(b bool)`

 SetPaperDoiNil sets the value for PaperDoi to be an explicit nil

### UnsetPaperDoi
`func (o *Publication) UnsetPaperDoi()`

UnsetPaperDoi ensures that no value is present for PaperDoi, not even an explicit nil
### GetPublicationType

`func (o *Publication) GetPublicationType() string`

GetPublicationType returns the PublicationType field if non-nil, zero value otherwise.

### GetPublicationTypeOk

`func (o *Publication) GetPublicationTypeOk() (*string, bool)`

GetPublicationTypeOk returns a tuple with the PublicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicationType

`func (o *Publication) SetPublicationType(v string)`

SetPublicationType sets PublicationType field to given value.

### HasPublicationType

`func (o *Publication) HasPublicationType() bool`

HasPublicationType returns a boolean if a field has been set.

### SetPublicationTypeNil

`func (o *Publication) SetPublicationTypeNil(b bool)`

 SetPublicationTypeNil sets the value for PublicationType to be an explicit nil

### UnsetPublicationType
`func (o *Publication) UnsetPublicationType()`

UnsetPublicationType ensures that no value is present for PublicationType, not even an explicit nil
### GetJournalName

`func (o *Publication) GetJournalName() string`

GetJournalName returns the JournalName field if non-nil, zero value otherwise.

### GetJournalNameOk

`func (o *Publication) GetJournalNameOk() (*string, bool)`

GetJournalNameOk returns a tuple with the JournalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalName

`func (o *Publication) SetJournalName(v string)`

SetJournalName sets JournalName field to given value.

### HasJournalName

`func (o *Publication) HasJournalName() bool`

HasJournalName returns a boolean if a field has been set.

### SetJournalNameNil

`func (o *Publication) SetJournalNameNil(b bool)`

 SetJournalNameNil sets the value for JournalName to be an explicit nil

### UnsetJournalName
`func (o *Publication) UnsetJournalName()`

UnsetJournalName ensures that no value is present for JournalName, not even an explicit nil
### GetAbstract

`func (o *Publication) GetAbstract() string`

GetAbstract returns the Abstract field if non-nil, zero value otherwise.

### GetAbstractOk

`func (o *Publication) GetAbstractOk() (*string, bool)`

GetAbstractOk returns a tuple with the Abstract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbstract

`func (o *Publication) SetAbstract(v string)`

SetAbstract sets Abstract field to given value.

### HasAbstract

`func (o *Publication) HasAbstract() bool`

HasAbstract returns a boolean if a field has been set.

### SetAbstractNil

`func (o *Publication) SetAbstractNil(b bool)`

 SetAbstractNil sets the value for Abstract to be an explicit nil

### UnsetAbstract
`func (o *Publication) UnsetAbstract()`

UnsetAbstract ensures that no value is present for Abstract, not even an explicit nil
### GetUrl

`func (o *Publication) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Publication) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Publication) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *Publication) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *Publication) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *Publication) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetOwnerId

`func (o *Publication) GetOwnerId() int32`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *Publication) GetOwnerIdOk() (*int32, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *Publication) SetOwnerId(v int32)`

SetOwnerId sets OwnerId field to given value.

### HasOwnerId

`func (o *Publication) HasOwnerId() bool`

HasOwnerId returns a boolean if a field has been set.

### SetOwnerIdNil

`func (o *Publication) SetOwnerIdNil(b bool)`

 SetOwnerIdNil sets the value for OwnerId to be an explicit nil

### UnsetOwnerId
`func (o *Publication) UnsetOwnerId()`

UnsetOwnerId ensures that no value is present for OwnerId, not even an explicit nil
### GetTeamId

`func (o *Publication) GetTeamId() int32`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *Publication) GetTeamIdOk() (*int32, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *Publication) SetTeamId(v int32)`

SetTeamId sets TeamId field to given value.

### HasTeamId

`func (o *Publication) HasTeamId() bool`

HasTeamId returns a boolean if a field has been set.

### SetTeamIdNil

`func (o *Publication) SetTeamIdNil(b bool)`

 SetTeamIdNil sets the value for TeamId to be an explicit nil

### UnsetTeamId
`func (o *Publication) UnsetTeamId()`

UnsetTeamId ensures that no value is present for TeamId, not even an explicit nil
### GetFirstPublicationDate

`func (o *Publication) GetFirstPublicationDate() string`

GetFirstPublicationDate returns the FirstPublicationDate field if non-nil, zero value otherwise.

### GetFirstPublicationDateOk

`func (o *Publication) GetFirstPublicationDateOk() (*string, bool)`

GetFirstPublicationDateOk returns a tuple with the FirstPublicationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPublicationDate

`func (o *Publication) SetFirstPublicationDate(v string)`

SetFirstPublicationDate sets FirstPublicationDate field to given value.

### HasFirstPublicationDate

`func (o *Publication) HasFirstPublicationDate() bool`

HasFirstPublicationDate returns a boolean if a field has been set.

### SetFirstPublicationDateNil

`func (o *Publication) SetFirstPublicationDateNil(b bool)`

 SetFirstPublicationDateNil sets the value for FirstPublicationDate to be an explicit nil

### UnsetFirstPublicationDate
`func (o *Publication) UnsetFirstPublicationDate()`

UnsetFirstPublicationDate ensures that no value is present for FirstPublicationDate, not even an explicit nil
### GetStatus

`func (o *Publication) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Publication) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Publication) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Publication) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Publication) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Publication) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Publication) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Publication) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Publication) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Publication) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Publication) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Publication) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


