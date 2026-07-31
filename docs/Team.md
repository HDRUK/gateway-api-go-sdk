# Team

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**AllowsMessaging** | Pointer to **bool** |  | [optional] 
**WorkflowEnabled** | Pointer to **bool** |  | [optional] 
**AccessRequestsManagement** | Pointer to **bool** |  | [optional] 
**Uses5Safes** | Pointer to **bool** |  | [optional] 
**IsAdmin** | Pointer to **bool** |  | [optional] 
**MemberOf** | Pointer to **NullableString** |  | [optional] 
**ContactPoint** | Pointer to **NullableString** |  | [optional] 
**NotificationStatus** | Pointer to **NullableBool** |  | [optional] 
**IsQuestionBank** | Pointer to **bool** |  | [optional] 
**TeamLogo** | Pointer to **NullableString** |  | [optional] 
**Introduction** | Pointer to **NullableString** |  | [optional] 
**DarModalContent** | Pointer to **NullableString** |  | [optional] 
**DarModalHeader** | Pointer to **NullableString** |  | [optional] 
**DarModalFooter** | Pointer to **NullableString** |  | [optional] 
**Service** | Pointer to **NullableString** |  | [optional] 
**IsDar** | Pointer to **bool** |  | [optional] 
**Pid** | Pointer to **NullableString** | Public identifier, cast to string | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewTeam

`func NewTeam() *Team`

NewTeam instantiates a new Team object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamWithDefaults

`func NewTeamWithDefaults() *Team`

NewTeamWithDefaults instantiates a new Team object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Team) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Team) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Team) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Team) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Team) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Team) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Team) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Team) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEnabled

`func (o *Team) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Team) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Team) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Team) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetAllowsMessaging

`func (o *Team) GetAllowsMessaging() bool`

GetAllowsMessaging returns the AllowsMessaging field if non-nil, zero value otherwise.

### GetAllowsMessagingOk

`func (o *Team) GetAllowsMessagingOk() (*bool, bool)`

GetAllowsMessagingOk returns a tuple with the AllowsMessaging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowsMessaging

`func (o *Team) SetAllowsMessaging(v bool)`

SetAllowsMessaging sets AllowsMessaging field to given value.

### HasAllowsMessaging

`func (o *Team) HasAllowsMessaging() bool`

HasAllowsMessaging returns a boolean if a field has been set.

### GetWorkflowEnabled

`func (o *Team) GetWorkflowEnabled() bool`

GetWorkflowEnabled returns the WorkflowEnabled field if non-nil, zero value otherwise.

### GetWorkflowEnabledOk

`func (o *Team) GetWorkflowEnabledOk() (*bool, bool)`

GetWorkflowEnabledOk returns a tuple with the WorkflowEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowEnabled

`func (o *Team) SetWorkflowEnabled(v bool)`

SetWorkflowEnabled sets WorkflowEnabled field to given value.

### HasWorkflowEnabled

`func (o *Team) HasWorkflowEnabled() bool`

HasWorkflowEnabled returns a boolean if a field has been set.

### GetAccessRequestsManagement

`func (o *Team) GetAccessRequestsManagement() bool`

GetAccessRequestsManagement returns the AccessRequestsManagement field if non-nil, zero value otherwise.

### GetAccessRequestsManagementOk

`func (o *Team) GetAccessRequestsManagementOk() (*bool, bool)`

GetAccessRequestsManagementOk returns a tuple with the AccessRequestsManagement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessRequestsManagement

`func (o *Team) SetAccessRequestsManagement(v bool)`

SetAccessRequestsManagement sets AccessRequestsManagement field to given value.

### HasAccessRequestsManagement

`func (o *Team) HasAccessRequestsManagement() bool`

HasAccessRequestsManagement returns a boolean if a field has been set.

### GetUses5Safes

`func (o *Team) GetUses5Safes() bool`

GetUses5Safes returns the Uses5Safes field if non-nil, zero value otherwise.

### GetUses5SafesOk

`func (o *Team) GetUses5SafesOk() (*bool, bool)`

GetUses5SafesOk returns a tuple with the Uses5Safes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUses5Safes

`func (o *Team) SetUses5Safes(v bool)`

SetUses5Safes sets Uses5Safes field to given value.

### HasUses5Safes

`func (o *Team) HasUses5Safes() bool`

HasUses5Safes returns a boolean if a field has been set.

### GetIsAdmin

`func (o *Team) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *Team) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *Team) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.

### HasIsAdmin

