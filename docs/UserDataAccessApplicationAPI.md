# \UserDataAccessApplicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountAllUserDarApplications**](UserDataAccessApplicationAPI.md#CountAllUserDarApplications) | **Get** /api/v1/users/{userId}/dar/applications/count | UserDataAccessApplicationController@allCounts
[**CountUserDarApplicationsByField**](UserDataAccessApplicationAPI.md#CountUserDarApplicationsByField) | **Get** /api/v1/users/{userId}/dar/applications/count/{field} | UserDataAccessApplicationController@count
[**CreateUserDarApplicationAnswers**](UserDataAccessApplicationAPI.md#CreateUserDarApplicationAnswers) | **Put** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplication@storeAnswers
[**FetchUserDarApplicationAnswers**](UserDataAccessApplicationAPI.md#FetchUserDarApplicationAnswers) | **Get** /api/v1/users/{userId}/dar/applications/{id}/answers | UserDataAccessApplicationController@showAnswers
[**FetchUserDarApplicationDetails**](UserDataAccessApplicationAPI.md#FetchUserDarApplicationDetails) | **Get** /api/v1/users/{userId}/dar/applications/{id} | UserDataAccessApplicationController@show
[**FetchUserDarApplicationHeader**](UserDataAccessApplicationAPI.md#FetchUserDarApplicationHeader) | **Get** /api/v1/users/{userId}/dar/applications/{id}/showHeader | UserDataAccessApplicationController@showHeader
[**FetchUserDarApplications**](UserDataAccessApplicationAPI.md#FetchUserDarApplications) | **Get** /api/v1/users/{userId}/dar/applications | UserDataAccessApplicationController@index



## CountAllUserDarApplications

> CountUniqueFieldsCollections200Response CountAllUserDarApplications(ctx, userId).Execute()

UserDataAccessApplicationController@allCounts



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
	userId := int32(1) // int32 | User id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.CountAllUserDarApplications(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.CountAllUserDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountAllUserDarApplications`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.CountAllUserDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountAllUserDarApplicationsRequest struct via the builder pattern


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


## CountUserDarApplicationsByField

> CountUniqueFieldsCollections200Response CountUserDarApplicationsByField(ctx, userId, field).Execute()

UserDataAccessApplicationController@count



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
	userId := int32(1) // int32 | User id
	field := "approval_status" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.CountUserDarApplicationsByField(context.Background(), userId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.CountUserDarApplicationsByField``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUserDarApplicationsByField`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.CountUserDarApplicationsByField`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUserDarApplicationsByFieldRequest struct via the builder pattern


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


## CreateUserDarApplicationAnswers

> CreateCategories200Response CreateUserDarApplicationAnswers(ctx, userId, id).CreateUserDarApplicationAnswersRequest(createUserDarApplicationAnswersRequest).Execute()

UserDataAccessApplication@storeAnswers



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
	userId := int32(1) // int32 | User id
	id := int32(1) // int32 | DAR application id
	createUserDarApplicationAnswersRequest := *openapiclient.NewCreateUserDarApplicationAnswersRequest() // CreateUserDarApplicationAnswersRequest | UserDataAccessApplication definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.CreateUserDarApplicationAnswers(context.Background(), userId, id).CreateUserDarApplicationAnswersRequest(createUserDarApplicationAnswersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.CreateUserDarApplicationAnswers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserDarApplicationAnswers`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.CreateUserDarApplicationAnswers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserDarApplicationAnswersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createUserDarApplicationAnswersRequest** | [**CreateUserDarApplicationAnswersRequest**](CreateUserDarApplicationAnswersRequest.md) | UserDataAccessApplication definition | 

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


## FetchUserDarApplicationAnswers

> FetchTeamDarApplicationAnswers200Response FetchUserDarApplicationAnswers(ctx, userId, id).Execute()

UserDataAccessApplicationController@showAnswers



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
	userId := int32(1) // int32 | User id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.FetchUserDarApplicationAnswers(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.FetchUserDarApplicationAnswers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserDarApplicationAnswers`: FetchTeamDarApplicationAnswers200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.FetchUserDarApplicationAnswers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserDarApplicationAnswersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchTeamDarApplicationAnswers200Response**](FetchTeamDarApplicationAnswers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUserDarApplicationDetails

> FetchTeamDarApplication200Response FetchUserDarApplicationDetails(ctx, userId, id).Execute()

UserDataAccessApplicationController@show



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
	userId := int32(1) // int32 | User id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.FetchUserDarApplicationDetails(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.FetchUserDarApplicationDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserDarApplicationDetails`: FetchTeamDarApplication200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.FetchUserDarApplicationDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserDarApplicationDetailsRequest struct via the builder pattern


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


## FetchUserDarApplicationHeader

> FetchTeamDarApplication200Response FetchUserDarApplicationHeader(ctx, userId, id).Execute()

UserDataAccessApplicationController@showHeader



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
	userId := int32(1) // int32 | User id
	id := int32(1) // int32 | DAR application id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.FetchUserDarApplicationHeader(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.FetchUserDarApplicationHeader``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserDarApplicationHeader`: FetchTeamDarApplication200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.FetchUserDarApplicationHeader`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 
**id** | **int32** | DAR application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserDarApplicationHeaderRequest struct via the builder pattern


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


## FetchUserDarApplications

> FetchTeamDarApplications200Response FetchUserDarApplications(ctx, userId).Execute()

UserDataAccessApplicationController@index



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
	userId := int32(1) // int32 | User id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserDataAccessApplicationAPI.FetchUserDarApplications(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserDataAccessApplicationAPI.FetchUserDarApplications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserDarApplications`: FetchTeamDarApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `UserDataAccessApplicationAPI.FetchUserDarApplications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | User id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserDarApplicationsRequest struct via the builder pattern


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

