# \AliasAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAliases**](AliasAPI.md#CreateAliases) | **Post** /api/v1/aliases | AliasController@store
[**DeleteAliases**](AliasAPI.md#DeleteAliases) | **Delete** /api/v1/aliases/{id} | AliasController@destroy
[**EditAliases**](AliasAPI.md#EditAliases) | **Patch** /api/v1/aliases/{id} | AliasController@edit
[**FetchAliases**](AliasAPI.md#FetchAliases) | **Get** /api/v1/aliases/{id} | Return a single alias
[**FetchAllAliases**](AliasAPI.md#FetchAllAliases) | **Get** /api/v1/aliases | List of aliases
[**UpdateAliases**](AliasAPI.md#UpdateAliases) | **Put** /api/v1/aliases/{id} | AliasController@update



## CreateAliases

> CreateAliases200Response CreateAliases(ctx).CreateAliasesRequest(createAliasesRequest).Execute()

AliasController@store



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
	createAliasesRequest := *openapiclient.NewCreateAliasesRequest("something") // CreateAliasesRequest | Alias definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AliasAPI.CreateAliases(context.Background()).CreateAliasesRequest(createAliasesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.CreateAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAliases`: CreateAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.CreateAliases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAliasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAliasesRequest** | [**CreateAliasesRequest**](CreateAliasesRequest.md) | Alias definition | 

### Return type

[**CreateAliases200Response**](CreateAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAliases

> DeleteAliases200Response DeleteAliases(ctx, id).Execute()

AliasController@destroy



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
	id := int32(1) // int32 | alias id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AliasAPI.DeleteAliases(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.DeleteAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAliases`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.DeleteAliases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | alias id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAliasesRequest struct via the builder pattern


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


## EditAliases

> UpdateAliases200Response EditAliases(ctx, id).EditAliasesRequest(editAliasesRequest).Execute()

AliasController@edit



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
	id := int32(1) // int32 | alias id
	editAliasesRequest := *openapiclient.NewEditAliasesRequest() // EditAliasesRequest | Alias definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AliasAPI.EditAliases(context.Background(), id).EditAliasesRequest(editAliasesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.EditAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditAliases`: UpdateAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.EditAliases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | alias id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditAliasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editAliasesRequest** | [**EditAliasesRequest**](EditAliasesRequest.md) | Alias definition | 

### Return type

[**UpdateAliases200Response**](UpdateAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAliases

> FetchAliases200Response FetchAliases(ctx, id).Execute()

Return a single alias



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
	id := int32(1) // int32 | alias id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AliasAPI.FetchAliases(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.FetchAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAliases`: FetchAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.FetchAliases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | alias id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAliasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAliases200Response**](FetchAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllAliases

> FetchAllAliases200Response FetchAllAliases(ctx).Execute()

List of aliases



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
	resp, r, err := apiClient.AliasAPI.FetchAllAliases(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.FetchAllAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllAliases`: FetchAllAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.FetchAllAliases`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllAliasesRequest struct via the builder pattern


### Return type

[**FetchAllAliases200Response**](FetchAllAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAliases

> UpdateAliases200Response UpdateAliases(ctx, id).CreateAliasesRequest(createAliasesRequest).Execute()

AliasController@update



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
	id := int32(1) // int32 | alias id
	createAliasesRequest := *openapiclient.NewCreateAliasesRequest("something") // CreateAliasesRequest | Alias definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AliasAPI.UpdateAliases(context.Background(), id).CreateAliasesRequest(createAliasesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AliasAPI.UpdateAliases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAliases`: UpdateAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `AliasAPI.UpdateAliases`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | alias id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAliasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createAliasesRequest** | [**CreateAliasesRequest**](CreateAliasesRequest.md) | Alias definition | 

### Return type

[**UpdateAliases200Response**](UpdateAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

