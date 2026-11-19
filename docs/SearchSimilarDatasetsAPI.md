# \SearchSimilarDatasetsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchSimilarDatasets**](SearchSimilarDatasetsAPI.md#SearchSimilarDatasets) | **Post** /api/v1/search/similar/datasets | Search for similar datasets (deprecated)
[**SearchSimilarDatasetsV2**](SearchSimilarDatasetsAPI.md#SearchSimilarDatasetsV2) | **Post** /api/v2/search/similar/datasets | Search for similar datasets



## SearchSimilarDatasets

> SearchSimilarDatasets(ctx).SearchSimilarDatasetsV2Request(searchSimilarDatasetsV2Request).Execute()

Search for similar datasets (deprecated)



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
	searchSimilarDatasetsV2Request := *openapiclient.NewSearchSimilarDatasetsV2Request(int32(1)) // SearchSimilarDatasetsV2Request | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SearchSimilarDatasetsAPI.SearchSimilarDatasets(context.Background()).SearchSimilarDatasetsV2Request(searchSimilarDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchSimilarDatasetsAPI.SearchSimilarDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchSimilarDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchSimilarDatasetsV2Request** | [**SearchSimilarDatasetsV2Request**](SearchSimilarDatasetsV2Request.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchSimilarDatasetsV2

> SearchSimilarDatasetsV2200Response SearchSimilarDatasetsV2(ctx).SearchSimilarDatasetsV2Request(searchSimilarDatasetsV2Request).Execute()

Search for similar datasets



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
	searchSimilarDatasetsV2Request := *openapiclient.NewSearchSimilarDatasetsV2Request(int32(1)) // SearchSimilarDatasetsV2Request | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchSimilarDatasetsAPI.SearchSimilarDatasetsV2(context.Background()).SearchSimilarDatasetsV2Request(searchSimilarDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchSimilarDatasetsAPI.SearchSimilarDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchSimilarDatasetsV2`: SearchSimilarDatasetsV2200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchSimilarDatasetsAPI.SearchSimilarDatasetsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchSimilarDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchSimilarDatasetsV2Request** | [**SearchSimilarDatasetsV2Request**](SearchSimilarDatasetsV2Request.md) |  | 

### Return type

[**SearchSimilarDatasetsV2200Response**](SearchSimilarDatasetsV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

