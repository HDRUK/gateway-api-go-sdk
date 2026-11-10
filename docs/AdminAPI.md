# \AdminAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RevokeAllTokensV2**](AdminAPI.md#RevokeAllTokensV2) | **Post** /api/v2/admin/tokens/revoke_all | TokenRevocationController@revokeAll



## RevokeAllTokensV2

> RevokeAllTokensV2200Response RevokeAllTokensV2(ctx).Execute()

TokenRevocationController@revokeAll



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
	resp, r, err := apiClient.AdminAPI.RevokeAllTokensV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.RevokeAllTokensV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeAllTokensV2`: RevokeAllTokensV2200Response
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.RevokeAllTokensV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeAllTokensV2Request struct via the builder pattern


### Return type

[**RevokeAllTokensV2200Response**](RevokeAllTokensV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

