# User

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Firstname** | Pointer to **NullableString** |  | [optional] 
**Lastname** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**SecondaryEmail** | Pointer to **NullableString** |  | [optional] 
**PreferredEmail** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**SectorId** | Pointer to **NullableInt32** |  | [optional] 
**Organisation** | Pointer to **NullableString** |  | [optional] 
**Bio** | Pointer to **NullableString** |  | [optional] 
**Domain** | Pointer to **NullableString** |  | [optional] 
**Link** | Pointer to **NullableString** |  | [optional] 
**Orcid** | Pointer to **NullableString** |  | [optional] 
**ContactFeedback** | Pointer to **NullableBool** |  | [optional] 
**ContactNews** | Pointer to **NullableBool** |  | [optional] 
**IsAdmin** | Pointer to **bool** |  | [optional] 
**Terms** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewUser

`func NewUser() *User`

NewUser instantiates a new User object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserWithDefaults

`func NewUserWithDefaults() *User`

NewUserWithDefaults instantiates a new User object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *User) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *User) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *User) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *User) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *User) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *User) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *User) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *User) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *User) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *User) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetFirstname

`func (o *User) GetFirstname() string`

GetFirstname returns the Firstname field if non-nil, zero value otherwise.

### GetFirstnameOk

`func (o *User) GetFirstnameOk() (*string, bool)`

GetFirstnameOk returns a tuple with the Firstname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstname

`func (o *User) SetFirstname(v string)`

SetFirstname sets Firstname field to given value.

### HasFirstname

`func (o *User) HasFirstname() bool`

HasFirstname returns a boolean if a field has been set.

### SetFirstnameNil

`func (o *User) SetFirstnameNil(b bool)`

 SetFirstnameNil sets the value for Firstname to be an explicit nil

### UnsetFirstname
`func (o *User) UnsetFirstname()`

UnsetFirstname ensures that no value is present for Firstname, not even an explicit nil
### GetLastname

`func (o *User) GetLastname() string`

GetLastname returns the Lastname field if non-nil, zero value otherwise.

### GetLastnameOk

`func (o *User) GetLastnameOk() (*string, bool)`

GetLastnameOk returns a tuple with the Lastname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastname

`func (o *User) SetLastname(v string)`

SetLastname sets Lastname field to given value.

### HasLastname

`func (o *User) HasLastname() bool`

HasLastname returns a boolean if a field has been set.

### SetLastnameNil

`func (o *User) SetLastnameNil(b bool)`

 SetLastnameNil sets the value for Lastname to be an explicit nil

### UnsetLastname
`func (o *User) UnsetLastname()`

UnsetLastname ensures that no value is present for Lastname, not even an explicit nil
### GetEmail

`func (o *User) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *User) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *User) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *User) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetSecondaryEmail

`func (o *User) GetSecondaryEmail() string`

GetSecondaryEmail returns the SecondaryEmail field if non-nil, zero value otherwise.

### GetSecondaryEmailOk

`func (o *User) GetSecondaryEmailOk() (*string, bool)`

GetSecondaryEmailOk returns a tuple with the SecondaryEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryEmail

`func (o *User) SetSecondaryEmail(v string)`

SetSecondaryEmail sets SecondaryEmail field to given value.

### HasSecondaryEmail

`func (o *User) HasSecondaryEmail() bool`

HasSecondaryEmail returns a boolean if a field has been set.

### SetSecondaryEmailNil

`func (o *User) SetSecondaryEmailNil(b bool)`

 SetSecondaryEmailNil sets the value for SecondaryEmail to be an explicit nil

### UnsetSecondaryEmail
`func (o *User) UnsetSecondaryEmail()`

UnsetSecondaryEmail ensures that no value is present for SecondaryEmail, not even an explicit nil
### GetPreferredEmail

`func (o *User) GetPreferredEmail() string`

GetPreferredEmail returns the PreferredEmail field if non-nil, zero value otherwise.

### GetPreferredEmailOk

`func (o *User) GetPreferredEmailOk() (*string, bool)`

GetPreferredEmailOk returns a tuple with the PreferredEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredEmail

`func (o *User) SetPreferredEmail(v string)`

SetPreferredEmail sets PreferredEmail field to given value.

### HasPreferredEmail

`func (o *User) HasPreferredEmail() bool`

HasPreferredEmail returns a boolean if a field has been set.

### SetPreferredEmailNil

`func (o *User) SetPreferredEmailNil(b bool)`

 SetPreferredEmailNil sets the value for PreferredEmail to be an explicit nil

### UnsetPreferredEmail
`func (o *User) UnsetPreferredEmail()`

UnsetPreferredEmail ensures that no value is present for PreferredEmail, not even an explicit nil
### GetProvider

`func (o *User) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *User) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *User) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *User) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *User) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *User) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetSectorId

`func (o *User) GetSectorId() int32`

GetSectorId returns the SectorId field if non-nil, zero value otherwise.

### GetSectorIdOk

`func (o *User) GetSectorIdOk() (*int32, bool)`

GetSectorIdOk returns a tuple with the SectorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSectorId

`func (o *User) SetSectorId(v int32)`

SetSectorId sets SectorId field to given value.

### HasSectorId

`func (o *User) HasSectorId() bool`

HasSectorId returns a boolean if a field has been set.

### SetSectorIdNil

