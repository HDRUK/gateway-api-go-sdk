# \MetricsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchKeyMetricsV2**](MetricsAPI.md#FetchKeyMetricsV2) | **Get** /api/v2/metrics | KeyMetricController@index



## FetchKeyMetricsV2

> FetchKeyMetricsV2200Response FetchKeyMetricsV2(ctx).Execute()

KeyMetricController@index



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
	resp, r, err := apiClient.MetricsAPI.FetchKeyMetricsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricsAPI.FetchKeyMetricsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchKeyMetricsV2`: FetchKeyMetricsV2200Response
	fmt.Fprintf(os.Stdout, "Response from `MetricsAPI.FetchKeyMetricsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchKeyMetricsV2Request struct via the builder pattern


### Return type

[**FetchKeyMetricsV2200Response**](FetchKeyMetricsV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

