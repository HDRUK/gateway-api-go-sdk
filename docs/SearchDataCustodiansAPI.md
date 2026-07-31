# \SearchDataCustodiansAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchDataCustodians**](SearchDataCustodiansAPI.md#SearchDataCustodians) | **Post** /api/v1/search/data_custodians | Search@data_custodians



## SearchDataCustodians

> SearchDataCustodians200Response SearchDataCustodians(ctx).SearchDataCustodiansRequest(searchDataCustodiansRequest).Sort(sort).Direction(direction).PerPage(perPage).Execute()

Search@data_custodians



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	searchDataCustodiansRequest := *openapiclient.NewSearchDataCustodiansRequest() // SearchDataCustodiansRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)
	perPage := int32(25) // int32 | Number of results to return per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchDataCustodiansAPI.SearchDataCustodians(context.Background()).SearchDataCustodiansRequest(searchDataCustodiansRequest).Sort(sort).Direction(direction).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchDataCustodiansAPI.SearchDataCustodians``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchDataCustodians`: SearchDataCustodians200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchDataCustodiansAPI.SearchDataCustodians`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchDataCustodiansRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchDataCustodiansRequest** | [**SearchDataCustodiansRequest**](SearchDataCustodiansRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 
 **perPage** | **int32** | Number of results to return per page | 

### Return type

[**SearchDataCustodians200Response**](SearchDataCustodians200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

