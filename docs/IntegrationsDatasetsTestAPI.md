# \IntegrationsDatasetsTestAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IntegrationsDatasetsTest**](IntegrationsDatasetsTestAPI.md#IntegrationsDatasetsTest) | **Post** /api/v1/integrations/datasets/test | IntegrationDatasetController@datasetTest



## IntegrationsDatasetsTest

> CreateDarIntegration201Response IntegrationsDatasetsTest(ctx).DatasetsTestRequest(datasetsTestRequest).Execute()

IntegrationDatasetController@datasetTest



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
	resp, r, err := apiClient.IntegrationsDatasetsTestAPI.IntegrationsDatasetsTest(context.Background()).DatasetsTestRequest(datasetsTestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsDatasetsTestAPI.IntegrationsDatasetsTest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsDatasetsTest`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsDatasetsTestAPI.IntegrationsDatasetsTest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsDatasetsTestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datasetsTestRequest** | [**DatasetsTestRequest**](DatasetsTestRequest.md) | Pass datasets payload | 

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

