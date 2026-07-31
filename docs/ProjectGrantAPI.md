# \ProjectGrantAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchAllProjectGrants**](ProjectGrantAPI.md#FetchAllProjectGrants) | **Get** /api/v1/project_grants | ProjectGrantController@index
[**FetchProjectGrant**](ProjectGrantAPI.md#FetchProjectGrant) | **Get** /api/v1/project_grants/{id} | ProjectGrantController@show



## FetchAllProjectGrants

> FetchAllProjectGrants200Response FetchAllProjectGrants(ctx).Pid(pid).Version(version).ProjectGrantName(projectGrantName).UserId(userId).TeamId(teamId).WithRelated(withRelated).Execute()

ProjectGrantController@index



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
	pid := "pid_example" // string | Filter by dataset pid (optional)
	version := int32(56) // int32 | Filter by dataset version number (optional)
	projectGrantName := "projectGrantName_example" // string | Filter by project grant name (optional)
	userId := int32(56) // int32 | Filter by owning user id (optional)
	teamId := int32(56) // int32 | Filter by owning team id (optional)
	withRelated := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectGrantAPI.FetchAllProjectGrants(context.Background()).Pid(pid).Version(version).ProjectGrantName(projectGrantName).UserId(userId).TeamId(teamId).WithRelated(withRelated).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectGrantAPI.FetchAllProjectGrants``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllProjectGrants`: FetchAllProjectGrants200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectGrantAPI.FetchAllProjectGrants`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllProjectGrantsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pid** | **string** | Filter by dataset pid | 
 **version** | **int32** | Filter by dataset version number | 
 **projectGrantName** | **string** | Filter by project grant name | 
 **userId** | **int32** | Filter by owning user id | 
 **teamId** | **int32** | Filter by owning team id | 
 **withRelated** | **bool** |  | 

### Return type

[**FetchAllProjectGrants200Response**](FetchAllProjectGrants200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchProjectGrant

> CountUniqueFieldsCollections200Response FetchProjectGrant(ctx, id).WithRelated(withRelated).Execute()

ProjectGrantController@show



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
	id := int32(56) // int32 | 
	withRelated := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectGrantAPI.FetchProjectGrant(context.Background(), id).WithRelated(withRelated).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectGrantAPI.FetchProjectGrant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchProjectGrant`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectGrantAPI.FetchProjectGrant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchProjectGrantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **withRelated** | **bool** |  | 

### Return type

[**CountUniqueFieldsCollections200Response**](CountUniqueFieldsCollections200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

