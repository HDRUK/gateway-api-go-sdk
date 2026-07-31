# \CategoryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCategories**](CategoryAPI.md#CreateCategories) | **Post** /api/v1/categories | Category@store
[**DeleteCategories**](CategoryAPI.md#DeleteCategories) | **Delete** /api/v1/categories/{id} | Category@destroy
[**EditCategories**](CategoryAPI.md#EditCategories) | **Patch** /api/v1/categories/{id} | Category@update
[**FetchAllCategories**](CategoryAPI.md#FetchAllCategories) | **Get** /api/v1/categories | Category@index
[**FetchCategories**](CategoryAPI.md#FetchCategories) | **Get** /api/v1/categories/{id} | Category@show
[**UpdateCategories**](CategoryAPI.md#UpdateCategories) | **Put** /api/v1/categories/{id} | Category@update



## CreateCategories

> CreateCategories200Response CreateCategories(ctx).CreateCategoriesRequest(createCategoriesRequest).Execute()

Category@store



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
	createCategoriesRequest := *openapiclient.NewCreateCategoriesRequest("Name", true) // CreateCategoriesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CategoryAPI.CreateCategories(context.Background()).CreateCategoriesRequest(createCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.CreateCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCategories`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.CreateCategories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Category definition | 

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


## DeleteCategories

> DeleteAliases200Response DeleteCategories(ctx, id).Execute()

Category@destroy



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
	id := int32(1) // int32 | category id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CategoryAPI.DeleteCategories(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.DeleteCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCategories`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.DeleteCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCategoriesRequest struct via the builder pattern


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


## EditCategories

> UpdateCategories200Response EditCategories(ctx, id).EditCategoriesRequest(editCategoriesRequest).Execute()

Category@update



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
	id := int32(1) // int32 | category id
	editCategoriesRequest := *openapiclient.NewEditCategoriesRequest() // EditCategoriesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CategoryAPI.EditCategories(context.Background(), id).EditCategoriesRequest(editCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.EditCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditCategories`: UpdateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.EditCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | Category definition | 

### Return type

[**UpdateCategories200Response**](UpdateCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllCategories

> FetchAllCategories200Response FetchAllCategories(ctx).PerPage(perPage).Execute()

Category@index



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
	resp, r, err := apiClient.CategoryAPI.FetchAllCategories(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.FetchAllCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCategories`: FetchAllCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.FetchAllCategories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllCategories200Response**](FetchAllCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCategories

> FetchAllCategories200Response FetchCategories(ctx, id).Execute()

Category@show



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
	id := int32(1) // int32 | category id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CategoryAPI.FetchCategories(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.FetchCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCategories`: FetchAllCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.FetchCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCategories200Response**](FetchAllCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCategories

> UpdateCategories200Response UpdateCategories(ctx, id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()

Category@update



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
	id := int32(1) // int32 | category id
	updateCategoriesRequest := *openapiclient.NewUpdateCategoriesRequest("Name", "true") // UpdateCategoriesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CategoryAPI.UpdateCategories(context.Background(), id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CategoryAPI.UpdateCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCategories`: UpdateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CategoryAPI.UpdateCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | Category definition | 

### Return type

[**UpdateCategories200Response**](UpdateCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

