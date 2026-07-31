# \DataAccessTemplatesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DarTemplateCountUniqueFields**](DataAccessTemplatesAPI.md#DarTemplateCountUniqueFields) | **Get** /api/v1/dar/templates/count/{field} | DataAccessTemplateController@count



## DarTemplateCountUniqueFields

> CountUniqueFieldsCollections200Response DarTemplateCountUniqueFields(ctx, field).Execute()

DataAccessTemplateController@count



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
	field := "published" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataAccessTemplatesAPI.DarTemplateCountUniqueFields(context.Background(), field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataAccessTemplatesAPI.DarTemplateCountUniqueFields``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DarTemplateCountUniqueFields`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `DataAccessTemplatesAPI.DarTemplateCountUniqueFields`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiDarTemplateCountUniqueFieldsRequest struct via the builder pattern


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

