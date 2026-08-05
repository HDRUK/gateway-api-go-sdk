# \ToolsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountUniqueFieldsTools**](ToolsAPI.md#CountUniqueFieldsTools) | **Get** /api/v1/tools/count/{field} | ToolController@count
[**CreateTools**](ToolsAPI.md#CreateTools) | **Post** /api/v1/tools | ToolController@store
[**CreateToolsByTeamV2**](ToolsAPI.md#CreateToolsByTeamV2) | **Post** /api/v2/teams/{teamId}/tools | ToolController@store
[**CreateToolsIntegrations**](ToolsAPI.md#CreateToolsIntegrations) | **Post** /api/v1/integrations/tools | IntegrationToolController@store
[**DeleteTools**](ToolsAPI.md#DeleteTools) | **Delete** /api/v1/tools/{id} | ToolController@destroy
[**DeleteToolsByTeamidV2**](ToolsAPI.md#DeleteToolsByTeamidV2) | **Delete** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@destroy
[**DeleteToolsIntegrations**](ToolsAPI.md#DeleteToolsIntegrations) | **Delete** /api/v1/integrations/tools/{id} | IntegrationToolController@destroy
[**EditTools**](ToolsAPI.md#EditTools) | **Patch** /api/v1/tools/{id} | ToolController@edit
[**EditToolsByTeamidV2**](ToolsAPI.md#EditToolsByTeamidV2) | **Patch** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@edit
[**EditToolsIntegrations**](ToolsAPI.md#EditToolsIntegrations) | **Patch** /api/v1/integrations/tools/{id} | IntegrationToolController@edit
[**FetchAllTools**](ToolsAPI.md#FetchAllTools) | **Get** /api/v1/tools | Fetch all tools
[**FetchAllToolsIntegrations**](ToolsAPI.md#FetchAllToolsIntegrations) | **Get** /api/v1/integrations/tools | IntegrationToolController@index
[**FetchAllToolsV2**](ToolsAPI.md#FetchAllToolsV2) | **Get** /api/v2/tools | ToolController@indexActive
[**FetchTools**](ToolsAPI.md#FetchTools) | **Get** /api/v1/tools/{id} | ToolController@show
[**FetchToolsIntegrations**](ToolsAPI.md#FetchToolsIntegrations) | **Get** /api/v1/integrations/tools/{id} | IntegrationToolController@show
[**FetchToolsV2**](ToolsAPI.md#FetchToolsV2) | **Get** /api/v2/tools/{id} | ToolController@showActive
[**UpdateTools**](ToolsAPI.md#UpdateTools) | **Put** /api/v1/tools/{id} | ToolController@update
[**UpdateToolsByTeamidV2**](ToolsAPI.md#UpdateToolsByTeamidV2) | **Put** /api/v2/teams/{teamId}/tools/{id} | TeamToolController@update
[**UpdateToolsIntegrations**](ToolsAPI.md#UpdateToolsIntegrations) | **Put** /api/v1/integrations/tools/{id} | IntegrationToolController@update



## CountUniqueFieldsTools

> CountUniqueFieldsCollections200Response CountUniqueFieldsTools(ctx, field).TeamId(teamId).Execute()

ToolController@count



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CountUniqueFieldsTools(context.Background(), field).TeamId(teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.CountUniqueFieldsTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsTools`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.CountUniqueFieldsTools`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **teamId** | **int32** | team id | 

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


## CreateTools

> CreateDarIntegration201Response CreateTools(ctx).CreateToolsRequest(createToolsRequest).Execute()

ToolController@store



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
	createToolsRequest := *openapiclient.NewCreateToolsRequest() // CreateToolsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CreateTools(context.Background()).CreateToolsRequest(createToolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.CreateTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTools`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.CreateTools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createToolsRequest** | [**CreateToolsRequest**](CreateToolsRequest.md) | Pass user credentials | 

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


## CreateToolsByTeamV2

> CreateDarIntegration201Response CreateToolsByTeamV2(ctx, teamId).CreateToolsRequest(createToolsRequest).Execute()

ToolController@store



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
	teamId := int32(1) // int32 | team id
	createToolsRequest := *openapiclient.NewCreateToolsRequest() // CreateToolsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CreateToolsByTeamV2(context.Background(), teamId).CreateToolsRequest(createToolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.CreateToolsByTeamV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateToolsByTeamV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.CreateToolsByTeamV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateToolsByTeamV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createToolsRequest** | [**CreateToolsRequest**](CreateToolsRequest.md) | Pass user credentials | 

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


## CreateToolsIntegrations

> CreateDarIntegration201Response CreateToolsIntegrations(ctx).CreateToolsIntegrationsRequest(createToolsIntegrationsRequest).Execute()

IntegrationToolController@store



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
	createToolsIntegrationsRequest := *openapiclient.NewCreateToolsIntegrationsRequest() // CreateToolsIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CreateToolsIntegrations(context.Background()).CreateToolsIntegrationsRequest(createToolsIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.CreateToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateToolsIntegrations`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.CreateToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateToolsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createToolsIntegrationsRequest** | [**CreateToolsIntegrationsRequest**](CreateToolsIntegrationsRequest.md) | Pass user credentials | 

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


## DeleteTools

> DeleteFederation200Response DeleteTools(ctx, id).Execute()

ToolController@destroy



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
	id := int32(1) // int32 | tool id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.DeleteTools(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.DeleteTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTools`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.DeleteTools`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteToolsRequest struct via the builder pattern


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


## DeleteToolsByTeamidV2

> DeleteFederation200Response DeleteToolsByTeamidV2(ctx, teamId, id).Execute()

TeamToolController@destroy



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | tool id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.DeleteToolsByTeamidV2(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.DeleteToolsByTeamidV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteToolsByTeamidV2`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.DeleteToolsByTeamidV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteToolsByTeamidV2Request struct via the builder pattern


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


## DeleteToolsIntegrations

> DeleteFederation200Response DeleteToolsIntegrations(ctx, id).Execute()

IntegrationToolController@destroy



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
	id := int32(1) // int32 | tool id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.DeleteToolsIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.DeleteToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteToolsIntegrations`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.DeleteToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteToolsIntegrationsRequest struct via the builder pattern


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


## EditTools

> FetchToolsIntegrations200Response EditTools(ctx, id).UpdateToolsRequest(updateToolsRequest).Unarchive(unarchive).Execute()

ToolController@edit



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
	id := int32(1) // int32 | tool id
	updateToolsRequest := *openapiclient.NewUpdateToolsRequest() // UpdateToolsRequest | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a tool (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.EditTools(context.Background(), id).UpdateToolsRequest(updateToolsRequest).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.EditTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditTools`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.EditTools`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a tool | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditToolsByTeamidV2

> FetchToolsIntegrations200Response EditToolsByTeamidV2(ctx, teamId, id).UpdateToolsRequest(updateToolsRequest).Execute()

TeamToolController@edit



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | tool id
	updateToolsRequest := *openapiclient.NewUpdateToolsRequest() // UpdateToolsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.EditToolsByTeamidV2(context.Background(), teamId, id).UpdateToolsRequest(updateToolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.EditToolsByTeamidV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditToolsByTeamidV2`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.EditToolsByTeamidV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditToolsByTeamidV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditToolsIntegrations

> FetchToolsIntegrations200Response EditToolsIntegrations(ctx, id).UpdateToolsIntegrationsRequest(updateToolsIntegrationsRequest).Execute()

IntegrationToolController@edit



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
	id := int32(1) // int32 | tool id
	updateToolsIntegrationsRequest := *openapiclient.NewUpdateToolsIntegrationsRequest() // UpdateToolsIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.EditToolsIntegrations(context.Background(), id).UpdateToolsIntegrationsRequest(updateToolsIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.EditToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditToolsIntegrations`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.EditToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditToolsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateToolsIntegrationsRequest** | [**UpdateToolsIntegrationsRequest**](UpdateToolsIntegrationsRequest.md) | Pass user credentials | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllTools

> FetchAllTools200Response FetchAllTools(ctx).MongoId(mongoId).TeamId(teamId).UserId(userId).Title(title).Sort(sort).Execute()

Fetch all tools



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
	mongoId := "mongoId_example" // string | Filter tools by mongo ID (optional)
	teamId := int32(56) // int32 | Filter tools by team ID (optional)
	userId := int32(56) // int32 | Filter tools by user ID (optional)
	title := "title_example" // string | Filter tools by title (optional)
	sort := "name:asc" // string | Sort tools by a specific field and direction, e.g., 'name:asc' or 'created_at:desc' (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.FetchAllTools(context.Background()).MongoId(mongoId).TeamId(teamId).UserId(userId).Title(title).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchAllTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllTools`: FetchAllTools200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchAllTools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mongoId** | **string** | Filter tools by mongo ID | 
 **teamId** | **int32** | Filter tools by team ID | 
 **userId** | **int32** | Filter tools by user ID | 
 **title** | **string** | Filter tools by title | 
 **sort** | **string** | Sort tools by a specific field and direction, e.g., &#39;name:asc&#39; or &#39;created_at:desc&#39; | 

### Return type

[**FetchAllTools200Response**](FetchAllTools200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllToolsIntegrations

> FetchAllToolsIntegrations200Response FetchAllToolsIntegrations(ctx).Execute()

IntegrationToolController@index



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
	resp, r, err := apiClient.ToolsAPI.FetchAllToolsIntegrations(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchAllToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllToolsIntegrations`: FetchAllToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchAllToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllToolsIntegrationsRequest struct via the builder pattern


### Return type

[**FetchAllToolsIntegrations200Response**](FetchAllToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllToolsV2

> FetchAllTools200Response FetchAllToolsV2(ctx).Name(name).Sort(sort).Execute()

ToolController@indexActive



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
	name := "name_example" // string | Filter tools by name (optional)
	sort := "name:asc" // string | Sort tools by a specific field and direction, e.g., 'name:asc' or 'created_at:desc' (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.FetchAllToolsV2(context.Background()).Name(name).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchAllToolsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllToolsV2`: FetchAllTools200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchAllToolsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllToolsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Filter tools by name | 
 **sort** | **string** | Sort tools by a specific field and direction, e.g., &#39;name:asc&#39; or &#39;created_at:desc&#39; | 

### Return type

[**FetchAllTools200Response**](FetchAllTools200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTools

> FetchToolsIntegrations200Response FetchTools(ctx, id).ViewType(viewType).Execute()

ToolController@show



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
	id := int32(1) // int32 | tool id
	viewType := "full" // string | Query flag to show full tool data or a trimmed version (defaults to full). (optional) (default to "full")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.FetchTools(context.Background(), id).ViewType(viewType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTools`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchTools`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **viewType** | **string** | Query flag to show full tool data or a trimmed version (defaults to full). | [default to &quot;full&quot;]

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchToolsIntegrations

> FetchToolsIntegrations200Response FetchToolsIntegrations(ctx, id).Execute()

IntegrationToolController@show



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
	id := int32(1) // int32 | tool id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.FetchToolsIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchToolsIntegrations`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchToolsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchToolsV2

> FetchToolsIntegrations200Response FetchToolsV2(ctx, id).Execute()

ToolController@showActive



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
	id := int32(1) // int32 | tool id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.FetchToolsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.FetchToolsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchToolsV2`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.FetchToolsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchToolsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTools

> FetchToolsIntegrations200Response UpdateTools(ctx, id).UpdateToolsRequest(updateToolsRequest).Execute()

ToolController@update



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
	id := int32(1) // int32 | tool id
	updateToolsRequest := *openapiclient.NewUpdateToolsRequest() // UpdateToolsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.UpdateTools(context.Background(), id).UpdateToolsRequest(updateToolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.UpdateTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTools`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.UpdateTools`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateToolsByTeamidV2

> FetchToolsIntegrations200Response UpdateToolsByTeamidV2(ctx, teamId, id).UpdateToolsRequest(updateToolsRequest).Execute()

TeamToolController@update



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | tool id
	updateToolsRequest := *openapiclient.NewUpdateToolsRequest() // UpdateToolsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.UpdateToolsByTeamidV2(context.Background(), teamId, id).UpdateToolsRequest(updateToolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.UpdateToolsByTeamidV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateToolsByTeamidV2`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.UpdateToolsByTeamidV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateToolsByTeamidV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateToolsRequest** | [**UpdateToolsRequest**](UpdateToolsRequest.md) | Pass user credentials | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateToolsIntegrations

> FetchToolsIntegrations200Response UpdateToolsIntegrations(ctx, id).UpdateToolsIntegrationsRequest(updateToolsIntegrationsRequest).Execute()

IntegrationToolController@update



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
	id := int32(1) // int32 | tool id
	updateToolsIntegrationsRequest := *openapiclient.NewUpdateToolsIntegrationsRequest() // UpdateToolsIntegrationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.UpdateToolsIntegrations(context.Background(), id).UpdateToolsIntegrationsRequest(updateToolsIntegrationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.UpdateToolsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateToolsIntegrations`: FetchToolsIntegrations200Response
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.UpdateToolsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | tool id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateToolsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateToolsIntegrationsRequest** | [**UpdateToolsIntegrationsRequest**](UpdateToolsIntegrationsRequest.md) | Pass user credentials | 

### Return type

[**FetchToolsIntegrations200Response**](FetchToolsIntegrations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

