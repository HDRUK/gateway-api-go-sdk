# \QuestionBankAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateQuestionBankQuestion**](QuestionBankAPI.md#CreateQuestionBankQuestion) | **Post** /api/v1/questions | QuestionBank@store
[**DeleteQuestionBankQuestion**](QuestionBankAPI.md#DeleteQuestionBankQuestion) | **Delete** /api/v1/questions/{id} | QuestionBank@destroy
[**DownloadQuestionBankQuestionFile**](QuestionBankAPI.md#DownloadQuestionBankQuestionFile) | **Get** /api/v1/questions/{id}/files/{fileId} | QuestionBank@destroyFile
[**EditQuestionBankQuestion**](QuestionBankAPI.md#EditQuestionBankQuestion) | **Patch** /api/v1/questions/{id} | QuestionBank@update
[**FetchArchivedQuestionBankQuestions**](QuestionBankAPI.md#FetchArchivedQuestionBankQuestions) | **Get** /api/v1/questions/archived | QuestionBank@indexArchived
[**FetchCustomQuestionBankQuestions**](QuestionBankAPI.md#FetchCustomQuestionBankQuestions) | **Get** /api/v1/questions/custom | QuestionBank@indexCustom
[**FetchQuestionBankQuestion**](QuestionBankAPI.md#FetchQuestionBankQuestion) | **Get** /api/v1/questions/{id} | QuestionBank@show
[**FetchQuestionBankQuestionVersion**](QuestionBankAPI.md#FetchQuestionBankQuestionVersion) | **Get** /api/v1/questions/version/{id} | QuestionBank@showVersion
[**FetchQuestionBankQuestions**](QuestionBankAPI.md#FetchQuestionBankQuestions) | **Get** /api/v1/questions | QuestionBank@index
[**FetchStandardQuestionBankQuestions**](QuestionBankAPI.md#FetchStandardQuestionBankQuestions) | **Get** /api/v1/questions/standard | QuestionBank@indexStandard
[**FetchTeamQuestionBankQuestionsBySection**](QuestionBankAPI.md#FetchTeamQuestionBankQuestionsBySection) | **Get** /api/v1/teams/{teamId}/questions/section/{sectionId} | TeamQuestionBank@indexBySection
[**UpdateQuestionBankQuestion**](QuestionBankAPI.md#UpdateQuestionBankQuestion) | **Put** /api/v1/questions/{id} | QuestionBank@update
[**UpdateQuestionBankQuestionStatus**](QuestionBankAPI.md#UpdateQuestionBankQuestionStatus) | **Patch** /api/v1/questions/{id}/{status} | QuestionBank@updateStatus



## CreateQuestionBankQuestion

> CreateDarIntegration201Response CreateQuestionBankQuestion(ctx).CreateQuestionBankQuestionRequest(createQuestionBankQuestionRequest).Execute()

QuestionBank@store



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
	createQuestionBankQuestionRequest := *openapiclient.NewCreateQuestionBankQuestionRequest(int32(1), false, true, "Question guidance", "Question title", []map[string]interface{}{map[string]interface{}(123)}, "RadioGroup", []map[string]interface{}{map[string]interface{}(123)}, []openapiclient.CreateQuestionBankQuestionRequestOptionsInner{*openapiclient.NewCreateQuestionBankQuestionRequestOptionsInner()}) // CreateQuestionBankQuestionRequest | QuestionBank definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.CreateQuestionBankQuestion(context.Background()).CreateQuestionBankQuestionRequest(createQuestionBankQuestionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.CreateQuestionBankQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateQuestionBankQuestion`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.CreateQuestionBankQuestion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateQuestionBankQuestionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createQuestionBankQuestionRequest** | [**CreateQuestionBankQuestionRequest**](CreateQuestionBankQuestionRequest.md) | QuestionBank definition | 

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


## DeleteQuestionBankQuestion

> DeleteApplications200Response DeleteQuestionBankQuestion(ctx, id).Execute()

QuestionBank@destroy



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
	id := int32(1) // int32 | question bank question id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.DeleteQuestionBankQuestion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.DeleteQuestionBankQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteQuestionBankQuestion`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.DeleteQuestionBankQuestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteQuestionBankQuestionRequest struct via the builder pattern


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


## DownloadQuestionBankQuestionFile

> DeleteApplications200Response DownloadQuestionBankQuestionFile(ctx, id, fileId).Execute()

QuestionBank@destroyFile



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
	id := int32(1) // int32 | question bank question id
	fileId := int32(1) // int32 | file uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.DownloadQuestionBankQuestionFile(context.Background(), id, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.DownloadQuestionBankQuestionFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadQuestionBankQuestionFile`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.DownloadQuestionBankQuestionFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 
**fileId** | **int32** | file uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadQuestionBankQuestionFileRequest struct via the builder pattern


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


## EditQuestionBankQuestion

> UpdateQuestionBankQuestion200Response EditQuestionBankQuestion(ctx, id).EditQuestionBankQuestionRequest(editQuestionBankQuestionRequest).Execute()

QuestionBank@update



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
	id := int32(1) // int32 | question bank question id
	editQuestionBankQuestionRequest := *openapiclient.NewEditQuestionBankQuestionRequest() // EditQuestionBankQuestionRequest | QuestionBank definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.EditQuestionBankQuestion(context.Background(), id).EditQuestionBankQuestionRequest(editQuestionBankQuestionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.EditQuestionBankQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditQuestionBankQuestion`: UpdateQuestionBankQuestion200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.EditQuestionBankQuestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditQuestionBankQuestionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editQuestionBankQuestionRequest** | [**EditQuestionBankQuestionRequest**](EditQuestionBankQuestionRequest.md) | QuestionBank definition | 

### Return type

[**UpdateQuestionBankQuestion200Response**](UpdateQuestionBankQuestion200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchArchivedQuestionBankQuestions

> FetchQuestionBankQuestions200Response FetchArchivedQuestionBankQuestions(ctx).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()

QuestionBank@indexArchived



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
	sectionId := int32(1) // int32 | section id (optional)
	isChild := int32(1) // int32 | filter on is_child field (optional)
	perPage := int32(1) // int32 | per page (optional)
	page := int32(1) // int32 | page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchArchivedQuestionBankQuestions(context.Background()).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchArchivedQuestionBankQuestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchArchivedQuestionBankQuestions`: FetchQuestionBankQuestions200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchArchivedQuestionBankQuestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchArchivedQuestionBankQuestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sectionId** | **int32** | section id | 
 **isChild** | **int32** | filter on is_child field | 
 **perPage** | **int32** | per page | 
 **page** | **int32** | page | 

### Return type

[**FetchQuestionBankQuestions200Response**](FetchQuestionBankQuestions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCustomQuestionBankQuestions

> FetchCustomQuestionBankQuestions200Response FetchCustomQuestionBankQuestions(ctx).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()

QuestionBank@indexCustom



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
	sectionId := int32(1) // int32 | section id (optional)
	isChild := int32(1) // int32 | filter on is_child field (optional)
	perPage := int32(1) // int32 | per page (optional)
	page := int32(1) // int32 | page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchCustomQuestionBankQuestions(context.Background()).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchCustomQuestionBankQuestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCustomQuestionBankQuestions`: FetchCustomQuestionBankQuestions200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchCustomQuestionBankQuestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchCustomQuestionBankQuestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sectionId** | **int32** | section id | 
 **isChild** | **int32** | filter on is_child field | 
 **perPage** | **int32** | per page | 
 **page** | **int32** | page | 

### Return type

[**FetchCustomQuestionBankQuestions200Response**](FetchCustomQuestionBankQuestions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchQuestionBankQuestion

> FetchQuestionBankQuestion200Response FetchQuestionBankQuestion(ctx, id).Execute()

QuestionBank@show



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
	id := int32(1) // int32 | question bank question id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchQuestionBankQuestion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchQuestionBankQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchQuestionBankQuestion`: FetchQuestionBankQuestion200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchQuestionBankQuestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchQuestionBankQuestionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchQuestionBankQuestion200Response**](FetchQuestionBankQuestion200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchQuestionBankQuestionVersion

> FetchQuestionBankQuestionVersion200Response FetchQuestionBankQuestionVersion(ctx, id).Execute()

QuestionBank@showVersion



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
	id := int32(1) // int32 | question bank question version id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchQuestionBankQuestionVersion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchQuestionBankQuestionVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchQuestionBankQuestionVersion`: FetchQuestionBankQuestionVersion200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchQuestionBankQuestionVersion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question version id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchQuestionBankQuestionVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchQuestionBankQuestionVersion200Response**](FetchQuestionBankQuestionVersion200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchQuestionBankQuestions

> FetchQuestionBankQuestions200Response FetchQuestionBankQuestions(ctx).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()

QuestionBank@index



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
	sectionId := int32(1) // int32 | section id (optional)
	isChild := int32(1) // int32 | filter on is_child field (optional)
	perPage := int32(1) // int32 | per page (optional)
	page := int32(1) // int32 | page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchQuestionBankQuestions(context.Background()).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchQuestionBankQuestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchQuestionBankQuestions`: FetchQuestionBankQuestions200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchQuestionBankQuestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchQuestionBankQuestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sectionId** | **int32** | section id | 
 **isChild** | **int32** | filter on is_child field | 
 **perPage** | **int32** | per page | 
 **page** | **int32** | page | 

### Return type

[**FetchQuestionBankQuestions200Response**](FetchQuestionBankQuestions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchStandardQuestionBankQuestions

> FetchStandardQuestionBankQuestions200Response FetchStandardQuestionBankQuestions(ctx).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()

QuestionBank@indexStandard



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
	sectionId := int32(1) // int32 | section id (optional)
	isChild := int32(1) // int32 | filter on is_child field (optional)
	perPage := int32(1) // int32 | per page (optional)
	page := int32(1) // int32 | page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchStandardQuestionBankQuestions(context.Background()).SectionId(sectionId).IsChild(isChild).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchStandardQuestionBankQuestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchStandardQuestionBankQuestions`: FetchStandardQuestionBankQuestions200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchStandardQuestionBankQuestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchStandardQuestionBankQuestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sectionId** | **int32** | section id | 
 **isChild** | **int32** | filter on is_child field | 
 **perPage** | **int32** | per page | 
 **page** | **int32** | page | 

### Return type

[**FetchStandardQuestionBankQuestions200Response**](FetchStandardQuestionBankQuestions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamQuestionBankQuestionsBySection

> FetchTeamQuestionBankQuestionsBySection200Response FetchTeamQuestionBankQuestionsBySection(ctx, teamId, sectionId).IsChild(isChild).Execute()

TeamQuestionBank@indexBySection



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
	teamId := int32(1) // int32 | Team ID
	sectionId := int32(1) // int32 | section id
	isChild := int32(1) // int32 | filter on is_child field (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.FetchTeamQuestionBankQuestionsBySection(context.Background(), teamId, sectionId).IsChild(isChild).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.FetchTeamQuestionBankQuestionsBySection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamQuestionBankQuestionsBySection`: FetchTeamQuestionBankQuestionsBySection200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.FetchTeamQuestionBankQuestionsBySection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 
**sectionId** | **int32** | section id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamQuestionBankQuestionsBySectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **isChild** | **int32** | filter on is_child field | 

### Return type

[**FetchTeamQuestionBankQuestionsBySection200Response**](FetchTeamQuestionBankQuestionsBySection200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateQuestionBankQuestion

> UpdateQuestionBankQuestion200Response UpdateQuestionBankQuestion(ctx, id).UpdateQuestionBankQuestionRequest(updateQuestionBankQuestionRequest).Execute()

QuestionBank@update



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
	id := int32(1) // int32 | question bank question id
	updateQuestionBankQuestionRequest := *openapiclient.NewUpdateQuestionBankQuestionRequest(int32(1), false, true, "Question guidance", "Question title", []map[string]interface{}{map[string]interface{}(123)}) // UpdateQuestionBankQuestionRequest | QuestionBank definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.UpdateQuestionBankQuestion(context.Background(), id).UpdateQuestionBankQuestionRequest(updateQuestionBankQuestionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.UpdateQuestionBankQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateQuestionBankQuestion`: UpdateQuestionBankQuestion200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.UpdateQuestionBankQuestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateQuestionBankQuestionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateQuestionBankQuestionRequest** | [**UpdateQuestionBankQuestionRequest**](UpdateQuestionBankQuestionRequest.md) | QuestionBank definition | 

### Return type

[**UpdateQuestionBankQuestion200Response**](UpdateQuestionBankQuestion200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateQuestionBankQuestionStatus

> UpdateQuestionBankQuestionStatus200Response UpdateQuestionBankQuestionStatus(ctx, id, status).Execute()

QuestionBank@updateStatus



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
	id := int32(1) // int32 | question bank question id
	status := "lock" // string | lock or unlock

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuestionBankAPI.UpdateQuestionBankQuestionStatus(context.Background(), id, status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuestionBankAPI.UpdateQuestionBankQuestionStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateQuestionBankQuestionStatus`: UpdateQuestionBankQuestionStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `QuestionBankAPI.UpdateQuestionBankQuestionStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | question bank question id | 
**status** | **string** | lock or unlock | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateQuestionBankQuestionStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**UpdateQuestionBankQuestionStatus200Response**](UpdateQuestionBankQuestionStatus200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

