# \DatasetLinkCheckResultsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchDatasetLinkCheckResultsV2**](DatasetLinkCheckResultsAPI.md#FetchDatasetLinkCheckResultsV2) | **Get** /api/v2/dataset_link_check_results | DatasetLinkCheckResultController@index



## FetchDatasetLinkCheckResultsV2

> FetchDatasetLinkCheckResultsV2200Response FetchDatasetLinkCheckResultsV2(ctx).Execute()

DatasetLinkCheckResultController@index



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetLinkCheckResultsAPI.FetchDatasetLinkCheckResultsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetLinkCheckResultsAPI.FetchDatasetLinkCheckResultsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasetLinkCheckResultsV2`: FetchDatasetLinkCheckResultsV2200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetLinkCheckResultsAPI.FetchDatasetLinkCheckResultsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetLinkCheckResultsV2Request struct via the builder pattern


### Return type

[**FetchDatasetLinkCheckResultsV2200Response**](FetchDatasetLinkCheckResultsV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

