# FetchAllCollections200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Collection**](Collection.md) |  | [optional] 
**FirstPageUrl** | Pointer to **string** |  | [optional] 
**From** | Pointer to **int32** |  | [optional] 
**LastPage** | Pointer to **int32** |  | [optional] 
**LastPageUrl** | Pointer to **string** |  | [optional] 
**Links** | Pointer to **[][]interface{}** |  | [optional] 
**NextPageUrl** | Pointer to **string** |  | [optional] 
**Path** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**PrevPageUrl** | Pointer to **string** |  | [optional] 
**To** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewFetchAllCollections200Response

`func NewFetchAllCollections200Response() *FetchAllCollections200Response`

NewFetchAllCollections200Response instantiates a new FetchAllCollections200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllCollections200ResponseWithDefaults

`func NewFetchAllCollections200ResponseWithDefaults() *FetchAllCollections200Response`

NewFetchAllCollections200ResponseWithDefaults instantiates a new FetchAllCollections200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllCollections200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllCollections200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllCollections200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllCollections200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllCollections200Response) GetData() []Collection`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllCollections200Response) GetDataOk() (*[]Collection, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllCollections200Response) SetData(v []Collection)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllCollections200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFirstPageUrl

`func (o *FetchAllCollections200Response) GetFirstPageUrl() string`

GetFirstPageUrl returns the FirstPageUrl field if non-nil, zero value otherwise.

### GetFirstPageUrlOk

`func (o *FetchAllCollections200Response) GetFirstPageUrlOk() (*string, bool)`

GetFirstPageUrlOk returns a tuple with the FirstPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPageUrl

`func (o *FetchAllCollections200Response) SetFirstPageUrl(v string)`

SetFirstPageUrl sets FirstPageUrl field to given value.

### HasFirstPageUrl

`func (o *FetchAllCollections200Response) HasFirstPageUrl() bool`

HasFirstPageUrl returns a boolean if a field has been set.

### GetFrom

`func (o *FetchAllCollections200Response) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *FetchAllCollections200Response) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *FetchAllCollections200Response) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *FetchAllCollections200Response) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetLastPage

`func (o *FetchAllCollections200Response) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *FetchAllCollections200Response) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *FetchAllCollections200Response) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *FetchAllCollections200Response) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLastPageUrl

`func (o *FetchAllCollections200Response) GetLastPageUrl() string`

GetLastPageUrl returns the LastPageUrl field if non-nil, zero value otherwise.

### GetLastPageUrlOk

`func (o *FetchAllCollections200Response) GetLastPageUrlOk() (*string, bool)`

GetLastPageUrlOk returns a tuple with the LastPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPageUrl

`func (o *FetchAllCollections200Response) SetLastPageUrl(v string)`

SetLastPageUrl sets LastPageUrl field to given value.

### HasLastPageUrl

`func (o *FetchAllCollections200Response) HasLastPageUrl() bool`

HasLastPageUrl returns a boolean if a field has been set.

### GetLinks

`func (o *FetchAllCollections200Response) GetLinks() [][]interface{}`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *FetchAllCollections200Response) GetLinksOk() (*[][]interface{}, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *FetchAllCollections200Response) SetLinks(v [][]interface{})`

SetLinks sets Links field to given value.

### HasLinks

`func (o *FetchAllCollections200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetNextPageUrl

`func (o *FetchAllCollections200Response) GetNextPageUrl() string`

GetNextPageUrl returns the NextPageUrl field if non-nil, zero value otherwise.

### GetNextPageUrlOk

`func (o *FetchAllCollections200Response) GetNextPageUrlOk() (*string, bool)`

GetNextPageUrlOk returns a tuple with the NextPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageUrl

`func (o *FetchAllCollections200Response) SetNextPageUrl(v string)`

SetNextPageUrl sets NextPageUrl field to given value.

### HasNextPageUrl

`func (o *FetchAllCollections200Response) HasNextPageUrl() bool`

HasNextPageUrl returns a boolean if a field has been set.

### GetPath

`func (o *FetchAllCollections200Response) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *FetchAllCollections200Response) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *FetchAllCollections200Response) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *FetchAllCollections200Response) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *FetchAllCollections200Response) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *FetchAllCollections200Response) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *FetchAllCollections200Response) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *FetchAllCollections200Response) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetPrevPageUrl

`func (o *FetchAllCollections200Response) GetPrevPageUrl() string`

GetPrevPageUrl returns the PrevPageUrl field if non-nil, zero value otherwise.

### GetPrevPageUrlOk

`func (o *FetchAllCollections200Response) GetPrevPageUrlOk() (*string, bool)`

GetPrevPageUrlOk returns a tuple with the PrevPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPageUrl

`func (o *FetchAllCollections200Response) SetPrevPageUrl(v string)`

SetPrevPageUrl sets PrevPageUrl field to given value.

### HasPrevPageUrl

`func (o *FetchAllCollections200Response) HasPrevPageUrl() bool`

HasPrevPageUrl returns a boolean if a field has been set.

### GetTo

`func (o *FetchAllCollections200Response) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *FetchAllCollections200Response) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *FetchAllCollections200Response) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *FetchAllCollections200Response) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetTotal

`func (o *FetchAllCollections200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FetchAllCollections200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FetchAllCollections200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FetchAllCollections200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


