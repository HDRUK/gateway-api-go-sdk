# \UserRolesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUserHasRoles**](UserRolesAPI.md#CreateUserHasRoles) | **Post** /api/v1/users/{userId}/roles | UserRoleController@store
[**DeleteUserHasRoles**](UserRolesAPI.md#DeleteUserHasRoles) | **Delete** /api/v1/users/{userId}/roles | UserRoleController@destroy
[**UpdateUserHasRoles**](UserRolesAPI.md#UpdateUserHasRoles) | **Patch** /api/v1/users/{userId}/roles | UserRoleController@edit



## CreateUserHasRoles

> DeleteApplications200Response CreateUserHasRoles(ctx, userId).CreateUserHasRolesRequest(createUserHasRolesRequest).Execute()

UserRoleController@store



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
	userId := int32(1) // int32 | user id
	createUserHasRolesRequest := *openapiclient.NewCreateUserHasRolesRequest() // CreateUserHasRolesRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserRolesAPI.CreateUserHasRoles(context.Background(), userId).CreateUserHasRolesRequest(createUserHasRolesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserRolesAPI.CreateUserHasRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserHasRoles`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `UserRolesAPI.CreateUserHasRoles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserHasRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createUserHasRolesRequest** | [**CreateUserHasRolesRequest**](CreateUserHasRolesRequest.md) | Pass user credentials | 

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


## DeleteUserHasRoles

> DeleteFederation200Response DeleteUserHasRoles(ctx, userId).Execute()

UserRoleController@destroy



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
	userId := int32(1) // int32 | user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserRolesAPI.DeleteUserHasRoles(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserRolesAPI.DeleteUserHasRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUserHasRoles`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `UserRolesAPI.DeleteUserHasRoles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserHasRolesRequest struct via the builder pattern


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


## UpdateUserHasRoles

> DeleteApplications200Response UpdateUserHasRoles(ctx, userId).UpdateUserHasRolesRequest(updateUserHasRolesRequest).Execute()

UserRoleController@edit



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
	userId := int32(1) // int32 | user id
	updateUserHasRolesRequest := *openapiclient.NewUpdateUserHasRolesRequest() // UpdateUserHasRolesRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserRolesAPI.UpdateUserHasRoles(context.Background(), userId).UpdateUserHasRolesRequest(updateUserHasRolesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserRolesAPI.UpdateUserHasRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserHasRoles`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `UserRolesAPI.UpdateUserHasRoles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserHasRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserHasRolesRequest** | [**UpdateUserHasRolesRequest**](UpdateUserHasRolesRequest.md) | Pass user credentials | 

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

