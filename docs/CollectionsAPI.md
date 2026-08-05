# \CollectionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountUniqueFieldsCollections**](CollectionsAPI.md#CountUniqueFieldsCollections) | **Get** /api/v1/collections/count/{field} | CollectionController@count
[**CountUniqueFieldsCollectionsV2**](CollectionsAPI.md#CountUniqueFieldsCollectionsV2) | **Get** /api/v2/collections/count/{field} | CollectionController@count
[**CreateCollections**](CollectionsAPI.md#CreateCollections) | **Post** /api/v2/collections | CollectionController@store
[**DeleteCollectionsV2**](CollectionsAPI.md#DeleteCollectionsV2) | **Delete** /api/v2/collections/{id} | Delete a collection
[**EditCollectionsV2**](CollectionsAPI.md#EditCollectionsV2) | **Patch** /api/v2/collections/{id} | Edit a collection
[**FetchAllCollections**](CollectionsAPI.md#FetchAllCollections) | **Get** /api/v1/collections | CollectionController@index
[**FetchAllCollectionsV2**](CollectionsAPI.md#FetchAllCollectionsV2) | **Get** /api/v2/collections | CollectionController@index
[**FetchCollections**](CollectionsAPI.md#FetchCollections) | **Get** /api/v1/collections/{id} | CollectionController@show
[**FetchCollectionsV2**](CollectionsAPI.md#FetchCollectionsV2) | **Get** /api/v2/collections/{id} | CollectionController@show
[**UpdateCollectionsV2**](CollectionsAPI.md#UpdateCollectionsV2) | **Put** /api/v2/collections/{id} | Update a collection



## CountUniqueFieldsCollections

> CountUniqueFieldsCollections200Response CountUniqueFieldsCollections(ctx, field).TeamId(teamId).UserId(userId).Execute()

CollectionController@count



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
	teamId := int32(1) // int32 | team id
	userId := int32(1) // int32 | user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CountUniqueFieldsCollections(context.Background(), field).TeamId(teamId).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountUniqueFieldsCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsCollections`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountUniqueFieldsCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **teamId** | **int32** | team id | 
 **userId** | **int32** | user id | 

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


## CountUniqueFieldsCollectionsV2

> CountUniqueFieldsCollections200Response CountUniqueFieldsCollectionsV2(ctx, field).Execute()

CollectionController@count



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CountUniqueFieldsCollectionsV2(context.Background(), field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountUniqueFieldsCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsCollectionsV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountUniqueFieldsCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## CreateCollections

> CreateDarIntegration201Response CreateCollections(ctx).CreateCollectionsRequest(createCollectionsRequest).Execute()

CollectionController@store



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
	createCollectionsRequest := *openapiclient.NewCreateCollectionsRequest() // CreateCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CreateCollections(context.Background()).CreateCollectionsRequest(createCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CreateCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCollections`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CreateCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials | 

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


## DeleteCollectionsV2

> DeleteApplications200Response DeleteCollectionsV2(ctx, id).Execute()

Delete a collection



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.DeleteCollectionsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.DeleteCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCollectionsV2`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.DeleteCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCollectionsV2Request struct via the builder pattern


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


## EditCollectionsV2

> FetchCollections200Response EditCollectionsV2(ctx, id).EditCollectionsV2Request(editCollectionsV2Request).Unarchive(unarchive).Execute()

Edit a collection



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
	id := int32(1) // int32 | collection id
	editCollectionsV2Request := *openapiclient.NewEditCollectionsV2Request() // EditCollectionsV2Request | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a collection (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.EditCollectionsV2(context.Background(), id).EditCollectionsV2Request(editCollectionsV2Request).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.EditCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.EditCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCollectionsV2Request** | [**EditCollectionsV2Request**](EditCollectionsV2Request.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a collection | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllCollections

> FetchAllCollections200Response FetchAllCollections(ctx).Name(name).TeamId(teamId).UserId(userId).Title(title).Status(status).PerPage(perPage).Execute()

CollectionController@index



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
	name := "name_example" // string | Filter collections by name (optional)
	teamId := int32(56) // int32 | Filter collections by team ID (optional)
	userId := int32(56) // int32 | Filter collections by user ID (optional)
	title := "title_example" // string | Filter collections by title (optional)
	status := "status_example" // string | Filter collections by status (DRAFT, ACTIVE, ARCHIVED) (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchAllCollections(context.Background()).Name(name).TeamId(teamId).UserId(userId).Title(title).Status(status).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchAllCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCollections`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchAllCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Filter collections by name | 
 **teamId** | **int32** | Filter collections by team ID | 
 **userId** | **int32** | Filter collections by user ID | 
 **title** | **string** | Filter collections by title | 
 **status** | **string** | Filter collections by status (DRAFT, ACTIVE, ARCHIVED) | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllCollectionsV2

> FetchAllCollections200Response FetchAllCollectionsV2(ctx).Execute()

CollectionController@index



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
	resp, r, err := apiClient.CollectionsAPI.FetchAllCollectionsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchAllCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchAllCollectionsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCollectionsV2Request struct via the builder pattern


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCollections

> FetchCollections200Response FetchCollections(ctx, id).ViewType(viewType).Execute()

CollectionController@show



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
	id := int32(1) // int32 | collection id
	viewType := "full" // string | Query flag to show full collection data or a trimmed version (defaults to full). (optional) (default to "full")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchCollections(context.Background(), id).ViewType(viewType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollections`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [default to &quot;full&quot;]

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCollectionsV2

> FetchCollections200Response FetchCollectionsV2(ctx, id).ViewType(viewType).Execute()

CollectionController@show



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
	id := int32(1) // int32 | collection id
	viewType := "full" // string | Query flag to show full collection data or a trimmed version (defaults to full). (optional) (default to "full")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchCollectionsV2(context.Background(), id).ViewType(viewType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [default to &quot;full&quot;]

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCollectionsV2

> FetchCollections200Response UpdateCollectionsV2(ctx, id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()

Update a collection



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
	id := int32(1) // int32 | collection id
	updateCollectionsV2Request := *openapiclient.NewUpdateCollectionsV2Request() // UpdateCollectionsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.UpdateCollectionsV2(context.Background(), id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.UpdateCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.UpdateCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCollectionsV2Request** | [**UpdateCollectionsV2Request**](UpdateCollectionsV2Request.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