`func (o *Team) HasIsAdmin() bool`

HasIsAdmin returns a boolean if a field has been set.

### GetMemberOf

`func (o *Team) GetMemberOf() string`

GetMemberOf returns the MemberOf field if non-nil, zero value otherwise.

### GetMemberOfOk

`func (o *Team) GetMemberOfOk() (*string, bool)`

GetMemberOfOk returns a tuple with the MemberOf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberOf

`func (o *Team) SetMemberOf(v string)`

SetMemberOf sets MemberOf field to given value.

### HasMemberOf

`func (o *Team) HasMemberOf() bool`

HasMemberOf returns a boolean if a field has been set.

### SetMemberOfNil

`func (o *Team) SetMemberOfNil(b bool)`

 SetMemberOfNil sets the value for MemberOf to be an explicit nil

### UnsetMemberOf
`func (o *Team) UnsetMemberOf()`

UnsetMemberOf ensures that no value is present for MemberOf, not even an explicit nil
### GetContactPoint

`func (o *Team) GetContactPoint() string`

GetContactPoint returns the ContactPoint field if non-nil, zero value otherwise.

### GetContactPointOk

`func (o *Team) GetContactPointOk() (*string, bool)`

GetContactPointOk returns a tuple with the ContactPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPoint

`func (o *Team) SetContactPoint(v string)`

SetContactPoint sets ContactPoint field to given value.

### HasContactPoint

`func (o *Team) HasContactPoint() bool`

HasContactPoint returns a boolean if a field has been set.

### SetContactPointNil

`func (o *Team) SetContactPointNil(b bool)`

 SetContactPointNil sets the value for ContactPoint to be an explicit nil

### UnsetContactPoint
`func (o *Team) UnsetContactPoint()`

UnsetContactPoint ensures that no value is present for ContactPoint, not even an explicit nil
### GetNotificationStatus

`func (o *Team) GetNotificationStatus() bool`

GetNotificationStatus returns the NotificationStatus field if non-nil, zero value otherwise.

### GetNotificationStatusOk

`func (o *Team) GetNotificationStatusOk() (*bool, bool)`

GetNotificationStatusOk returns a tuple with the NotificationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationStatus

`func (o *Team) SetNotificationStatus(v bool)`

SetNotificationStatus sets NotificationStatus field to given value.

### HasNotificationStatus

`func (o *Team) HasNotificationStatus() bool`

HasNotificationStatus returns a boolean if a field has been set.

### SetNotificationStatusNil

`func (o *Team) SetNotificationStatusNil(b bool)`

 SetNotificationStatusNil sets the value for NotificationStatus to be an explicit nil

### UnsetNotificationStatus
`func (o *Team) UnsetNotificationStatus()`

UnsetNotificationStatus ensures that no value is present for NotificationStatus, not even an explicit nil
### GetIsQuestionBank

`func (o *Team) GetIsQuestionBank() bool`

GetIsQuestionBank returns the IsQuestionBank field if non-nil, zero value otherwise.

### GetIsQuestionBankOk

`func (o *Team) GetIsQuestionBankOk() (*bool, bool)`

GetIsQuestionBankOk returns a tuple with the IsQuestionBank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsQuestionBank

`func (o *Team) SetIsQuestionBank(v bool)`

SetIsQuestionBank sets IsQuestionBank field to given value.

### HasIsQuestionBank

`func (o *Team) HasIsQuestionBank() bool`

HasIsQuestionBank returns a boolean if a field has been set.

### GetTeamLogo

`func (o *Team) GetTeamLogo() string`

GetTeamLogo returns the TeamLogo field if non-nil, zero value otherwise.

### GetTeamLogoOk

`func (o *Team) GetTeamLogoOk() (*string, bool)`

GetTeamLogoOk returns a tuple with the TeamLogo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamLogo

`func (o *Team) SetTeamLogo(v string)`

SetTeamLogo sets TeamLogo field to given value.

### HasTeamLogo

`func (o *Team) HasTeamLogo() bool`

HasTeamLogo returns a boolean if a field has been set.

### SetTeamLogoNil

`func (o *Team) SetTeamLogoNil(b bool)`

 SetTeamLogoNil sets the value for TeamLogo to be an explicit nil

### UnsetTeamLogo
`func (o *Team) UnsetTeamLogo()`

UnsetTeamLogo ensures that no value is present for TeamLogo, not even an explicit nil
### GetIntroduction

