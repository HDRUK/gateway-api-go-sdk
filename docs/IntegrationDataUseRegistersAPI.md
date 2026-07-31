# \IntegrationDataUseRegistersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDurIntegrations**](IntegrationDataUseRegistersAPI.md#CreateDurIntegrations) | **Post** /api/v1/integrations/dur | IntegrationDurController@store
[**DeleteDurIntegrations**](IntegrationDataUseRegistersAPI.md#DeleteDurIntegrations) | **Delete** /api/v1/integrations/dur/{id} | Delete a dur
[**EditDurIntegrations**](IntegrationDataUseRegistersAPI.md#EditDurIntegrations) | **Patch** /api/v1/integrations/dur/{id} | Edit a dur
[**FetchAllDurIntegrations**](IntegrationDataUseRegistersAPI.md#FetchAllDurIntegrations) | **Get** /api/v1/integrations/dur | IntegrationDurController@index
[**FetchDurByIdIntegrations**](IntegrationDataUseRegistersAPI.md#FetchDurByIdIntegrations) | **Get** /api/v1/integrations/dur/{id} | IntegrationDurController@show
[**UpdateDurIntegrations**](IntegrationDataUseRegistersAPI.md#UpdateDurIntegrations) | **Put** /api/v1/integrations/dur/{id} | Update a dur by id



## CreateDurIntegrations

> CreateCategories200Response CreateDurIntegrations(ctx).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()

IntegrationDurController@store



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
	createDurIntegrationsRequest := *openapiclient.NewCreateDurIntegrationsRequest() // CreateDurIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.CreateDurIntegrations(context.Background()).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.CreateDurIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDurIntegrations`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.CreateDurIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDurIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials | 

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


## DeleteDurIntegrations

> DeleteAliases200Response DeleteDurIntegrations(ctx, id).Execute()

Delete a dur



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
	id := int32(1) // int32 | dur id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.DeleteDurIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.DeleteDurIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDurIntegrations`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.DeleteDurIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDurIntegrationsRequest struct via the builder pattern


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


## EditDurIntegrations

> UpdateDurIntegrations200Response EditDurIntegrations(ctx, id).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()

Edit a dur



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
	id := int32(1) // int32 | dur id
	createDurIntegrationsRequest := *openapiclient.NewCreateDurIntegrationsRequest() // CreateDurIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.EditDurIntegrations(context.Background(), id).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.EditDurIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDurIntegrations`: UpdateDurIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.EditDurIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDurIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials | 

### Return type

[**UpdateDurIntegrations200Response**](UpdateDurIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDurIntegrations

> FetchAllDurIntegrations200Response FetchAllDurIntegrations(ctx).Sort(sort).PerPage(perPage).Execute()

IntegrationDurController@index



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
	sort := TODO // ProjectTitleAscupdatedAtAsc | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.FetchAllDurIntegrations(context.Background()).Sort(sort).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.FetchAllDurIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDurIntegrations`: FetchAllDurIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.FetchAllDurIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDurIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllDurIntegrations200Response**](FetchAllDurIntegrations200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDurByIdIntegrations

> FetchDurByIdIntegrations200Response FetchDurByIdIntegrations(ctx, id).Execute()

IntegrationDurController@show



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
	id := int32(1) // int32 | data use register id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.FetchDurByIdIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.FetchDurByIdIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDurByIdIntegrations`: FetchDurByIdIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.FetchDurByIdIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | data use register id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDurByIdIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDurByIdIntegrations200Response**](FetchDurByIdIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDurIntegrations

> UpdateDurIntegrations200Response UpdateDurIntegrations(ctx, id).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()

Update a dur by id



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
	id := int32(1) // int32 | dur id
	createDurIntegrationsRequest := *openapiclient.NewCreateDurIntegrationsRequest() // CreateDurIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationDataUseRegistersAPI.UpdateDurIntegrations(context.Background(), id).CreateDurIntegrationsRequest(createDurIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationDataUseRegistersAPI.UpdateDurIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDurIntegrations`: UpdateDurIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationDataUseRegistersAPI.UpdateDurIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDurIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDurIntegrationsRequest** | [**CreateDurIntegrationsRequest**](CreateDurIntegrationsRequest.md) | Pass user credentials | 

### Return type

[**UpdateDurIntegrations200Response**](UpdateDurIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

