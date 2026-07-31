# \KeywordAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateKeywords**](KeywordAPI.md#CreateKeywords) | **Post** /api/v1/keywords | KeywordController@store
[**DeleteKeywords**](KeywordAPI.md#DeleteKeywords) | **Delete** /api/v1/keywords/{id} | KeywordController@destroy
[**EditKeywords**](KeywordAPI.md#EditKeywords) | **Patch** /api/v1/keywords/{id} | KeywordController@update
[**FetchAllKeywords**](KeywordAPI.md#FetchAllKeywords) | **Get** /api/v1/keywords | KeywordController@index
[**FetchKeywords**](KeywordAPI.md#FetchKeywords) | **Get** /api/v1/keywords/{id} | KeywordController@show
[**UpdateKeywords**](KeywordAPI.md#UpdateKeywords) | **Put** /api/v1/keywords/{id} | KeywordController@update



## CreateKeywords

> CreateCategories200Response CreateKeywords(ctx).CreateCategoriesRequest(createCategoriesRequest).Execute()

KeywordController@store



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
	createCategoriesRequest := *openapiclient.NewCreateCategoriesRequest("Name", true) // CreateCategoriesRequest | Keyword definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.CreateKeywords(context.Background()).CreateCategoriesRequest(createCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.CreateKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateKeywords`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.CreateKeywords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateKeywordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Keyword definition | 

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


## DeleteKeywords

> DeleteAliases200Response DeleteKeywords(ctx, id).Execute()

KeywordController@destroy



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
	id := int32(1) // int32 | keyword id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.DeleteKeywords(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.DeleteKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteKeywords`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.DeleteKeywords`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | keyword id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteKeywordsRequest struct via the builder pattern


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


## EditKeywords

> UpdateKeywords200Response EditKeywords(ctx, id).EditCategoriesRequest(editCategoriesRequest).Execute()

KeywordController@update



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
	id := int32(1) // int32 | keyword id
	editCategoriesRequest := *openapiclient.NewEditCategoriesRequest() // EditCategoriesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.EditKeywords(context.Background(), id).EditCategoriesRequest(editCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.EditKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditKeywords`: UpdateKeywords200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.EditKeywords`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | keyword id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditKeywordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | Category definition | 

### Return type

[**UpdateKeywords200Response**](UpdateKeywords200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllKeywords

> FetchAllKeywords200Response FetchAllKeywords(ctx).PerPage(perPage).Execute()

KeywordController@index



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
	perPage := int32(56) // int32 | Alternative output schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.FetchAllKeywords(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.FetchAllKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllKeywords`: FetchAllKeywords200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.FetchAllKeywords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllKeywordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Alternative output schema version. | 

### Return type

[**FetchAllKeywords200Response**](FetchAllKeywords200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchKeywords

> FetchKeywords200Response FetchKeywords(ctx, id).Execute()

KeywordController@show



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
	id := int32(1) // int32 | keyword id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.FetchKeywords(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.FetchKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchKeywords`: FetchKeywords200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.FetchKeywords`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | keyword id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchKeywordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchKeywords200Response**](FetchKeywords200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateKeywords

> UpdateKeywords200Response UpdateKeywords(ctx, id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()

KeywordController@update



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
	id := int32(1) // int32 | keyword id
	updateCategoriesRequest := *openapiclient.NewUpdateCategoriesRequest("Name", "true") // UpdateCategoriesRequest | Keyword definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KeywordAPI.UpdateKeywords(context.Background(), id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KeywordAPI.UpdateKeywords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateKeywords`: UpdateKeywords200Response
	fmt.Fprintf(os.Stdout, "Response from `KeywordAPI.UpdateKeywords`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | keyword id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateKeywordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | Keyword definition | 

### Return type

[**UpdateKeywords200Response**](UpdateKeywords200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

