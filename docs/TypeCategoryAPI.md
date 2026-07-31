# \TypeCategoryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTypeCategories**](TypeCategoryAPI.md#CreateTypeCategories) | **Post** /api/v1/type_categories | TypeCategory@store
[**DeleteTypeCategories**](TypeCategoryAPI.md#DeleteTypeCategories) | **Delete** /api/v1/type_categories/{id} | TypeCategory@destroy
[**EditTypeCategories**](TypeCategoryAPI.md#EditTypeCategories) | **Patch** /api/v1/type_categories/{id} | TypeCategory@update
[**FetchAllTypeCategories**](TypeCategoryAPI.md#FetchAllTypeCategories) | **Get** /api/v1/type_categories | TypeCategory@index
[**FetchTypeCategories**](TypeCategoryAPI.md#FetchTypeCategories) | **Get** /api/v1/type_categories/{id} | TypeCategory@show
[**UpdateTypeCategories**](TypeCategoryAPI.md#UpdateTypeCategories) | **Put** /api/v1/type_categories/{id} | TypeCategory@update



## CreateTypeCategories

> CreateCategories200Response CreateTypeCategories(ctx).CreateTypeCategoriesRequest(createTypeCategoriesRequest).Execute()

TypeCategory@store



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
	createTypeCategoriesRequest := *openapiclient.NewCreateTypeCategoriesRequest("Name", true) // CreateTypeCategoriesRequest | Programming language definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TypeCategoryAPI.CreateTypeCategories(context.Background()).CreateTypeCategoriesRequest(createTypeCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.CreateTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTypeCategories`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.CreateTypeCategories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTypeCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTypeCategoriesRequest** | [**CreateTypeCategoriesRequest**](CreateTypeCategoriesRequest.md) | Programming language definition | 

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


## DeleteTypeCategories

> DeleteAliases200Response DeleteTypeCategories(ctx, id).Execute()

TypeCategory@destroy



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
	id := int32(1) // int32 | type category id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TypeCategoryAPI.DeleteTypeCategories(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.DeleteTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTypeCategories`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.DeleteTypeCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | type category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTypeCategoriesRequest struct via the builder pattern


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


## EditTypeCategories

> UpdateTypeCategories200Response EditTypeCategories(ctx, id).EditCategoriesRequest(editCategoriesRequest).Execute()

TypeCategory@update



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
	id := int32(1) // int32 | type category id
	editCategoriesRequest := *openapiclient.NewEditCategoriesRequest() // EditCategoriesRequest | TypeCategory definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TypeCategoryAPI.EditTypeCategories(context.Background(), id).EditCategoriesRequest(editCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.EditTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditTypeCategories`: UpdateTypeCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.EditTypeCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | type category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditTypeCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | TypeCategory definition | 

### Return type

[**UpdateTypeCategories200Response**](UpdateTypeCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllTypeCategories

> FetchAllTypeCategories200Response FetchAllTypeCategories(ctx).Execute()

TypeCategory@index



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
	resp, r, err := apiClient.TypeCategoryAPI.FetchAllTypeCategories(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.FetchAllTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllTypeCategories`: FetchAllTypeCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.FetchAllTypeCategories`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllTypeCategoriesRequest struct via the builder pattern


### Return type

[**FetchAllTypeCategories200Response**](FetchAllTypeCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTypeCategories

> FetchTypeCategories200Response FetchTypeCategories(ctx, id).Execute()

TypeCategory@show



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
	id := int32(1) // int32 | type category id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TypeCategoryAPI.FetchTypeCategories(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.FetchTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTypeCategories`: FetchTypeCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.FetchTypeCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | type category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTypeCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchTypeCategories200Response**](FetchTypeCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTypeCategories

> UpdateTypeCategories200Response UpdateTypeCategories(ctx, id).UpdateTypeCategoriesRequest(updateTypeCategoriesRequest).Execute()

TypeCategory@update



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
	id := int32(1) // int32 | type category id
	updateTypeCategoriesRequest := *openapiclient.NewUpdateTypeCategoriesRequest("Name", "true") // UpdateTypeCategoriesRequest | TypeCategory definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TypeCategoryAPI.UpdateTypeCategories(context.Background(), id).UpdateTypeCategoriesRequest(updateTypeCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TypeCategoryAPI.UpdateTypeCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTypeCategories`: UpdateTypeCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TypeCategoryAPI.UpdateTypeCategories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | type category id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTypeCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateTypeCategoriesRequest** | [**UpdateTypeCategoriesRequest**](UpdateTypeCategoriesRequest.md) | TypeCategory definition | 

### Return type

[**UpdateTypeCategories200Response**](UpdateTypeCategories200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

