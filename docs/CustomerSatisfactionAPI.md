# \CustomerSatisfactionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCsat**](CustomerSatisfactionAPI.md#CreateCsat) | **Post** /api/v1/csat | Create Customer Satisfaction Score
[**EditCsat**](CustomerSatisfactionAPI.md#EditCsat) | **Patch** /api/v1/csat/{id} | Update Customer Satisfaction Description



## CreateCsat

> DeleteAliases200Response CreateCsat(ctx).CreateCsatRequest(createCsatRequest).Execute()

Create Customer Satisfaction Score



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
	createCsatRequest := *openapiclient.NewCreateCsatRequest(int32(1)) // CreateCsatRequest | Customer Satisfaction score

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerSatisfactionAPI.CreateCsat(context.Background()).CreateCsatRequest(createCsatRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerSatisfactionAPI.CreateCsat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCsat`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CustomerSatisfactionAPI.CreateCsat`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCsatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCsatRequest** | [**CreateCsatRequest**](CreateCsatRequest.md) | Customer Satisfaction score | 

### Return type

[**DeleteAliases200Response**](DeleteAliases200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditCsat

> EditCsat200Response EditCsat(ctx, id).EditCsatRequest(editCsatRequest).Execute()

Update Customer Satisfaction Description



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
	id := int32(56) // int32 | ID of the CSAT entry
	editCsatRequest := *openapiclient.NewEditCsatRequest("Your feedback goes here...", int32(1)) // EditCsatRequest | Reason to update

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerSatisfactionAPI.EditCsat(context.Background(), id).EditCsatRequest(editCsatRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerSatisfactionAPI.EditCsat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditCsat`: EditCsat200Response
	fmt.Fprintf(os.Stdout, "Response from `CustomerSatisfactionAPI.EditCsat`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | ID of the CSAT entry | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditCsatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCsatRequest** | [**EditCsatRequest**](EditCsatRequest.md) | Reason to update | 

### Return type

[**EditCsat200Response**](EditCsat200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

