# \ProgrammingPackageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProgrammingPackages**](ProgrammingPackageAPI.md#CreateProgrammingPackages) | **Post** /api/v1/programming_packages | ProgrammingPackage@store
[**DeleteProgrammingPackages**](ProgrammingPackageAPI.md#DeleteProgrammingPackages) | **Delete** /api/v1/programming_packages/{id} | ProgrammingPackage@destroy
[**EditProgrammingPackages**](ProgrammingPackageAPI.md#EditProgrammingPackages) | **Patch** /api/v1/programming_packages/{id} | ProgrammingPackage@update
[**UpdateProgrammingPackages**](ProgrammingPackageAPI.md#UpdateProgrammingPackages) | **Put** /api/v1/programming_packages/{id} | ProgrammingPackage@update



## CreateProgrammingPackages

> CreateDarIntegration201Response CreateProgrammingPackages(ctx).CreateProgrammingLanguagesRequest(createProgrammingLanguagesRequest).Execute()

ProgrammingPackage@store



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
	createProgrammingLanguagesRequest := *openapiclient.NewCreateProgrammingLanguagesRequest("Name", true) // CreateProgrammingLanguagesRequest | Programming package definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.CreateProgrammingPackages(context.Background()).CreateProgrammingLanguagesRequest(createProgrammingLanguagesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.CreateProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProgrammingPackages`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.CreateProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProgrammingLanguagesRequest** | [**CreateProgrammingLanguagesRequest**](CreateProgrammingLanguagesRequest.md) | Programming package definition | 

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


## DeleteProgrammingPackages

> DeleteApplications200Response DeleteProgrammingPackages(ctx, id).Execute()

ProgrammingPackage@destroy



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
	id := int32(1) // int32 | programming package id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.DeleteProgrammingPackages(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.DeleteProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProgrammingPackages`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.DeleteProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProgrammingPackagesRequest struct via the builder pattern


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


## EditProgrammingPackages

> UpdateProgrammingPackages200Response EditProgrammingPackages(ctx, id).EditProgrammingLanguagesRequest(editProgrammingLanguagesRequest).Execute()

ProgrammingPackage@update



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
	id := int32(1) // int32 | programming package id
	editProgrammingLanguagesRequest := *openapiclient.NewEditProgrammingLanguagesRequest() // EditProgrammingLanguagesRequest | ProgrammingPackage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.EditProgrammingPackages(context.Background(), id).EditProgrammingLanguagesRequest(editProgrammingLanguagesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.EditProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditProgrammingPackages`: UpdateProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.EditProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editProgrammingLanguagesRequest** | [**EditProgrammingLanguagesRequest**](EditProgrammingLanguagesRequest.md) | ProgrammingPackage definition | 

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProgrammingPackages

> UpdateProgrammingPackages200Response UpdateProgrammingPackages(ctx, id).UpdateProgrammingLanguagesRequest(updateProgrammingLanguagesRequest).Execute()

ProgrammingPackage@update



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
	id := int32(1) // int32 | programming package id
	updateProgrammingLanguagesRequest := *openapiclient.NewUpdateProgrammingLanguagesRequest("Name", "true") // UpdateProgrammingLanguagesRequest | ProgrammingPackage definition

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgrammingPackageAPI.UpdateProgrammingPackages(context.Background(), id).UpdateProgrammingLanguagesRequest(updateProgrammingLanguagesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgrammingPackageAPI.UpdateProgrammingPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProgrammingPackages`: UpdateProgrammingPackages200Response
	fmt.Fprintf(os.Stdout, "Response from `ProgrammingPackageAPI.UpdateProgrammingPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | programming package id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProgrammingPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateProgrammingLanguagesRequest** | [**UpdateProgrammingLanguagesRequest**](UpdateProgrammingLanguagesRequest.md) | ProgrammingPackage definition | 

### Return type

[**UpdateProgrammingPackages200Response**](UpdateProgrammingPackages200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

