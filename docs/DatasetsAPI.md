# \DatasetsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountUniqueFields**](DatasetsAPI.md#CountUniqueFields) | **Get** /api/v1/datasets/count/{field} | DatasetController@count
[**CreateDatasets**](DatasetsAPI.md#CreateDatasets) | **Post** /api/v1/datasets | DatasetController@store
[**CreateDatasetsIntegrations**](DatasetsAPI.md#CreateDatasetsIntegrations) | **Post** /api/v1/integrations/datasets | IntegrationDatasetController@store
[**CreateDatasetsLinkageExtraction**](DatasetsAPI.md#CreateDatasetsLinkageExtraction) | **Post** /api/v1/datasets/admin_ctrl/trigger/linkage_extraction | Trigger Term Extraction for Datasets
[**CreateDatasetsTermExtraction**](DatasetsAPI.md#CreateDatasetsTermExtraction) | **Post** /api/v1/datasets/admin_ctrl/trigger/term_extraction | Trigger Term Extraction for Datasets
[**CreateDatasetsV2**](DatasetsAPI.md#CreateDatasetsV2) | **Post** /api/v2/datasets | DatasetController@store
[**CreateTeamDatasetsV2**](DatasetsAPI.md#CreateTeamDatasetsV2) | **Post** /api/v2/teams/{teamId}/datasets | TeamDatasetController@store
[**DeleteDatasets**](DatasetsAPI.md#DeleteDatasets) | **Delete** /api/v1/datasets/{id} | DatasetController@destroy
[**DeleteDatasetsIntegrations**](DatasetsAPI.md#DeleteDatasetsIntegrations) | **Delete** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@destroy
[**DeleteDatasetsV2**](DatasetsAPI.md#DeleteDatasetsV2) | **Delete** /api/v2/datasets/{id} | Delete a dataset
[**DeleteTeamDatasetsV2**](DatasetsAPI.md#DeleteTeamDatasetsV2) | **Delete** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@destroy
[**ExportDatasetMetadata**](DatasetsAPI.md#ExportDatasetMetadata) | **Get** /api/v1/datasets/export_metadata/{id} | DatasetController@exportMetadata
[**ExportDatasets**](DatasetsAPI.md#ExportDatasets) | **Get** /api/v1/datasets/export | DatasetController@export
[**ExportDur**](DatasetsAPI.md#ExportDur) | **Get** /api/v1/dur/export | DurController@export
[**ExportMockDataset**](DatasetsAPI.md#ExportMockDataset) | **Get** /api/v1/datasets/export/mock | DatasetController@exportMock
[**ExportMockDatasetV2**](DatasetsAPI.md#ExportMockDatasetV2) | **Get** /api/v2/datasets/export/mock | DatasetController@exportMock
[**FetchAllDatasets**](DatasetsAPI.md#FetchAllDatasets) | **Get** /api/v1/datasets | DatasetController@index
[**FetchAllDatasetsIntegrations**](DatasetsAPI.md#FetchAllDatasetsIntegrations) | **Get** /api/v1/integrations/datasets | IntegrationDatasetController@index
[**FetchAllDatasetsV2**](DatasetsAPI.md#FetchAllDatasetsV2) | **Get** /api/v2/datasets | DatasetController@index
[**FetchDatasets**](DatasetsAPI.md#FetchDatasets) | **Get** /api/v1/datasets/{id} | DatasetController@show
[**FetchDatasetsIntegrations**](DatasetsAPI.md#FetchDatasetsIntegrations) | **Get** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@show
[**FetchDatasetsV2**](DatasetsAPI.md#FetchDatasetsV2) | **Get** /api/v2/datasets/{id} | DatasetController@showActive
[**PatchDatasets**](DatasetsAPI.md#PatchDatasets) | **Patch** /api/v1/datasets/{id} | DatasetController@edit
[**PatchDatasetsIntegrations**](DatasetsAPI.md#PatchDatasetsIntegrations) | **Patch** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@edit
[**PatchDatasetsV2**](DatasetsAPI.md#PatchDatasetsV2) | **Patch** /api/v2/datasets/{id} | DatasetController@edit
[**PatchTeamDatasetsV2**](DatasetsAPI.md#PatchTeamDatasetsV2) | **Patch** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@edit
[**UpdateDatasets**](DatasetsAPI.md#UpdateDatasets) | **Put** /api/v1/datasets/{id} | DatasetController@update
[**UpdateDatasetsIntegrations**](DatasetsAPI.md#UpdateDatasetsIntegrations) | **Put** /api/v1/integrations/datasets/{id} | IntegrationDatasetController@update
[**UpdateDatasetsV2**](DatasetsAPI.md#UpdateDatasetsV2) | **Put** /api/v2/datasets/{id} | DatasetController@update
[**UpdateTeamDatasetsV2**](DatasetsAPI.md#UpdateTeamDatasetsV2) | **Put** /api/v2/teams/{teamId}/datasets/{id} | TeamDatasetController@update



## CountUniqueFields

> CountUniqueFieldsCollections200Response CountUniqueFields(ctx, field).TeamId(teamId).Execute()

DatasetController@count



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
	resp, r, err := apiClient.DatasetsAPI.CountUniqueFields(context.Background(), field).TeamId(teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CountUniqueFields``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFields`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CountUniqueFields`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsRequest struct via the builder pattern


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


## CreateDatasets

> CreateDarIntegration201Response CreateDatasets(ctx).CreateDatasetsRequest(createDatasetsRequest).Execute()

DatasetController@store



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
	createDatasetsRequest := *openapiclient.NewCreateDatasetsRequest() // CreateDatasetsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateDatasets(context.Background()).CreateDatasetsRequest(createDatasetsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDatasets`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateDatasets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDatasetsRequest** | [**CreateDatasetsRequest**](CreateDatasetsRequest.md) | Pass user credentials | 

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


## CreateDatasetsIntegrations

> CreateDarIntegration201Response CreateDatasetsIntegrations(ctx).DatasetsTestRequest(datasetsTestRequest).InputSchema(inputSchema).InputVersion(inputVersion).Execute()

IntegrationDatasetController@store



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
	datasetsTestRequest := *openapiclient.NewDatasetsTestRequest() // DatasetsTestRequest | Pass user credentials
	inputSchema := "HDRUK" // string | Input schema model. (optional)
	inputVersion := "3.0.0" // string | Input schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateDatasetsIntegrations(context.Background()).DatasetsTestRequest(datasetsTestRequest).InputSchema(inputSchema).InputVersion(inputVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDatasetsIntegrations`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDatasetsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datasetsTestRequest** | [**DatasetsTestRequest**](DatasetsTestRequest.md) | Pass user credentials | 
 **inputSchema** | **string** | Input schema model. | 
 **inputVersion** | **string** | Input schema version. | 

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


## CreateDatasetsLinkageExtraction

> CreateDatasetsLinkageExtraction200Response CreateDatasetsLinkageExtraction(ctx).Authorization(authorization).CreateDatasetsLinkageExtractionRequest(createDatasetsLinkageExtractionRequest).Execute()

Trigger Term Extraction for Datasets



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
	authorization := "authorization_example" // string | JWT token for authorization in the format 'Bearer {token}'
	createDatasetsLinkageExtractionRequest := *openapiclient.NewCreateDatasetsLinkageExtractionRequest() // CreateDatasetsLinkageExtractionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateDatasetsLinkageExtraction(context.Background()).Authorization(authorization).CreateDatasetsLinkageExtractionRequest(createDatasetsLinkageExtractionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateDatasetsLinkageExtraction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDatasetsLinkageExtraction`: CreateDatasetsLinkageExtraction200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateDatasetsLinkageExtraction`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDatasetsLinkageExtractionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | JWT token for authorization in the format &#39;Bearer {token}&#39; | 
 **createDatasetsLinkageExtractionRequest** | [**CreateDatasetsLinkageExtractionRequest**](CreateDatasetsLinkageExtractionRequest.md) |  | 

### Return type

[**CreateDatasetsLinkageExtraction200Response**](CreateDatasetsLinkageExtraction200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDatasetsTermExtraction

> CreateDatasetsTermExtraction200Response CreateDatasetsTermExtraction(ctx).Authorization(authorization).Role(role).CreateDatasetsTermExtractionRequest(createDatasetsTermExtractionRequest).Execute()

Trigger Term Extraction for Datasets



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
	authorization := "authorization_example" // string | JWT token for authorization in the format 'Bearer {token}'
	role := "role_example" // string | Role required to access this endpoint, e.g., 'hdruk.superadmin'
	createDatasetsTermExtractionRequest := *openapiclient.NewCreateDatasetsTermExtractionRequest() // CreateDatasetsTermExtractionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateDatasetsTermExtraction(context.Background()).Authorization(authorization).Role(role).CreateDatasetsTermExtractionRequest(createDatasetsTermExtractionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateDatasetsTermExtraction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDatasetsTermExtraction`: CreateDatasetsTermExtraction200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateDatasetsTermExtraction`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDatasetsTermExtractionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | JWT token for authorization in the format &#39;Bearer {token}&#39; | 
 **role** | **string** | Role required to access this endpoint, e.g., &#39;hdruk.superadmin&#39; | 
 **createDatasetsTermExtractionRequest** | [**CreateDatasetsTermExtractionRequest**](CreateDatasetsTermExtractionRequest.md) |  | 

### Return type

[**CreateDatasetsTermExtraction200Response**](CreateDatasetsTermExtraction200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDatasetsV2

> CreateDarIntegration201Response CreateDatasetsV2(ctx).CreateDatasetsV2Request(createDatasetsV2Request).Execute()

DatasetController@store



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
	createDatasetsV2Request := *openapiclient.NewCreateDatasetsV2Request() // CreateDatasetsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateDatasetsV2(context.Background()).CreateDatasetsV2Request(createDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDatasetsV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateDatasetsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDatasetsV2Request** | [**CreateDatasetsV2Request**](CreateDatasetsV2Request.md) | Pass user credentials | 

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


## CreateTeamDatasetsV2

> CreateDarIntegration201Response CreateTeamDatasetsV2(ctx, teamId).CreateTeamDatasetsV2Request(createTeamDatasetsV2Request).Execute()

TeamDatasetController@store



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
	createTeamDatasetsV2Request := *openapiclient.NewCreateTeamDatasetsV2Request() // CreateTeamDatasetsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.CreateTeamDatasetsV2(context.Background(), teamId).CreateTeamDatasetsV2Request(createTeamDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.CreateTeamDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamDatasetsV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.CreateTeamDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createTeamDatasetsV2Request** | [**CreateTeamDatasetsV2Request**](CreateTeamDatasetsV2Request.md) | Pass user credentials | 

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


## DeleteDatasets

> DeleteApplications200Response DeleteDatasets(ctx, id).Execute()

DatasetController@destroy



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
	id := int32(1) // int32 | dataset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.DeleteDatasets(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.DeleteDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDatasets`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.DeleteDatasets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDatasetsRequest struct via the builder pattern


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


## DeleteDatasetsIntegrations

> DeleteApplications200Response DeleteDatasetsIntegrations(ctx, id).Execute()

IntegrationDatasetController@destroy



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
	id := int32(1) // int32 | dataset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.DeleteDatasetsIntegrations(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.DeleteDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDatasetsIntegrations`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.DeleteDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDatasetsIntegrationsRequest struct via the builder pattern


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


## DeleteDatasetsV2

> DeleteApplications200Response DeleteDatasetsV2(ctx, id).Execute()

Delete a dataset



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
	id := int32(1) // int32 | dataset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.DeleteDatasetsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.DeleteDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDatasetsV2`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.DeleteDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDatasetsV2Request struct via the builder pattern


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


## DeleteTeamDatasetsV2

> DeleteApplications200Response DeleteTeamDatasetsV2(ctx, teamId, id).Execute()

TeamDatasetController@destroy



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
	id := int32(1) // int32 | dataset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.DeleteTeamDatasetsV2(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.DeleteTeamDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDatasetsV2`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.DeleteTeamDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDatasetsV2Request struct via the builder pattern


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


## ExportDatasetMetadata

> string ExportDatasetMetadata(ctx, id).DownloadType(downloadType).Execute()

DatasetController@exportMetadata



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
	id := int32(1) // int32 | dataset id
	downloadType := "structural" // string | download type

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.ExportDatasetMetadata(context.Background(), id).DownloadType(downloadType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.ExportDatasetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDatasetMetadata`: string
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.ExportDatasetMetadata`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiExportDatasetMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **downloadType** | **string** | download type | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportDatasets

> string ExportDatasets(ctx).TeamId(teamId).DatasetId(datasetId).Execute()

DatasetController@export



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
	datasetId := int32(1) // int32 | dataset id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.ExportDatasets(context.Background()).TeamId(teamId).DatasetId(datasetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.ExportDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDatasets`: string
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.ExportDatasets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExportDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **int32** | team id | 
 **datasetId** | **int32** | dataset id | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportDur

> string ExportDur(ctx).TeamId(teamId).DurId(durId).Execute()

DurController@export



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
	durId := int32(1) // int32 | dur id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.ExportDur(context.Background()).TeamId(teamId).DurId(durId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.ExportDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDur`: string
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.ExportDur`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExportDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **int32** | team id | 
 **durId** | **int32** | dur id | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportMockDataset

> string ExportMockDataset(ctx).Type_(type_).Execute()

DatasetController@exportMock



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
	type_ := "type__example" // string | type export

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.ExportMockDataset(context.Background()).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.ExportMockDataset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportMockDataset`: string
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.ExportMockDataset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExportMockDatasetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **string** | type export | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportMockDatasetV2

> string ExportMockDatasetV2(ctx).Type_(type_).Execute()

DatasetController@exportMock



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
	type_ := "type__example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.ExportMockDatasetV2(context.Background()).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.ExportMockDatasetV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportMockDatasetV2`: string
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.ExportMockDatasetV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExportMockDatasetV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **string** |  | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDatasets

> FetchAllDatasets200Response FetchAllDatasets(ctx).TeamId(teamId).Pid(pid).Sort(sort).Title(title).Status(status).Execute()

DatasetController@index



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
	pid := "aa588d1c-21e7-42d9-9b60-48e3d6b784a9" // string | get based on a pid (optional)
	sort := "created:desc" // string | Field and direction (colon separated) to sort by (default: 'created:desc') ... <br/> <br/>         - ?sort=\\<field\\>:\\<direction\\> <br/>         - \\<direction\\> can only be 'asc' or 'desc'  <br/>         - \\<field\\> can only be a valid field for the dataset table that can be ordered on  <br/>         - \\<field\\> can start with the prefix 'metadata.' so that nested values within the field 'metadata'  <br/>             (represented by the GWDM JSON structure) can be used to order on.  <br/>  <br/> (optional)
	title := "hdr" // string | Three or more characters to filter dataset titles by (optional)
	status := "ACTIVE" // string | Dataset status to filter by ('ACTIVE', 'DRAFT', 'ARCHIVED') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchAllDatasets(context.Background()).TeamId(teamId).Pid(pid).Sort(sort).Title(title).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchAllDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDatasets`: FetchAllDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchAllDatasets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **int32** | team id | 
 **pid** | **string** | get based on a pid | 
 **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | 
 **title** | **string** | Three or more characters to filter dataset titles by | 
 **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | 

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDatasetsIntegrations

> FetchAllDatasets200Response FetchAllDatasetsIntegrations(ctx).TeamId(teamId).Pid(pid).Sort(sort).Title(title).Status(status).Execute()

IntegrationDatasetController@index



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
	pid := "aa588d1c-21e7-42d9-9b60-48e3d6b784a9" // string | get based on a pid (optional)
	sort := "created:desc" // string | Field and direction (colon separated) to sort by (default: 'created:desc') ... <br/> <br/>         - ?sort=\\<field\\>:\\<direction\\> <br/>         - \\<direction\\> can only be 'asc' or 'desc'  <br/>         - \\<field\\> can only be a valid field for the dataset table that can be ordered on  <br/>         - \\<field\\> can start with the prefix 'metadata.' so that nested values within the field 'metadata'  <br/>             (represented by the GWDM JSON structure) can be used to order on.  <br/>  <br/> (optional)
	title := "hdr" // string | Three or more characters to filter dataset titles by (optional)
	status := "ACTIVE" // string | Dataset status to filter by ('ACTIVE', 'DRAFT', 'ARCHIVED') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchAllDatasetsIntegrations(context.Background()).TeamId(teamId).Pid(pid).Sort(sort).Title(title).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchAllDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDatasetsIntegrations`: FetchAllDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchAllDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDatasetsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **int32** | team id | 
 **pid** | **string** | get based on a pid | 
 **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | 
 **title** | **string** | Three or more characters to filter dataset titles by | 
 **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | 

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDatasetsV2

> FetchAllDatasets200Response FetchAllDatasetsV2(ctx).Sort(sort).Title(title).Status(status).WithMetadata(withMetadata).Execute()

DatasetController@index



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
	sort := "created:desc" // string | Field and direction (colon separated) to sort by (default: 'created:desc') ... <br/> <br/>         - ?sort=\\<field\\>:\\<direction\\> <br/>         - \\<direction\\> can only be 'asc' or 'desc'  <br/>         - \\<field\\> can only be a valid field for the dataset table that can be ordered on  <br/>         - \\<field\\> can start with the prefix 'metadata.' so that nested values within the field 'metadata'  <br/>             (represented by the GWDM JSON structure) can be used to order on.  <br/>  <br/> (optional)
	title := "hdr" // string | Three or more characters to filter dataset titles by (optional)
	status := "ACTIVE" // string | Dataset status to filter by ('ACTIVE', 'DRAFT', 'ARCHIVED') (optional)
	withMetadata := "true" // string | Boolean whether to return dataset metadata (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchAllDatasetsV2(context.Background()).Sort(sort).Title(title).Status(status).WithMetadata(withMetadata).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchAllDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDatasetsV2`: FetchAllDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchAllDatasetsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sort** | **string** | Field and direction (colon separated) to sort by (default: &#39;created:desc&#39;) ... &lt;br/&gt; &lt;br/&gt;         - ?sort&#x3D;\\&lt;field\\&gt;:\\&lt;direction\\&gt; &lt;br/&gt;         - \\&lt;direction\\&gt; can only be &#39;asc&#39; or &#39;desc&#39;  &lt;br/&gt;         - \\&lt;field\\&gt; can only be a valid field for the dataset table that can be ordered on  &lt;br/&gt;         - \\&lt;field\\&gt; can start with the prefix &#39;metadata.&#39; so that nested values within the field &#39;metadata&#39;  &lt;br/&gt;             (represented by the GWDM JSON structure) can be used to order on.  &lt;br/&gt;  &lt;br/&gt; | 
 **title** | **string** | Three or more characters to filter dataset titles by | 
 **status** | **string** | Dataset status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | 
 **withMetadata** | **string** | Boolean whether to return dataset metadata | 

### Return type

[**FetchAllDatasets200Response**](FetchAllDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDatasets

> FetchDatasets200Response FetchDatasets(ctx, id).Export(export).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()

DatasetController@show



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
	id := int32(1) // int32 | dataset id
	export := "structuralMetadata" // string | Alternative output schema model. (optional)
	schemaModel := "schemaModel_example" // string | Alternative output schema model. (optional)
	schemaVersion := "schemaVersion_example" // string | Alternative output schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchDatasets(context.Background(), id).Export(export).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasets`: FetchDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchDatasets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **export** | **string** | Alternative output schema model. | 
 **schemaModel** | **string** | Alternative output schema model. | 
 **schemaVersion** | **string** | Alternative output schema version. | 

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDatasetsIntegrations

> FetchDatasets200Response FetchDatasetsIntegrations(ctx, id).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()

IntegrationDatasetController@show



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
	id := int32(1) // int32 | dataset id
	schemaModel := "schemaModel_example" // string | Alternative output schema model. (optional)
	schemaVersion := "schemaVersion_example" // string | Alternative output schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchDatasetsIntegrations(context.Background(), id).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasetsIntegrations`: FetchDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **schemaModel** | **string** | Alternative output schema model. | 
 **schemaVersion** | **string** | Alternative output schema version. | 

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDatasetsV2

> FetchDatasets200Response FetchDatasetsV2(ctx, id).Export(export).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()

DatasetController@showActive



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
	id := int32(1) // int32 | dataset id
	export := "structuralMetadata" // string | Set to 'structuralMetadata' to download as CSV. (optional)
	schemaModel := "schemaModel_example" // string | Alternative output schema model. (optional)
	schemaVersion := "schemaVersion_example" // string | Alternative output schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.FetchDatasetsV2(context.Background(), id).Export(export).SchemaModel(schemaModel).SchemaVersion(schemaVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.FetchDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasetsV2`: FetchDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.FetchDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **export** | **string** | Set to &#39;structuralMetadata&#39; to download as CSV. | 
 **schemaModel** | **string** | Alternative output schema model. | 
 **schemaVersion** | **string** | Alternative output schema version. | 

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDatasets

> DeleteApplications200Response PatchDatasets(ctx, id).Unarchive(unarchive).Execute()

DatasetController@edit



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
	id := int32(1) // int32 | dataset id
	unarchive := "unarchive_example" // string | Unarchive a dataset (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.PatchDatasets(context.Background(), id).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.PatchDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDatasets`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.PatchDatasets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **unarchive** | **string** | Unarchive a dataset | 

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


## PatchDatasetsIntegrations

> DeleteApplications200Response PatchDatasetsIntegrations(ctx, id).Unarchive(unarchive).Execute()

IntegrationDatasetController@edit



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
	id := int32(1) // int32 | dataset id
	unarchive := "unarchive_example" // string | Unarchive a dataset (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.PatchDatasetsIntegrations(context.Background(), id).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.PatchDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDatasetsIntegrations`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.PatchDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDatasetsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **unarchive** | **string** | Unarchive a dataset | 

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


## PatchDatasetsV2

> DeleteApplications200Response PatchDatasetsV2(ctx, id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()

DatasetController@edit



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
	id := int32(1) // int32 | dataset id
	patchDatasetsV2Request := *openapiclient.NewPatchDatasetsV2Request() // PatchDatasetsV2Request | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.PatchDatasetsV2(context.Background(), id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.PatchDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDatasetsV2`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.PatchDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) |  | 

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchTeamDatasetsV2

> DeleteApplications200Response PatchTeamDatasetsV2(ctx, teamId, id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()

TeamDatasetController@edit



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
	id := int32(1) // int32 | dataset id
	patchDatasetsV2Request := *openapiclient.NewPatchDatasetsV2Request() // PatchDatasetsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.PatchTeamDatasetsV2(context.Background(), teamId, id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.PatchTeamDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchTeamDatasetsV2`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.PatchTeamDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchTeamDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) | Pass user credentials | 

### Return type

[**DeleteApplications200Response**](DeleteApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDatasets

> CreateDarIntegration201Response UpdateDatasets(ctx, id).UpdateDatasetsRequest(updateDatasetsRequest).Execute()

DatasetController@update



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
	id := int32(1) // int32 | dataset id
	updateDatasetsRequest := *openapiclient.NewUpdateDatasetsRequest() // UpdateDatasetsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.UpdateDatasets(context.Background(), id).UpdateDatasetsRequest(updateDatasetsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.UpdateDatasets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDatasets`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.UpdateDatasets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDatasetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) | Pass user credentials | 

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


## UpdateDatasetsIntegrations

> FetchDatasets200Response UpdateDatasetsIntegrations(ctx, id).UpdateDatasetsRequest(updateDatasetsRequest).InputSchema(inputSchema).InputVersion(inputVersion).Execute()

IntegrationDatasetController@update



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
	id := int32(1) // int32 | dataset id
	updateDatasetsRequest := *openapiclient.NewUpdateDatasetsRequest() // UpdateDatasetsRequest | Pass user credentials
	inputSchema := "HDRUK" // string | Input schema model. (optional)
	inputVersion := "3.0.0" // string | Input schema version. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.UpdateDatasetsIntegrations(context.Background(), id).UpdateDatasetsRequest(updateDatasetsRequest).InputSchema(inputSchema).InputVersion(inputVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.UpdateDatasetsIntegrations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDatasetsIntegrations`: FetchDatasets200Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.UpdateDatasetsIntegrations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDatasetsIntegrationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) | Pass user credentials | 
 **inputSchema** | **string** | Input schema model. | 
 **inputVersion** | **string** | Input schema version. | 

### Return type

[**FetchDatasets200Response**](FetchDatasets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDatasetsV2

> CreateDarIntegration201Response UpdateDatasetsV2(ctx, id).UpdateDatasetsRequest(updateDatasetsRequest).Execute()

DatasetController@update



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
	id := int32(1) // int32 | dataset id
	updateDatasetsRequest := *openapiclient.NewUpdateDatasetsRequest() // UpdateDatasetsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.UpdateDatasetsV2(context.Background(), id).UpdateDatasetsRequest(updateDatasetsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.UpdateDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDatasetsV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.UpdateDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDatasetsRequest** | [**UpdateDatasetsRequest**](UpdateDatasetsRequest.md) |  | 

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


## UpdateTeamDatasetsV2

> CreateDarIntegration201Response UpdateTeamDatasetsV2(ctx, teamId, id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()

TeamDatasetController@update



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
	id := int32(1) // int32 | dataset id
	patchDatasetsV2Request := *openapiclient.NewPatchDatasetsV2Request() // PatchDatasetsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatasetsAPI.UpdateTeamDatasetsV2(context.Background(), teamId, id).PatchDatasetsV2Request(patchDatasetsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatasetsAPI.UpdateTeamDatasetsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamDatasetsV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DatasetsAPI.UpdateTeamDatasetsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dataset id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamDatasetsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **patchDatasetsV2Request** | [**PatchDatasetsV2Request**](PatchDatasetsV2Request.md) | Pass user credentials | 

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

