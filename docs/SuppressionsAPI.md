# \SuppressionsAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SuppressionsArchive**](SuppressionsAPI.md#SuppressionsArchive) | **Delete** /suppressions/{id} | Delete a suppression
[**SuppressionsBulk**](SuppressionsAPI.md#SuppressionsBulk) | **Post** /suppressions/bulk | Bulk-suppress addresses
[**SuppressionsCreate**](SuppressionsAPI.md#SuppressionsCreate) | **Post** /suppressions | Suppress an address or domain
[**SuppressionsFind**](SuppressionsAPI.md#SuppressionsFind) | **Get** /suppressions/{id} | Get a suppression
[**SuppressionsList**](SuppressionsAPI.md#SuppressionsList) | **Get** /suppressions | List suppressions



## SuppressionsArchive

> Suppression SuppressionsArchive(ctx, id).Execute()

Delete a suppression

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
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppressionsAPI.SuppressionsArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppressionsAPI.SuppressionsArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppressionsArchive`: Suppression
	fmt.Fprintf(os.Stdout, "Response from `SuppressionsAPI.SuppressionsArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppressionsArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Suppression**](Suppression.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppressionsBulk

> SuppressionBulkResult SuppressionsBulk(ctx).SuppressionBulkParams(suppressionBulkParams).IdempotencyKey(idempotencyKey).Execute()

Bulk-suppress addresses



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
	suppressionBulkParams := *openapiclient.NewSuppressionBulkParams([]string{"Emails_example"}) // SuppressionBulkParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppressionsAPI.SuppressionsBulk(context.Background()).SuppressionBulkParams(suppressionBulkParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppressionsAPI.SuppressionsBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppressionsBulk`: SuppressionBulkResult
	fmt.Fprintf(os.Stdout, "Response from `SuppressionsAPI.SuppressionsBulk`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppressionsBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **suppressionBulkParams** | [**SuppressionBulkParams**](SuppressionBulkParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**SuppressionBulkResult**](SuppressionBulkResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppressionsCreate

> Suppression SuppressionsCreate(ctx).SuppressionCreateParams(suppressionCreateParams).IdempotencyKey(idempotencyKey).Execute()

Suppress an address or domain



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
	suppressionCreateParams := *openapiclient.NewSuppressionCreateParams("EmailOrDomain_example") // SuppressionCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppressionsAPI.SuppressionsCreate(context.Background()).SuppressionCreateParams(suppressionCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppressionsAPI.SuppressionsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppressionsCreate`: Suppression
	fmt.Fprintf(os.Stdout, "Response from `SuppressionsAPI.SuppressionsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppressionsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **suppressionCreateParams** | [**SuppressionCreateParams**](SuppressionCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Suppression**](Suppression.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppressionsFind

> Suppression SuppressionsFind(ctx, id).Execute()

Get a suppression



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
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppressionsAPI.SuppressionsFind(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppressionsAPI.SuppressionsFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppressionsFind`: Suppression
	fmt.Fprintf(os.Stdout, "Response from `SuppressionsAPI.SuppressionsFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuppressionsFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Suppression**](Suppression.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuppressionsList

> SuppressionList SuppressionsList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Execute()

List suppressions



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
	cursor := "cursor_example" // string |  (optional)
	includeArchived := true // bool |  (optional)
	limit := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuppressionsAPI.SuppressionsList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuppressionsAPI.SuppressionsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuppressionsList`: SuppressionList
	fmt.Fprintf(os.Stdout, "Response from `SuppressionsAPI.SuppressionsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuppressionsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 

### Return type

[**SuppressionList**](SuppressionList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

