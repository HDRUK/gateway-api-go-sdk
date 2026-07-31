# \NotificationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateNotifications**](NotificationAPI.md#CreateNotifications) | **Post** /api/v1/notifications | Notification@store
[**DeleteNotifications**](NotificationAPI.md#DeleteNotifications) | **Delete** /api/v1/notifications/{id} | Notification@destroy
[**EditNotifications**](NotificationAPI.md#EditNotifications) | **Patch** /api/v1/notifications/{id} | Notification@edit
[**FetchAllNotifications**](NotificationAPI.md#FetchAllNotifications) | **Get** /api/v1/notifications | Notification@index
[**FetchNotifications**](NotificationAPI.md#FetchNotifications) | **Get** /api/v1/notifications/{id} | Notification@show
[**UpdateNotifications**](NotificationAPI.md#UpdateNotifications) | **Put** /api/v1/notifications/{id} | Notification@update



## CreateNotifications

> CreateCategories200Response CreateNotifications(ctx).CreateNotificationsRequest(createNotificationsRequest).Execute()

Notification@store



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
	createNotificationsRequest := *openapiclient.NewCreateNotificationsRequest("applicationSubmitted", "your message here", false, false) // CreateNotificationsRequest | Notification definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.CreateNotifications(context.Background()).CreateNotificationsRequest(createNotificationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.CreateNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateNotifications`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.CreateNotifications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createNotificationsRequest** | [**CreateNotificationsRequest**](CreateNotificationsRequest.md) | Notification definition | 

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


## DeleteNotifications

> DeleteAliases200Response DeleteNotifications(ctx, id).Execute()

Notification@destroy



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
	id := int32(1) // int32 | notification id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.DeleteNotifications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.DeleteNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteNotifications`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.DeleteNotifications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | notification id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteNotificationsRequest struct via the builder pattern


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


## EditNotifications

> UpdateNotifications200Response EditNotifications(ctx, id).EditNotificationsRequest(editNotificationsRequest).Execute()

Notification@edit



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
	id := int32(1) // int32 | notification id
	editNotificationsRequest := *openapiclient.NewEditNotificationsRequest() // EditNotificationsRequest | Notification definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.EditNotifications(context.Background(), id).EditNotificationsRequest(editNotificationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.EditNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditNotifications`: UpdateNotifications200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.EditNotifications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | notification id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editNotificationsRequest** | [**EditNotificationsRequest**](EditNotificationsRequest.md) | Notification definition | 

### Return type

[**UpdateNotifications200Response**](UpdateNotifications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllNotifications

> FetchAllNotifications200Response FetchAllNotifications(ctx).Execute()

Notification@index



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
	resp, r, err := apiClient.NotificationAPI.FetchAllNotifications(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.FetchAllNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllNotifications`: FetchAllNotifications200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.FetchAllNotifications`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllNotificationsRequest struct via the builder pattern


### Return type

[**FetchAllNotifications200Response**](FetchAllNotifications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchNotifications

> FetchNotifications200Response FetchNotifications(ctx, id).Execute()

Notification@show



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
	id := int32(1) // int32 | notification id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.FetchNotifications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.FetchNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchNotifications`: FetchNotifications200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.FetchNotifications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | notification id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchNotifications200Response**](FetchNotifications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateNotifications

> UpdateNotifications200Response UpdateNotifications(ctx, id).CreateNotificationsRequest(createNotificationsRequest).Execute()

Notification@update



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
	id := int32(1) // int32 | notification id
	createNotificationsRequest := *openapiclient.NewCreateNotificationsRequest("applicationSubmitted", "your message here", false, false) // CreateNotificationsRequest | Notification definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.UpdateNotifications(context.Background(), id).CreateNotificationsRequest(createNotificationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.UpdateNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateNotifications`: UpdateNotifications200Response
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.UpdateNotifications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | notification id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createNotificationsRequest** | [**CreateNotificationsRequest**](CreateNotificationsRequest.md) | Notification definition | 

### Return type

[**UpdateNotifications200Response**](UpdateNotifications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

