# \PublicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountUniqueFieldsPublications**](PublicationAPI.md#CountUniqueFieldsPublications) | **Get** /api/v1/publication/count/{field} | PublicationController@count
[**CreatePublications**](PublicationAPI.md#CreatePublications) | **Post** /api/v1/publications | PublicationController@store
[**DeletePublications**](PublicationAPI.md#DeletePublications) | **Delete** /api/v1/publications/{id} | PublicationController@destroy
[**EditPublications**](PublicationAPI.md#EditPublications) | **Patch** /api/v1/publications/{id} | PublicationController@edit
[**FetchAllPublications**](PublicationAPI.md#FetchAllPublications) | **Get** /api/v1/publications | PublicationController@index
[**FetchAllPublicationsV2**](PublicationAPI.md#FetchAllPublicationsV2) | **Get** /api/v2/publications | PublicationController@indexActive
[**FetchPublications**](PublicationAPI.md#FetchPublications) | **Get** /api/v1/publications/{id} | PublicationController@show
[**FetchPublicationsV2**](PublicationAPI.md#FetchPublicationsV2) | **Get** /api/v2/publications/{id} | PublicationController@showActive
[**UpdatePublications**](PublicationAPI.md#UpdatePublications) | **Put** /api/v1/publications/{id} | PublicationController@update



## CountUniqueFieldsPublications

> CountUniqueFieldsCollections200Response CountUniqueFieldsPublications(ctx, field).OwnerId(ownerId).TeamId(teamId).Execute()

PublicationController@count



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
	field := "status" // string | name of the field to perform a count on
	ownerId := int32(1) // int32 | owner id
	teamId := int32(1) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CountUniqueFieldsPublications(context.Background(), field).OwnerId(ownerId).TeamId(teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CountUniqueFieldsPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsPublications`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CountUniqueFieldsPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ownerId** | **int32** | owner id | 
 **teamId** | **int32** |  | 

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePublications

> CreateDarIntegration201Response CreatePublications(ctx).CreatePublicationsRequest(createPublicationsRequest).Execute()

PublicationController@store



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
	createPublicationsRequest := *openapiclient.NewCreatePublicationsRequest() // CreatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CreatePublications(context.Background()).CreatePublicationsRequest(createPublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CreatePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublications`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CreatePublications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials | 

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


## DeletePublications

> DeleteFederation200Response DeletePublications(ctx, id).Execute()

PublicationController@destroy



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.DeletePublications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.DeletePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePublications`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.DeletePublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteFederation200Response**](DeleteFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditPublications

> FetchPublications200Response EditPublications(ctx, id).UpdatePublicationsRequest(updatePublicationsRequest).Unarchive(unarchive).Execute()

PublicationController@edit



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
	id := int32(1) // int32 | publications id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a publication (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.EditPublications(context.Background(), id).UpdatePublicationsRequest(updatePublicationsRequest).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.EditPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditPublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.EditPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publications id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a publication | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublications

> FetchAllPublications200Response FetchAllPublications(ctx).PaperTitle(paperTitle).OwnerId(ownerId).TeamId(teamId).Status(status).Execute()

PublicationController@index



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
	paperTitle := "paperTitle_example" // string | Filter tools by paper title (optional)
	ownerId := TODO // int | Filter tools by owner id (optional)
	teamId := TODO // int | Filter tools by team id (optional)
	status := "ACTIVE" // string | Publication status to filter by ('ACTIVE', 'DRAFT', 'ARCHIVED') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublications(context.Background()).PaperTitle(paperTitle).OwnerId(ownerId).TeamId(teamId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublications`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **paperTitle** | **string** | Filter tools by paper title | 
 **ownerId** | [**int**](int.md) | Filter tools by owner id | 
 **teamId** | [**int**](int.md) | Filter tools by team id | 
 **status** | **string** | Publication status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublicationsV2

> FetchAllPublications200Response FetchAllPublicationsV2(ctx).PaperTitle(paperTitle).WithRelated(withRelated).PerPage(perPage).Execute()

PublicationController@indexActive



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
	paperTitle := "paperTitle_example" // string | Filter tools by paper title (optional)
	withRelated := true // bool | Return related datasets (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublicationsV2(context.Background()).PaperTitle(paperTitle).WithRelated(withRelated).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublicationsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublicationsV2`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublicationsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **paperTitle** | **string** | Filter tools by paper title | 
 **withRelated** | **bool** | Return related datasets | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublications

> FetchPublications200Response FetchPublications(ctx, id).Execute()

PublicationController@show



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublicationsV2

> FetchPublications200Response FetchPublicationsV2(ctx, id).Execute()

PublicationController@showActive



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublicationsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublicationsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublicationsV2`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublicationsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePublications

> FetchPublications200Response UpdatePublications(ctx, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

PublicationController@update



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
	id := int32(1) // int32 | publication id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.UpdatePublications(context.Background(), id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.UpdatePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.UpdatePublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

