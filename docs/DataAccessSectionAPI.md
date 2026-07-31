# \DataAccessSectionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDarSection**](DataAccessSectionAPI.md#CreateDarSection) | **Post** /api/v1/dar/sections | DataAccessSection@store
[**DeleteDarSection**](DataAccessSectionAPI.md#DeleteDarSection) | **Delete** /api/v1/dar/sections/{id} | DataAccessSection@destroy
[**FetchDarSection**](DataAccessSectionAPI.md#FetchDarSection) | **Get** /api/v1/dar/sections/{id} | DataAccessSection@show
[**FetchDarSections**](DataAccessSectionAPI.md#FetchDarSections) | **Get** /api/v1/dar/sections | DataAccessSection@index
[**PatchDarSection**](DataAccessSectionAPI.md#PatchDarSection) | **Patch** /api/v1/dar/sections/{id} | DataAccessSection@update
[**UpdateDarSection**](DataAccessSectionAPI.md#UpdateDarSection) | **Put** /api/v1/dar/sections/{id} | DataAccessSection@update



## CreateDarSection

> CreateCategories200Response CreateDarSection(ctx).CreateDarSectionRequest(createDarSectionRequest).Execute()

DataAccessSection@store



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
	createDarSectionRequest := *openapiclient.NewCreateDarSectionRequest("Safe People", "Who has access?", int32(1)) // CreateDarSectionRequest | DataAccessSection definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessSectionAPI.CreateDarSection(context.Background()).CreateDarSectionRequest(createDarSectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.CreateDarSection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDarSection`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.CreateDarSection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDarSectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition | 

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


## DeleteDarSection

> DeleteAliases200Response DeleteDarSection(ctx, id).Execute()

DataAccessSection@destroy



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
	id := int32(1) // int32 | DAR section id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessSectionAPI.DeleteDarSection(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.DeleteDarSection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDarSection`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.DeleteDarSection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR section id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDarSectionRequest struct via the builder pattern


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


## FetchDarSection

> FetchDarSection200Response FetchDarSection(ctx, id).Execute()

DataAccessSection@show



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
	id := int32(1) // int32 | DAR section id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessSectionAPI.FetchDarSection(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.FetchDarSection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarSection`: FetchDarSection200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.FetchDarSection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR section id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarSectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarSections

> FetchDarSections200Response FetchDarSections(ctx).PerPage(perPage).Execute()

DataAccessSection@index



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
	resp, r, err := apiClient.DataAccessSectionAPI.FetchDarSections(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.FetchDarSections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarSections`: FetchDarSections200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.FetchDarSections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarSectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

### Return type

[**FetchDarSections200Response**](FetchDarSections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDarSection

> FetchDarSection200Response PatchDarSection(ctx, id).PatchDarSectionRequest(patchDarSectionRequest).Execute()

DataAccessSection@update



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
	id := int32(1) // int32 | DAR section id
	patchDarSectionRequest := *openapiclient.NewPatchDarSectionRequest() // PatchDarSectionRequest | DataAccessSection definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessSectionAPI.PatchDarSection(context.Background(), id).PatchDarSectionRequest(patchDarSectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.PatchDarSection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDarSection`: FetchDarSection200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.PatchDarSection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR section id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDarSectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchDarSectionRequest** | [**PatchDarSectionRequest**](PatchDarSectionRequest.md) | DataAccessSection definition | 

### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDarSection

> FetchDarSection200Response UpdateDarSection(ctx, id).CreateDarSectionRequest(createDarSectionRequest).Execute()

DataAccessSection@update



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
	id := int32(1) // int32 | DAR section id
	createDarSectionRequest := *openapiclient.NewCreateDarSectionRequest("Safe People", "Who has access?", int32(1)) // CreateDarSectionRequest | DataAccessSection definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessSectionAPI.UpdateDarSection(context.Background(), id).CreateDarSectionRequest(createDarSectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessSectionAPI.UpdateDarSection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDarSection`: FetchDarSection200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessSectionAPI.UpdateDarSection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR section id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDarSectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDarSectionRequest** | [**CreateDarSectionRequest**](CreateDarSectionRequest.md) | DataAccessSection definition | 

### Return type

[**FetchDarSection200Response**](FetchDarSection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