`func (o *Team) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *Team) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *Team) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *Team) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *Team) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *Team) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetDarModalContent

`func (o *Team) GetDarModalContent() string`

GetDarModalContent returns the DarModalContent field if non-nil, zero value otherwise.

### GetDarModalContentOk

`func (o *Team) GetDarModalContentOk() (*string, bool)`

GetDarModalContentOk returns a tuple with the DarModalContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDarModalContent

`func (o *Team) SetDarModalContent(v string)`

SetDarModalContent sets DarModalContent field to given value.

### HasDarModalContent

`func (o *Team) HasDarModalContent() bool`

HasDarModalContent returns a boolean if a field has been set.

### SetDarModalContentNil

`func (o *Team) SetDarModalContentNil(b bool)`

 SetDarModalContentNil sets the value for DarModalContent to be an explicit nil

### UnsetDarModalContent
`func (o *Team) UnsetDarModalContent()`

UnsetDarModalContent ensures that no value is present for DarModalContent, not even an explicit nil
### GetDarModalHeader

`func (o *Team) GetDarModalHeader() string`

GetDarModalHeader returns the DarModalHeader field if non-nil, zero value otherwise.

### GetDarModalHeaderOk

`func (o *Team) GetDarModalHeaderOk() (*string, bool)`

GetDarModalHeaderOk returns a tuple with the DarModalHeader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDarModalHeader

`func (o *Team) SetDarModalHeader(v string)`

SetDarModalHeader sets DarModalHeader field to given value.

### HasDarModalHeader

`func (o *Team) HasDarModalHeader() bool`

HasDarModalHeader returns a boolean if a field has been set.

### SetDarModalHeaderNil

`func (o *Team) SetDarModalHeaderNil(b bool)`

 SetDarModalHeaderNil sets the value for DarModalHeader to be an explicit nil

### UnsetDarModalHeader
`func (o *Team) UnsetDarModalHeader()`

UnsetDarModalHeader ensures that no value is present for DarModalHeader, not even an explicit nil
### GetDarModalFooter

`func (o *Team) GetDarModalFooter() string`

GetDarModalFooter returns the DarModalFooter field if non-nil, zero value otherwise.

### GetDarModalFooterOk

`func (o *Team) GetDarModalFooterOk() (*string, bool)`

GetDarModalFooterOk returns a tuple with the DarModalFooter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDarModalFooter

`func (o *Team) SetDarModalFooter(v string)`

SetDarModalFooter sets DarModalFooter field to given value.

### HasDarModalFooter

`func (o *Team) HasDarModalFooter() bool`

HasDarModalFooter returns a boolean if a field has been set.

### SetDarModalFooterNil

`func (o *Team) SetDarModalFooterNil(b bool)`

 SetDarModalFooterNil sets the value for DarModalFooter to be an explicit nil

### UnsetDarModalFooter
`func (o *Team) UnsetDarModalFooter()`

UnsetDarModalFooter ensures that no value is present for DarModalFooter, not even an explicit nil
### GetService

`func (o *Team) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *Team) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *Team) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *Team) HasService() bool`

HasService returns a boolean if a field has been set.

### SetServiceNil

`func (o *Team) SetServiceNil(b bool)`

 SetServiceNil sets the value for Service to be an explicit nil

### UnsetService
`func (o *Team) UnsetService()`

UnsetService ensures that no value is present for Service, not even an explicit nil
### GetIsDar

`func (o *Team) GetIsDar() bool`

GetIsDar returns the IsDar field if non-nil, zero value otherwise.

### GetIsDarOk

`func (o *Team) GetIsDarOk() (*bool, bool)`

GetIsDarOk returns a tuple with the IsDar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDar

`func (o *Team) SetIsDar(v bool)`

SetIsDar sets IsDar field to given value.

### HasIsDar

`func (o *Team) HasIsDar() bool`

HasIsDar returns a boolean if a field has been set.

### GetPid

`func (o *Team) GetPid() string`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *Team) GetPidOk() (*string, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *Team) SetPid(v string)`

SetPid sets Pid field to given value.

### HasPid

`func (o *Team) HasPid() bool`

HasPid returns a boolean if a field has been set.

### SetPidNil

`func (o *Team) SetPidNil(b bool)`

 SetPidNil sets the value for Pid to be an explicit nil

### UnsetPid
`func (o *Team) UnsetPid()`

UnsetPid ensures that no value is present for Pid, not even an explicit nil
### GetCreatedAt

`func (o *Team) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Team) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Team) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Team) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Team) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Team) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Team) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Team) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


