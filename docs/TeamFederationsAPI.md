# \TeamFederationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateFederationTeam**](TeamFederationsAPI.md#CreateFederationTeam) | **Post** /api/v1/teams/{teamId}/federations | FederationController@store
[**DeleteFederation**](TeamFederationsAPI.md#DeleteFederation) | **Delete** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@destroy
[**EditFederationTeam**](TeamFederationsAPI.md#EditFederationTeam) | **Patch** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@edit
[**GetFederationByFederationIdAndTeamId**](TeamFederationsAPI.md#GetFederationByFederationIdAndTeamId) | **Get** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@show
[**GetFederationHistory**](TeamFederationsAPI.md#GetFederationHistory) | **Get** /api/v1/teams/{teamId}/federations/{federationId}/history | FederationController@history
[**GetFederationTeamId**](TeamFederationsAPI.md#GetFederationTeamId) | **Get** /api/v1/teams/{teamId}/federations | FederationController@index
[**RunFederation**](TeamFederationsAPI.md#RunFederation) | **Get** /api/v1/teams/{teamId}/federations/{federationId}/run | FederationController@runNow
[**TestFederation**](TeamFederationsAPI.md#TestFederation) | **Post** /api/v1/teams/{teamId}/federations/test | FederationController@testFederation
[**UpdateFederationTeam**](TeamFederationsAPI.md#UpdateFederationTeam) | **Put** /api/v1/teams/{teamId}/federations/{federationId} | FederationController@update



## CreateFederationTeam

> CreateCategories200Response CreateFederationTeam(ctx, teamId).CreateFederationTeamRequest(createFederationTeamRequest).Execute()

FederationController@store



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
	createFederationTeamRequest := *openapiclient.NewCreateFederationTeamRequest() // CreateFederationTeamRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.CreateFederationTeam(context.Background(), teamId).CreateFederationTeamRequest(createFederationTeamRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.CreateFederationTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateFederationTeam`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.CreateFederationTeam`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateFederationTeamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createFederationTeamRequest** | [**CreateFederationTeamRequest**](CreateFederationTeamRequest.md) | Pass user credentials | 

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


## DeleteFederation

> DeleteFederation200Response DeleteFederation(ctx, teamId, federationId).Execute()

FederationController@destroy



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
	federationId := int32(1) // int32 | federation id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.DeleteFederation(context.Background(), teamId, federationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.DeleteFederation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteFederation`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.DeleteFederation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFederationRequest struct via the builder pattern


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


## EditFederationTeam

> CreateCategories200Response EditFederationTeam(ctx, teamId, federationId).CreateFederationTeamRequest(createFederationTeamRequest).Execute()

FederationController@edit



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
	federationId := int32(1) // int32 | federation id
	createFederationTeamRequest := *openapiclient.NewCreateFederationTeamRequest() // CreateFederationTeamRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.EditFederationTeam(context.Background(), teamId, federationId).CreateFederationTeamRequest(createFederationTeamRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.EditFederationTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditFederationTeam`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.EditFederationTeam`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditFederationTeamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createFederationTeamRequest** | [**CreateFederationTeamRequest**](CreateFederationTeamRequest.md) | Pass user credentials | 

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


## GetFederationByFederationIdAndTeamId

> GetFederationByFederationIdAndTeamId200Response GetFederationByFederationIdAndTeamId(ctx, teamId, federationId).Execute()

FederationController@show



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
	federationId := int32(1) // int32 | federation id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.GetFederationByFederationIdAndTeamId(context.Background(), teamId, federationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.GetFederationByFederationIdAndTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFederationByFederationIdAndTeamId`: GetFederationByFederationIdAndTeamId200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.GetFederationByFederationIdAndTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFederationByFederationIdAndTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetFederationByFederationIdAndTeamId200Response**](GetFederationByFederationIdAndTeamId200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFederationHistory

> GetFederationHistory200Response GetFederationHistory(ctx, teamId, federationId).PerPage(perPage).Execute()

FederationController@history



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
	federationId := int32(1) // int32 | federation id
	perPage := int32(25) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.GetFederationHistory(context.Background(), teamId, federationId).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.GetFederationHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFederationHistory`: GetFederationHistory200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.GetFederationHistory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFederationHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **perPage** | **int32** | per page | 

### Return type

[**GetFederationHistory200Response**](GetFederationHistory200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFederationTeamId

> GetFederationTeamId200Response GetFederationTeamId(ctx, teamId).Execute()

FederationController@index



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.GetFederationTeamId(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.GetFederationTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFederationTeamId`: GetFederationTeamId200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.GetFederationTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFederationTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetFederationTeamId200Response**](GetFederationTeamId200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunFederation

> TestFederation200Response RunFederation(ctx, teamId, federationId).Execute()

FederationController@runNow



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
	federationId := int32(1) // int32 | federation id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.RunFederation(context.Background(), teamId, federationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.RunFederation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunFederation`: TestFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.RunFederation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunFederationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**TestFederation200Response**](TestFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestFederation

> TestFederation200Response TestFederation(ctx, teamId).Execute()

FederationController@testFederation



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.TestFederation(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.TestFederation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestFederation`: TestFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.TestFederation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiTestFederationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TestFederation200Response**](TestFederation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateFederationTeam

> CreateCategories200Response UpdateFederationTeam(ctx, teamId, federationId).UpdateFederationTeamRequest(updateFederationTeamRequest).Execute()

FederationController@update



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
	federationId := int32(1) // int32 | federation id
	updateFederationTeamRequest := *openapiclient.NewUpdateFederationTeamRequest() // UpdateFederationTeamRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamFederationsAPI.UpdateFederationTeam(context.Background(), teamId, federationId).UpdateFederationTeamRequest(updateFederationTeamRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamFederationsAPI.UpdateFederationTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateFederationTeam`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamFederationsAPI.UpdateFederationTeam`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**federationId** | **int32** | federation id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateFederationTeamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateFederationTeamRequest** | [**UpdateFederationTeamRequest**](UpdateFederationTeamRequest.md) | Pass user credentials | 

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

