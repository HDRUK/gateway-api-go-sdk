# \DataAccessSectionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDarSection**](DataAccessSectionAPI.md#CreateDarSection) | **Post** /api/v1/dar/sections | DataAccessSection@store
[**DeleteDarSection**](DataAccessSectionAPI.md#DeleteDarSection) | **Delete** /api/v1/dar/sections/{id} | DataAccessSection@destroy
[**PatchDarSection**](DataAccessSectionAPI.md#PatchDarSection) | **Patch** /api/v1/dar/sections/{id} | DataAccessSection@update
[**UpdateDarSection**](DataAccessSectionAPI.md#UpdateDarSection) | **Put** /api/v1/dar/sections/{id} | DataAccessSection@update



## CreateDarSection

> CreateDarIntegration201Response CreateDarSection(ctx).CreateDarSectionRequest(createDarSectionRequest).Execute()

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
	// response from `CreateDarSection`: CreateDarIntegration201Response
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

[**CreateDarIntegration201Response**](CreateDarIntegration201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDarSection

> DeleteApplications200Response DeleteDarSection(ctx, id).Execute()

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
	// response from `DeleteDarSection`: DeleteApplications200Response
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

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDarSection

> UpdateDarSection200Response PatchDarSection(ctx, id).PatchDarSectionRequest(patchDarSectionRequest).Execute()

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
	// response from `PatchDarSection`: UpdateDarSection200Response
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

[**UpdateDarSection200Response**](UpdateDarSection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDarSection

> UpdateDarSection200Response UpdateDarSection(ctx, id).CreateDarSectionRequest(createDarSectionRequest).Execute()

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
	// response from `UpdateDarSection`: UpdateDarSection200Response
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

[**UpdateDarSection200Response**](UpdateDarSection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

