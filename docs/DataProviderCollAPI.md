# \DataProviderCollAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchDataProviderColl**](DataProviderCollAPI.md#FetchDataProviderColl) | **Get** /api/v1/data_provider_colls/{id} | DataProviderColl@show
[**FetchDataProviderCollSummary**](DataProviderCollAPI.md#FetchDataProviderCollSummary) | **Get** /api/v1/data_provider_colls/{id}/summary | DataProviderColl@showSummary
[**FetchDataProviderColls**](DataProviderCollAPI.md#FetchDataProviderColls) | **Get** /api/v1/data_provider_colls | DataProviderColl@index



## FetchDataProviderColl

> FetchDataProviderColl200Response FetchDataProviderColl(ctx, id).Execute()

DataProviderColl@show



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
	id := int32(1) // int32 | DataProviderColl ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.FetchDataProviderColl(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.FetchDataProviderColl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataProviderColl`: FetchDataProviderColl200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.FetchDataProviderColl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataProviderColl ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataProviderCollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataProviderColl200Response**](FetchDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataProviderCollSummary

> FetchDataProviderCollSummary200Response FetchDataProviderCollSummary(ctx, id).Execute()

DataProviderColl@showSummary



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
	id := int32(1) // int32 | DataProviderColl ID - summary

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.FetchDataProviderCollSummary(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.FetchDataProviderCollSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataProviderCollSummary`: FetchDataProviderCollSummary200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.FetchDataProviderCollSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataProviderColl ID - summary | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataProviderCollSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataProviderCollSummary200Response**](FetchDataProviderCollSummary200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataProviderColls

> FetchDataProviderColls200Response FetchDataProviderColls(ctx).PerPage(perPage).Execute()

DataProviderColl@index



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
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.FetchDataProviderColls(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.FetchDataProviderColls``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataProviderColls`: FetchDataProviderColls200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.FetchDataProviderColls`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataProviderCollsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

### Return type

[**FetchDataProviderColls200Response**](FetchDataProviderColls200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

