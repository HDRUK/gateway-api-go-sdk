# \ReviewsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateReviews**](ReviewsAPI.md#CreateReviews) | **Post** /api/v1/reviews | ReviewController@store
[**DeleteReviews**](ReviewsAPI.md#DeleteReviews) | **Delete** /api/v1/reviews/{id} | Delete a review
[**EditReviews**](ReviewsAPI.md#EditReviews) | **Patch** /api/v1/reviews/{id} | Edit a review
[**FetchAllReviews**](ReviewsAPI.md#FetchAllReviews) | **Get** /api/v1/reviews | ReviewController@index
[**FetchReviews**](ReviewsAPI.md#FetchReviews) | **Get** /api/v1/reviews/{id} | ReviewController@show
[**UpdateReviews**](ReviewsAPI.md#UpdateReviews) | **Put** /api/v1/reviews/{id} | Update a review



## CreateReviews

> CreateCategories200Response CreateReviews(ctx).CreateReviewsRequest(createReviewsRequest).Execute()

ReviewController@store



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
	createReviewsRequest := *openapiclient.NewCreateReviewsRequest() // CreateReviewsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.CreateReviews(context.Background()).CreateReviewsRequest(createReviewsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.CreateReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReviews`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.CreateReviews`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateReviewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials | 

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


## DeleteReviews

> DeleteAliases200Response DeleteReviews(ctx, id).Execute()

Delete a review



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
	id := int32(1) // int32 | review id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.DeleteReviews(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.DeleteReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteReviews`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.DeleteReviews`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteReviewsRequest struct via the builder pattern


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


## EditReviews

> UpdateReviews200Response EditReviews(ctx, id).CreateReviewsRequest(createReviewsRequest).Execute()

Edit a review



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
	id := int32(1) // int32 | review id
	createReviewsRequest := *openapiclient.NewCreateReviewsRequest() // CreateReviewsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.EditReviews(context.Background(), id).CreateReviewsRequest(createReviewsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.EditReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditReviews`: UpdateReviews200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.EditReviews`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditReviewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials | 

### Return type

[**UpdateReviews200Response**](UpdateReviews200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllReviews

> FetchAllReviews200Response FetchAllReviews(ctx).Execute()

ReviewController@index



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
	resp, r, err := apiClient.ReviewsAPI.FetchAllReviews(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.FetchAllReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllReviews`: FetchAllReviews200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.FetchAllReviews`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllReviewsRequest struct via the builder pattern


### Return type

[**FetchAllReviews200Response**](FetchAllReviews200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchReviews

> FetchAllReviews200Response FetchReviews(ctx, id).Execute()

ReviewController@show



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
	id := int32(1) // int32 | review id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.FetchReviews(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.FetchReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchReviews`: FetchAllReviews200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.FetchReviews`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchReviewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllReviews200Response**](FetchAllReviews200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateReviews

> UpdateReviews200Response UpdateReviews(ctx, id).CreateReviewsRequest(createReviewsRequest).Execute()

Update a review



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
	id := int32(1) // int32 | review id
	createReviewsRequest := *openapiclient.NewCreateReviewsRequest() // CreateReviewsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.UpdateReviews(context.Background(), id).CreateReviewsRequest(createReviewsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReviewsAPI.UpdateReviews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReviews`: UpdateReviews200Response
	fmt.Fprintf(os.Stdout, "Response from `ReviewsAPI.UpdateReviews`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | review id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReviewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createReviewsRequest** | [**CreateReviewsRequest**](CreateReviewsRequest.md) | Pass user credentials | 

### Return type

[**UpdateReviews200Response**](UpdateReviews200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

