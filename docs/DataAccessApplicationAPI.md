# \DataAccessApplicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteDarApplicationFiles**](DataAccessApplicationAPI.md#DeleteDarApplicationFiles) | **Delete** /api/v1/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile
[**DeleteDarApplications**](DataAccessApplicationAPI.md#DeleteDarApplications) | **Delete** /api/v1/dar/applications/{id} | DataAccessApplication@destroy
[**DeleteTeamDarApplicationFile**](DataAccessApplicationAPI.md#DeleteTeamDarApplicationFile) | **Delete** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId} | DataAccessApplication@destroyFile
[**FetchTeamDarApplicationAnswers**](DataAccessApplicationAPI.md#FetchTeamDarApplicationAnswers) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/answers | DataAccessApplication@showAnswers
[**FetchTeamDarApplicationDownloadZip**](DataAccessApplicationAPI.md#FetchTeamDarApplicationDownloadZip) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/download | DataAccessApplication@download
[**FetchTeamDarApplicationFile**](DataAccessApplicationAPI.md#FetchTeamDarApplicationFile) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/files/{fileId}/download | DataAccessApplication@downloadFile
[**FetchTeamDarApplicationFiles**](DataAccessApplicationAPI.md#FetchTeamDarApplicationFiles) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/files | DataAccessApplication@showFiles
[**FetchTeamDarApplicationStatusHistory**](DataAccessApplicationAPI.md#FetchTeamDarApplicationStatusHistory) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/status | DataAccessApplication@status
[**UpdateTeamDarApplication**](DataAccessApplicationAPI.md#UpdateTeamDarApplication) | **Patch** /api/v1/teams/{teamId}/dar/applications/{id} | DataAccessApplication@update



## DeleteDarApplicationFiles

> DeleteApplications200Response DeleteDarApplicationFiles(ctx, id, fileId).Execute()

DataAccessApplication@destroyFile



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
	id := int32(1) // int32 | DAR application id
	fileId := "1" // string | File id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.DeleteDarApplicationFiles(context.Background(), id, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.DeleteDarApplicationFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDarApplicationFiles`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.DeleteDarApplicationFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR application id | 
**fileId** | **string** | File id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDarApplicationFilesRequest struct via the builder pattern


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


## DeleteDarApplications

> DeleteApplications200Response DeleteDarApplications(ctx, id).Execute()

DataAccessApplication@destroy



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
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.DeleteDarApplications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.DeleteDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDarApplications`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.DeleteDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDarApplicationsRequest struct via the builder pattern


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


## DeleteTeamDarApplicationFile

> DeleteApplications200Response DeleteTeamDarApplicationFile(ctx, teamId, id, fileId).Execute()

DataAccessApplication@destroyFile



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id
	fileId := int32(1) // int32 | File id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.DeleteTeamDarApplicationFile(context.Background(), teamId, id, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.DeleteTeamDarApplicationFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDarApplicationFile`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.DeleteTeamDarApplicationFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**fileId** | **int32** | File id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDarApplicationFileRequest struct via the builder pattern


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


## FetchTeamDarApplicationAnswers

> FetchTeamDarApplicationAnswers200Response FetchTeamDarApplicationAnswers(ctx, teamId, id).Execute()

DataAccessApplication@showAnswers



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.FetchTeamDarApplicationAnswers(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.FetchTeamDarApplicationAnswers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplicationAnswers`: FetchTeamDarApplicationAnswers200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.FetchTeamDarApplicationAnswers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationAnswersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplicationAnswers200Response**](FetchTeamDarApplicationAnswers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamDarApplicationDownloadZip

> FetchTeamDarApplicationDownloadZip(ctx, teamId, id).Execute()

DataAccessApplication@download



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DataAccessApplicationAPI.FetchTeamDarApplicationDownloadZip(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.FetchTeamDarApplicationDownloadZip``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationDownloadZipRequest struct via the builder pattern


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


## FetchTeamDarApplicationFile

> FetchTeamDarApplicationFile(ctx, teamId, id, fileId).Execute()

DataAccessApplication@downloadFile



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id
	fileId := "1" // string | File uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DataAccessApplicationAPI.FetchTeamDarApplicationFile(context.Background(), teamId, id, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.FetchTeamDarApplicationFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**fileId** | **string** | File uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationFileRequest struct via the builder pattern


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


## FetchTeamDarApplicationFiles

> FetchTeamDarApplicationFiles200Response FetchTeamDarApplicationFiles(ctx, teamId, id).Execute()

DataAccessApplication@showFiles



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.FetchTeamDarApplicationFiles(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.FetchTeamDarApplicationFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplicationFiles`: FetchTeamDarApplicationFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.FetchTeamDarApplicationFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplicationFiles200Response**](FetchTeamDarApplicationFiles200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamDarApplicationStatusHistory

> FetchTeamDarApplicationStatusHistory200Response FetchTeamDarApplicationStatusHistory(ctx, teamId, id).Execute()

DataAccessApplication@status



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.FetchTeamDarApplicationStatusHistory(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.FetchTeamDarApplicationStatusHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplicationStatusHistory`: FetchTeamDarApplicationStatusHistory200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.FetchTeamDarApplicationStatusHistory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationStatusHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplicationStatusHistory200Response**](FetchTeamDarApplicationStatusHistory200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTeamDarApplication

> FetchTeamDarApplication200Response UpdateTeamDarApplication(ctx, teamId, id).UpdateTeamDarApplicationRequest(updateTeamDarApplicationRequest).Execute()

DataAccessApplication@update



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR application id
	updateTeamDarApplicationRequest := *openapiclient.NewUpdateTeamDarApplicationRequest() // UpdateTeamDarApplicationRequest | DataAccessApplication definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationAPI.UpdateTeamDarApplication(context.Background(), teamId, id).UpdateTeamDarApplicationRequest(updateTeamDarApplicationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationAPI.UpdateTeamDarApplication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamDarApplication`: FetchTeamDarApplication200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationAPI.UpdateTeamDarApplication`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamDarApplicationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateTeamDarApplicationRequest** | [**UpdateTeamDarApplicationRequest**](UpdateTeamDarApplicationRequest.md) | DataAccessApplication definition | 

### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

