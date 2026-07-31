# \SearchToolsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchTools**](SearchToolsAPI.md#SearchTools) | **Post** /api/v1/search/tools | Search@tools



## SearchTools

> SearchTools200Response SearchTools(ctx).SearchToolsRequest(searchToolsRequest).Sort(sort).Direction(direction).Execute()

Search@tools



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
	searchToolsRequest := *openapiclient.NewSearchToolsRequest() // SearchToolsRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchToolsAPI.SearchTools(context.Background()).SearchToolsRequest(searchToolsRequest).Sort(sort).Direction(direction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchToolsAPI.SearchTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchTools`: SearchTools200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchToolsAPI.SearchTools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchToolsRequest** | [**SearchToolsRequest**](SearchToolsRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 

### Return type

[**SearchTools200Response**](SearchTools200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

