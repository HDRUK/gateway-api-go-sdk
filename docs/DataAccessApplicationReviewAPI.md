# \DataAccessApplicationReviewAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTeamDarApplicationQuestionReview**](DataAccessApplicationReviewAPI.md#CreateTeamDarApplicationQuestionReview) | **Post** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews | DataAccessApplicationReview@store
[**CreateTeamDarApplicationReview**](DataAccessApplicationReviewAPI.md#CreateTeamDarApplicationReview) | **Post** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@storeGlobal
[**DeleteTeamDarApplicationQuestionReview**](DataAccessApplicationReviewAPI.md#DeleteTeamDarApplicationQuestionReview) | **Delete** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@destroy
[**DeleteTeamDarApplicationReview**](DataAccessApplicationReviewAPI.md#DeleteTeamDarApplicationReview) | **Delete** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@destroyGlobal
[**DeleteTeamDarApplicationReviewFile**](DataAccessApplicationReviewAPI.md#DeleteTeamDarApplicationReviewFile) | **Delete** /api/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/files/{fileId} | DataAccessApplicationReview@destroyFile
[**FetchTeamDarApplicationReviewFile**](DataAccessApplicationReviewAPI.md#FetchTeamDarApplicationReviewFile) | **Get** /api/v1/teams/{teamId}/dar/applications/{id}/reviews/{reviewId}/download/{fileId} | DataAccessApplicationReview@downloadFile
[**FetchTeamDarApplicationReviews**](DataAccessApplicationReviewAPI.md#FetchTeamDarApplicationReviews) | **Get** /api/v1/teams/{team_id}/dar/applications/{id}/reviews | DataAccessApplicationReview@index
[**UpdateTeamDarApplicationQuestionReview**](DataAccessApplicationReviewAPI.md#UpdateTeamDarApplicationQuestionReview) | **Put** /api/v1/teams/{team_id}/dar/applications/{id}/questions/{questionId}/reviews/{reviewId} | DataAccessApplicationReview@update
[**UpdateTeamDarApplicationReview**](DataAccessApplicationReviewAPI.md#UpdateTeamDarApplicationReview) | **Put** /api/v1/teams/{team_id}/dar/applications/{id}/reviews/{reviewId} | DataAccessApplicationReview@updateGlobal



## CreateTeamDarApplicationQuestionReview

> CreateDarIntegration201Response CreateTeamDarApplicationQuestionReview(ctx, teamId, id, questionId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()

DataAccessApplicationReview@store



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
	questionId := int32(1) // int32 | DAR application question id
	createTeamDarApplicationReviewRequest := *openapiclient.NewCreateTeamDarApplicationReviewRequest("A review of this application") // CreateTeamDarApplicationReviewRequest | DataAccessApplicationReview definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.CreateTeamDarApplicationQuestionReview(context.Background(), teamId, id, questionId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.CreateTeamDarApplicationQuestionReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamDarApplicationQuestionReview`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.CreateTeamDarApplicationQuestionReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**questionId** | **int32** | DAR application question id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamDarApplicationQuestionReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition | 

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


## CreateTeamDarApplicationReview

> CreateDarIntegration201Response CreateTeamDarApplicationReview(ctx, teamId, id).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()

DataAccessApplicationReview@storeGlobal



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
	createTeamDarApplicationReviewRequest := *openapiclient.NewCreateTeamDarApplicationReviewRequest("A review of this application") // CreateTeamDarApplicationReviewRequest | DataAccessApplicationReview definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.CreateTeamDarApplicationReview(context.Background(), teamId, id).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.CreateTeamDarApplicationReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamDarApplicationReview`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.CreateTeamDarApplicationReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamDarApplicationReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition | 

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


## DeleteTeamDarApplicationQuestionReview

> DeleteApplications200Response DeleteTeamDarApplicationQuestionReview(ctx, teamId, id, questionId, reviewId).Execute()

DataAccessApplicationReview@destroy



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
	questionId := int32(1) // int32 | DAR application question id
	reviewId := int32(1) // int32 | DAR application review id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.DeleteTeamDarApplicationQuestionReview(context.Background(), teamId, id, questionId, reviewId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationQuestionReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDarApplicationQuestionReview`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationQuestionReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**questionId** | **int32** | DAR application question id | 
**reviewId** | **int32** | DAR application review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDarApplicationQuestionReviewRequest struct via the builder pattern


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


## DeleteTeamDarApplicationReview

> DeleteApplications200Response DeleteTeamDarApplicationReview(ctx, teamId, id, reviewId).Execute()

DataAccessApplicationReview@destroyGlobal



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
	reviewId := int32(1) // int32 | DAR application review id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReview(context.Background(), teamId, id, reviewId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDarApplicationReview`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**reviewId** | **int32** | DAR application review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDarApplicationReviewRequest struct via the builder pattern


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


## DeleteTeamDarApplicationReviewFile

> DeleteApplications200Response DeleteTeamDarApplicationReviewFile(ctx, teamId, id, reviewId, fileId).Execute()

DataAccessApplicationReview@destroyFile



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
	id := int32(1) // int32 | Dar application id
	reviewId := int32(1) // int32 | Review id
	fileId := "1" // string | File uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReviewFile(context.Background(), teamId, id, reviewId, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReviewFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDarApplicationReviewFile`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.DeleteTeamDarApplicationReviewFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | Dar application id | 
**reviewId** | **int32** | Review id | 
**fileId** | **string** | File uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDarApplicationReviewFileRequest struct via the builder pattern


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


## FetchTeamDarApplicationReviewFile

> FetchTeamDarApplicationReviewFile(ctx, teamId, id, reviewId, fileId).Execute()

DataAccessApplicationReview@downloadFile



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
	reviewId := int32(1) // int32 | DAR application review id
	fileId := "1" // string | File uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DataAccessApplicationReviewAPI.FetchTeamDarApplicationReviewFile(context.Background(), teamId, id, reviewId, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.FetchTeamDarApplicationReviewFile``: %v\n", err)
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
**reviewId** | **int32** | DAR application review id | 
**fileId** | **string** | File uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationReviewFileRequest struct via the builder pattern


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


## FetchTeamDarApplicationReviews

> FetchTeamDarApplicationReviews200Response FetchTeamDarApplicationReviews(ctx, teamId, id).Execute()

DataAccessApplicationReview@index



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
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.FetchTeamDarApplicationReviews(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.FetchTeamDarApplicationReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplicationReviews`: FetchTeamDarApplicationReviews200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.FetchTeamDarApplicationReviews`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationReviewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplicationReviews200Response**](FetchTeamDarApplicationReviews200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTeamDarApplicationQuestionReview

> UpdateTeamDarApplicationQuestionReview200Response UpdateTeamDarApplicationQuestionReview(ctx, teamId, id, questionId, reviewId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()

DataAccessApplicationReview@update



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
	questionId := int32(1) // int32 | DAR application question id
	reviewId := int32(1) // int32 | DAR application review id
	createTeamDarApplicationReviewRequest := *openapiclient.NewCreateTeamDarApplicationReviewRequest("A review of this application") // CreateTeamDarApplicationReviewRequest | DataAccessApplicationReview definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.UpdateTeamDarApplicationQuestionReview(context.Background(), teamId, id, questionId, reviewId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.UpdateTeamDarApplicationQuestionReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamDarApplicationQuestionReview`: UpdateTeamDarApplicationQuestionReview200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.UpdateTeamDarApplicationQuestionReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**questionId** | **int32** | DAR application question id | 
**reviewId** | **int32** | DAR application review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamDarApplicationQuestionReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition | 

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTeamDarApplicationReview

> UpdateTeamDarApplicationQuestionReview200Response UpdateTeamDarApplicationReview(ctx, teamId, id, reviewId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()

DataAccessApplicationReview@updateGlobal



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
	reviewId := int32(1) // int32 | DAR application review id
	createTeamDarApplicationReviewRequest := *openapiclient.NewCreateTeamDarApplicationReviewRequest("A review of this application") // CreateTeamDarApplicationReviewRequest | DataAccessApplicationReview definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessApplicationReviewAPI.UpdateTeamDarApplicationReview(context.Background(), teamId, id, reviewId).CreateTeamDarApplicationReviewRequest(createTeamDarApplicationReviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessApplicationReviewAPI.UpdateTeamDarApplicationReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamDarApplicationReview`: UpdateTeamDarApplicationQuestionReview200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessApplicationReviewAPI.UpdateTeamDarApplicationReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 
**reviewId** | **int32** | DAR application review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamDarApplicationReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **createTeamDarApplicationReviewRequest** | [**CreateTeamDarApplicationReviewRequest**](CreateTeamDarApplicationReviewRequest.md) | DataAccessApplicationReview definition | 

### Return type

[**UpdateTeamDarApplicationQuestionReview200Response**](UpdateTeamDarApplicationQuestionReview200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

