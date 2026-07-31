# \SearchDataUsesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchDataUses**](SearchDataUsesAPI.md#SearchDataUses) | **Post** /api/v1/search/dur | Search@data_uses



## SearchDataUses

> SearchDataUses200Response SearchDataUses(ctx).SearchDataUsesRequest(searchDataUsesRequest).Sort(sort).Direction(direction).Download(download).Execute()

Search@data_uses



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
	searchDataUsesRequest := *openapiclient.NewSearchDataUsesRequest() // SearchDataUsesRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)
	download := true // bool | Download a csv of the results (default: false) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchDataUsesAPI.SearchDataUses(context.Background()).SearchDataUsesRequest(searchDataUsesRequest).Sort(sort).Direction(direction).Download(download).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchDataUsesAPI.SearchDataUses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchDataUses`: SearchDataUses200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchDataUsesAPI.SearchDataUses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchDataUsesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchDataUsesRequest** | [**SearchDataUsesRequest**](SearchDataUsesRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 
 **download** | **bool** | Download a csv of the results (default: false) | 

### Return type

[**SearchDataUses200Response**](SearchDataUses200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

