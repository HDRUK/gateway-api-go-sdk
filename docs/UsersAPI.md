# \UsersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**VerifySecondaryEmail**](UsersAPI.md#VerifySecondaryEmail) | **Get** /api/v1/users/verify-secondary-email/{uuid} | Verify user&#39;s secondary email using a UUID



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

