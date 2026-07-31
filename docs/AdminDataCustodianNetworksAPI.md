# \AdminDataCustodianNetworksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchAdminDataCustodianNetworks**](AdminDataCustodianNetworksAPI.md#FetchAdminDataCustodianNetworks) | **Get** /api/v2/admin/data_custodian_networks | DataCustodianNetworks@adminIndex



## FetchAdminDataCustodianNetworks

> FetchAdminDataCustodianNetworks(ctx).PerPage(perPage).Execute()

DataCustodianNetworks@adminIndex



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
	r, err := apiClient.AdminDataCustodianNetworksAPI.FetchAdminDataCustodianNetworks(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminDataCustodianNetworksAPI.FetchAdminDataCustodianNetworks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAdminDataCustodianNetworksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

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

