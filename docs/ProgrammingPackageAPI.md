# \ProgrammingPackageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProgrammingPackages**](ProgrammingPackageAPI.md#CreateProgrammingPackages) | **Post** /api/v1/programming_packages | ProgrammingPackage@store
[**DeleteProgrammingPackages**](ProgrammingPackageAPI.md#DeleteProgrammingPackages) | **Delete** /api/v1/programming_packages/{id} | ProgrammingPackage@destroy
[**EditProgrammingPackages**](ProgrammingPackageAPI.md#EditProgrammingPackages) | **Patch** /api/v1/programming_packages/{id} | ProgrammingPackage@update
[**FetchAllProgrammingPackages**](ProgrammingPackageAPI.md#FetchAllProgrammingPackages) | **Get** /api/v1/programming_packages | ProgrammingPackage@index
[**FetchProgrammingPackages**](ProgrammingPackageAPI.md#FetchProgrammingPackages) | **Get** /api/v1/programming_packages/{id} | ProgrammingPackage@show
[**UpdateProgrammingPackages**](ProgrammingPackageAPI.md#UpdateProgrammingPackages) | **Put** /api/v1/programming_packages/{id} | ProgrammingPackage@update



## CreateProgrammingPackages

> CreateCategories200Response CreateProgrammingPackages(ctx).CreateCategoriesRequest(createCategoriesRequest).Execute()

ProgrammingPackage@store



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
	createCategoriesRequest := *openapiclient.NewCreateCategoriesRequest("Name", true) // CreateCategoriesRequest | Programming package definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.CreateProgrammingPackages(context.Background()).CreateCategoriesRequest(createCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.CreateProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProgrammingPackages`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.CreateProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Programming package definition | 

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


## DeleteProgrammingPackages

> DeleteAliases200Response DeleteProgrammingPackages(ctx, id).Execute()

ProgrammingPackage@destroy



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
	id := int32(1) // int32 | programming package id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.DeleteProgrammingPackages(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.DeleteProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProgrammingPackages`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.DeleteProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProgrammingPackagesRequest struct via the builder pattern


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


## EditProgrammingPackages

> UpdateProgrammingPackages200Response EditProgrammingPackages(ctx, id).EditCategoriesRequest(editCategoriesRequest).Execute()

ProgrammingPackage@update



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
	id := int32(1) // int32 | programming package id
	editCategoriesRequest := *openapiclient.NewEditCategoriesRequest() // EditCategoriesRequest | ProgrammingPackage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.EditProgrammingPackages(context.Background(), id).EditCategoriesRequest(editCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.EditProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditProgrammingPackages`: UpdateProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.EditProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | ProgrammingPackage definition | 

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllProgrammingPackages

> FetchAllProgrammingPackages200Response FetchAllProgrammingPackages(ctx).Execute()

ProgrammingPackage@index



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
	resp, r, err := apiClient.ProgrammingPackageAPI.FetchAllProgrammingPackages(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.FetchAllProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllProgrammingPackages`: FetchAllProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.FetchAllProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllProgrammingPackagesRequest struct via the builder pattern


### Return type

[**FetchAllProgrammingPackages200Response**](FetchAllProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchProgrammingPackages

> FetchProgrammingPackages200Response FetchProgrammingPackages(ctx, id).Execute()

ProgrammingPackage@show



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
	id := int32(1) // int32 | programming package id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.FetchProgrammingPackages(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.FetchProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchProgrammingPackages`: FetchProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.FetchProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchProgrammingPackages200Response**](FetchProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProgrammingPackages

> UpdateProgrammingPackages200Response UpdateProgrammingPackages(ctx, id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()

ProgrammingPackage@update



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
	id := int32(1) // int32 | programming package id
	updateCategoriesRequest := *openapiclient.NewUpdateCategoriesRequest("Name", "true") // UpdateCategoriesRequest | ProgrammingPackage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.UpdateProgrammingPackages(context.Background(), id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.UpdateProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProgrammingPackages`: UpdateProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.UpdateProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | ProgrammingPackage definition | 

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

