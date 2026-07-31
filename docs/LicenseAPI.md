# \LicenseAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateLicenses**](LicenseAPI.md#CreateLicenses) | **Post** /api/v1/licenses | License@store
[**DeleteLicenses**](LicenseAPI.md#DeleteLicenses) | **Delete** /api/v1/licenses/{id} | License@destroy
[**EditLicenses**](LicenseAPI.md#EditLicenses) | **Patch** /api/v1/licenses/{id} | License@edit
[**FetchAllLicenses**](LicenseAPI.md#FetchAllLicenses) | **Get** /api/v1/licenses | License@index
[**FetchLicenses**](LicenseAPI.md#FetchLicenses) | **Get** /api/v1/licenses/{id} | License@show
[**UpdateLicenses**](LicenseAPI.md#UpdateLicenses) | **Put** /api/v1/licenses/{id} | License@update



## CreateLicenses

> CreateCategories200Response CreateLicenses(ctx).CreateLicensesRequest(createLicensesRequest).Execute()

License@store



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	createLicensesRequest := *openapiclient.NewCreateLicensesRequest("HDR_CATEGORY_AVAILABLE_UPON_REQUEST", "Available upon request", time.Now(), "Access to the software ...", "HDR") // CreateLicensesRequest | License definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseAPI.CreateLicenses(context.Background()).CreateLicensesRequest(createLicensesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.CreateLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateLicenses`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.CreateLicenses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateLicensesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | License definition | 

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


## DeleteLicenses

> DeleteAliases200Response DeleteLicenses(ctx, id).Execute()

License@destroy



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
	id := int32(1) // int32 | License id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseAPI.DeleteLicenses(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.DeleteLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteLicenses`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.DeleteLicenses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | License id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteLicensesRequest struct via the builder pattern


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


## EditLicenses

> UpdateLicenses200Response EditLicenses(ctx, id).CreateLicensesRequest(createLicensesRequest).Execute()

License@edit



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | license id
	createLicensesRequest := *openapiclient.NewCreateLicensesRequest("HDR_CATEGORY_AVAILABLE_UPON_REQUEST", "Available upon request", time.Now(), "Access to the software ...", "HDR") // CreateLicensesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseAPI.EditLicenses(context.Background(), id).CreateLicensesRequest(createLicensesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.EditLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditLicenses`: UpdateLicenses200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.EditLicenses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | license id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditLicensesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | Category definition | 

### Return type

[**UpdateLicenses200Response**](UpdateLicenses200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllLicenses

> FetchAllLicenses200Response FetchAllLicenses(ctx).Execute()

License@index



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
	resp, r, err := apiClient.LicenseAPI.FetchAllLicenses(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.FetchAllLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllLicenses`: FetchAllLicenses200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.FetchAllLicenses`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllLicensesRequest struct via the builder pattern


### Return type

[**FetchAllLicenses200Response**](FetchAllLicenses200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchLicenses

> FetchLicenses200Response FetchLicenses(ctx, id).Execute()

License@show



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
	id := int32(1) // int32 | License ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseAPI.FetchLicenses(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.FetchLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchLicenses`: FetchLicenses200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.FetchLicenses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | License ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchLicensesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchLicenses200Response**](FetchLicenses200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateLicenses

> UpdateLicenses200Response UpdateLicenses(ctx, id).CreateLicensesRequest(createLicensesRequest).Execute()

License@update



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | license id
	createLicensesRequest := *openapiclient.NewCreateLicensesRequest("HDR_CATEGORY_AVAILABLE_UPON_REQUEST", "Available upon request", time.Now(), "Access to the software ...", "HDR") // CreateLicensesRequest | Category definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseAPI.UpdateLicenses(context.Background(), id).CreateLicensesRequest(createLicensesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseAPI.UpdateLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateLicenses`: UpdateLicenses200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseAPI.UpdateLicenses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | license id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateLicensesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createLicensesRequest** | [**CreateLicensesRequest**](CreateLicensesRequest.md) | Category definition | 

### Return type

[**UpdateLicenses200Response**](UpdateLicenses200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

