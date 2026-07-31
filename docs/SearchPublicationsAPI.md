# \SearchPublicationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchPublications**](SearchPublicationsAPI.md#SearchPublications) | **Post** /api/v1/search/publications | Search@publications
[**SearchPublicationsByDoi**](SearchPublicationsAPI.md#SearchPublicationsByDoi) | **Post** /api/v1/search/doi | Search@publications



## SearchPublications

> SearchPublications200Response SearchPublications(ctx).SearchPublicationsRequest(searchPublicationsRequest).Sort(sort).Direction(direction).Source(source).Execute()

Search@publications



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
	searchPublicationsRequest := *openapiclient.NewSearchPublicationsRequest() // SearchPublicationsRequest | Submit search query
	sort := "created" // string | Field to sort by (default: 'score') (optional)
	direction := "desc" // string | Sort direction ('asc' or 'desc', default: 'desc') (optional)
	source := "GAT" // string | Which source to search ('GAT' or 'FED', default: 'GAT') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchPublicationsAPI.SearchPublications(context.Background()).SearchPublicationsRequest(searchPublicationsRequest).Sort(sort).Direction(direction).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchPublicationsAPI.SearchPublications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPublications`: SearchPublications200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchPublicationsAPI.SearchPublications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPublicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchPublicationsRequest** | [**SearchPublicationsRequest**](SearchPublicationsRequest.md) | Submit search query | 
 **sort** | **string** | Field to sort by (default: &#39;score&#39;) | 
 **direction** | **string** | Sort direction (&#39;asc&#39; or &#39;desc&#39;, default: &#39;desc&#39;) | 
 **source** | **string** | Which source to search (&#39;GAT&#39; or &#39;FED&#39;, default: &#39;GAT&#39;) | 

### Return type

[**SearchPublications200Response**](SearchPublications200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPublicationsByDoi

> SearchPublicationsByDoi200Response SearchPublicationsByDoi(ctx).SearchPublicationsByDoiRequest(searchPublicationsByDoiRequest).Execute()

Search@publications



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
	searchPublicationsByDoiRequest := *openapiclient.NewSearchPublicationsByDoiRequest() // SearchPublicationsByDoiRequest | Submit search query

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchPublicationsAPI.SearchPublicationsByDoi(context.Background()).SearchPublicationsByDoiRequest(searchPublicationsByDoiRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchPublicationsAPI.SearchPublicationsByDoi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPublicationsByDoi`: SearchPublicationsByDoi200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchPublicationsAPI.SearchPublicationsByDoi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPublicationsByDoiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchPublicationsByDoiRequest** | [**SearchPublicationsByDoiRequest**](SearchPublicationsByDoiRequest.md) | Submit search query | 

### Return type

[**SearchPublicationsByDoi200Response**](SearchPublicationsByDoi200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

