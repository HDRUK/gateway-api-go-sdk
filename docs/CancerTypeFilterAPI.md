# \CancerTypeFilterAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCancerTypeFilter**](CancerTypeFilterAPI.md#GetCancerTypeFilter) | **Get** /api/v1/cancer-type-filters/{filter_id} | Get a single cancer type filter
[**GetCancerTypeFilters**](CancerTypeFilterAPI.md#GetCancerTypeFilters) | **Get** /api/v1/cancer-type-filters | Get all cancer type filters



## GetCancerTypeFilter

> GetCancerTypeFilter200Response GetCancerTypeFilter(ctx, filterId).Execute()

Get a single cancer type filter



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
	filterId := "0_0_2_59" // string | Filter ID (e.g., 0_0, 0_0_2_59)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CancerTypeFilterAPI.GetCancerTypeFilter(context.Background(), filterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CancerTypeFilterAPI.GetCancerTypeFilter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCancerTypeFilter`: GetCancerTypeFilter200Response
	fmt.Fprintf(os.Stdout, "Response from `CancerTypeFilterAPI.GetCancerTypeFilter`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**filterId** | **string** | Filter ID (e.g., 0_0, 0_0_2_59) | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCancerTypeFilterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetCancerTypeFilter200Response**](GetCancerTypeFilter200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCancerTypeFilters

> GetCancerTypeFilters200Response GetCancerTypeFilters(ctx).ParentId(parentId).Level(level).Execute()

Get all cancer type filters



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
	parentId := int32(56) // int32 | Filter by parent ID (optional)
	level := int32(56) // int32 | Filter by hierarchy level (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CancerTypeFilterAPI.GetCancerTypeFilters(context.Background()).ParentId(parentId).Level(level).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CancerTypeFilterAPI.GetCancerTypeFilters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCancerTypeFilters`: GetCancerTypeFilters200Response
	fmt.Fprintf(os.Stdout, "Response from `CancerTypeFilterAPI.GetCancerTypeFilters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCancerTypeFiltersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **parentId** | **int32** | Filter by parent ID | 
 **level** | **int32** | Filter by hierarchy level | 

### Return type

[**GetCancerTypeFilters200Response**](GetCancerTypeFilters200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

