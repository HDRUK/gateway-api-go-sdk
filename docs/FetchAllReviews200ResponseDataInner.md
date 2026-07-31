# FetchAllReviews200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ToolId** | Pointer to **int32** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Rating** | Pointer to **int32** |  | [optional] 
**ReviewText** | Pointer to **string** |  | [optional] 
**ReviewState** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **time.Time** |  | [optional] 
**Tool** | Pointer to [**FetchAllReviews200ResponseDataInnerTool**](FetchAllReviews200ResponseDataInnerTool.md) |  | [optional] 
**User** | Pointer to [**FetchAllReviews200ResponseDataInnerUser**](FetchAllReviews200ResponseDataInnerUser.md) |  | [optional] 

## Methods

### NewFetchAllReviews200ResponseDataInner

`func NewFetchAllReviews200ResponseDataInner() *FetchAllReviews200ResponseDataInner`

NewFetchAllReviews200ResponseDataInner instantiates a new FetchAllReviews200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllReviews200ResponseDataInnerWithDefaults

`func NewFetchAllReviews200ResponseDataInnerWithDefaults() *FetchAllReviews200ResponseDataInner`

NewFetchAllReviews200ResponseDataInnerWithDefaults instantiates a new FetchAllReviews200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FetchAllReviews200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FetchAllReviews200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FetchAllReviews200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FetchAllReviews200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetToolId

`func (o *FetchAllReviews200ResponseDataInner) GetToolId() int32`

GetToolId returns the ToolId field if non-nil, zero value otherwise.

### GetToolIdOk

`func (o *FetchAllReviews200ResponseDataInner) GetToolIdOk() (*int32, bool)`

GetToolIdOk returns a tuple with the ToolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolId

`func (o *FetchAllReviews200ResponseDataInner) SetToolId(v int32)`

SetToolId sets ToolId field to given value.

### HasToolId

`func (o *FetchAllReviews200ResponseDataInner) HasToolId() bool`

HasToolId returns a boolean if a field has been set.

### GetUserId

`func (o *FetchAllReviews200ResponseDataInner) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *FetchAllReviews200ResponseDataInner) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *FetchAllReviews200ResponseDataInner) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *FetchAllReviews200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetRating

`func (o *FetchAllReviews200ResponseDataInner) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *FetchAllReviews200ResponseDataInner) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *FetchAllReviews200ResponseDataInner) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *FetchAllReviews200ResponseDataInner) HasRating() bool`

HasRating returns a boolean if a field has been set.

### GetReviewText

`func (o *FetchAllReviews200ResponseDataInner) GetReviewText() string`

GetReviewText returns the ReviewText field if non-nil, zero value otherwise.

### GetReviewTextOk

`func (o *FetchAllReviews200ResponseDataInner) GetReviewTextOk() (*string, bool)`

GetReviewTextOk returns a tuple with the ReviewText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewText

`func (o *FetchAllReviews200ResponseDataInner) SetReviewText(v string)`

SetReviewText sets ReviewText field to given value.

### HasReviewText

`func (o *FetchAllReviews200ResponseDataInner) HasReviewText() bool`

HasReviewText returns a boolean if a field has been set.

### GetReviewState

`func (o *FetchAllReviews200ResponseDataInner) GetReviewState() int32`

GetReviewState returns the ReviewState field if non-nil, zero value otherwise.

### GetReviewStateOk

`func (o *FetchAllReviews200ResponseDataInner) GetReviewStateOk() (*int32, bool)`

GetReviewStateOk returns a tuple with the ReviewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewState

`func (o *FetchAllReviews200ResponseDataInner) SetReviewState(v int32)`

SetReviewState sets ReviewState field to given value.

### HasReviewState

`func (o *FetchAllReviews200ResponseDataInner) HasReviewState() bool`

HasReviewState returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FetchAllReviews200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FetchAllReviews200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FetchAllReviews200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FetchAllReviews200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FetchAllReviews200ResponseDataInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FetchAllReviews200ResponseDataInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FetchAllReviews200ResponseDataInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FetchAllReviews200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *FetchAllReviews200ResponseDataInner) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *FetchAllReviews200ResponseDataInner) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *FetchAllReviews200ResponseDataInner) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *FetchAllReviews200ResponseDataInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetTool

`func (o *FetchAllReviews200ResponseDataInner) GetTool() FetchAllReviews200ResponseDataInnerTool`

GetTool returns the Tool field if non-nil, zero value otherwise.

### GetToolOk

`func (o *FetchAllReviews200ResponseDataInner) GetToolOk() (*FetchAllReviews200ResponseDataInnerTool, bool)`

GetToolOk returns a tuple with the Tool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTool

`func (o *FetchAllReviews200ResponseDataInner) SetTool(v FetchAllReviews200ResponseDataInnerTool)`

SetTool sets Tool field to given value.

### HasTool

`func (o *FetchAllReviews200ResponseDataInner) HasTool() bool`

HasTool returns a boolean if a field has been set.

### GetUser

`func (o *FetchAllReviews200ResponseDataInner) GetUser() FetchAllReviews200ResponseDataInnerUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *FetchAllReviews200ResponseDataInner) GetUserOk() (*FetchAllReviews200ResponseDataInnerUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *FetchAllReviews200ResponseDataInner) SetUser(v FetchAllReviews200ResponseDataInnerUser)`

SetUser sets User field to given value.

### HasUser

`func (o *FetchAllReviews200ResponseDataInner) HasUser() bool`

HasUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


