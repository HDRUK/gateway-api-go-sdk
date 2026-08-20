# \NightlyDatasetTestsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchNightlyDatasetTestsV2**](NightlyDatasetTestsAPI.md#FetchNightlyDatasetTestsV2) | **Get** /api/v2/nightly_dataset_tests | NightlyDatasetTestController@index



## FetchNightlyDatasetTestsV2

> FetchDatasetLinkCheckResultsV2200Response FetchNightlyDatasetTestsV2(ctx).Execute()

NightlyDatasetTestController@index



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
	resp, r, err := apiClient.NightlyDatasetTestsAPI.FetchNightlyDatasetTestsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NightlyDatasetTestsAPI.FetchNightlyDatasetTestsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchNightlyDatasetTestsV2`: FetchDatasetLinkCheckResultsV2200Response
	fmt.Fprintf(os.Stdout, "Response from `NightlyDatasetTestsAPI.FetchNightlyDatasetTestsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchNightlyDatasetTestsV2Request struct via the builder pattern


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

