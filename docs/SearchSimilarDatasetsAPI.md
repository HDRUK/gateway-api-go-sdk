# \SearchSimilarDatasetsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchSimilarDatasets**](SearchSimilarDatasetsAPI.md#SearchSimilarDatasets) | **Post** /api/v1/search/similar/datasets | Search@similarDatasets



## SearchSimilarDatasets

> SearchSimilarDatasets200Response SearchSimilarDatasets(ctx).SearchSimilarDatasetsRequest(searchSimilarDatasetsRequest).Execute()

Search@similarDatasets



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
	searchSimilarDatasetsRequest := *openapiclient.NewSearchSimilarDatasetsRequest() // SearchSimilarDatasetsRequest | Submit dataset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchSimilarDatasetsAPI.SearchSimilarDatasets(context.Background()).SearchSimilarDatasetsRequest(searchSimilarDatasetsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchSimilarDatasetsAPI.SearchSimilarDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchSimilarDatasets`: SearchSimilarDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchSimilarDatasetsAPI.SearchSimilarDatasets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchSimilarDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchSimilarDatasetsRequest** | [**SearchSimilarDatasetsRequest**](SearchSimilarDatasetsRequest.md) | Submit dataset id | 

### Return type

[**SearchSimilarDatasets200Response**](SearchSimilarDatasets200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

