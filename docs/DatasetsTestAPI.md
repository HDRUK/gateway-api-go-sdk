# \DatasetsTestAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DatasetsTest**](DatasetsTestAPI.md#DatasetsTest) | **Post** /api/v1/datasets/test | DatasetController@datasetTest



## DatasetsTest

> CreateCategories200Response DatasetsTest(ctx).DatasetsTestRequest(datasetsTestRequest).Execute()

DatasetController@datasetTest



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
	datasetsTestRequest := *openapiclient.NewDatasetsTestRequest() // DatasetsTestRequest | Pass datasets payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsTestAPI.DatasetsTest(context.Background()).DatasetsTestRequest(datasetsTestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsTestAPI.DatasetsTest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DatasetsTest`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsTestAPI.DatasetsTest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDatasetsTestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datasetsTestRequest** | [**DatasetsTestRequest**](DatasetsTestRequest.md) | Pass datasets payload | 

### Return type

[**CreateCategories200Response**](CreateCategories200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

