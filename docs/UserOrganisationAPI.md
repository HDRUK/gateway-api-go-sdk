# \UserOrganisationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchUserOrganisations**](UserOrganisationAPI.md#FetchUserOrganisations) | **Get** /api/v1/users/organisations | UserOrganisation@index



## FetchUserOrganisations

> FetchUserOrganisations200Response FetchUserOrganisations(ctx).Execute()

UserOrganisation@index



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
	resp, r, err := apiClient.UserOrganisationAPI.FetchUserOrganisations(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserOrganisationAPI.FetchUserOrganisations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserOrganisations`: FetchUserOrganisations200Response
	fmt.Fprintf(os.Stdout, "Response from `UserOrganisationAPI.FetchUserOrganisations`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserOrganisationsRequest struct via the builder pattern


### Return type

[**FetchUserOrganisations200Response**](FetchUserOrganisations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

