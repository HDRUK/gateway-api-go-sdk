# \TeamDashboardAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FetchCollectionsViewsV3**](TeamDashboardAPI.md#FetchCollectionsViewsV3) | **Get** /api/v3/teams/{id}/dashboard/collections/views | TeamDashboardController@collectionViews
[**FetchDarApplicationsApplicationTimelineV3**](TeamDashboardAPI.md#FetchDarApplicationsApplicationTimelineV3) | **Get** /api/v3/teams/{id}/dar/dashboard/timeline | DataAccessDashboardController@getApplicationTimeline
[**FetchDarApplicationsAverageTimeToApprovalV3**](TeamDashboardAPI.md#FetchDarApplicationsAverageTimeToApprovalV3) | **Get** /api/v3/teams/{id}/dar/dashboard/average-time | DataAccessDashboardController@getAverageTimeToApproval
[**FetchDarApplicationsCurrentStatusV3**](TeamDashboardAPI.md#FetchDarApplicationsCurrentStatusV3) | **Get** /api/v3/teams/{id}/dar/dashboard/status | DataAccessDashboardController@getApplicationStatus
[**FetchDarApplicationsDashboardExportCsvV3**](TeamDashboardAPI.md#FetchDarApplicationsDashboardExportCsvV3) | **Get** /api/v3/teams/{id}/dar/dashboard/export/csv | DataAccessDashboardController@exportDashboardCsv
[**FetchDarApplicationsDashboardRequiredActionsExportCsvV3**](TeamDashboardAPI.md#FetchDarApplicationsDashboardRequiredActionsExportCsvV3) | **Get** /api/v3/teams/{id}/dar/dashboard/required-actions/export/csv | DataAccessDashboardController@exportRequiredActionsCsv
[**FetchDarApplicationsDashboardTimelineExportCsvV3**](TeamDashboardAPI.md#FetchDarApplicationsDashboardTimelineExportCsvV3) | **Get** /api/v3/teams/{id}/dar/dashboard/timeline/export/csv | DataAccessDashboardController@exportDashboardTimelineCsv
[**FetchDarApplicationsRequiredActionsV3**](TeamDashboardAPI.md#FetchDarApplicationsRequiredActionsV3) | **Get** /api/v3/teams/{id}/dar/dashboard/required-actions | DataAccessDashboardController@getRequiredActions
[**FetchDarMyApplicationsV3**](TeamDashboardAPI.md#FetchDarMyApplicationsV3) | **Get** /api/v3/teams/{id}/dar/dashboard/count | DataAccessDashboardController@getMyApplications
[**FetchDashboardDownloadCsvV3**](TeamDashboardAPI.md#FetchDashboardDownloadCsvV3) | **Get** /api/v3/teams/{id}/dashboard/download/csv | TeamDashboardController@downloadCsv
[**FetchDataCustodiansViewsV3**](TeamDashboardAPI.md#FetchDataCustodiansViewsV3) | **Get** /api/v3/teams/{id}/dashboard/datacustodians/views | TeamDashboardController@datacustodianViews
[**FetchDatasetViews360V3**](TeamDashboardAPI.md#FetchDatasetViews360V3) | **Get** /api/v3/teams/{id}/dashboard/datasets/views/360 | TeamDashboardController@datasetViews360
[**FetchDatasetViewsTopV3**](TeamDashboardAPI.md#FetchDatasetViewsTopV3) | **Get** /api/v3/teams/{id}/dashboard/datasets/views/top | TeamDashboardController@datasetViewsTop
[**FetchEntitiesCountV3**](TeamDashboardAPI.md#FetchEntitiesCountV3) | **Get** /api/v3/teams/{id}/dashboard/{entity}/count | TeamDashboardController@entityCount



## FetchCollectionsViewsV3

> FetchCollectionsViewsV3200Response FetchCollectionsViewsV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@collectionViews



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchCollectionsViewsV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchCollectionsViewsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchCollectionsViewsV3`: FetchCollectionsViewsV3200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchCollectionsViewsV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchCollectionsViewsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**FetchCollectionsViewsV3200Response**](FetchCollectionsViewsV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsApplicationTimelineV3

> CreateWidget201Response FetchDarApplicationsApplicationTimelineV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@getApplicationTimeline



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsApplicationTimelineV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsApplicationTimelineV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsApplicationTimelineV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsApplicationTimelineV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsApplicationTimelineV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsAverageTimeToApprovalV3

> CreateWidget201Response FetchDarApplicationsAverageTimeToApprovalV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@getAverageTimeToApproval



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsAverageTimeToApprovalV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsAverageTimeToApprovalV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsAverageTimeToApprovalV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsAverageTimeToApprovalV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsAverageTimeToApprovalV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsCurrentStatusV3

> CreateWidget201Response FetchDarApplicationsCurrentStatusV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@getApplicationStatus



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsCurrentStatusV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsCurrentStatusV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsCurrentStatusV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsCurrentStatusV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsCurrentStatusV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsDashboardExportCsvV3

> CreateWidget201Response FetchDarApplicationsDashboardExportCsvV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@exportDashboardCsv



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsDashboardExportCsvV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsDashboardExportCsvV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsDashboardExportCsvV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsDashboardExportCsvV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsDashboardExportCsvV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsDashboardRequiredActionsExportCsvV3

> CreateWidget201Response FetchDarApplicationsDashboardRequiredActionsExportCsvV3(ctx, id).Execute()

DataAccessDashboardController@exportRequiredActionsCsv



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
	id := int32(1) // int32 | Team ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsDashboardRequiredActionsExportCsvV3(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsDashboardRequiredActionsExportCsvV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsDashboardRequiredActionsExportCsvV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsDashboardRequiredActionsExportCsvV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsDashboardRequiredActionsExportCsvV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsDashboardTimelineExportCsvV3

> CreateWidget201Response FetchDarApplicationsDashboardTimelineExportCsvV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@exportDashboardTimelineCsv



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsDashboardTimelineExportCsvV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsDashboardTimelineExportCsvV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsDashboardTimelineExportCsvV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsDashboardTimelineExportCsvV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsDashboardTimelineExportCsvV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarApplicationsRequiredActionsV3

> CreateWidget201Response FetchDarApplicationsRequiredActionsV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@getRequiredActions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarApplicationsRequiredActionsV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarApplicationsRequiredActionsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarApplicationsRequiredActionsV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarApplicationsRequiredActionsV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarApplicationsRequiredActionsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDarMyApplicationsV3

> CreateWidget201Response FetchDarMyApplicationsV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

DataAccessDashboardController@getMyApplications



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDarMyApplicationsV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDarMyApplicationsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDarMyApplicationsV3`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDarMyApplicationsV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDarMyApplicationsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDashboardDownloadCsvV3

> *os.File FetchDashboardDownloadCsvV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@downloadCsv



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDashboardDownloadCsvV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDashboardDownloadCsvV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDashboardDownloadCsvV3`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDashboardDownloadCsvV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDashboardDownloadCsvV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDataCustodiansViewsV3

> FetchCollectionsViewsV3200Response FetchDataCustodiansViewsV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@datacustodianViews



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDataCustodiansViewsV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDataCustodiansViewsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDataCustodiansViewsV3`: FetchCollectionsViewsV3200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDataCustodiansViewsV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDataCustodiansViewsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**FetchCollectionsViewsV3200Response**](FetchCollectionsViewsV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDatasetViews360V3

> FetchDatasetViews360V3200Response FetchDatasetViews360V3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@datasetViews360



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDatasetViews360V3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDatasetViews360V3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasetViews360V3`: FetchDatasetViews360V3200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDatasetViews360V3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetViews360V3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**FetchDatasetViews360V3200Response**](FetchDatasetViews360V3200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchDatasetViewsTopV3

> FetchDatasetViewsTopV3200Response FetchDatasetViewsTopV3(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@datasetViewsTop



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchDatasetViewsTopV3(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchDatasetViewsTopV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchDatasetViewsTopV3`: FetchDatasetViewsTopV3200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchDatasetViewsTopV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchDatasetViewsTopV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**FetchDatasetViewsTopV3200Response**](FetchDatasetViewsTopV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchEntitiesCountV3

> FetchEntitiesCountV3200Response FetchEntitiesCountV3(ctx, id, entity).StartDate(startDate).EndDate(endDate).Execute()

TeamDashboardController@entityCount



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/HDRUK/gateway-api-go-sdk"
)

func main() {
	id := int32(1) // int32 | Team ID
	entity := "entity_example" // string | Entity type to count
	startDate := time.Now() // string | Start date for the reporting interval (Y-m-d). Defaults to one year ago. (optional)
	endDate := time.Now() // string | End date for the reporting interval (Y-m-d). Defaults to today. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamDashboardAPI.FetchEntitiesCountV3(context.Background(), id, entity).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamDashboardAPI.FetchEntitiesCountV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchEntitiesCountV3`: FetchEntitiesCountV3200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamDashboardAPI.FetchEntitiesCountV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Team ID | 
**entity** | **string** | Entity type to count | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchEntitiesCountV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **startDate** | **string** | Start date for the reporting interval (Y-m-d). Defaults to one year ago. | 
 **endDate** | **string** | End date for the reporting interval (Y-m-d). Defaults to today. | 

### Return type

[**FetchEntitiesCountV3200Response**](FetchEntitiesCountV3200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

