# \EnquiryThreadAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateEnquiryThreads**](EnquiryThreadAPI.md#CreateEnquiryThreads) | **Post** /api/v1/enquiry_threads | EnquiryThread@store
[**FetchAllEnquiryThreads**](EnquiryThreadAPI.md#FetchAllEnquiryThreads) | **Get** /api/v1/enquiry_threads | EnquiryThread@index
[**FetchEnquiryThreads**](EnquiryThreadAPI.md#FetchEnquiryThreads) | **Get** /api/v1/enquiry_threads/{id} | EnquiryThread@show



## CreateEnquiryThreads

> CreateCategories200Response CreateEnquiryThreads(ctx).CreateEnquiryThreadsRequest(createEnquiryThreadsRequest).Execute()

EnquiryThread@store



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
	createEnquiryThreadsRequest := *openapiclient.NewCreateEnquiryThreadsRequest(int32(123), "Project Title") // CreateEnquiryThreadsRequest | EnquiryThread definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnquiryThreadAPI.CreateEnquiryThreads(context.Background()).CreateEnquiryThreadsRequest(createEnquiryThreadsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnquiryThreadAPI.CreateEnquiryThreads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateEnquiryThreads`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `EnquiryThreadAPI.CreateEnquiryThreads`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateEnquiryThreadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createEnquiryThreadsRequest** | [**CreateEnquiryThreadsRequest**](CreateEnquiryThreadsRequest.md) | EnquiryThread definition | 

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


## FetchAllEnquiryThreads

> FetchAllEnquiryThreads200Response FetchAllEnquiryThreads(ctx).PerPage(perPage).Execute()

EnquiryThread@index



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
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnquiryThreadAPI.FetchAllEnquiryThreads(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnquiryThreadAPI.FetchAllEnquiryThreads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllEnquiryThreads`: FetchAllEnquiryThreads200Response
	fmt.Fprintf(os.Stdout, "Response from `EnquiryThreadAPI.FetchAllEnquiryThreads`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllEnquiryThreadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllEnquiryThreads200Response**](FetchAllEnquiryThreads200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchEnquiryThreads

> FetchAllEnquiryThreads200Response FetchEnquiryThreads(ctx, id).Execute()

EnquiryThread@show



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
	id := int32(1) // int32 | EnquiryThread id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnquiryThreadAPI.FetchEnquiryThreads(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnquiryThreadAPI.FetchEnquiryThreads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchEnquiryThreads`: FetchAllEnquiryThreads200Response
	fmt.Fprintf(os.Stdout, "Response from `EnquiryThreadAPI.FetchEnquiryThreads`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | EnquiryThread id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchEnquiryThreadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllEnquiryThreads200Response**](FetchAllEnquiryThreads200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

