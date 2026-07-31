# \UploadAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateFiles**](UploadAPI.md#CreateFiles) | **Post** /api/v1/files | Upload@upload
[**DeleteFilesProcessed**](UploadAPI.md#DeleteFilesProcessed) | **Delete** /api/v1/files/processed/{id} | Upload@destroy
[**FetchFiles**](UploadAPI.md#FetchFiles) | **Get** /api/v1/files/{uuid} | Upload@show
[**FetchFilesProcessedContent**](UploadAPI.md#FetchFilesProcessedContent) | **Get** /api/v1/files/processed/{uuid}/download | Upload@content



## CreateFiles

> CreateFiles200Response CreateFiles(ctx).EntityFlag(entityFlag).TeamId(teamId).ApplicationId(applicationId).QuestionId(questionId).Execute()

Upload@upload



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
	entityFlag := "dur-from-upload" // string | Flag to indicate the purpose of the file upload e.g. dur-from-upload (optional)
	teamId := int32(10) // int32 | Id of team associated with the file upload (optional)
	applicationId := int32(10) // int32 | Id of dar application associated with the file upload (optional)
	questionId := int32(10) // int32 | Id of the question in the dar application associated with the file upload (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.CreateFiles(context.Background()).EntityFlag(entityFlag).TeamId(teamId).ApplicationId(applicationId).QuestionId(questionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.CreateFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateFiles`: CreateFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.CreateFiles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **entityFlag** | **string** | Flag to indicate the purpose of the file upload e.g. dur-from-upload | 
 **teamId** | **int32** | Id of team associated with the file upload | 
 **applicationId** | **int32** | Id of dar application associated with the file upload | 
 **questionId** | **int32** | Id of the question in the dar application associated with the file upload | 

### Return type

[**CreateFiles200Response**](CreateFiles200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteFilesProcessed

> DeleteAliases200Response DeleteFilesProcessed(ctx, id).Execute()

Upload@destroy



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
	id := "1" // string | file uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.DeleteFilesProcessed(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.DeleteFilesProcessed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteFilesProcessed`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.DeleteFilesProcessed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | file uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFilesProcessedRequest struct via the builder pattern


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


## FetchFiles

> FetchFiles200Response FetchFiles(ctx, uuid).Execute()

Upload@show



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
	uuid := "1" // string | upload id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.FetchFiles(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.FetchFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchFiles`: FetchFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.FetchFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | upload id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchFiles200Response**](FetchFiles200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchFilesProcessedContent

> FetchFilesProcessedContent200Response FetchFilesProcessedContent(ctx, uuid).Execute()

Upload@content



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
	uuid := "1" // string | upload id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.FetchFilesProcessedContent(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.FetchFilesProcessedContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchFilesProcessedContent`: FetchFilesProcessedContent200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.FetchFilesProcessedContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | upload id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchFilesProcessedContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchFilesProcessedContent200Response**](FetchFilesProcessedContent200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

