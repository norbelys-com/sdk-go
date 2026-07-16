# \AnalyticsAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AnalyticsQuery**](AnalyticsAPI.md#AnalyticsQuery) | **Post** /analytics/query | Run an analytics query



## AnalyticsQuery

> AnalyticsQueryResult AnalyticsQuery(ctx).AnalyticsQuery(analyticsQuery).IdempotencyKey(idempotencyKey).Execute()

Run an analytics query



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/norbelys-com/sdk-go"
)

func main() {
	analyticsQuery := *openapiclient.NewAnalyticsQuery(openapiclient.AnalyticsQueryName("activity_feed")) // AnalyticsQuery | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.AnalyticsQuery(context.Background()).AnalyticsQuery(analyticsQuery).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.AnalyticsQuery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AnalyticsQuery`: AnalyticsQueryResult
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.AnalyticsQuery`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAnalyticsQueryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **analyticsQuery** | [**AnalyticsQuery**](AnalyticsQuery.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**AnalyticsQueryResult**](AnalyticsQueryResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

