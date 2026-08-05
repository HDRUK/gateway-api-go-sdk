# \DataUseRegistersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDur**](DataUseRegistersAPI.md#CreateDur) | **Post** /api/v1/dur | DurController@store
[**CreateDurByTeamV2**](DataUseRegistersAPI.md#CreateDurByTeamV2) | **Post** /api/v2/teams/{teamId}/dur | TeamDurController@store
[**DeleteDur**](DataUseRegistersAPI.md#DeleteDur) | **Delete** /api/v1/dur/{id} | Delete a dur
[**DeleteDursV2ByTeamId**](DataUseRegistersAPI.md#DeleteDursV2ByTeamId) | **Delete** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@destroy
[**EditDur**](DataUseRegistersAPI.md#EditDur) | **Patch** /api/v1/dur/{id} | Edit a dur
[**EditDursV2ByTeamId**](DataUseRegistersAPI.md#EditDursV2ByTeamId) | **Patch** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@edit
[**ExportDurTemplate**](DataUseRegistersAPI.md#ExportDurTemplate) | **Get** /api/v1/dur/template | DurController@exportTemplate
[**ExportDurTemplateV2**](DataUseRegistersAPI.md#ExportDurTemplateV2) | **Get** /api/v2/dur/template | DurController@exportTemplate
[**ExportDurV2**](DataUseRegistersAPI.md#ExportDurV2) | **Get** /api/v2/dur/export | DurController@export
[**FetchAllDur**](DataUseRegistersAPI.md#FetchAllDur) | **Get** /api/v1/dur | DurController@index
[**FetchAllDurV2**](DataUseRegistersAPI.md#FetchAllDurV2) | **Get** /api/v2/dur | DurController@indexActive
[**FetchDurById**](DataUseRegistersAPI.md#FetchDurById) | **Get** /api/v1/dur/{id} | DurController@show
[**FetchDurByIdV2**](DataUseRegistersAPI.md#FetchDurByIdV2) | **Get** /api/v2/dur/{id} | DurController@showActive
[**UpdateDur**](DataUseRegistersAPI.md#UpdateDur) | **Put** /api/v1/dur/{id} | Update a dur by id
[**UpdateDurV2ByTeamId**](DataUseRegistersAPI.md#UpdateDurV2ByTeamId) | **Put** /api/v2/teams/{teamId}/dur/{id} | TeamDurController@update
[**UploadDur**](DataUseRegistersAPI.md#UploadDur) | **Post** /api/v1/dur/upload | DurController@upload



## CreateDur

> CreateDarIntegration201Response CreateDur(ctx).CreateDurRequest(createDurRequest).Execute()

DurController@store



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
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.CreateDur(context.Background()).CreateDurRequest(createDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.CreateDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDur`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.CreateDur`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 

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


## CreateDurByTeamV2

> CreateDarIntegration201Response CreateDurByTeamV2(ctx, teamId).CreateDurRequest(createDurRequest).Execute()

TeamDurController@store



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
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.CreateDurByTeamV2(context.Background(), teamId).CreateDurRequest(createDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.CreateDurByTeamV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDurByTeamV2`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.CreateDurByTeamV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDurByTeamV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 

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


## DeleteDur

> DeleteApplications200Response DeleteDur(ctx, id).Execute()

Delete a dur



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
	id := int32(1) // int32 | dur id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.DeleteDur(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.DeleteDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDur`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.DeleteDur`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDurRequest struct via the builder pattern


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


## DeleteDursV2ByTeamId

> DeleteApplications200Response DeleteDursV2ByTeamId(ctx, teamId, id).Execute()

TeamDurController@destroy



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
	id := int32(1) // int32 | dur id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.DeleteDursV2ByTeamId(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.DeleteDursV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDursV2ByTeamId`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.DeleteDursV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDursV2ByTeamIdRequest struct via the builder pattern


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


## EditDur

> UpdateDur200Response EditDur(ctx, id).CreateDurRequest(createDurRequest).Unarchive(unarchive).Execute()

Edit a dur



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
	id := int32(1) // int32 | dur id
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials
	unarchive := "unarchive_example" // string | Unarchive a dur (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.EditDur(context.Background(), id).CreateDurRequest(createDurRequest).Unarchive(unarchive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.EditDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDur`: UpdateDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.EditDur`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 
 **unarchive** | **string** | Unarchive a dur | 

### Return type

[**UpdateDur200Response**](UpdateDur200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditDursV2ByTeamId

> UpdateDur200Response EditDursV2ByTeamId(ctx, teamId, id).CreateDurRequest(createDurRequest).Execute()

TeamDurController@edit



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
	id := int32(1) // int32 | dur id
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.EditDursV2ByTeamId(context.Background(), teamId, id).CreateDurRequest(createDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.EditDursV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditDursV2ByTeamId`: UpdateDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.EditDursV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditDursV2ByTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 

### Return type

[**UpdateDur200Response**](UpdateDur200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportDurTemplate

> interface{} ExportDurTemplate(ctx).Execute()

DurController@exportTemplate



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
	resp, r, err := apiClient.DataUseRegistersAPI.ExportDurTemplate(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.ExportDurTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDurTemplate`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.ExportDurTemplate`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiExportDurTemplateRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportDurTemplateV2

> interface{} ExportDurTemplateV2(ctx).Execute()

DurController@exportTemplate



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
	resp, r, err := apiClient.DataUseRegistersAPI.ExportDurTemplateV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.ExportDurTemplateV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDurTemplateV2`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.ExportDurTemplateV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiExportDurTemplateV2Request struct via the builder pattern


### Return type

**interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportDurV2

> string ExportDurV2(ctx).Id(id).Execute()

DurController@export



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
	id := int32(1) // int32 | dur id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.ExportDurV2(context.Background()).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.ExportDurV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportDurV2`: string
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.ExportDurV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExportDurV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int32** | dur id | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDur

> FetchAllDur200Response FetchAllDur(ctx).Sort(sort).ProjectTitle(projectTitle).PerPage(perPage).Execute()

DurController@index



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
	sort := TODO // ProjectTitleAscupdatedAtAsc | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc (optional)
	projectTitle := "projectTitle_example" // string | Filter tools by project title (optional)
	perPage := int32(1) // int32 | per page (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.FetchAllDur(context.Background()).Sort(sort).ProjectTitle(projectTitle).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.FetchAllDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDur`: FetchAllDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.FetchAllDur`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | 
 **projectTitle** | **string** | Filter tools by project title | 
 **perPage** | **int32** | per page | 

### Return type

[**FetchAllDur200Response**](FetchAllDur200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchAllDurV2

> FetchAllDurV2200Response FetchAllDurV2(ctx).Sort(sort).ProjectTitle(projectTitle).PerPage(perPage).WithRelated(withRelated).Execute()

DurController@indexActive



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
	sort := TODO // ProjectTitleAscupdatedAtAsc | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc (optional)
	projectTitle := "projectTitle_example" // string | Filter tools by project title (optional)
	perPage := int32(1) // int32 | per page (optional)
	withRelated := true // bool | Show related entities (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.FetchAllDurV2(context.Background()).Sort(sort).ProjectTitle(projectTitle).PerPage(perPage).WithRelated(withRelated).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.FetchAllDurV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllDurV2`: FetchAllDurV2200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.FetchAllDurV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllDurV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sort** | [**ProjectTitleAscupdatedAtAsc**](ProjectTitleAscupdatedAtAsc.md) | Sort fields in the format field:direction, e.g., project_title:asc,updated_at:asc | 
 **projectTitle** | **string** | Filter tools by project title | 
 **perPage** | **int32** | per page | 
 **withRelated** | **bool** | Show related entities | 

### Return type

[**FetchAllDurV2200Response**](FetchAllDurV2200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDurById

> FetchDurById200Response FetchDurById(ctx, id).Execute()

DurController@show



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
	id := int32(1) // int32 | data use register id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.FetchDurById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.FetchDurById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDurById`: FetchDurById200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.FetchDurById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | data use register id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDurByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchDurById200Response**](FetchDurById200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDurByIdV2

> UpdateDur200Response FetchDurByIdV2(ctx, id).Execute()

DurController@showActive



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
	id := int32(1) // int32 | data use register id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.FetchDurByIdV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.FetchDurByIdV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDurByIdV2`: UpdateDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.FetchDurByIdV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | data use register id | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDurByIdV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UpdateDur200Response**](UpdateDur200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDur

> UpdateDur200Response UpdateDur(ctx, id).CreateDurRequest(createDurRequest).Execute()

Update a dur by id



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
	id := int32(1) // int32 | dur id
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.UpdateDur(context.Background(), id).CreateDurRequest(createDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.UpdateDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDur`: UpdateDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.UpdateDur`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 

### Return type

[**UpdateDur200Response**](UpdateDur200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDurV2ByTeamId

> UpdateDur200Response UpdateDurV2ByTeamId(ctx, teamId, id).CreateDurRequest(createDurRequest).Execute()

TeamDurController@update



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
	id := int32(1) // int32 | dur id
	createDurRequest := *openapiclient.NewCreateDurRequest() // CreateDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.UpdateDurV2ByTeamId(context.Background(), teamId, id).CreateDurRequest(createDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.UpdateDurV2ByTeamId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDurV2ByTeamId`: UpdateDur200Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.UpdateDurV2ByTeamId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | team id | 
**id** | **int32** | dur id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDurV2ByTeamIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDurRequest** | [**CreateDurRequest**](CreateDurRequest.md) | Pass user credentials | 

### Return type

[**UpdateDur200Response**](UpdateDur200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadDur

> CreateDarIntegration201Response UploadDur(ctx).UploadDurRequest(uploadDurRequest).Execute()

DurController@upload



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
	uploadDurRequest := *openapiclient.NewUploadDurRequest() // UploadDurRequest | Pass user credentials

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DataUseRegistersAPI.UploadDur(context.Background()).UploadDurRequest(uploadDurRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DataUseRegistersAPI.UploadDur``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadDur`: CreateDarIntegration201Response
	fmt.Fprintf(os.Stdout, "Response from `DataUseRegistersAPI.UploadDur`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadDurRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uploadDurRequest** | [**UploadDurRequest**](UploadDurRequest.md) | Pass user credentials | 

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

