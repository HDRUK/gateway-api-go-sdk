# \SearchCollectionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchCollections**](SearchCollectionsAPI.md#SearchCollections) | **Post** /api/v1/search/collections | Search@collections



## SearchCollections

> SearchCollections200Response SearchCollections(ctx).SearchCollectionsRequest(searchCollectionsRequest).Sort(sort).Direction(direction).Execute()

Search@collections



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
	searchCollectionsRequest := *openapiclient.NewSearchCollectionsRequest() // SearchCollectionsRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchCollectionsAPI.SearchCollections(context.Background()).SearchCollectionsRequest(searchCollectionsRequest).Sort(sort).Direction(direction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchCollectionsAPI.SearchCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchCollections`: SearchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchCollectionsAPI.SearchCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchCollectionsRequest** | [**SearchCollectionsRequest**](SearchCollectionsRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 

### Return type

[**SearchCollections200Response**](SearchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

