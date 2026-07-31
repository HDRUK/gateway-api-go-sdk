# \AdminSearchAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAdminSearchReindex**](AdminSearchAPI.md#CreateAdminSearchReindex) | **Post** /api/v1/admin/search/reindex | Queue a drop+recreate+import of a search entity&#39;s Typesense collection
[**FetchAdminSearchStatus**](AdminSearchAPI.md#FetchAdminSearchStatus) | **Get** /api/v1/admin/search/status | Get Typesense collection status for every onboarded search entity
[**UpdateAdminSearchFeature**](AdminSearchAPI.md#UpdateAdminSearchFeature) | **Post** /api/v1/admin/search/feature | Activate or deactivate a search-related Pennant feature flag



## CreateAdminSearchReindex

> CreateAdminSearchReindex(ctx).CreateAdminSearchReindexRequest(createAdminSearchReindexRequest).Execute()

Queue a drop+recreate+import of a search entity's Typesense collection

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
	createAdminSearchReindexRequest := *openapiclient.NewCreateAdminSearchReindexRequest() // CreateAdminSearchReindexRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminSearchAPI.CreateAdminSearchReindex(context.Background()).CreateAdminSearchReindexRequest(createAdminSearchReindexRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminSearchAPI.CreateAdminSearchReindex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAdminSearchReindexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAdminSearchReindexRequest** | [**CreateAdminSearchReindexRequest**](CreateAdminSearchReindexRequest.md) |  | 

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


## FetchAdminSearchStatus

> FetchAdminSearchStatus(ctx).Execute()

Get Typesense collection status for every onboarded search entity

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
	r, err := apiClient.AdminSearchAPI.FetchAdminSearchStatus(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminSearchAPI.FetchAdminSearchStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAdminSearchStatusRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAdminSearchFeature

> UpdateAdminSearchFeature(ctx).UpdateAdminSearchFeatureRequest(updateAdminSearchFeatureRequest).Execute()

Activate or deactivate a search-related Pennant feature flag

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
	updateAdminSearchFeatureRequest := *openapiclient.NewUpdateAdminSearchFeatureRequest() // UpdateAdminSearchFeatureRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminSearchAPI.UpdateAdminSearchFeature(context.Background()).UpdateAdminSearchFeatureRequest(updateAdminSearchFeatureRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminSearchAPI.UpdateAdminSearchFeature``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAdminSearchFeatureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateAdminSearchFeatureRequest** | [**UpdateAdminSearchFeatureRequest**](UpdateAdminSearchFeatureRequest.md) |  | 

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

