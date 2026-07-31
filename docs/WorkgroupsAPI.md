# \WorkgroupsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchAllWorkgroups**](WorkgroupsAPI.md#FetchAllWorkgroups) | **Get** /api/v1/workgroups | WorkgroupController@index



## FetchAllWorkgroups

> FetchAllWorkgroups200Response FetchAllWorkgroups(ctx).Execute()

WorkgroupController@index



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
	resp, r, err := apiClient.WorkgroupsAPI.FetchAllWorkgroups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkgroupsAPI.FetchAllWorkgroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllWorkgroups`: FetchAllWorkgroups200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkgroupsAPI.FetchAllWorkgroups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllWorkgroupsRequest struct via the builder pattern


### Return type

[**FetchAllWorkgroups200Response**](FetchAllWorkgroups200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

