# \TeamDataAccessApplicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountTeamDarApplications**](TeamDataAccessApplicationAPI.md#CountTeamDarApplications) | **Get** /api/v1/teams/{teamId}/dar/applications/count | TeamDataAccessApplicationController@allCounts
[**CountUniqueFieldsDarApplications**](TeamDataAccessApplicationAPI.md#CountUniqueFieldsDarApplications) | **Get** /api/v1/teams/{teamId}/dar/applications/count/{field} | TeamDataAccessApplicationController@count
[**FetchTeamDarApplication**](TeamDataAccessApplicationAPI.md#FetchTeamDarApplication) | **Get** /api/v1/teams/{teamId}/dar/applications/{id} | TeamDataAccessApplicationController@show
[**FetchTeamDarApplications**](TeamDataAccessApplicationAPI.md#FetchTeamDarApplications) | **Get** /api/v1/teams/{teamId}/dar/applications | TeamDataAccessApplicationController@index



## CountTeamDarApplications

> CountUniqueFieldsCollections200Response CountTeamDarApplications(ctx, teamId).Execute()

TeamDataAccessApplicationController@allCounts



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessApplicationAPI.CountTeamDarApplications(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessApplicationAPI.CountTeamDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountTeamDarApplications`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessApplicationAPI.CountTeamDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountTeamDarApplicationsRequest struct via the builder pattern


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


## CountUniqueFieldsDarApplications

> CountUniqueFieldsCollections200Response CountUniqueFieldsDarApplications(ctx, teamId, field).Execute()

TeamDataAccessApplicationController@count



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
	field := "approval_status" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessApplicationAPI.CountUniqueFieldsDarApplications(context.Background(), teamId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessApplicationAPI.CountUniqueFieldsDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsDarApplications`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessApplicationAPI.CountUniqueFieldsDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsDarApplicationsRequest struct via the builder pattern


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


## FetchTeamDarApplication

> FetchTeamDarApplication200Response FetchTeamDarApplication(ctx, teamId, id).Execute()

TeamDataAccessApplicationController@show



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
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessApplicationAPI.FetchTeamDarApplication(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessApplicationAPI.FetchTeamDarApplication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplication`: FetchTeamDarApplication200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessApplicationAPI.FetchTeamDarApplication`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplication200Response**](FetchTeamDarApplication200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamDarApplications

> FetchTeamDarApplications200Response FetchTeamDarApplications(ctx, teamId).Execute()

TeamDataAccessApplicationController@index



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDataAccessApplicationAPI.FetchTeamDarApplications(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDataAccessApplicationAPI.FetchTeamDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDarApplications`: FetchTeamDarApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDataAccessApplicationAPI.FetchTeamDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDarApplicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchTeamDarApplications200Response**](FetchTeamDarApplications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

