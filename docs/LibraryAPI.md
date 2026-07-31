# \LibraryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateLibraries**](LibraryAPI.md#CreateLibraries) | **Post** /api/v1/libraries | Library@store
[**DeleteLibraries**](LibraryAPI.md#DeleteLibraries) | **Delete** /api/v1/libraries/{id} | Library@destroy
[**EditLibraries**](LibraryAPI.md#EditLibraries) | **Patch** /api/v1/libraries/{id} | Library@update
[**FetchLibraries**](LibraryAPI.md#FetchLibraries) | **Get** /api/v1/libraries/{id} | Return a single library
[**ListLibraries**](LibraryAPI.md#ListLibraries) | **Get** /api/v1/libraries | Retrieve a list of libraries
[**UpdateLibraries**](LibraryAPI.md#UpdateLibraries) | **Put** /api/v1/libraries/{id} | Library@update



## CreateLibraries

> CreateCategories200Response CreateLibraries(ctx).CreateLibrariesRequest(createLibrariesRequest).Execute()

Library@store



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
	createLibrariesRequest := *openapiclient.NewCreateLibrariesRequest(int32(123)) // CreateLibrariesRequest | library definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.CreateLibraries(context.Background()).CreateLibrariesRequest(createLibrariesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.CreateLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateLibraries`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.CreateLibraries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateLibrariesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition | 

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


## DeleteLibraries

> DeleteAliases200Response DeleteLibraries(ctx, id).Execute()

Library@destroy



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
	id := int32(1) // int32 | library id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.DeleteLibraries(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.DeleteLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteLibraries`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.DeleteLibraries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | library id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteLibrariesRequest struct via the builder pattern


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


## EditLibraries

> UpdateLibraries200Response EditLibraries(ctx, id).CreateLibrariesRequest(createLibrariesRequest).Execute()

Library@update



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
	id := int32(1) // int32 | library id
	createLibrariesRequest := *openapiclient.NewCreateLibrariesRequest(int32(123)) // CreateLibrariesRequest | library definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.EditLibraries(context.Background(), id).CreateLibrariesRequest(createLibrariesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.EditLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditLibraries`: UpdateLibraries200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.EditLibraries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | library id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditLibrariesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition | 

### Return type

[**UpdateLibraries200Response**](UpdateLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchLibraries

> FetchLibraries200Response FetchLibraries(ctx, id).Execute()

Return a single library



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
	id := int32(1) // int32 | library id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.FetchLibraries(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.FetchLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchLibraries`: FetchLibraries200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.FetchLibraries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | library id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchLibrariesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchLibraries200Response**](FetchLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLibraries

> ListLibraries200Response ListLibraries(ctx).PerPage(perPage).Execute()

Retrieve a list of libraries



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
	perPage := int32(56) // int32 | Specify the number of libraries per page (optional) (default to 10)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.ListLibraries(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.ListLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLibraries`: ListLibraries200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.ListLibraries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListLibrariesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Specify the number of libraries per page | [default to 10]

### Return type

[**ListLibraries200Response**](ListLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateLibraries

> UpdateLibraries200Response UpdateLibraries(ctx, id).CreateLibrariesRequest(createLibrariesRequest).Execute()

Library@update



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
	id := int32(1) // int32 | library id
	createLibrariesRequest := *openapiclient.NewCreateLibrariesRequest(int32(123)) // CreateLibrariesRequest | library definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LibraryAPI.UpdateLibraries(context.Background(), id).CreateLibrariesRequest(createLibrariesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LibraryAPI.UpdateLibraries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateLibraries`: UpdateLibraries200Response
	fmt.Fprintf(os.Stdout, "Response from `LibraryAPI.UpdateLibraries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | library id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateLibrariesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createLibrariesRequest** | [**CreateLibrariesRequest**](CreateLibrariesRequest.md) | library definition | 

### Return type

[**UpdateLibraries200Response**](UpdateLibraries200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

