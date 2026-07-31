# \UsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUsers**](UsersAPI.md#CreateUsers) | **Post** /api/v1/users | UserController@store
[**DeleteUsers**](UsersAPI.md#DeleteUsers) | **Delete** /api/v1/users/{id} | UserController@destroy
[**EditUsers**](UsersAPI.md#EditUsers) | **Patch** /api/v1/users/{id} | UserController@edit
[**FetchAllUsers**](UsersAPI.md#FetchAllUsers) | **Get** /api/v1/users | UserController@index
[**FetchUsers**](UsersAPI.md#FetchUsers) | **Get** /api/v1/users/{id} | UserController@show
[**ResendSecondaryVerificationEmail**](UsersAPI.md#ResendSecondaryVerificationEmail) | **Post** /api/v1/users/{id}/resend-secondary-verification | Resend secondary email verification
[**UpdateUsers**](UsersAPI.md#UpdateUsers) | **Put** /api/v1/users/{id} | UserController@update
[**VerifySecondaryEmail**](UsersAPI.md#VerifySecondaryEmail) | **Get** /api/v1/users/verify-secondary-email/{uuid} | Verify user&#39;s secondary email using a UUID



## CreateUsers

> CreateCategories200Response CreateUsers(ctx).CreateUsersRequest(createUsersRequest).Execute()

UserController@store



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
	createUsersRequest := *openapiclient.NewCreateUsersRequest() // CreateUsersRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.CreateUsers(context.Background()).CreateUsersRequest(createUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.CreateUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUsers`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.CreateUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUsersRequest** | [**CreateUsersRequest**](CreateUsersRequest.md) | Pass user credentials | 

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


## DeleteUsers

> DeleteFederation200Response DeleteUsers(ctx, id).Execute()

UserController@destroy



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
	id := int32(1) // int32 | user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.DeleteUsers(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUsers`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.DeleteUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUsersRequest struct via the builder pattern


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


## EditUsers

> FetchUsers200Response EditUsers(ctx, id).UpdateUsersRequest(updateUsersRequest).Execute()

UserController@edit



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
	id := int32(1) // int32 | user id
	updateUsersRequest := *openapiclient.NewUpdateUsersRequest() // UpdateUsersRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.EditUsers(context.Background(), id).UpdateUsersRequest(updateUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.EditUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditUsers`: FetchUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.EditUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUsersRequest** | [**UpdateUsersRequest**](UpdateUsersRequest.md) | Pass user credentials | 

### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllUsers

> FetchAllUsers200Response FetchAllUsers(ctx).FilterNames(filterNames).Execute()

UserController@index



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
	filterNames := "abc" // string | Three or more characters to filter users names by (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.FetchAllUsers(context.Background()).FilterNames(filterNames).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.FetchAllUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllUsers`: FetchAllUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.FetchAllUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filterNames** | **string** | Three or more characters to filter users names by | 

### Return type

[**FetchAllUsers200Response**](FetchAllUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUsers

> FetchUsers200Response FetchUsers(ctx, id).Execute()

UserController@show



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
	id := int32(1) // int32 | user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.FetchUsers(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.FetchUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUsers`: FetchUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.FetchUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResendSecondaryVerificationEmail

> ResendSecondaryVerificationEmail200Response ResendSecondaryVerificationEmail(ctx, id).Execute()

Resend secondary email verification



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
	id := int32(123) // int32 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.ResendSecondaryVerificationEmail(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ResendSecondaryVerificationEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResendSecondaryVerificationEmail`: ResendSecondaryVerificationEmail200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ResendSecondaryVerificationEmail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiResendSecondaryVerificationEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResendSecondaryVerificationEmail200Response**](ResendSecondaryVerificationEmail200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUsers

> FetchUsers200Response UpdateUsers(ctx, id).UpdateUsersRequest(updateUsersRequest).Execute()

UserController@update



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
	id := int32(1) // int32 | user id
	updateUsersRequest := *openapiclient.NewUpdateUsersRequest() // UpdateUsersRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateUsers(context.Background(), id).UpdateUsersRequest(updateUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUsers`: FetchUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateUsers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUsersRequest** | [**UpdateUsersRequest**](UpdateUsersRequest.md) | Pass user credentials | 

### Return type

[**FetchUsers200Response**](FetchUsers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifySecondaryEmail

> VerifySecondaryEmail200Response VerifySecondaryEmail(ctx, uuid).Execute()

Verify user's secondary email using a UUID



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
	uuid := "03af1f5e-5cd2-4c41-ae23-56dd2c9efc67" // string | Verification UUID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.VerifySecondaryEmail(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.VerifySecondaryEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifySecondaryEmail`: VerifySecondaryEmail200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.VerifySecondaryEmail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Verification UUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifySecondaryEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VerifySecondaryEmail200Response**](VerifySecondaryEmail200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

