# \DarIntegrationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDarIntegration**](DarIntegrationAPI.md#CreateDarIntegration) | **Post** /api/v1/dar-integration/{id} | DarIntegration@store
[**DeleteDarIntegration**](DarIntegrationAPI.md#DeleteDarIntegration) | **Delete** /api/v1/dar-integrations/{id} | DarIntegration@destroy
[**EditDarIntegration**](DarIntegrationAPI.md#EditDarIntegration) | **Patch** /api/v1/dar-integration/{id} | DarIntegration@edit
[**FetchAllDarIntegrations**](DarIntegrationAPI.md#FetchAllDarIntegrations) | **Get** /api/v1/dar-integration | DarIntegration@index
[**FetchDarIntegration**](DarIntegrationAPI.md#FetchDarIntegration) | **Get** /api/v1/dar-integration/{id} | DarIntegration@show
[**UpdateDarIntegration**](DarIntegrationAPI.md#UpdateDarIntegration) | **Put** /api/v1/dar-integration/{id} | DarIntegration@update



## CreateDarIntegration

> CreateCategories200Response CreateDarIntegration(ctx, id).UpdateDarIntegrationRequest(updateDarIntegrationRequest).Execute()

DarIntegration@store



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
	id := int32(1) // int32 | dar integration id
	updateDarIntegrationRequest := *openapiclient.NewUpdateDarIntegrationRequest(int32(1), "someone@somewhere.com", "OutboundAuthType_example", "OutboundAuthKey_example", "OutboundEndpointsBaseUrl_example", "OutboundEndpointsEnquiry_example", "OutboundEndpoints5safes_example", "OutboundEndpoints5safesFiles_example", "InboundServiceAccountId_example") // UpdateDarIntegrationRequest | DarIntegration definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DarIntegrationAPI.CreateDarIntegration(context.Background(), id).UpdateDarIntegrationRequest(updateDarIntegrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.CreateDarIntegration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDarIntegration`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.CreateDarIntegration`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dar integration id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDarIntegrationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDarIntegrationRequest** | [**UpdateDarIntegrationRequest**](UpdateDarIntegrationRequest.md) | DarIntegration definition | 

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


## DeleteDarIntegration

> DeleteAliases200Response DeleteDarIntegration(ctx, id).Execute()

DarIntegration@destroy



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
	id := int32(1) // int32 | dar integration id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DarIntegrationAPI.DeleteDarIntegration(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.DeleteDarIntegration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDarIntegration`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.DeleteDarIntegration`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dar integration id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDarIntegrationRequest struct via the builder pattern


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


## EditDarIntegration

> UpdateDarIntegration200Response EditDarIntegration(ctx, id).EditDarIntegrationRequest(editDarIntegrationRequest).Execute()

DarIntegration@edit



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
	id := int32(1) // int32 | dar integration id
	editDarIntegrationRequest := *openapiclient.NewEditDarIntegrationRequest() // EditDarIntegrationRequest | DarIntegration definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DarIntegrationAPI.EditDarIntegration(context.Background(), id).EditDarIntegrationRequest(editDarIntegrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.EditDarIntegration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDarIntegration`: UpdateDarIntegration200Response
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.EditDarIntegration`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dar integration id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDarIntegrationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editDarIntegrationRequest** | [**EditDarIntegrationRequest**](EditDarIntegrationRequest.md) | DarIntegration definition | 

### Return type

[**UpdateDarIntegration200Response**](UpdateDarIntegration200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDarIntegrations

> FetchAllDarIntegrations200Response FetchAllDarIntegrations(ctx).Execute()

DarIntegration@index



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
	resp, r, err := apiClient.DarIntegrationAPI.FetchAllDarIntegrations(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.FetchAllDarIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDarIntegrations`: FetchAllDarIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.FetchAllDarIntegrations`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDarIntegrationsRequest struct via the builder pattern


### Return type

[**FetchAllDarIntegrations200Response**](FetchAllDarIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarIntegration

> FetchAllDarIntegrations200ResponseDataInner FetchDarIntegration(ctx, id).Execute()

DarIntegration@show



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
	id := int32(1) // int32 | dar integration id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DarIntegrationAPI.FetchDarIntegration(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.FetchDarIntegration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarIntegration`: FetchAllDarIntegrations200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.FetchDarIntegration`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dar integration id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarIntegrationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllDarIntegrations200ResponseDataInner**](FetchAllDarIntegrations200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDarIntegration

> UpdateDarIntegration200Response UpdateDarIntegration(ctx, id).UpdateDarIntegrationRequest(updateDarIntegrationRequest).Execute()

DarIntegration@update



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
	id := int32(1) // int32 | dar integration id
	updateDarIntegrationRequest := *openapiclient.NewUpdateDarIntegrationRequest(int32(1), "someone@somewhere.com", "OutboundAuthType_example", "OutboundAuthKey_example", "OutboundEndpointsBaseUrl_example", "OutboundEndpointsEnquiry_example", "OutboundEndpoints5safes_example", "OutboundEndpoints5safesFiles_example", "InboundServiceAccountId_example") // UpdateDarIntegrationRequest | DarIntegration definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DarIntegrationAPI.UpdateDarIntegration(context.Background(), id).UpdateDarIntegrationRequest(updateDarIntegrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DarIntegrationAPI.UpdateDarIntegration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDarIntegration`: UpdateDarIntegration200Response
	fmt.Fprintf(os.Stdout, "Response from `DarIntegrationAPI.UpdateDarIntegration`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dar integration id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDarIntegrationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDarIntegrationRequest** | [**UpdateDarIntegrationRequest**](UpdateDarIntegrationRequest.md) | DarIntegration definition | 

### Return type

[**UpdateDarIntegration200Response**](UpdateDarIntegration200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

