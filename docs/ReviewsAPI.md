# \ReviewsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteReviews**](ReviewsAPI.md#DeleteReviews) | **Delete** /api/v1/reviews/{id} | Delete a review
[**EditReviews**](ReviewsAPI.md#EditReviews) | **Patch** /api/v1/reviews/{id} | Edit a review
[**UpdateReviews**](ReviewsAPI.md#UpdateReviews) | **Put** /api/v1/reviews/{id} | Update a review



## DeleteReviews

> DeleteApplications200Response DeleteReviews(ctx, id).Execute()

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
	// response from `DeleteReviews`: DeleteApplications200Response
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

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditReviews

> UpdateReviews200Response EditReviews(ctx, id).UpdateReviewsRequest(updateReviewsRequest).Execute()

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
	updateReviewsRequest := *openapiclient.NewUpdateReviewsRequest() // UpdateReviewsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.EditReviews(context.Background(), id).UpdateReviewsRequest(updateReviewsRequest).Execute()
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

 **updateReviewsRequest** | [**UpdateReviewsRequest**](UpdateReviewsRequest.md) | Pass user credentials | 

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


## UpdateReviews

> UpdateReviews200Response UpdateReviews(ctx, id).UpdateReviewsRequest(updateReviewsRequest).Execute()

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
	updateReviewsRequest := *openapiclient.NewUpdateReviewsRequest() // UpdateReviewsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReviewsAPI.UpdateReviews(context.Background(), id).UpdateReviewsRequest(updateReviewsRequest).Execute()
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

 **updateReviewsRequest** | [**UpdateReviewsRequest**](UpdateReviewsRequest.md) | Pass user credentials | 

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

