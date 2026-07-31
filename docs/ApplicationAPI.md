# \ApplicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateApplications**](ApplicationAPI.md#CreateApplications) | **Post** /api/v1/applications | ApplicationController@store
[**DeleteApplications**](ApplicationAPI.md#DeleteApplications) | **Delete** /api/v1/applications/{id} | ApplicationController@delete
[**EditApplications**](ApplicationAPI.md#EditApplications) | **Patch** /api/v1/applications/{id} | ApplicationController@edit
[**FetchAllApplications**](ApplicationAPI.md#FetchAllApplications) | **Get** /api/v1/applications | ApplicationController@index
[**FetchAllSitemap**](ApplicationAPI.md#FetchAllSitemap) | **Get** /api/v1/sitemap | SiteMapController@index
[**FetchApplications**](ApplicationAPI.md#FetchApplications) | **Get** /api/v1/applications/{id} | ApplicationController@show
[**PatchApplicationsClientId**](ApplicationAPI.md#PatchApplicationsClientId) | **Patch** /api/v1/applications/{id}/clientid | ApplicationController@generateClientIdById
[**UpdateApplications**](ApplicationAPI.md#UpdateApplications) | **Put** /api/v1/applications/{id} | ApplicationController@update



## CreateApplications

> CreateApplications200Response CreateApplications(ctx).CreateApplicationsRequest(createApplicationsRequest).Execute()

ApplicationController@store



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
	createApplicationsRequest := *openapiclient.NewCreateApplicationsRequest() // CreateApplicationsRequest | Application definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.CreateApplications(context.Background()).CreateApplicationsRequest(createApplicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.CreateApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateApplications`: CreateApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.CreateApplications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createApplicationsRequest** | [**CreateApplicationsRequest**](CreateApplicationsRequest.md) | Application definition | 

### Return type

[**CreateApplications200Response**](CreateApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteApplications

> DeleteAliases200Response DeleteApplications(ctx, id).Execute()

ApplicationController@delete



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
	id := int32(1) // int32 | application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.DeleteApplications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.DeleteApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteApplications`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.DeleteApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteApplicationsRequest struct via the builder pattern


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


## EditApplications

> UpdateApplications200Response EditApplications(ctx, id).EditApplicationsRequest(editApplicationsRequest).Execute()

ApplicationController@edit



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
	id := int32(1) // int32 | application id
	editApplicationsRequest := *openapiclient.NewEditApplicationsRequest() // EditApplicationsRequest | ActivityLog definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.EditApplications(context.Background(), id).EditApplicationsRequest(editApplicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.EditApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditApplications`: UpdateApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.EditApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editApplicationsRequest** | [**EditApplicationsRequest**](EditApplicationsRequest.md) | ActivityLog definition | 

### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllApplications

> FetchAllApplications200Response FetchAllApplications(ctx).TeamId(teamId).Text(text).Status(status).Execute()

ApplicationController@index



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
	teamId := int32(56) // int32 | Filter Apps by the teamId (optional)
	text := "text_example" // string | Search term to filter by application name or description. (optional)
	status := "status_example" // string | Filter by application status is enabled or not (true or false). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.FetchAllApplications(context.Background()).TeamId(teamId).Text(text).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.FetchAllApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllApplications`: FetchAllApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.FetchAllApplications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **int32** | Filter Apps by the teamId | 
 **text** | **string** | Search term to filter by application name or description. | 
 **status** | **string** | Filter by application status is enabled or not (true or false). | 

### Return type

[**FetchAllApplications200Response**](FetchAllApplications200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllSitemap

> FetchAllSitemap200Response FetchAllSitemap(ctx).Execute()

SiteMapController@index



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
	resp, r, err := apiClient.ApplicationAPI.FetchAllSitemap(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.FetchAllSitemap``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllSitemap`: FetchAllSitemap200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.FetchAllSitemap`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllSitemapRequest struct via the builder pattern


### Return type

[**FetchAllSitemap200Response**](FetchAllSitemap200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchApplications

> FetchApplications200Response FetchApplications(ctx, id).Execute()

ApplicationController@show



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
	id := int32(1) // int32 | application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.FetchApplications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.FetchApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchApplications`: FetchApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.FetchApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchApplications200Response**](FetchApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchApplicationsClientId

> UpdateApplications200Response PatchApplicationsClientId(ctx, id).Execute()

ApplicationController@generateClientIdById



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
	id := int32(1) // int32 | application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.PatchApplicationsClientId(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.PatchApplicationsClientId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchApplicationsClientId`: UpdateApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.PatchApplicationsClientId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchApplicationsClientIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateApplications

> UpdateApplications200Response UpdateApplications(ctx, id).UpdateApplicationsRequest(updateApplicationsRequest).Execute()

ApplicationController@update



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
	id := int32(1) // int32 | application id
	updateApplicationsRequest := *openapiclient.NewUpdateApplicationsRequest("Corrupti in a voluptas. Eligendi saepe sed sit.", "https://via.placeholder.com/640x480.png/0022dd?text=animals+aliquam", "Praesentium ut et quae suscipit ut quo adipisci. Enim ut tenetur ad omnis ut consequatur. ", int32(1), int32(2), false, []interface{}{nil}) // UpdateApplicationsRequest | ActivityLog definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationAPI.UpdateApplications(context.Background(), id).UpdateApplicationsRequest(updateApplicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationAPI.UpdateApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateApplications`: UpdateApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ApplicationAPI.UpdateApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateApplicationsRequest** | [**UpdateApplicationsRequest**](UpdateApplicationsRequest.md) | ActivityLog definition | 

### Return type

[**UpdateApplications200Response**](UpdateApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

