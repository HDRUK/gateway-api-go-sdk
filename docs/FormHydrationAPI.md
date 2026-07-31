# \FormHydrationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetFormSchema**](FormHydrationAPI.md#GetFormSchema) | **Get** /api/v1/form_hydration/schema | Retrieve form schema data
[**OnboardingFormHydration**](FormHydrationAPI.md#OnboardingFormHydration) | **Get** /api/v1/form_hydration | Retrieve form schema data



## GetFormSchema

> map[string]interface{} GetFormSchema(ctx).Model(model).Version(version).Execute()

Retrieve form schema data



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
	model := "model_example" // string | The model for which form schema is requested. (optional)
	version := "version_example" // string | The version of the model for which form schema is requested. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormHydrationAPI.GetFormSchema(context.Background()).Model(model).Version(version).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormHydrationAPI.GetFormSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFormSchema`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `FormHydrationAPI.GetFormSchema`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFormSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | **string** | The model for which form schema is requested. | 
 **version** | **string** | The version of the model for which form schema is requested. | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OnboardingFormHydration

> map[string]interface{} OnboardingFormHydration(ctx).Name(name).Version(version).DataTypes(dataTypes).Execute()

Retrieve form schema data



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
	name := "name_example" // string | The model name for which form schema is requested. (optional)
	version := "version_example" // string | The version of the model for which form schema is requested. (optional)
	dataTypes := "dataTypes_example" // string | The data types of the dataset about to be onboarded. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormHydrationAPI.OnboardingFormHydration(context.Background()).Name(name).Version(version).DataTypes(dataTypes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormHydrationAPI.OnboardingFormHydration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OnboardingFormHydration`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `FormHydrationAPI.OnboardingFormHydration`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOnboardingFormHydrationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | The model name for which form schema is requested. | 
 **version** | **string** | The version of the model for which form schema is requested. | 
 **dataTypes** | **string** | The data types of the dataset about to be onboarded. | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

