# GetFederationHistory200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]GetFederationHistory200ResponseDataInner**](GetFederationHistory200ResponseDataInner.md) |  | [optional] 
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

### NewGetFederationHistory200Response

`func NewGetFederationHistory200Response() *GetFederationHistory200Response`

NewGetFederationHistory200Response instantiates a new GetFederationHistory200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFederationHistory200ResponseWithDefaults

`func NewGetFederationHistory200ResponseWithDefaults() *GetFederationHistory200Response`

NewGetFederationHistory200ResponseWithDefaults instantiates a new GetFederationHistory200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *GetFederationHistory200Response) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *GetFederationHistory200Response) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *GetFederationHistory200Response) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *GetFederationHistory200Response) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetData

`func (o *GetFederationHistory200Response) GetData() []GetFederationHistory200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetFederationHistory200Response) GetDataOk() (*[]GetFederationHistory200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetFederationHistory200Response) SetData(v []GetFederationHistory200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetFederationHistory200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFirstPageUrl

`func (o *GetFederationHistory200Response) GetFirstPageUrl() string`

GetFirstPageUrl returns the FirstPageUrl field if non-nil, zero value otherwise.

### GetFirstPageUrlOk

`func (o *GetFederationHistory200Response) GetFirstPageUrlOk() (*string, bool)`

GetFirstPageUrlOk returns a tuple with the FirstPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPageUrl

`func (o *GetFederationHistory200Response) SetFirstPageUrl(v string)`

SetFirstPageUrl sets FirstPageUrl field to given value.

### HasFirstPageUrl

`func (o *GetFederationHistory200Response) HasFirstPageUrl() bool`

HasFirstPageUrl returns a boolean if a field has been set.

### GetFrom

`func (o *GetFederationHistory200Response) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *GetFederationHistory200Response) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *GetFederationHistory200Response) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *GetFederationHistory200Response) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetLastPage

`func (o *GetFederationHistory200Response) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *GetFederationHistory200Response) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *GetFederationHistory200Response) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *GetFederationHistory200Response) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLastPageUrl

`func (o *GetFederationHistory200Response) GetLastPageUrl() string`

GetLastPageUrl returns the LastPageUrl field if non-nil, zero value otherwise.

### GetLastPageUrlOk

`func (o *GetFederationHistory200Response) GetLastPageUrlOk() (*string, bool)`

GetLastPageUrlOk returns a tuple with the LastPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPageUrl

`func (o *GetFederationHistory200Response) SetLastPageUrl(v string)`

SetLastPageUrl sets LastPageUrl field to given value.

### HasLastPageUrl

`func (o *GetFederationHistory200Response) HasLastPageUrl() bool`

HasLastPageUrl returns a boolean if a field has been set.

### GetLinks

`func (o *GetFederationHistory200Response) GetLinks() [][]interface{}`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetFederationHistory200Response) GetLinksOk() (*[][]interface{}, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetFederationHistory200Response) SetLinks(v [][]interface{})`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetFederationHistory200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetNextPageUrl

`func (o *GetFederationHistory200Response) GetNextPageUrl() string`

GetNextPageUrl returns the NextPageUrl field if non-nil, zero value otherwise.

### GetNextPageUrlOk

`func (o *GetFederationHistory200Response) GetNextPageUrlOk() (*string, bool)`

GetNextPageUrlOk returns a tuple with the NextPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageUrl

`func (o *GetFederationHistory200Response) SetNextPageUrl(v string)`

SetNextPageUrl sets NextPageUrl field to given value.

### HasNextPageUrl

`func (o *GetFederationHistory200Response) HasNextPageUrl() bool`

HasNextPageUrl returns a boolean if a field has been set.

### GetPath

`func (o *GetFederationHistory200Response) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *GetFederationHistory200Response) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *GetFederationHistory200Response) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *GetFederationHistory200Response) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *GetFederationHistory200Response) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GetFederationHistory200Response) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GetFederationHistory200Response) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GetFederationHistory200Response) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetPrevPageUrl

`func (o *GetFederationHistory200Response) GetPrevPageUrl() string`

GetPrevPageUrl returns the PrevPageUrl field if non-nil, zero value otherwise.

### GetPrevPageUrlOk

`func (o *GetFederationHistory200Response) GetPrevPageUrlOk() (*string, bool)`

GetPrevPageUrlOk returns a tuple with the PrevPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPageUrl

`func (o *GetFederationHistory200Response) SetPrevPageUrl(v string)`

SetPrevPageUrl sets PrevPageUrl field to given value.

### HasPrevPageUrl

`func (o *GetFederationHistory200Response) HasPrevPageUrl() bool`

HasPrevPageUrl returns a boolean if a field has been set.

### GetTo

`func (o *GetFederationHistory200Response) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *GetFederationHistory200Response) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *GetFederationHistory200Response) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *GetFederationHistory200Response) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetTotal

`func (o *GetFederationHistory200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetFederationHistory200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetFederationHistory200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetFederationHistory200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


