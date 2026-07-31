# \SearchDataCustodianNetworksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchDataCustodianNetworks**](SearchDataCustodianNetworksAPI.md#SearchDataCustodianNetworks) | **Post** /api/v1/search/data_custodian_networks | Search@data_custodian_networks



## SearchDataCustodianNetworks

> SearchDataCustodianNetworks200Response SearchDataCustodianNetworks(ctx).SearchDataCustodianNetworksRequest(searchDataCustodianNetworksRequest).Sort(sort).Direction(direction).Execute()

Search@data_custodian_networks



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
	searchDataCustodianNetworksRequest := *openapiclient.NewSearchDataCustodianNetworksRequest() // SearchDataCustodianNetworksRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchDataCustodianNetworksAPI.SearchDataCustodianNetworks(context.Background()).SearchDataCustodianNetworksRequest(searchDataCustodianNetworksRequest).Sort(sort).Direction(direction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchDataCustodianNetworksAPI.SearchDataCustodianNetworks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchDataCustodianNetworks`: SearchDataCustodianNetworks200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchDataCustodianNetworksAPI.SearchDataCustodianNetworks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchDataCustodianNetworksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchDataCustodianNetworksRequest** | [**SearchDataCustodianNetworksRequest**](SearchDataCustodianNetworksRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 

### Return type

[**SearchDataCustodianNetworks200Response**](SearchDataCustodianNetworks200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

