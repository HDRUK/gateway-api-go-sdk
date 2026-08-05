# \DataProviderCollAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDataProviderColl**](DataProviderCollAPI.md#CreateDataProviderColl) | **Post** /api/v1/data_provider_colls | DataProviderColl@store
[**DeleteDataProviderColl**](DataProviderCollAPI.md#DeleteDataProviderColl) | **Delete** /api/v1/data_provider_colls/{id} | DataProviderColl@destroy
[**EditDataProviderColl**](DataProviderCollAPI.md#EditDataProviderColl) | **Patch** /api/v1/data_provider_colls/{id} | DataProviderColl@edit
[**FetchDataProviderColl**](DataProviderCollAPI.md#FetchDataProviderColl) | **Get** /api/v1/data_provider_colls/{id} | DataProviderColl@show
[**FetchDataProviderCollSummary**](DataProviderCollAPI.md#FetchDataProviderCollSummary) | **Get** /api/v1/data_provider_colls/{id}/summary | DataProviderColl@showSummary
[**FetchDataProviderColls**](DataProviderCollAPI.md#FetchDataProviderColls) | **Get** /api/v1/data_provider_colls | DataProviderColl@index
[**UpdateDataProviderColl**](DataProviderCollAPI.md#UpdateDataProviderColl) | **Put** /api/v1/data_provider_colls/{id} | DataProviderColl@update



## CreateDataProviderColl

> CreateDarIntegration201Response CreateDataProviderColl(ctx).CreateDataProviderCollRequest(createDataProviderCollRequest).Execute()

DataProviderColl@store



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
	createDataProviderCollRequest := *openapiclient.NewCreateDataProviderCollRequest("Name", "Summary", true, []int32{int32(123)}) // CreateDataProviderCollRequest | DataProviderColl definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.CreateDataProviderColl(context.Background()).CreateDataProviderCollRequest(createDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.CreateDataProviderColl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDataProviderColl`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.CreateDataProviderColl`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDataProviderCollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDataProviderCollRequest** | [**CreateDataProviderCollRequest**](CreateDataProviderCollRequest.md) | DataProviderColl definition | 

### Return type

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDataProviderColl

> DeleteApplications200Response DeleteDataProviderColl(ctx, id).Execute()

DataProviderColl@destroy



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
	resp, r, err := apiClient.DataProviderCollAPI.DeleteDataProviderColl(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.DeleteDataProviderColl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDataProviderColl`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.DeleteDataProviderColl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataProviderColl ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDataProviderCollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditDataProviderColl

> UpdateDataProviderColl200Response EditDataProviderColl(ctx, id).EditDataProviderCollRequest(editDataProviderCollRequest).Execute()

DataProviderColl@edit



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
	editDataProviderCollRequest := *openapiclient.NewEditDataProviderCollRequest() // EditDataProviderCollRequest | DataProviderColl definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.EditDataProviderColl(context.Background(), id).EditDataProviderCollRequest(editDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.EditDataProviderColl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDataProviderColl`: UpdateDataProviderColl200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.EditDataProviderColl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataProviderColl ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDataProviderCollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editDataProviderCollRequest** | [**EditDataProviderCollRequest**](EditDataProviderCollRequest.md) | DataProviderColl definition | 

### Return type

[**UpdateDataProviderColl200Response**](UpdateDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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


## UpdateDataProviderColl

> UpdateDataProviderColl200Response UpdateDataProviderColl(ctx, id).UpdateDataProviderCollRequest(updateDataProviderCollRequest).Execute()

DataProviderColl@update



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
	updateDataProviderCollRequest := *openapiclient.NewUpdateDataProviderCollRequest("Name", "Summary", "true", []int32{int32(123)}) // UpdateDataProviderCollRequest | DataProviderColl definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataProviderCollAPI.UpdateDataProviderColl(context.Background(), id).UpdateDataProviderCollRequest(updateDataProviderCollRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataProviderCollAPI.UpdateDataProviderColl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDataProviderColl`: UpdateDataProviderColl200Response
	fmt.Fprintf(os.Stdout, "Response from `DataProviderCollAPI.UpdateDataProviderColl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DataProviderColl ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDataProviderCollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDataProviderCollRequest** | [**UpdateDataProviderCollRequest**](UpdateDataProviderCollRequest.md) | DataProviderColl definition | 

### Return type

[**UpdateDataProviderColl200Response**](UpdateDataProviderColl200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

