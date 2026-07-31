# \DataCustodianNetworksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDataCustodianNetwork**](DataCustodianNetworksAPI.md#CreateDataCustodianNetwork) | **Post** /api/v2/data_custodian_networks | DataCustodianNetworks@store
[**DeleteDataCustodianNetwork**](DataCustodianNetworksAPI.md#DeleteDataCustodianNetwork) | **Delete** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@destroy
[**EditDataCustodianNetwork**](DataCustodianNetworksAPI.md#EditDataCustodianNetwork) | **Patch** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@edit
[**FetchDataCustodianNetwork**](DataCustodianNetworksAPI.md#FetchDataCustodianNetwork) | **Get** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@show
[**FetchDataCustodianNetworkCustodiansSummary**](DataCustodianNetworksAPI.md#FetchDataCustodianNetworkCustodiansSummary) | **Get** /api/v2/data_custodian_networks/{id}/custodians_summary | DataCustodianNetworks@showCustodiansSummary
[**FetchDataCustodianNetworkDatasetsSummary**](DataCustodianNetworksAPI.md#FetchDataCustodianNetworkDatasetsSummary) | **Get** /api/v2/data_custodian_networks/{id}/datasets_summary | DataCustodianNetworks@showDatasetsSummary
[**FetchDataCustodianNetworkEntitiesSummary**](DataCustodianNetworksAPI.md#FetchDataCustodianNetworkEntitiesSummary) | **Get** /api/v2/data_custodian_networks/{id}/entities_summary | DataCustodianNetworks@showSummary
[**FetchDataCustodianNetworkInfo**](DataCustodianNetworksAPI.md#FetchDataCustodianNetworkInfo) | **Get** /api/v2/data_custodian_networks/{id}/info | DataCustodianNetworks@showInfoSummary
[**FetchDataCustodianNetworks**](DataCustodianNetworksAPI.md#FetchDataCustodianNetworks) | **Get** /api/v2/data_custodian_networks | DataCustodianNetworks@index
[**UpdateDataCustodianNetwork**](DataCustodianNetworksAPI.md#UpdateDataCustodianNetwork) | **Put** /api/v2/data_custodian_networks/{id} | DataCustodianNetworks@update



## CreateDataCustodianNetwork

> CreateCategories200Response CreateDataCustodianNetwork(ctx).CreateDataProviderCollRequest(createDataProviderCollRequest).Execute()

DataCustodianNetworks@store



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
	createDataProviderCollRequest := *openapiclient.NewCreateDataProviderCollRequest("Name", "Summary", true, []int32{int32(123)}) // CreateDataProviderCollRequest | DataCustodianNetwork definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.CreateDataCustodianNetwork(context.Background()).CreateDataProviderCollRequest(createDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.CreateDataCustodianNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDataCustodianNetwork`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.CreateDataCustodianNetwork`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDataCustodianNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDataProviderCollRequest** | [**CreateDataProviderCollRequest**](CreateDataProviderCollRequest.md) | DataCustodianNetwork definition | 

### Return type

[**CreateCategories200Response**](CreateCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDataCustodianNetwork

> DeleteAliases200Response DeleteDataCustodianNetwork(ctx, id).Execute()

DataCustodianNetworks@destroy



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
	id := int32(1) // int32 | DataCustodianNetwork ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.DeleteDataCustodianNetwork(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.DeleteDataCustodianNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDataCustodianNetwork`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.DeleteDataCustodianNetwork`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDataCustodianNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditDataCustodianNetwork

> UpdateDataCustodianNetwork200Response EditDataCustodianNetwork(ctx, id).EditDataProviderCollRequest(editDataProviderCollRequest).Execute()

DataCustodianNetworks@edit



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
	id := int32(1) // int32 | DataCustodianNetwork ID
	editDataProviderCollRequest := *openapiclient.NewEditDataProviderCollRequest() // EditDataProviderCollRequest | DataCustodianNetwork definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.EditDataCustodianNetwork(context.Background(), id).EditDataProviderCollRequest(editDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.EditDataCustodianNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDataCustodianNetwork`: UpdateDataCustodianNetwork200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.EditDataCustodianNetwork`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDataCustodianNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editDataProviderCollRequest** | [**EditDataProviderCollRequest**](EditDataProviderCollRequest.md) | DataCustodianNetwork definition | 

### Return type

[**UpdateDataCustodianNetwork200Response**](UpdateDataCustodianNetwork200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetwork

> FetchDataCustodianNetwork200Response FetchDataCustodianNetwork(ctx, id).Execute()

DataCustodianNetworks@show



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
	id := int32(1) // int32 | DataCustodianNetwork ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetwork(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetwork`: FetchDataCustodianNetwork200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetwork`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataCustodianNetwork200Response**](FetchDataCustodianNetwork200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetworkCustodiansSummary

> FetchDataCustodianNetworkCustodiansSummary200Response FetchDataCustodianNetworkCustodiansSummary(ctx, id).Execute()

DataCustodianNetworks@showCustodiansSummary



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
	id := int32(1) // int32 | DataCustodianNetwork ID - summary

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetworkCustodiansSummary(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetworkCustodiansSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetworkCustodiansSummary`: FetchDataCustodianNetworkCustodiansSummary200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetworkCustodiansSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID - summary | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworkCustodiansSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataCustodianNetworkCustodiansSummary200Response**](FetchDataCustodianNetworkCustodiansSummary200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetworkDatasetsSummary

> FetchDataCustodianNetworkDatasetsSummary200Response FetchDataCustodianNetworkDatasetsSummary(ctx, id).Execute()

DataCustodianNetworks@showDatasetsSummary



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
	id := int32(1) // int32 | DataCustodianNetwork ID - summary

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetworkDatasetsSummary(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetworkDatasetsSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetworkDatasetsSummary`: FetchDataCustodianNetworkDatasetsSummary200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetworkDatasetsSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID - summary | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworkDatasetsSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataCustodianNetworkDatasetsSummary200Response**](FetchDataCustodianNetworkDatasetsSummary200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetworkEntitiesSummary

> FetchDataCustodianNetworkEntitiesSummary200Response FetchDataCustodianNetworkEntitiesSummary(ctx, id).Execute()

DataCustodianNetworks@showSummary



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
	id := int32(1) // int32 | DataCustodianNetwork ID - summary

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetworkEntitiesSummary(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetworkEntitiesSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetworkEntitiesSummary`: FetchDataCustodianNetworkEntitiesSummary200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetworkEntitiesSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID - summary | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworkEntitiesSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataCustodianNetworkEntitiesSummary200Response**](FetchDataCustodianNetworkEntitiesSummary200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetworkInfo

> FetchDataCustodianNetworkInfo200Response FetchDataCustodianNetworkInfo(ctx, id).Execute()

DataCustodianNetworks@showInfoSummary



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
	id := int32(1) // int32 | DataCustodianNetwork ID - summary

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetworkInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetworkInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetworkInfo`: FetchDataCustodianNetworkInfo200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetworkInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetwork ID - summary | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworkInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDataCustodianNetworkInfo200Response**](FetchDataCustodianNetworkInfo200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodianNetworks

> FetchDataCustodianNetworks200Response FetchDataCustodianNetworks(ctx).PerPage(perPage).Execute()

DataCustodianNetworks@index



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
	resp, r, err := apiClient.DataCustodianNetworksAPI.FetchDataCustodianNetworks(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.FetchDataCustodianNetworks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodianNetworks`: FetchDataCustodianNetworks200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.FetchDataCustodianNetworks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodianNetworksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

### Return type

[**FetchDataCustodianNetworks200Response**](FetchDataCustodianNetworks200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDataCustodianNetwork

> UpdateDataCustodianNetwork200Response UpdateDataCustodianNetwork(ctx, id).UpdateDataProviderCollRequest(updateDataProviderCollRequest).Execute()

DataCustodianNetworks@update



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
	id := int32(1) // int32 | DataCustodianNetworks ID
	updateDataProviderCollRequest := *openapiclient.NewUpdateDataProviderCollRequest("Name", "Summary", "true", []int32{int32(123)}) // UpdateDataProviderCollRequest | DataCustodianNetwork definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataCustodianNetworksAPI.UpdateDataCustodianNetwork(context.Background(), id).UpdateDataProviderCollRequest(updateDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataCustodianNetworksAPI.UpdateDataCustodianNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDataCustodianNetwork`: UpdateDataCustodianNetwork200Response
	fmt.Fprintf(os.Stdout, "Response from `DataCustodianNetworksAPI.UpdateDataCustodianNetwork`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataCustodianNetworks ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDataCustodianNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDataProviderCollRequest** | [**UpdateDataProviderCollRequest**](UpdateDataProviderCollRequest.md) | DataCustodianNetwork definition | 

### Return type

[**UpdateDataCustodianNetwork200Response**](UpdateDataCustodianNetwork200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