`func (o *User) SetSectorIdNil(b bool)`

 SetSectorIdNil sets the value for SectorId to be an explicit nil

### UnsetSectorId
`func (o *User) UnsetSectorId()`

UnsetSectorId ensures that no value is present for SectorId, not even an explicit nil
### GetOrganisation

`func (o *User) GetOrganisation() string`

GetOrganisation returns the Organisation field if non-nil, zero value otherwise.

### GetOrganisationOk

`func (o *User) GetOrganisationOk() (*string, bool)`

GetOrganisationOk returns a tuple with the Organisation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganisation

`func (o *User) SetOrganisation(v string)`

SetOrganisation sets Organisation field to given value.

### HasOrganisation

`func (o *User) HasOrganisation() bool`

HasOrganisation returns a boolean if a field has been set.

### SetOrganisationNil

`func (o *User) SetOrganisationNil(b bool)`

 SetOrganisationNil sets the value for Organisation to be an explicit nil

### UnsetOrganisation
`func (o *User) UnsetOrganisation()`

UnsetOrganisation ensures that no value is present for Organisation, not even an explicit nil
### GetBio

`func (o *User) GetBio() string`

GetBio returns the Bio field if non-nil, zero value otherwise.

### GetBioOk

`func (o *User) GetBioOk() (*string, bool)`

GetBioOk returns a tuple with the Bio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBio

`func (o *User) SetBio(v string)`

SetBio sets Bio field to given value.

### HasBio

`func (o *User) HasBio() bool`

HasBio returns a boolean if a field has been set.

### SetBioNil

`func (o *User) SetBioNil(b bool)`

 SetBioNil sets the value for Bio to be an explicit nil

### UnsetBio
`func (o *User) UnsetBio()`

UnsetBio ensures that no value is present for Bio, not even an explicit nil
### GetDomain

`func (o *User) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *User) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *User) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *User) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *User) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *User) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetLink

`func (o *User) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *User) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *User) SetLink(v string)`

SetLink sets Link field to given value.

### HasLink

`func (o *User) HasLink() bool`

HasLink returns a boolean if a field has been set.

### SetLinkNil

`func (o *User) SetLinkNil(b bool)`

 SetLinkNil sets the value for Link to be an explicit nil

### UnsetLink
`func (o *User) UnsetLink()`

UnsetLink ensures that no value is present for Link, not even an explicit nil
### GetOrcid

`func (o *User) GetOrcid() string`

GetOrcid returns the Orcid field if non-nil, zero value otherwise.

### GetOrcidOk

`func (o *User) GetOrcidOk() (*string, bool)`

GetOrcidOk returns a tuple with the Orcid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrcid

`func (o *User) SetOrcid(v string)`

SetOrcid sets Orcid field to given value.

### HasOrcid

`func (o *User) HasOrcid() bool`

HasOrcid returns a boolean if a field has been set.

### SetOrcidNil

`func (o *User) SetOrcidNil(b bool)`

 SetOrcidNil sets the value for Orcid to be an explicit nil

### UnsetOrcid
`func (o *User) UnsetOrcid()`

UnsetOrcid ensures that no value is present for Orcid, not even an explicit nil
### GetContactFeedback

`func (o *User) GetContactFeedback() bool`

GetContactFeedback returns the ContactFeedback field if non-nil, zero value otherwise.

### GetContactFeedbackOk

`func (o *User) GetContactFeedbackOk() (*bool, bool)`

GetContactFeedbackOk returns a tuple with the ContactFeedback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactFeedback

`func (o *User) SetContactFeedback(v bool)`

SetContactFeedback sets ContactFeedback field to given value.

### HasContactFeedback

`func (o *User) HasContactFeedback() bool`

HasContactFeedback returns a boolean if a field has been set.

### SetContactFeedbackNil

`func (o *User) SetContactFeedbackNil(b bool)`

 SetContactFeedbackNil sets the value for ContactFeedback to be an explicit nil

### UnsetContactFeedback
`func (o *User) UnsetContactFeedback()`

UnsetContactFeedback ensures that no value is present for ContactFeedback, not even an explicit nil
### GetContactNews

`func (o *User) GetContactNews() bool`

GetContactNews returns the ContactNews field if non-nil, zero value otherwise.

### GetContactNewsOk

`func (o *User) GetContactNewsOk() (*bool, bool)`

GetContactNewsOk returns a tuple with the ContactNews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNews

`func (o *User) SetContactNews(v bool)`

SetContactNews sets ContactNews field to given value.

### HasContactNews

`func (o *User) HasContactNews() bool`

HasContactNews returns a boolean if a field has been set.

### SetContactNewsNil

`func (o *User) SetContactNewsNil(b bool)`

 SetContactNewsNil sets the value for ContactNews to be an explicit nil

### UnsetContactNews
`func (o *User) UnsetContactNews()`

UnsetContactNews ensures that no value is present for ContactNews, not even an explicit nil
### GetIsAdmin

`func (o *User) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *User) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *User) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.

### HasIsAdmin

`func (o *User) HasIsAdmin() bool`

HasIsAdmin returns a boolean if a field has been set.

### GetTerms

`func (o *User) GetTerms() bool`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *User) GetTermsOk() (*bool, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *User) SetTerms(v bool)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *User) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetCreatedAt

`func (o *User) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *User) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *User) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *User) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *User) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *User) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *User) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *User) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


