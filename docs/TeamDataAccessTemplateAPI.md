# \TeamDataAccessTemplateAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteTeamDarTemplateFile**](TeamDataAccessTemplateAPI.md#DeleteTeamDarTemplateFile) | **Delete** /api/v1/teams/{teamId}/dar/templates/{id}/files/{fileId} | TeamDataAccessTemplateController@destroyFile
[**FetchTeamDarTemplates**](TeamDataAccessTemplateAPI.md#FetchTeamDarTemplates) | **Get** /api/v1/teams/{teamId}/dar/templates | TeamDataAccessTemplateController@index
[**TeamDarTemplateCountUniqueFields**](TeamDataAccessTemplateAPI.md#TeamDarTemplateCountUniqueFields) | **Get** /api/v1/teams/{teamId}/dar/templates/count/{field} | TeamDataAccessTemplateController@count



## DeleteTeamDarTemplateFile

> DeleteAliases200Response DeleteTeamDarTemplateFile(ctx, teamId, id, fileId).Execute()

TeamDataAccessTemplateController@destroyFile



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
	teamId := int32(1) // int32 | Team id
	id := int32(1) // int32 | DAR template id
	fileId := "1" // string | File id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessTemplateAPI.DeleteTeamDarTemplateFile(context.Background(), teamId, id, fileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessTemplateAPI.DeleteTeamDarTemplateFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamDarTemplateFile`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessTemplateAPI.DeleteTeamDarTemplateFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR template id | 
**fileId** | **string** | File id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamDarTemplateFileRequest struct via the builder pattern


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


## FetchTeamDarTemplates

> FetchDarTemplates200Response FetchTeamDarTemplates(ctx, teamId).Published(published).Execute()

TeamDataAccessTemplateController@index



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
	teamId := int32(1) // int32 | Team id
	published := "true" // string | Template publication status to filter by (true, false) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessTemplateAPI.FetchTeamDarTemplates(context.Background(), teamId).Published(published).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessTemplateAPI.FetchTeamDarTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarTemplates`: FetchDarTemplates200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessTemplateAPI.FetchTeamDarTemplates`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarTemplatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **published** | **string** | Template publication status to filter by (true, false) | 

### Return type

[**FetchDarTemplates200Response**](FetchDarTemplates200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TeamDarTemplateCountUniqueFields

> CountUniqueFieldsCollections200Response TeamDarTemplateCountUniqueFields(ctx, teamId, field).Execute()

TeamDataAccessTemplateController@count



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
	teamId := int32(1) // int32 | Team id
	field := "published" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessTemplateAPI.TeamDarTemplateCountUniqueFields(context.Background(), teamId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessTemplateAPI.TeamDarTemplateCountUniqueFields``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TeamDarTemplateCountUniqueFields`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessTemplateAPI.TeamDarTemplateCountUniqueFields`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiTeamDarTemplateCountUniqueFieldsRequest struct via the builder pattern


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

