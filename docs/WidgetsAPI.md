# \WidgetsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateWidget**](WidgetsAPI.md#CreateWidget) | **Post** /api/v1/teams/{teamId}/widgets | Create a new widget
[**DeleteWidget**](WidgetsAPI.md#DeleteWidget) | **Delete** /api/v1/teams/{teamId}/widgets/{id} | Delete a widget
[**FetchAllWidgets**](WidgetsAPI.md#FetchAllWidgets) | **Get** /api/v1/teams/{teamId}/widgets | WidgetController@index
[**FetchWidget**](WidgetsAPI.md#FetchWidget) | **Get** /api/v1/teams/{teamId}/widgets/{id} | WidgetController@retrieve
[**FetchWidgetDataSources**](WidgetsAPI.md#FetchWidgetDataSources) | **Get** /api/v1/teams/{teamId}/widgets/data | WidgetController@getWidgetData
[**RetrieveWidgetData**](WidgetsAPI.md#RetrieveWidgetData) | **Get** /api/v1/teams/{teamId}/widgets/{id}/data | Retrieve data related to a widget
[**TrackWidgetEvent**](WidgetsAPI.md#TrackWidgetEvent) | **Post** /api/v1/teams/{teamId}/widgets/{id}/track | Record a widget analytics event
[**UpdateWidget**](WidgetsAPI.md#UpdateWidget) | **Patch** /api/v1/teams/{teamId}/widgets/{id} | Update an existing widget
[**WidgetAnalytics**](WidgetsAPI.md#WidgetAnalytics) | **Get** /api/v1/teams/{teamId}/widgets/analytics | Get widget analytics for a team



## CreateWidget

> CreateWidget201Response CreateWidget(ctx, teamId).CreateWidgetRequest(createWidgetRequest).Execute()

Create a new widget



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
	teamId := int32(5) // int32 | Team ID the widget belongs to
	createWidgetRequest := *openapiclient.NewCreateWidgetRequest("A really nice name") // CreateWidgetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.CreateWidget(context.Background(), teamId).CreateWidgetRequest(createWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.CreateWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWidget`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.CreateWidget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID the widget belongs to | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateWidgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createWidgetRequest** | [**CreateWidgetRequest**](CreateWidgetRequest.md) |  | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWidget

> DeleteApplications200Response DeleteWidget(ctx, teamId, id).Execute()

Delete a widget



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
	teamId := int32(5) // int32 | Team ID
	id := int32(1) // int32 | Widget ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.DeleteWidget(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.DeleteWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWidget`: DeleteApplications200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.DeleteWidget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 
**id** | **int32** | Widget ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWidgetRequest struct via the builder pattern


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


## FetchAllWidgets

> FetchAllWidgets200Response FetchAllWidgets(ctx, teamId).Execute()

WidgetController@index



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
	teamId := int32(56) // int32 | Team ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.FetchAllWidgets(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.FetchAllWidgets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchAllWidgets`: FetchAllWidgets200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.FetchAllWidgets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchAllWidgetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FetchAllWidgets200Response**](FetchAllWidgets200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchWidget

> FetchWidget200Response FetchWidget(ctx, teamId, id).Execute()

WidgetController@retrieve



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
	teamId := int32(56) // int32 | Team ID
	id := int32(56) // int32 | Widget ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.FetchWidget(context.Background(), teamId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.FetchWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchWidget`: FetchWidget200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.FetchWidget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 
**id** | **int32** | Widget ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchWidgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**FetchWidget200Response**](FetchWidget200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FetchWidgetDataSources

> FetchWidgetDataSources200Response FetchWidgetDataSources(ctx, teamId).TeamIds(teamIds).Execute()

WidgetController@getWidgetData



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
	teamId := int32(56) // int32 | Team ID
	teamIds := "1,2,3" // string | Comma-separated list of team IDs to filter data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.FetchWidgetDataSources(context.Background(), teamId).TeamIds(teamIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.FetchWidgetDataSources``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FetchWidgetDataSources`: FetchWidgetDataSources200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.FetchWidgetDataSources`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFetchWidgetDataSourcesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **teamIds** | **string** | Comma-separated list of team IDs to filter data | 

### Return type

[**FetchWidgetDataSources200Response**](FetchWidgetDataSources200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrieveWidgetData

> RetrieveWidgetData200Response RetrieveWidgetData(ctx, teamId, id).DomainOrigin(domainOrigin).Execute()

Retrieve data related to a widget



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
	teamId := int32(56) // int32 | Team ID
	id := int32(56) // int32 | Widget ID
	domainOrigin := "https://example.com" // string | Optional domain URL to check against the widget's permitted_domains list

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.RetrieveWidgetData(context.Background(), teamId, id).DomainOrigin(domainOrigin).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.RetrieveWidgetData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveWidgetData`: RetrieveWidgetData200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.RetrieveWidgetData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 
**id** | **int32** | Widget ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveWidgetDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **domainOrigin** | **string** | Optional domain URL to check against the widget&#39;s permitted_domains list | 

### Return type

[**RetrieveWidgetData200Response**](RetrieveWidgetData200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackWidgetEvent

> TrackWidgetEvent(ctx, teamId, id).TrackWidgetEventRequest(trackWidgetEventRequest).Execute()

Record a widget analytics event



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
	teamId := int32(56) // int32 | 
	id := int32(56) // int32 | 
	trackWidgetEventRequest := *openapiclient.NewTrackWidgetEventRequest("EventType_example") // TrackWidgetEventRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WidgetsAPI.TrackWidgetEvent(context.Background(), teamId, id).TrackWidgetEventRequest(trackWidgetEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.TrackWidgetEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** |  | 
**id** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrackWidgetEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **trackWidgetEventRequest** | [**TrackWidgetEventRequest**](TrackWidgetEventRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWidget

> UpdateWidget200Response UpdateWidget(ctx, teamId, id).UpdateWidgetRequest(updateWidgetRequest).Execute()

Update an existing widget



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
	teamId := int32(1) // int32 | Team ID
	id := int32(12) // int32 | Widget ID
	updateWidgetRequest := *openapiclient.NewUpdateWidgetRequest() // UpdateWidgetRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.UpdateWidget(context.Background(), teamId, id).UpdateWidgetRequest(updateWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.UpdateWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWidget`: UpdateWidget200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.UpdateWidget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** | Team ID | 
**id** | **int32** | Widget ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateWidgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateWidgetRequest** | [**UpdateWidgetRequest**](UpdateWidgetRequest.md) |  | 

### Return type

[**UpdateWidget200Response**](UpdateWidget200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WidgetAnalytics

> WidgetAnalytics200Response WidgetAnalytics(ctx, teamId).From(from).To(to).GroupBy(groupBy).Execute()

Get widget analytics for a team



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
	teamId := int32(56) // int32 | 
	from := "2026-01-01" // string | Start date (Y-m-d) (optional)
	to := "2026-06-30" // string | End date (Y-m-d) (optional)
	groupBy := "groupBy_example" // string | Time granularity (optional) (default to "day")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.WidgetAnalytics(context.Background(), teamId).From(from).To(to).GroupBy(groupBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.WidgetAnalytics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WidgetAnalytics`: WidgetAnalytics200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.WidgetAnalytics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWidgetAnalyticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **from** | **string** | Start date (Y-m-d) | 
 **to** | **string** | End date (Y-m-d) | 
 **groupBy** | **string** | Time granularity | [default to &quot;day&quot;]

### Return type

[**WidgetAnalytics200Response**](WidgetAnalytics200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

