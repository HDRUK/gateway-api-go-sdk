# \IntegrationCollectionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCollectionsIntegrations**](IntegrationCollectionsAPI.md#CreateCollectionsIntegrations) | **Post** /api/v1/integrations/collections | IntegrationCollectionController@store
[**DeleteCollectionsIntegrations**](IntegrationCollectionsAPI.md#DeleteCollectionsIntegrations) | **Delete** /api/v1/integrations/collections/{id} | Delete a collection
[**EditCollectionsIntegrations**](IntegrationCollectionsAPI.md#EditCollectionsIntegrations) | **Patch** /api/v1/integrations/collections/{id} | Edit a collection
[**FetchAllCollectionsIntegrations**](IntegrationCollectionsAPI.md#FetchAllCollectionsIntegrations) | **Get** /api/v1/integrations/collections | IntegrationCollectionController@index
[**FetchCollectionsIntegrations**](IntegrationCollectionsAPI.md#FetchCollectionsIntegrations) | **Get** /api/v1/integrations/collections/{id} | IntegrationCollectionController@show
[**UpdateCollectionsIntegrations**](IntegrationCollectionsAPI.md#UpdateCollectionsIntegrations) | **Put** /api/v1/integrations/collections/{id} | Update a collection



## CreateCollectionsIntegrations

> CreateCategories200Response CreateCollectionsIntegrations(ctx).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()

IntegrationCollectionController@store



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
	updateTeamCollectionsRequest := *openapiclient.NewUpdateTeamCollectionsRequest() // UpdateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationCollectionsAPI.CreateCollectionsIntegrations(context.Background()).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.CreateCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCollectionsIntegrations`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.CreateCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCollectionsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials | 

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


## DeleteCollectionsIntegrations

> DeleteAliases200Response DeleteCollectionsIntegrations(ctx, id).Execute()

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
	resp, r, err := apiClient.IntegrationCollectionsAPI.DeleteCollectionsIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.DeleteCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCollectionsIntegrations`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.DeleteCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCollectionsIntegrationsRequest struct via the builder pattern


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


## EditCollectionsIntegrations

> FetchCollections200Response EditCollectionsIntegrations(ctx, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()

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
	updateTeamCollectionsRequest := *openapiclient.NewUpdateTeamCollectionsRequest() // UpdateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationCollectionsAPI.EditCollectionsIntegrations(context.Background(), id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.EditCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditCollectionsIntegrations`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.EditCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditCollectionsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials | 

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


## FetchAllCollectionsIntegrations

> FetchAllCollections200Response FetchAllCollectionsIntegrations(ctx).Name(name).PerPage(perPage).Execute()

IntegrationCollectionController@index



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
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationCollectionsAPI.FetchAllCollectionsIntegrations(context.Background()).Name(name).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.FetchAllCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCollectionsIntegrations`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.FetchAllCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCollectionsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Filter collections by name | 
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


## FetchCollectionsIntegrations

> FetchCollections200Response FetchCollectionsIntegrations(ctx, id).Execute()

IntegrationCollectionController@show



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
	resp, r, err := apiClient.IntegrationCollectionsAPI.FetchCollectionsIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.FetchCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollectionsIntegrations`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.FetchCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## UpdateCollectionsIntegrations

> FetchCollections200Response UpdateCollectionsIntegrations(ctx, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()

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
	updateTeamCollectionsRequest := *openapiclient.NewUpdateTeamCollectionsRequest() // UpdateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationCollectionsAPI.UpdateCollectionsIntegrations(context.Background(), id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationCollectionsAPI.UpdateCollectionsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCollectionsIntegrations`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `IntegrationCollectionsAPI.UpdateCollectionsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCollectionsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials | 

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

