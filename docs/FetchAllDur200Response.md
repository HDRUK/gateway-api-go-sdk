# FetchAllDur200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Dur**](Dur.md) |  | [optional] 
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

### NewFetchAllDur200Response

`func NewFetchAllDur200Response() *FetchAllDur200Response`

NewFetchAllDur200Response instantiates a new FetchAllDur200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchAllDur200ResponseWithDefaults

`func NewFetchAllDur200ResponseWithDefaults() *FetchAllDur200Response`

NewFetchAllDur200ResponseWithDefaults instantiates a new FetchAllDur200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FetchAllDur200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FetchAllDur200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FetchAllDur200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *FetchAllDur200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetData

`func (o *FetchAllDur200Response) GetData() []Dur`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FetchAllDur200Response) GetDataOk() (*[]Dur, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FetchAllDur200Response) SetData(v []Dur)`

SetData sets Data field to given value.

### HasData

`func (o *FetchAllDur200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFirstPageUrl

`func (o *FetchAllDur200Response) GetFirstPageUrl() string`

GetFirstPageUrl returns the FirstPageUrl field if non-nil, zero value otherwise.

### GetFirstPageUrlOk

`func (o *FetchAllDur200Response) GetFirstPageUrlOk() (*string, bool)`

GetFirstPageUrlOk returns a tuple with the FirstPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPageUrl

`func (o *FetchAllDur200Response) SetFirstPageUrl(v string)`

SetFirstPageUrl sets FirstPageUrl field to given value.

### HasFirstPageUrl

`func (o *FetchAllDur200Response) HasFirstPageUrl() bool`

HasFirstPageUrl returns a boolean if a field has been set.

### GetFrom

`func (o *FetchAllDur200Response) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *FetchAllDur200Response) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *FetchAllDur200Response) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *FetchAllDur200Response) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetLastPage

`func (o *FetchAllDur200Response) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *FetchAllDur200Response) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *FetchAllDur200Response) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *FetchAllDur200Response) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLastPageUrl

`func (o *FetchAllDur200Response) GetLastPageUrl() string`

GetLastPageUrl returns the LastPageUrl field if non-nil, zero value otherwise.

### GetLastPageUrlOk

`func (o *FetchAllDur200Response) GetLastPageUrlOk() (*string, bool)`

GetLastPageUrlOk returns a tuple with the LastPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPageUrl

`func (o *FetchAllDur200Response) SetLastPageUrl(v string)`

SetLastPageUrl sets LastPageUrl field to given value.

### HasLastPageUrl

`func (o *FetchAllDur200Response) HasLastPageUrl() bool`

HasLastPageUrl returns a boolean if a field has been set.

### GetLinks

`func (o *FetchAllDur200Response) GetLinks() [][]interface{}`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *FetchAllDur200Response) GetLinksOk() (*[][]interface{}, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *FetchAllDur200Response) SetLinks(v [][]interface{})`

SetLinks sets Links field to given value.

### HasLinks

`func (o *FetchAllDur200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetNextPageUrl

`func (o *FetchAllDur200Response) GetNextPageUrl() string`

GetNextPageUrl returns the NextPageUrl field if non-nil, zero value otherwise.

### GetNextPageUrlOk

`func (o *FetchAllDur200Response) GetNextPageUrlOk() (*string, bool)`

GetNextPageUrlOk returns a tuple with the NextPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageUrl

`func (o *FetchAllDur200Response) SetNextPageUrl(v string)`

SetNextPageUrl sets NextPageUrl field to given value.

### HasNextPageUrl

`func (o *FetchAllDur200Response) HasNextPageUrl() bool`

HasNextPageUrl returns a boolean if a field has been set.

### GetPath

`func (o *FetchAllDur200Response) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *FetchAllDur200Response) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *FetchAllDur200Response) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *FetchAllDur200Response) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *FetchAllDur200Response) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *FetchAllDur200Response) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *FetchAllDur200Response) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *FetchAllDur200Response) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetPrevPageUrl

`func (o *FetchAllDur200Response) GetPrevPageUrl() string`

GetPrevPageUrl returns the PrevPageUrl field if non-nil, zero value otherwise.

### GetPrevPageUrlOk

`func (o *FetchAllDur200Response) GetPrevPageUrlOk() (*string, bool)`

GetPrevPageUrlOk returns a tuple with the PrevPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPageUrl

`func (o *FetchAllDur200Response) SetPrevPageUrl(v string)`

SetPrevPageUrl sets PrevPageUrl field to given value.

### HasPrevPageUrl

`func (o *FetchAllDur200Response) HasPrevPageUrl() bool`

HasPrevPageUrl returns a boolean if a field has been set.

### GetTo

`func (o *FetchAllDur200Response) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *FetchAllDur200Response) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *FetchAllDur200Response) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *FetchAllDur200Response) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetTotal

`func (o *FetchAllDur200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FetchAllDur200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FetchAllDur200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FetchAllDur200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


