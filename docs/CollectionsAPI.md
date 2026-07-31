# \CollectionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CountTeamUniqueFieldsCollectionV2**](CollectionsAPI.md#CountTeamUniqueFieldsCollectionV2) | **Get** /api/v2/teams/{teamId}/collections/count/{field} | TeamCollectionController@count
[**CountUniqueFieldsCollections**](CollectionsAPI.md#CountUniqueFieldsCollections) | **Get** /api/v1/collections/count/{field} | CollectionController@count
[**CountUniqueFieldsCollectionsV2**](CollectionsAPI.md#CountUniqueFieldsCollectionsV2) | **Get** /api/v2/collections/count/{field} | CollectionController@count
[**CountUserUniqueFieldsCollectionV2**](CollectionsAPI.md#CountUserUniqueFieldsCollectionV2) | **Get** /api/v2/users/{userId}/collections/count/{field} | UserCollectionController@count
[**CreateCollections**](CollectionsAPI.md#CreateCollections) | **Post** /api/v2/collections | CollectionController@store
[**CreateTeamCollections**](CollectionsAPI.md#CreateTeamCollections) | **Post** /api/v1/teams/{teamId}/collections | CollectionController@store
[**CreateTeamCollectionsV2**](CollectionsAPI.md#CreateTeamCollectionsV2) | **Post** /api/v2/teams/{teamId}/collections | TeamCollectionController@store
[**CreateUserCollections**](CollectionsAPI.md#CreateUserCollections) | **Post** /api/v2/users/collections | UserCollectionController@store
[**DeleteCollectionsV2**](CollectionsAPI.md#DeleteCollectionsV2) | **Delete** /api/v2/collections/{id} | Delete a collection
[**DeleteTeamCollections**](CollectionsAPI.md#DeleteTeamCollections) | **Delete** /api/v1/teams/{teamId}/collections/{id} | Delete a collection
[**DeleteTeamCollectionsV2**](CollectionsAPI.md#DeleteTeamCollectionsV2) | **Delete** /api/v2/teams/{teamId}/collections/{id} | Delete a collection
[**DeleteUserCollectionsV2**](CollectionsAPI.md#DeleteUserCollectionsV2) | **Delete** /api/v2/users/{userId}/collections/{id} | Delete a collection
[**EditCollectionsV2**](CollectionsAPI.md#EditCollectionsV2) | **Patch** /api/v2/collections/{id} | Edit a collection
[**EditTeamCollections**](CollectionsAPI.md#EditTeamCollections) | **Patch** /api/v1/teams/{teamId}/collections/{id} | Edit a collection
[**EditTeamCollectionsV2**](CollectionsAPI.md#EditTeamCollectionsV2) | **Patch** /api/v2/teams/{teamId}/collections/{id} | Edit a collection
[**EditUserCollectionsV2**](CollectionsAPI.md#EditUserCollectionsV2) | **Patch** /api/v2/users/{userId}/collections/{id} | Edit a collection
[**FetchAllCollections**](CollectionsAPI.md#FetchAllCollections) | **Get** /api/v1/collections | CollectionController@index
[**FetchAllCollectionsV2**](CollectionsAPI.md#FetchAllCollectionsV2) | **Get** /api/v2/collections | CollectionController@index
[**FetchCollections**](CollectionsAPI.md#FetchCollections) | **Get** /api/v1/collections/{id} | CollectionController@show
[**FetchCollectionsV2**](CollectionsAPI.md#FetchCollectionsV2) | **Get** /api/v2/collections/{id} | CollectionController@show
[**FetchTeamActiveCollectionsV2**](CollectionsAPI.md#FetchTeamActiveCollectionsV2) | **Get** /api/v2/teams/{teamId}/collections/status/active | TeamCollectionController@indexActive
[**FetchTeamArchivedCollectionsV2**](CollectionsAPI.md#FetchTeamArchivedCollectionsV2) | **Get** /api/v2/teams/{teamId}/collections/status/archived | TeamCollectionController@indexArchived
[**FetchTeamCollectionV2**](CollectionsAPI.md#FetchTeamCollectionV2) | **Get** /api/v2/teams/{teamId}/collections/{id} | TeamCollectionController@show
[**FetchTeamDraftCollectionsV2**](CollectionsAPI.md#FetchTeamDraftCollectionsV2) | **Get** /api/v2/teams/{teamId}/collections/status/draft | TeamCollectionController@indexDraft
[**FetchUserArchivedCollectionsV2**](CollectionsAPI.md#FetchUserArchivedCollectionsV2) | **Get** /api/v2/users/{userId}/collections/status/archived | UserCollectionController@indexArchived
[**FetchUserCollectionV2**](CollectionsAPI.md#FetchUserCollectionV2) | **Get** /api/v2/users/{userId}/collections/{id} | CollectionController@show
[**FetchUserCollectionsV2**](CollectionsAPI.md#FetchUserCollectionsV2) | **Get** /api/v2/users/{userId}/collections/status/active | UserCollectionController@indexActive
[**FetchUserDraftCollectionsV2**](CollectionsAPI.md#FetchUserDraftCollectionsV2) | **Get** /api/v2/users/{userId}/collections/status/draft | UserCollectionController@indexDraft
[**UpdateCollectionsV2**](CollectionsAPI.md#UpdateCollectionsV2) | **Put** /api/v2/collections/{id} | Update a collection
[**UpdateTeamCollections**](CollectionsAPI.md#UpdateTeamCollections) | **Put** /api/v1/teams/{teamId}/collections/{id} | Update a collection
[**UpdateTeamCollectionsV2**](CollectionsAPI.md#UpdateTeamCollectionsV2) | **Put** /api/v2/teams/{teamId}/collections/{id} | Update a collection
[**UpdateUserCollectionsV2**](CollectionsAPI.md#UpdateUserCollectionsV2) | **Put** /api/v2/users/{userId}/collections/{id} | Update a collection



## CountTeamUniqueFieldsCollectionV2

> CountUniqueFieldsCollections200Response CountTeamUniqueFieldsCollectionV2(ctx, teamId, field).Execute()

TeamCollectionController@count



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
	resp, r, err := apiClient.CollectionsAPI.CountTeamUniqueFieldsCollectionV2(context.Background(), teamId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountTeamUniqueFieldsCollectionV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountTeamUniqueFieldsCollectionV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountTeamUniqueFieldsCollectionV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountTeamUniqueFieldsCollectionV2Request struct via the builder pattern


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


## CountUniqueFieldsCollections

> CountUniqueFieldsCollections200Response CountUniqueFieldsCollections(ctx, field).TeamId(teamId).UserId(userId).Execute()

CollectionController@count



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
	teamId := int32(1) // int32 | team id
	userId := int32(1) // int32 | user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CountUniqueFieldsCollections(context.Background(), field).TeamId(teamId).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountUniqueFieldsCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsCollections`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountUniqueFieldsCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **teamId** | **int32** | team id | 
 **userId** | **int32** | user id | 

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


## CountUniqueFieldsCollectionsV2

> CountUniqueFieldsCollections200Response CountUniqueFieldsCollectionsV2(ctx, field).Execute()

CollectionController@count



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CountUniqueFieldsCollectionsV2(context.Background(), field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountUniqueFieldsCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUniqueFieldsCollectionsV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountUniqueFieldsCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUniqueFieldsCollectionsV2Request struct via the builder pattern


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


## CountUserUniqueFieldsCollectionV2

> CountUniqueFieldsCollections200Response CountUserUniqueFieldsCollectionV2(ctx, userId, field).Execute()

UserCollectionController@count



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
	resp, r, err := apiClient.CollectionsAPI.CountUserUniqueFieldsCollectionV2(context.Background(), userId, field).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CountUserUniqueFieldsCollectionV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountUserUniqueFieldsCollectionV2`: CountUniqueFieldsCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CountUserUniqueFieldsCollectionV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**field** | **string** | name of the field to perform a count on | 

### Other Parameters

Other parameters are passed through a pointer to a apiCountUserUniqueFieldsCollectionV2Request struct via the builder pattern


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


## CreateCollections

> CreateCategories200Response CreateCollections(ctx).CreateCollectionsRequest(createCollectionsRequest).Execute()

CollectionController@store



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
	createCollectionsRequest := *openapiclient.NewCreateCollectionsRequest() // CreateCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CreateCollections(context.Background()).CreateCollectionsRequest(createCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CreateCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCollections`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CreateCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials | 

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


## CreateTeamCollections

> CreateCategories200Response CreateTeamCollections(ctx, teamId).CreateTeamCollectionsRequest(createTeamCollectionsRequest).Execute()

CollectionController@store



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
	createTeamCollectionsRequest := *openapiclient.NewCreateTeamCollectionsRequest() // CreateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CreateTeamCollections(context.Background(), teamId).CreateTeamCollectionsRequest(createTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CreateTeamCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamCollections`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CreateTeamCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials | 

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


## CreateTeamCollectionsV2

> CreateCategories200Response CreateTeamCollectionsV2(ctx, teamId).CreateTeamCollectionsRequest(createTeamCollectionsRequest).Execute()

TeamCollectionController@store



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
	createTeamCollectionsRequest := *openapiclient.NewCreateTeamCollectionsRequest() // CreateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CreateTeamCollectionsV2(context.Background(), teamId).CreateTeamCollectionsRequest(createTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CreateTeamCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamCollectionsV2`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CreateTeamCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createTeamCollectionsRequest** | [**CreateTeamCollectionsRequest**](CreateTeamCollectionsRequest.md) | Pass user credentials | 

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


## CreateUserCollections

> CreateCategories200Response CreateUserCollections(ctx).CreateCollectionsRequest(createCollectionsRequest).Execute()

UserCollectionController@store



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
	createCollectionsRequest := *openapiclient.NewCreateCollectionsRequest() // CreateCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CreateUserCollections(context.Background()).CreateCollectionsRequest(createCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CreateUserCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserCollections`: CreateCategories200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CreateUserCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionsRequest** | [**CreateCollectionsRequest**](CreateCollectionsRequest.md) | Pass user credentials | 

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


## DeleteCollectionsV2

> DeleteAliases200Response DeleteCollectionsV2(ctx, id).Execute()

Delete a collection



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.DeleteCollectionsV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.DeleteCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCollectionsV2`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.DeleteCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCollectionsV2Request struct via the builder pattern


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


## DeleteTeamCollections

> DeleteAliases200Response DeleteTeamCollections(ctx, teamId, id).Execute()

Delete a collection



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.DeleteTeamCollections(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.DeleteTeamCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamCollections`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.DeleteTeamCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamCollectionsRequest struct via the builder pattern


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


## DeleteTeamCollectionsV2

> DeleteAliases200Response DeleteTeamCollectionsV2(ctx, teamId, id).Execute()

Delete a collection



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.DeleteTeamCollectionsV2(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.DeleteTeamCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTeamCollectionsV2`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.DeleteTeamCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTeamCollectionsV2Request struct via the builder pattern


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


## DeleteUserCollectionsV2

> DeleteAliases200Response DeleteUserCollectionsV2(ctx, userId, id).Execute()

Delete a collection



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.DeleteUserCollectionsV2(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.DeleteUserCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUserCollectionsV2`: DeleteAliases200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.DeleteUserCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserCollectionsV2Request struct via the builder pattern


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


## EditCollectionsV2

> FetchCollections200Response EditCollectionsV2(ctx, id).EditCollectionsV2Request(editCollectionsV2Request).Unarchive(unarchive).Execute()

Edit a collection



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
	id := int32(1) // int32 | collection id
	editCollectionsV2Request := *openapiclient.NewEditCollectionsV2Request() // EditCollectionsV2Request | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a collection (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.EditCollectionsV2(context.Background(), id).EditCollectionsV2Request(editCollectionsV2Request).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.EditCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.EditCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **editCollectionsV2Request** | [**EditCollectionsV2Request**](EditCollectionsV2Request.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a collection | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditTeamCollections

> FetchCollections200Response EditTeamCollections(ctx, teamId, id).EditTeamCollectionsRequest(editTeamCollectionsRequest).Unarchive(unarchive).Execute()

Edit a collection



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
	id := int32(1) // int32 | collection id
	editTeamCollectionsRequest := *openapiclient.NewEditTeamCollectionsRequest() // EditTeamCollectionsRequest | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a collection (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.EditTeamCollections(context.Background(), teamId, id).EditTeamCollectionsRequest(editTeamCollectionsRequest).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.EditTeamCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditTeamCollections`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.EditTeamCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditTeamCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **editTeamCollectionsRequest** | [**EditTeamCollectionsRequest**](EditTeamCollectionsRequest.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a collection | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditTeamCollectionsV2

> FetchCollections200Response EditTeamCollectionsV2(ctx, teamId, id).EditTeamCollectionsRequest(editTeamCollectionsRequest).Execute()

Edit a collection



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
	id := int32(1) // int32 | collection id
	editTeamCollectionsRequest := *openapiclient.NewEditTeamCollectionsRequest() // EditTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.EditTeamCollectionsV2(context.Background(), teamId, id).EditTeamCollectionsRequest(editTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.EditTeamCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditTeamCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.EditTeamCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditTeamCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **editTeamCollectionsRequest** | [**EditTeamCollectionsRequest**](EditTeamCollectionsRequest.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditUserCollectionsV2

> FetchCollections200Response EditUserCollectionsV2(ctx, userId, id).EditCollectionsV2Request(editCollectionsV2Request).Execute()

Edit a collection



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
	id := int32(1) // int32 | collection id
	editCollectionsV2Request := *openapiclient.NewEditCollectionsV2Request() // EditCollectionsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.EditUserCollectionsV2(context.Background(), userId, id).EditCollectionsV2Request(editCollectionsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.EditUserCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditUserCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.EditUserCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditUserCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **editCollectionsV2Request** | [**EditCollectionsV2Request**](EditCollectionsV2Request.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllCollections

> FetchAllCollections200Response FetchAllCollections(ctx).Name(name).TeamId(teamId).UserId(userId).Title(title).Status(status).PerPage(perPage).Execute()

CollectionController@index



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
	name := "name_example" // string | Filter collections by name (optional)
	teamId := int32(56) // int32 | Filter collections by team ID (optional)
	userId := int32(56) // int32 | Filter collections by user ID (optional)
	title := "title_example" // string | Filter collections by title (optional)
	status := "status_example" // string | Filter collections by status (DRAFT, ACTIVE, ARCHIVED) (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchAllCollections(context.Background()).Name(name).TeamId(teamId).UserId(userId).Title(title).Status(status).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchAllCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCollections`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchAllCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Filter collections by name | 
 **teamId** | **int32** | Filter collections by team ID | 
 **userId** | **int32** | Filter collections by user ID | 
 **title** | **string** | Filter collections by title | 
 **status** | **string** | Filter collections by status (DRAFT, ACTIVE, ARCHIVED) | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllCollectionsV2

> FetchAllCollections200Response FetchAllCollectionsV2(ctx).Execute()

CollectionController@index



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
	resp, r, err := apiClient.CollectionsAPI.FetchAllCollectionsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchAllCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchAllCollectionsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllCollectionsV2Request struct via the builder pattern


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCollections

> FetchCollections200Response FetchCollections(ctx, id).ViewType(viewType).Execute()

CollectionController@show



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
	id := int32(1) // int32 | collection id
	viewType := "full" // string | Query flag to show full collection data or a trimmed version (defaults to full). (optional) (default to "full")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchCollections(context.Background(), id).ViewType(viewType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollections`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [default to &quot;full&quot;]

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchCollectionsV2

> FetchCollections200Response FetchCollectionsV2(ctx, id).ViewType(viewType).Execute()

CollectionController@show



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
	id := int32(1) // int32 | collection id
	viewType := "full" // string | Query flag to show full collection data or a trimmed version (defaults to full). (optional) (default to "full")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchCollectionsV2(context.Background(), id).ViewType(viewType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **viewType** | **string** | Query flag to show full collection data or a trimmed version (defaults to full). | [default to &quot;full&quot;]

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamActiveCollectionsV2

> FetchAllCollections200Response FetchTeamActiveCollectionsV2(ctx, teamId).Execute()

TeamCollectionController@indexActive



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchTeamActiveCollectionsV2(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchTeamActiveCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamActiveCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchTeamActiveCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamActiveCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamArchivedCollectionsV2

> FetchAllCollections200Response FetchTeamArchivedCollectionsV2(ctx, teamId).Execute()

TeamCollectionController@indexArchived



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchTeamArchivedCollectionsV2(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchTeamArchivedCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamArchivedCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchTeamArchivedCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamArchivedCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamCollectionV2

> FetchCollections200Response FetchTeamCollectionV2(ctx, teamId, id).Execute()

TeamCollectionController@show



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchTeamCollectionV2(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchTeamCollectionV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamCollectionV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchTeamCollectionV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamCollectionV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchTeamDraftCollectionsV2

> FetchAllCollections200Response FetchTeamDraftCollectionsV2(ctx, teamId).Execute()

TeamCollectionController@indexDraft



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchTeamDraftCollectionsV2(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchTeamDraftCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchTeamDraftCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchTeamDraftCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchTeamDraftCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUserArchivedCollectionsV2

> FetchAllCollections200Response FetchUserArchivedCollectionsV2(ctx, userId).Execute()

UserCollectionController@indexArchived



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchUserArchivedCollectionsV2(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchUserArchivedCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserArchivedCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchUserArchivedCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserArchivedCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUserCollectionV2

> FetchCollections200Response FetchUserCollectionV2(ctx, userId, id).Execute()

CollectionController@show



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
	id := int32(1) // int32 | collection id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchUserCollectionV2(context.Background(), userId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchUserCollectionV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserCollectionV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchUserCollectionV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserCollectionV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUserCollectionsV2

> FetchAllCollections200Response FetchUserCollectionsV2(ctx, userId).Execute()

UserCollectionController@indexActive



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchUserCollectionsV2(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchUserCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchUserCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchUserDraftCollectionsV2

> FetchAllCollections200Response FetchUserDraftCollectionsV2(ctx, userId).Execute()

UserCollectionController@indexDraft



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.FetchUserDraftCollectionsV2(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.FetchUserDraftCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchUserDraftCollectionsV2`: FetchAllCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.FetchUserDraftCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchUserDraftCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllCollections200Response**](FetchAllCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCollectionsV2

> FetchCollections200Response UpdateCollectionsV2(ctx, id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()

Update a collection



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
	id := int32(1) // int32 | collection id
	updateCollectionsV2Request := *openapiclient.NewUpdateCollectionsV2Request() // UpdateCollectionsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.UpdateCollectionsV2(context.Background(), id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.UpdateCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.UpdateCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCollectionsV2Request** | [**UpdateCollectionsV2Request**](UpdateCollectionsV2Request.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTeamCollections

> FetchCollections200Response UpdateTeamCollections(ctx, teamId, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()

Update a collection



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
	id := int32(1) // int32 | collection id
	updateTeamCollectionsRequest := *openapiclient.NewUpdateTeamCollectionsRequest() // UpdateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.UpdateTeamCollections(context.Background(), teamId, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.UpdateTeamCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamCollections`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.UpdateTeamCollections`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTeamCollectionsV2

> FetchCollections200Response UpdateTeamCollectionsV2(ctx, teamId, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()

Update a collection



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
	id := int32(1) // int32 | collection id
	updateTeamCollectionsRequest := *openapiclient.NewUpdateTeamCollectionsRequest() // UpdateTeamCollectionsRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.UpdateTeamCollectionsV2(context.Background(), teamId, id).UpdateTeamCollectionsRequest(updateTeamCollectionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.UpdateTeamCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTeamCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.UpdateTeamCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTeamCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateTeamCollectionsRequest** | [**UpdateTeamCollectionsRequest**](UpdateTeamCollectionsRequest.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserCollectionsV2

> FetchCollections200Response UpdateUserCollectionsV2(ctx, userId, id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()

Update a collection



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
	id := int32(1) // int32 | collection id
	updateCollectionsV2Request := *openapiclient.NewUpdateCollectionsV2Request() // UpdateCollectionsV2Request | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.UpdateUserCollectionsV2(context.Background(), userId, id).UpdateCollectionsV2Request(updateCollectionsV2Request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.UpdateUserCollectionsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserCollectionsV2`: FetchCollections200Response
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.UpdateUserCollectionsV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **int32** | user id | 
**id** | **int32** | collection id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserCollectionsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateCollectionsV2Request** | [**UpdateCollectionsV2Request**](UpdateCollectionsV2Request.md) | Pass user credentials | 

### Return type

[**FetchCollections200Response**](FetchCollections200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

