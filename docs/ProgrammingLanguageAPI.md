# \ProgrammingLanguageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProgrammingLanguages**](ProgrammingLanguageAPI.md#CreateProgrammingLanguages) | **Post** /api/v1/programming_languages | ProgrammingLanguage@store
[**DeleteProgrammingLanguages**](ProgrammingLanguageAPI.md#DeleteProgrammingLanguages) | **Delete** /api/v1/programming_languages/{id} | ProgrammingLanguage@destroy
[**EditProgrammingLanguages**](ProgrammingLanguageAPI.md#EditProgrammingLanguages) | **Patch** /api/v1/programming_languages/{id} | ProgrammingLanguage@update
[**FetchAllProgrammingLanguages**](ProgrammingLanguageAPI.md#FetchAllProgrammingLanguages) | **Get** /api/v1/programming_languages | ProgrammingLanguage@index
[**FetchProgrammingLanguages**](ProgrammingLanguageAPI.md#FetchProgrammingLanguages) | **Get** /api/v1/programming_languages/{id} | ProgrammingLanguage@show
[**UpdateProgrammingLanguages**](ProgrammingLanguageAPI.md#UpdateProgrammingLanguages) | **Put** /api/v1/programming_languages/{id} | ProgrammingLanguage@update



## CreateProgrammingLanguages

> CreateCategories200Response CreateProgrammingLanguages(ctx).CreateCategoriesRequest(createCategoriesRequest).Execute()

ProgrammingLanguage@store



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
	createCategoriesRequest := *openapiclient.NewCreateCategoriesRequest("Name", true) // CreateCategoriesRequest | Programming language definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.CreateProgrammingLanguages(context.Background()).CreateCategoriesRequest(createCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.CreateProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProgrammingLanguages`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.CreateProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProgrammingLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCategoriesRequest** | [**CreateCategoriesRequest**](CreateCategoriesRequest.md) | Programming language definition | 

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


## DeleteProgrammingLanguages

> DeleteAliases200Response DeleteProgrammingLanguages(ctx, id).Execute()

ProgrammingLanguage@destroy



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
	id := int32(1) // int32 | programming language id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.DeleteProgrammingLanguages(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.DeleteProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProgrammingLanguages`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.DeleteProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming language id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProgrammingLanguagesRequest struct via the builder pattern


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


## EditProgrammingLanguages

> UpdateProgrammingLanguages200Response EditProgrammingLanguages(ctx, id).EditCategoriesRequest(editCategoriesRequest).Execute()

ProgrammingLanguage@update



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
	id := int32(1) // int32 | programming language id
	editCategoriesRequest := *openapiclient.NewEditCategoriesRequest() // EditCategoriesRequest | ProgrammingLanguage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.EditProgrammingLanguages(context.Background(), id).EditCategoriesRequest(editCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.EditProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditProgrammingLanguages`: UpdateProgrammingLanguages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.EditProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming language id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditProgrammingLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCategoriesRequest** | [**EditCategoriesRequest**](EditCategoriesRequest.md) | ProgrammingLanguage definition | 

### Return type

[**UpdateProgrammingLanguages200Response**](UpdateProgrammingLanguages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllProgrammingLanguages

> FetchAllProgrammingLanguages200Response FetchAllProgrammingLanguages(ctx).Execute()

ProgrammingLanguage@index



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
	resp, r, err := apiClient.ProgrammingLanguageAPI.FetchAllProgrammingLanguages(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.FetchAllProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllProgrammingLanguages`: FetchAllProgrammingLanguages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.FetchAllProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllProgrammingLanguagesRequest struct via the builder pattern


### Return type

[**FetchAllProgrammingLanguages200Response**](FetchAllProgrammingLanguages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchProgrammingLanguages

> FetchProgrammingLanguages200Response FetchProgrammingLanguages(ctx, id).Execute()

ProgrammingLanguage@show



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
	id := int32(1) // int32 | programming language id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.FetchProgrammingLanguages(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.FetchProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchProgrammingLanguages`: FetchProgrammingLanguages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.FetchProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming language id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchProgrammingLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchProgrammingLanguages200Response**](FetchProgrammingLanguages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProgrammingLanguages

> UpdateProgrammingLanguages200Response UpdateProgrammingLanguages(ctx, id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()

ProgrammingLanguage@update



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
	id := int32(1) // int32 | programming language id
	updateCategoriesRequest := *openapiclient.NewUpdateCategoriesRequest("Name", "true") // UpdateCategoriesRequest | ProgrammingLanguage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.UpdateProgrammingLanguages(context.Background(), id).UpdateCategoriesRequest(updateCategoriesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.UpdateProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProgrammingLanguages`: UpdateProgrammingLanguages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.UpdateProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming language id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProgrammingLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCategoriesRequest** | [**UpdateCategoriesRequest**](UpdateCategoriesRequest.md) | ProgrammingLanguage definition | 

### Return type

[**UpdateProgrammingLanguages200Response**](UpdateProgrammingLanguages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

