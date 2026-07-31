# DataAccessApplicationReview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ApplicationId** | Pointer to **int32** |  | [optional] 
**QuestionId** | Pointer to **NullableInt32** |  | [optional] 
**Resolved** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewDataAccessApplicationReview

`func NewDataAccessApplicationReview() *DataAccessApplicationReview`

NewDataAccessApplicationReview instantiates a new DataAccessApplicationReview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataAccessApplicationReviewWithDefaults

`func NewDataAccessApplicationReviewWithDefaults() *DataAccessApplicationReview`

NewDataAccessApplicationReviewWithDefaults instantiates a new DataAccessApplicationReview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DataAccessApplicationReview) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DataAccessApplicationReview) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DataAccessApplicationReview) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DataAccessApplicationReview) HasId() bool`

HasId returns a boolean if a field has been set.

### GetApplicationId

`func (o *DataAccessApplicationReview) GetApplicationId() int32`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *DataAccessApplicationReview) GetApplicationIdOk() (*int32, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *DataAccessApplicationReview) SetApplicationId(v int32)`

SetApplicationId sets ApplicationId field to given value.

### HasApplicationId

`func (o *DataAccessApplicationReview) HasApplicationId() bool`

HasApplicationId returns a boolean if a field has been set.

### GetQuestionId

`func (o *DataAccessApplicationReview) GetQuestionId() int32`

GetQuestionId returns the QuestionId field if non-nil, zero value otherwise.

### GetQuestionIdOk

`func (o *DataAccessApplicationReview) GetQuestionIdOk() (*int32, bool)`

GetQuestionIdOk returns a tuple with the QuestionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionId

`func (o *DataAccessApplicationReview) SetQuestionId(v int32)`

SetQuestionId sets QuestionId field to given value.

### HasQuestionId

`func (o *DataAccessApplicationReview) HasQuestionId() bool`

HasQuestionId returns a boolean if a field has been set.

### SetQuestionIdNil

`func (o *DataAccessApplicationReview) SetQuestionIdNil(b bool)`

 SetQuestionIdNil sets the value for QuestionId to be an explicit nil

### UnsetQuestionId
`func (o *DataAccessApplicationReview) UnsetQuestionId()`

UnsetQuestionId ensures that no value is present for QuestionId, not even an explicit nil
### GetResolved

`func (o *DataAccessApplicationReview) GetResolved() int32`

GetResolved returns the Resolved field if non-nil, zero value otherwise.

### GetResolvedOk

`func (o *DataAccessApplicationReview) GetResolvedOk() (*int32, bool)`

GetResolvedOk returns a tuple with the Resolved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolved

`func (o *DataAccessApplicationReview) SetResolved(v int32)`

SetResolved sets Resolved field to given value.

### HasResolved

`func (o *DataAccessApplicationReview) HasResolved() bool`

HasResolved returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DataAccessApplicationReview) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DataAccessApplicationReview) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DataAccessApplicationReview) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DataAccessApplicationReview) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DataAccessApplicationReview) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DataAccessApplicationReview) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DataAccessApplicationReview) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DataAccessApplicationReview) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *DataAccessApplicationReview) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *DataAccessApplicationReview) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *DataAccessApplicationReview) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *DataAccessApplicationReview) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *DataAccessApplicationReview) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *DataAccessApplicationReview) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


