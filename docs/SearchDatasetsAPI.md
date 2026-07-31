# \SearchDatasetsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchDatasets**](SearchDatasetsAPI.md#SearchDatasets) | **Post** /api/v1/search/datasets | Search@datasets



## SearchDatasets

> SearchDatasets200Response SearchDatasets(ctx).SearchDatasetsRequest(searchDatasetsRequest).Execute()

Search@datasets



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
	searchDatasetsRequest := *openapiclient.NewSearchDatasetsRequest() // SearchDatasetsRequest | Submit search query

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchDatasetsAPI.SearchDatasets(context.Background()).SearchDatasetsRequest(searchDatasetsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchDatasetsAPI.SearchDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchDatasets`: SearchDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchDatasetsAPI.SearchDatasets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchDatasetsRequest** | [**SearchDatasetsRequest**](SearchDatasetsRequest.md) | Submit search query | 

### Return type

[**SearchDatasets200Response**](SearchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

