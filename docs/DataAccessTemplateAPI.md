# \DataAccessTemplateAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDarTemplate**](DataAccessTemplateAPI.md#CreateDarTemplate) | **Post** /api/v1/dar/templates | DataAccessTemplate@store
[**DeleteDarTemplate**](DataAccessTemplateAPI.md#DeleteDarTemplate) | **Delete** /api/v1/dar/templates/{id} | DataAccessTemplate@destroy
[**DownloadDarTemplateFile**](DataAccessTemplateAPI.md#DownloadDarTemplateFile) | **Get** /api/v1/dar/templates/{id}/download | DataAccessTemplate@downloadFile
[**FetchDarTemplate**](DataAccessTemplateAPI.md#FetchDarTemplate) | **Get** /api/v1/dar/templates/{id} | DataAccessTemplate@show
[**FetchDarTemplates**](DataAccessTemplateAPI.md#FetchDarTemplates) | **Get** /api/v1/dar/templates | DataAccessTemplate@index
[**PatchDarTemplate**](DataAccessTemplateAPI.md#PatchDarTemplate) | **Patch** /api/v1/dar/templates/{id} | DataAccessTemplate@update
[**UpdateDarTemplate**](DataAccessTemplateAPI.md#UpdateDarTemplate) | **Put** /api/v1/dar/templates/{id} | DataAccessTemplate@update



## CreateDarTemplate

> CreateCategories200Response CreateDarTemplate(ctx).CreateDarTemplateRequest(createDarTemplateRequest).Execute()

DataAccessTemplate@store



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
	createDarTemplateRequest := *openapiclient.NewCreateDarTemplateRequest(int32(1)) // CreateDarTemplateRequest | DataAccessTemplate definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.CreateDarTemplate(context.Background()).CreateDarTemplateRequest(createDarTemplateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.CreateDarTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDarTemplate`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.CreateDarTemplate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDarTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDarTemplateRequest** | [**CreateDarTemplateRequest**](CreateDarTemplateRequest.md) | DataAccessTemplate definition | 

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


## DeleteDarTemplate

> DeleteAliases200Response DeleteDarTemplate(ctx, id).Execute()

DataAccessTemplate@destroy



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
	id := int32(1) // int32 | DAR template id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.DeleteDarTemplate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.DeleteDarTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDarTemplate`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.DeleteDarTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDarTemplateRequest struct via the builder pattern


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


## DownloadDarTemplateFile

> DownloadDarTemplateFile(ctx, id).Execute()

DataAccessTemplate@downloadFile



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
	id := int32(1) // int32 | DAR template id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DataAccessTemplateAPI.DownloadDarTemplateFile(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.DownloadDarTemplateFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadDarTemplateFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: file, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarTemplate

> FetchDarTemplate200Response FetchDarTemplate(ctx, id).Execute()

DataAccessTemplate@show



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
	id := int32(1) // int32 | DAR template id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.FetchDarTemplate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.FetchDarTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarTemplate`: FetchDarTemplate200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.FetchDarTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDarTemplate200Response**](FetchDarTemplate200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarTemplates

> FetchDarTemplates200Response FetchDarTemplates(ctx).WithQuestions(withQuestions).Published(published).Execute()

DataAccessTemplate@index



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
	withQuestions := int32(1) // int32 | Include questions in response (optional)
	published := "true" // string | Template publication status to filter by (true, false) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.FetchDarTemplates(context.Background()).WithQuestions(withQuestions).Published(published).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.FetchDarTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarTemplates`: FetchDarTemplates200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.FetchDarTemplates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarTemplatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **withQuestions** | **int32** | Include questions in response | 
 **published** | **string** | Template publication status to filter by (true, false) | 

### Return type

[**FetchDarTemplates200Response**](FetchDarTemplates200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDarTemplate

> PatchDarTemplate200Response PatchDarTemplate(ctx, id).PatchDarTemplateRequest(patchDarTemplateRequest).SectionId(sectionId).Execute()

DataAccessTemplate@update



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
	id := int32(1) // int32 | DAR template id
	patchDarTemplateRequest := *openapiclient.NewPatchDarTemplateRequest() // PatchDarTemplateRequest | DataAccessTemplate definition
	sectionId := int32(1) // int32 | Section id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.PatchDarTemplate(context.Background(), id).PatchDarTemplateRequest(patchDarTemplateRequest).SectionId(sectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.PatchDarTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDarTemplate`: PatchDarTemplate200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.PatchDarTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDarTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchDarTemplateRequest** | [**PatchDarTemplateRequest**](PatchDarTemplateRequest.md) | DataAccessTemplate definition | 
 **sectionId** | **int32** | Section id | 

### Return type

[**PatchDarTemplate200Response**](PatchDarTemplate200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDarTemplate

> FetchDarTemplate200Response UpdateDarTemplate(ctx, id).UpdateDarTemplateRequest(updateDarTemplateRequest).Execute()

DataAccessTemplate@update



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
	id := int32(1) // int32 | DAR template id
	updateDarTemplateRequest := *openapiclient.NewUpdateDarTemplateRequest(int32(1)) // UpdateDarTemplateRequest | DataAccessTemplate definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplateAPI.UpdateDarTemplate(context.Background(), id).UpdateDarTemplateRequest(updateDarTemplateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplateAPI.UpdateDarTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDarTemplate`: FetchDarTemplate200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplateAPI.UpdateDarTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDarTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDarTemplateRequest** | [**UpdateDarTemplateRequest**](UpdateDarTemplateRequest.md) | DataAccessTemplate definition | 

### Return type

[**FetchDarTemplate200Response**](FetchDarTemplate200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

