# \SavedSearchAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateSavedSearches**](SavedSearchAPI.md#CreateSavedSearches) | **Post** /api/v1/saved_searches | SavedSearch@store
[**DeleteSavedSearches**](SavedSearchAPI.md#DeleteSavedSearches) | **Delete** /api/v1/saved_searches/{id} | SavedSearch@destroy
[**EditSavedSearches**](SavedSearchAPI.md#EditSavedSearches) | **Patch** /api/v1/saved_searches/{id} | SavedSearch@update
[**FetchAllSavedSearches**](SavedSearchAPI.md#FetchAllSavedSearches) | **Get** /api/v1/saved_searches | SavedSearch@index
[**FetchSavedSearches**](SavedSearchAPI.md#FetchSavedSearches) | **Get** /api/v1/saved_searches/{id} | SavedSearch@show
[**UpdateSavedSearches**](SavedSearchAPI.md#UpdateSavedSearches) | **Put** /api/v1/saved_searches/{id} | SavedSearch@update



## CreateSavedSearches

> CreateCategories200Response CreateSavedSearches(ctx).CreateSavedSearchesRequest(createSavedSearchesRequest).Execute()

SavedSearch@store



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
	createSavedSearchesRequest := *openapiclient.NewCreateSavedSearchesRequest("Name", true) // CreateSavedSearchesRequest | Saved search definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.CreateSavedSearches(context.Background()).CreateSavedSearchesRequest(createSavedSearchesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.CreateSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateSavedSearches`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.CreateSavedSearches`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSavedSearchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createSavedSearchesRequest** | [**CreateSavedSearchesRequest**](CreateSavedSearchesRequest.md) | Saved search definition | 

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


## DeleteSavedSearches

> DeleteAliases200Response DeleteSavedSearches(ctx, id).Execute()

SavedSearch@destroy



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
	id := int32(1) // int32 | saved search id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.DeleteSavedSearches(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.DeleteSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteSavedSearches`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.DeleteSavedSearches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | saved search id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteSavedSearchesRequest struct via the builder pattern


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


## EditSavedSearches

> UpdateSavedSearches200Response EditSavedSearches(ctx, id).EditSavedSearchesRequest(editSavedSearchesRequest).Execute()

SavedSearch@update



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
	id := int32(1) // int32 | saved search id
	editSavedSearchesRequest := *openapiclient.NewEditSavedSearchesRequest() // EditSavedSearchesRequest | Saved search definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.EditSavedSearches(context.Background(), id).EditSavedSearchesRequest(editSavedSearchesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.EditSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditSavedSearches`: UpdateSavedSearches200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.EditSavedSearches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | saved search id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditSavedSearchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editSavedSearchesRequest** | [**EditSavedSearchesRequest**](EditSavedSearchesRequest.md) | Saved search definition | 

### Return type

[**UpdateSavedSearches200Response**](UpdateSavedSearches200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllSavedSearches

> FetchAllSavedSearches200Response FetchAllSavedSearches(ctx).PerPage(perPage).Execute()

SavedSearch@index



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
	perPage := int32(56) // int32 | Specify number of results per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.FetchAllSavedSearches(context.Background()).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.FetchAllSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllSavedSearches`: FetchAllSavedSearches200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.FetchAllSavedSearches`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllSavedSearchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Specify number of results per page | 

### Return type

[**FetchAllSavedSearches200Response**](FetchAllSavedSearches200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchSavedSearches

> FetchAllSavedSearches200Response FetchSavedSearches(ctx, id).Execute()

SavedSearch@show



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
	id := int32(1) // int32 | saved search id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.FetchSavedSearches(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.FetchSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchSavedSearches`: FetchAllSavedSearches200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.FetchSavedSearches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | saved search id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchSavedSearchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllSavedSearches200Response**](FetchAllSavedSearches200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSavedSearches

> UpdateSavedSearches200Response UpdateSavedSearches(ctx, id).UpdateSavedSearchesRequest(updateSavedSearchesRequest).Execute()

SavedSearch@update



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
	id := int32(1) // int32 | saved search id
	updateSavedSearchesRequest := *openapiclient.NewUpdateSavedSearchesRequest("Name", "true") // UpdateSavedSearchesRequest | Saved search definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SavedSearchAPI.UpdateSavedSearches(context.Background(), id).UpdateSavedSearchesRequest(updateSavedSearchesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SavedSearchAPI.UpdateSavedSearches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateSavedSearches`: UpdateSavedSearches200Response
	fmt.Fprintf(os.Stdout, "Response from `SavedSearchAPI.UpdateSavedSearches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | saved search id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSavedSearchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateSavedSearchesRequest** | [**UpdateSavedSearchesRequest**](UpdateSavedSearchesRequest.md) | Saved search definition | 

### Return type

[**UpdateSavedSearches200Response**](UpdateSavedSearches200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

