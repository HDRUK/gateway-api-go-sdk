# \PublicationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountTeamUniqueFieldsPublicationV2**](PublicationAPI.md#CountTeamUniqueFieldsPublicationV2) | **Get** /api/v2/teams/{teamId}/publications/count/{field} | TeamPublicationController@count
[**CountUniqueFieldsPublications**](PublicationAPI.md#CountUniqueFieldsPublications) | **Get** /api/v1/publication/count/{field} | PublicationController@count
[**CountUserUniqueFieldsPublicationV2**](PublicationAPI.md#CountUserUniqueFieldsPublicationV2) | **Get** /api/v2/users/{userId}/publications/count/{field} | UserPublicationController@count
[**CreatePublications**](PublicationAPI.md#CreatePublications) | **Post** /api/v1/publications | PublicationController@store
[**CreatePublicationsV2ByTeamId**](PublicationAPI.md#CreatePublicationsV2ByTeamId) | **Post** /api/v2/teams/{teamId}/publications | TeamPublicationController@store
[**CreatePublicationsV2ByUserId**](PublicationAPI.md#CreatePublicationsV2ByUserId) | **Post** /api/v2/users/{userId}/publications | UserPublicationController@store
[**DeletePublications**](PublicationAPI.md#DeletePublications) | **Delete** /api/v1/publications/{id} | PublicationController@destroy
[**DeletePublicationsV2ByTeamId**](PublicationAPI.md#DeletePublicationsV2ByTeamId) | **Delete** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@destroy
[**DeletePublicationsV2ByUserId**](PublicationAPI.md#DeletePublicationsV2ByUserId) | **Delete** /api/v2/users/{userId}/publications/{id} | UserPublicationController@destroy
[**EditPublications**](PublicationAPI.md#EditPublications) | **Patch** /api/v1/publications/{id} | PublicationController@edit
[**EditPublicationsV2ByTeamId**](PublicationAPI.md#EditPublicationsV2ByTeamId) | **Patch** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@edit
[**EditPublicationsV2ByUserId**](PublicationAPI.md#EditPublicationsV2ByUserId) | **Patch** /api/v2/users/{userId}/publications/{id} | UserPublicationController@edit
[**FetchAllPublications**](PublicationAPI.md#FetchAllPublications) | **Get** /api/v1/publications | PublicationController@index
[**FetchAllPublicationsByTeamAndStatusV2**](PublicationAPI.md#FetchAllPublicationsByTeamAndStatusV2) | **Get** /api/v2/teams/{teamId}/publications/status/{status} | TeamPublicationController@indexStatus
[**FetchAllPublicationsByUserAndStatusV2**](PublicationAPI.md#FetchAllPublicationsByUserAndStatusV2) | **Get** /api/v2/users/{userId}/publications/{status} | UserPublicationController@indexStatus
[**FetchAllPublicationsV2**](PublicationAPI.md#FetchAllPublicationsV2) | **Get** /api/v2/publications | PublicationController@indexActive
[**FetchPublications**](PublicationAPI.md#FetchPublications) | **Get** /api/v1/publications/{id} | PublicationController@show
[**FetchPublicationsByTeamAndByIdV2**](PublicationAPI.md#FetchPublicationsByTeamAndByIdV2) | **Get** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@show
[**FetchPublicationsByUserAndByIdV2**](PublicationAPI.md#FetchPublicationsByUserAndByIdV2) | **Get** /api/v2/users/{userId}/publications/{id} | UserPublicationController@show
[**FetchPublicationsV2**](PublicationAPI.md#FetchPublicationsV2) | **Get** /api/v2/publications/{id} | PublicationController@showActive
[**UpdatePublications**](PublicationAPI.md#UpdatePublications) | **Put** /api/v1/publications/{id} | PublicationController@update
[**UpdatePublicationsV2ByTeamId**](PublicationAPI.md#UpdatePublicationsV2ByTeamId) | **Put** /api/v2/teams/{teamId}/publications/{id} | TeamPublicationController@update
[**UpdatePublicationsV2ByUserId**](PublicationAPI.md#UpdatePublicationsV2ByUserId) | **Put** /api/v2/users/{userId}/publications/{id} | UserPublicationController@update



## CountTeamUniqueFieldsPublicationV2

> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsPublicationV2(ctx, teamId, field).Execute()

TeamPublicationController@count



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
	teamId := int32(1) // int32 | team id
	field := "status" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CountTeamUniqueFieldsPublicationV2(context.Background(), teamId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CountTeamUniqueFieldsPublicationV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountTeamUniqueFieldsPublicationV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CountTeamUniqueFieldsPublicationV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountTeamUniqueFieldsPublicationV2Request struct via the builder pattern


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


## CountUniqueFieldsPublications

> CountUniqueFieldsCollections200Response CountUniqueFieldsPublications(ctx, field).OwnerId(ownerId).TeamId(teamId).Execute()

PublicationController@count



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
	field := "status" // string | name of the field to perform a count on
	ownerId := int32(1) // int32 | owner id
	teamId := int32(1) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CountUniqueFieldsPublications(context.Background(), field).OwnerId(ownerId).TeamId(teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CountUniqueFieldsPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsPublications`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CountUniqueFieldsPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ownerId** | **int32** | owner id | 
 **teamId** | **int32** |  | 

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


## CountUserUniqueFieldsPublicationV2

> CountUniqueFieldsCollections200Response CountUserUniqueFieldsPublicationV2(ctx, userId, field).Execute()

UserPublicationController@count



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
	userId := int32(1) // int32 | user id
	field := "status" // string | name of the field to perform a count on

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CountUserUniqueFieldsPublicationV2(context.Background(), userId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CountUserUniqueFieldsPublicationV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUserUniqueFieldsPublicationV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CountUserUniqueFieldsPublicationV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUserUniqueFieldsPublicationV2Request struct via the builder pattern


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


## CreatePublications

> CreateCategories200Response CreatePublications(ctx).CreatePublicationsRequest(createPublicationsRequest).Execute()

PublicationController@store



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
	createPublicationsRequest := *openapiclient.NewCreatePublicationsRequest() // CreatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CreatePublications(context.Background()).CreatePublicationsRequest(createPublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CreatePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublications`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CreatePublications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials | 

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


## CreatePublicationsV2ByTeamId

> CreateCategories200Response CreatePublicationsV2ByTeamId(ctx, teamId).CreatePublicationsRequest(createPublicationsRequest).Execute()

TeamPublicationController@store



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
	teamId := int32(1) // int32 | team id
	createPublicationsRequest := *openapiclient.NewCreatePublicationsRequest() // CreatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CreatePublicationsV2ByTeamId(context.Background(), teamId).CreatePublicationsRequest(createPublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CreatePublicationsV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublicationsV2ByTeamId`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CreatePublicationsV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePublicationsV2ByTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials | 

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


## CreatePublicationsV2ByUserId

> CreateCategories200Response CreatePublicationsV2ByUserId(ctx, userId).CreatePublicationsRequest(createPublicationsRequest).Execute()

UserPublicationController@store



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
	userId := int64(789) // int64 | ID of the user
	createPublicationsRequest := *openapiclient.NewCreatePublicationsRequest() // CreatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.CreatePublicationsV2ByUserId(context.Background(), userId).CreatePublicationsRequest(createPublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.CreatePublicationsV2ByUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublicationsV2ByUserId`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.CreatePublicationsV2ByUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePublicationsV2ByUserIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createPublicationsRequest** | [**CreatePublicationsRequest**](CreatePublicationsRequest.md) | Pass user credentials | 

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


## DeletePublications

> DeleteFederation200Response DeletePublications(ctx, id).Execute()

PublicationController@destroy



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.DeletePublications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.DeletePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePublications`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.DeletePublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePublicationsRequest struct via the builder pattern


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


## DeletePublicationsV2ByTeamId

> DeleteFederation200Response DeletePublicationsV2ByTeamId(ctx, teamId, id).Execute()

TeamPublicationController@destroy



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.DeletePublicationsV2ByTeamId(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.DeletePublicationsV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePublicationsV2ByTeamId`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.DeletePublicationsV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePublicationsV2ByTeamIdRequest struct via the builder pattern


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


## DeletePublicationsV2ByUserId

> DeleteFederation200Response DeletePublicationsV2ByUserId(ctx, userId, id).Execute()

UserPublicationController@destroy



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
	userId := int64(789) // int64 | ID of the user
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.DeletePublicationsV2ByUserId(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.DeletePublicationsV2ByUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePublicationsV2ByUserId`: DeleteFederation200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.DeletePublicationsV2ByUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePublicationsV2ByUserIdRequest struct via the builder pattern


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


## EditPublications

> FetchPublications200Response EditPublications(ctx, id).UpdatePublicationsRequest(updatePublicationsRequest).Unarchive(unarchive).Execute()

PublicationController@edit



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
	id := int32(1) // int32 | publications id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a publication (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.EditPublications(context.Background(), id).UpdatePublicationsRequest(updatePublicationsRequest).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.EditPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditPublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.EditPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publications id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a publication | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditPublicationsV2ByTeamId

> FetchPublications200Response EditPublicationsV2ByTeamId(ctx, teamId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

TeamPublicationController@edit



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | publications id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.EditPublicationsV2ByTeamId(context.Background(), teamId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.EditPublicationsV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditPublicationsV2ByTeamId`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.EditPublicationsV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | publications id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditPublicationsV2ByTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditPublicationsV2ByUserId

> FetchPublications200Response EditPublicationsV2ByUserId(ctx, userId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

UserPublicationController@edit



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
	userId := int64(789) // int64 | ID of the user
	id := int32(1) // int32 | publications id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.EditPublicationsV2ByUserId(context.Background(), userId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.EditPublicationsV2ByUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditPublicationsV2ByUserId`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.EditPublicationsV2ByUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 
**id** | **int32** | publications id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditPublicationsV2ByUserIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublications

> FetchAllPublications200Response FetchAllPublications(ctx).PaperTitle(paperTitle).OwnerId(ownerId).TeamId(teamId).Status(status).Execute()

PublicationController@index



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
	paperTitle := "paperTitle_example" // string | Filter tools by paper title (optional)
	ownerId := TODO // int | Filter tools by owner id (optional)
	teamId := TODO // int | Filter tools by team id (optional)
	status := "ACTIVE" // string | Publication status to filter by ('ACTIVE', 'DRAFT', 'ARCHIVED') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublications(context.Background()).PaperTitle(paperTitle).OwnerId(ownerId).TeamId(teamId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublications`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **paperTitle** | **string** | Filter tools by paper title | 
 **ownerId** | [**int**](int.md) | Filter tools by owner id | 
 **teamId** | [**int**](int.md) | Filter tools by team id | 
 **status** | **string** | Publication status to filter by (&#39;ACTIVE&#39;, &#39;DRAFT&#39;, &#39;ARCHIVED&#39;) | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublicationsByTeamAndStatusV2

> FetchAllPublications200Response FetchAllPublicationsByTeamAndStatusV2(ctx, teamId, status).PaperTitle(paperTitle).Execute()

TeamPublicationController@indexStatus



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
	teamId := int64(789) // int64 | ID of the team
	status := "status_example" // string | Status of the team (active, draft, or archived). Defaults to active if not provided. (default to "active")
	paperTitle := "paperTitle_example" // string | Filter Publication by title (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublicationsByTeamAndStatusV2(context.Background(), teamId, status).PaperTitle(paperTitle).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublicationsByTeamAndStatusV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublicationsByTeamAndStatusV2`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublicationsByTeamAndStatusV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int64** | ID of the team | 
**status** | **string** | Status of the team (active, draft, or archived). Defaults to active if not provided. | [default to &quot;active&quot;]

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsByTeamAndStatusV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **paperTitle** | **string** | Filter Publication by title | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublicationsByUserAndStatusV2

> FetchAllPublications200Response FetchAllPublicationsByUserAndStatusV2(ctx, userId, status).PaperTitle(paperTitle).Execute()

UserPublicationController@indexStatus



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
	userId := int64(789) // int64 | ID of the user
	status := "status_example" // string | Status of the team (active, draft, or archived). Defaults to active if not provided. (default to "active")
	paperTitle := "paperTitle_example" // string | Filter Publication by title (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublicationsByUserAndStatusV2(context.Background(), userId, status).PaperTitle(paperTitle).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublicationsByUserAndStatusV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublicationsByUserAndStatusV2`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublicationsByUserAndStatusV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 
**status** | **string** | Status of the team (active, draft, or archived). Defaults to active if not provided. | [default to &quot;active&quot;]

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsByUserAndStatusV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **paperTitle** | **string** | Filter Publication by title | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllPublicationsV2

> FetchAllPublications200Response FetchAllPublicationsV2(ctx).PaperTitle(paperTitle).WithRelated(withRelated).PerPage(perPage).Execute()

PublicationController@indexActive



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
	paperTitle := "paperTitle_example" // string | Filter tools by paper title (optional)
	withRelated := true // bool | Return related datasets (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchAllPublicationsV2(context.Background()).PaperTitle(paperTitle).WithRelated(withRelated).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchAllPublicationsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllPublicationsV2`: FetchAllPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchAllPublicationsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllPublicationsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **paperTitle** | **string** | Filter tools by paper title | 
 **withRelated** | **bool** | Return related datasets | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllPublications200Response**](FetchAllPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublications

> FetchPublications200Response FetchPublications(ctx, id).Execute()

PublicationController@show



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublications(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublicationsByTeamAndByIdV2

> FetchPublications200Response FetchPublicationsByTeamAndByIdV2(ctx, teamId, id).Execute()

TeamPublicationController@show



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublicationsByTeamAndByIdV2(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublicationsByTeamAndByIdV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublicationsByTeamAndByIdV2`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublicationsByTeamAndByIdV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsByTeamAndByIdV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublicationsByUserAndByIdV2

> FetchPublications200Response FetchPublicationsByUserAndByIdV2(ctx, userId, id).Execute()

UserPublicationController@show



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
	userId := int64(789) // int64 | ID of the user
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublicationsByUserAndByIdV2(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublicationsByUserAndByIdV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublicationsByUserAndByIdV2`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublicationsByUserAndByIdV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsByUserAndByIdV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchPublicationsV2

> FetchPublications200Response FetchPublicationsV2(ctx, id).Execute()

PublicationController@showActive



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
	id := int32(1) // int32 | publication id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.FetchPublicationsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.FetchPublicationsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchPublicationsV2`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.FetchPublicationsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchPublicationsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePublications

> FetchPublications200Response UpdatePublications(ctx, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

PublicationController@update



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
	id := int32(1) // int32 | publication id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.UpdatePublications(context.Background(), id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.UpdatePublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePublications`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.UpdatePublications`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePublicationsV2ByTeamId

> FetchPublications200Response UpdatePublicationsV2ByTeamId(ctx, teamId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

TeamPublicationController@update



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
	teamId := int32(1) // int32 | team id
	id := int32(1) // int32 | publication id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.UpdatePublicationsV2ByTeamId(context.Background(), teamId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.UpdatePublicationsV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePublicationsV2ByTeamId`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.UpdatePublicationsV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePublicationsV2ByTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePublicationsV2ByUserId

> FetchPublications200Response UpdatePublicationsV2ByUserId(ctx, userId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()

UserPublicationController@update



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
	userId := int64(789) // int64 | ID of the user
	id := int32(1) // int32 | publication id
	updatePublicationsRequest := *openapiclient.NewUpdatePublicationsRequest() // UpdatePublicationsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicationAPI.UpdatePublicationsV2ByUserId(context.Background(), userId, id).UpdatePublicationsRequest(updatePublicationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicationAPI.UpdatePublicationsV2ByUserId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePublicationsV2ByUserId`: FetchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicationAPI.UpdatePublicationsV2ByUserId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int64** | ID of the user | 
**id** | **int32** | publication id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePublicationsV2ByUserIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePublicationsRequest** | [**UpdatePublicationsRequest**](UpdatePublicationsRequest.md) | Pass user credentials | 

### Return type

[**FetchPublications200Response**](FetchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

