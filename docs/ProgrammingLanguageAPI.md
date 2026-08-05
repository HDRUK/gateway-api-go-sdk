# \ProgrammingLanguageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProgrammingLanguages**](ProgrammingLanguageAPI.md#CreateProgrammingLanguages) | **Post** /api/v1/programming_languages | ProgrammingLanguage@store
[**DeleteProgrammingLanguages**](ProgrammingLanguageAPI.md#DeleteProgrammingLanguages) | **Delete** /api/v1/programming_languages/{id} | ProgrammingLanguage@destroy
[**EditProgrammingLanguages**](ProgrammingLanguageAPI.md#EditProgrammingLanguages) | **Patch** /api/v1/programming_languages/{id} | ProgrammingLanguage@update
[**UpdateProgrammingLanguages**](ProgrammingLanguageAPI.md#UpdateProgrammingLanguages) | **Put** /api/v1/programming_languages/{id} | ProgrammingLanguage@update



## CreateProgrammingLanguages

> CreateDarIntegration201Response CreateProgrammingLanguages(ctx).CreateProgrammingLanguagesRequest(createProgrammingLanguagesRequest).Execute()

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
	createProgrammingLanguagesRequest := *openapiclient.NewCreateProgrammingLanguagesRequest("Name", true) // CreateProgrammingLanguagesRequest | Programming language definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.CreateProgrammingLanguages(context.Background()).CreateProgrammingLanguagesRequest(createProgrammingLanguagesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingLanguageAPI.CreateProgrammingLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProgrammingLanguages`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingLanguageAPI.CreateProgrammingLanguages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProgrammingLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProgrammingLanguagesRequest** | [**CreateProgrammingLanguagesRequest**](CreateProgrammingLanguagesRequest.md) | Programming language definition | 

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


## DeleteProgrammingLanguages

> DeleteApplications200Response DeleteProgrammingLanguages(ctx, id).Execute()

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
	// response from `DeleteProgrammingLanguages`: DeleteApplications200Response
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

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditProgrammingLanguages

> UpdateProgrammingLanguages200Response EditProgrammingLanguages(ctx, id).EditProgrammingLanguagesRequest(editProgrammingLanguagesRequest).Execute()

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
	editProgrammingLanguagesRequest := *openapiclient.NewEditProgrammingLanguagesRequest() // EditProgrammingLanguagesRequest | ProgrammingLanguage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.EditProgrammingLanguages(context.Background(), id).EditProgrammingLanguagesRequest(editProgrammingLanguagesRequest).Execute()
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

 **editProgrammingLanguagesRequest** | [**EditProgrammingLanguagesRequest**](EditProgrammingLanguagesRequest.md) | ProgrammingLanguage definition | 

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


## UpdateProgrammingLanguages

> UpdateProgrammingLanguages200Response UpdateProgrammingLanguages(ctx, id).UpdateProgrammingLanguagesRequest(updateProgrammingLanguagesRequest).Execute()

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
	updateProgrammingLanguagesRequest := *openapiclient.NewUpdateProgrammingLanguagesRequest("Name", "true") // UpdateProgrammingLanguagesRequest | ProgrammingLanguage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingLanguageAPI.UpdateProgrammingLanguages(context.Background(), id).UpdateProgrammingLanguagesRequest(updateProgrammingLanguagesRequest).Execute()
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

 **updateProgrammingLanguagesRequest** | [**UpdateProgrammingLanguagesRequest**](UpdateProgrammingLanguagesRequest.md) | ProgrammingLanguage definition | 

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

