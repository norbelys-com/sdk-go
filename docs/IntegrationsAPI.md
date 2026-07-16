# \IntegrationsAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IntegrationsConnect**](IntegrationsAPI.md#IntegrationsConnect) | **Post** /integrations/connect | Connect an integration
[**IntegrationsFind**](IntegrationsAPI.md#IntegrationsFind) | **Get** /integrations/{id} | Get an integration
[**IntegrationsList**](IntegrationsAPI.md#IntegrationsList) | **Get** /integrations | List integrations
[**IntegrationsOptions**](IntegrationsAPI.md#IntegrationsOptions) | **Get** /integrations/{id}/options | List an integration&#39;s config options
[**IntegrationsRemove**](IntegrationsAPI.md#IntegrationsRemove) | **Delete** /integrations/{id} | Disconnect an integration
[**IntegrationsSync**](IntegrationsAPI.md#IntegrationsSync) | **Post** /integrations/{id}/sync | Sync an integration now
[**IntegrationsUpdate**](IntegrationsAPI.md#IntegrationsUpdate) | **Patch** /integrations/{id} | Update an integration



## IntegrationsConnect

> IntegrationConnectResult IntegrationsConnect(ctx).IntegrationConnectParams(integrationConnectParams).IdempotencyKey(idempotencyKey).Execute()

Connect an integration



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
	integrationConnectParams := *openapiclient.NewIntegrationConnectParams(openapiclient.IntegrationProvider("slack")) // IntegrationConnectParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsConnect(context.Background()).IntegrationConnectParams(integrationConnectParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsConnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsConnect`: IntegrationConnectResult
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsConnect`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsConnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **integrationConnectParams** | [**IntegrationConnectParams**](IntegrationConnectParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**IntegrationConnectResult**](IntegrationConnectResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsFind

> Integration IntegrationsFind(ctx, id).Execute()

Get an integration

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
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsFind(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsFind`: Integration
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Integration**](Integration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsList

> IntegrationList IntegrationsList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Provider(provider).Execute()

List integrations



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
	provider := "provider_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Provider(provider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsList`: IntegrationList
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 
 **provider** | **string** |  | 

### Return type

[**IntegrationList**](IntegrationList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsOptions

> IntegrationOptions IntegrationsOptions(ctx, id).Execute()

List an integration's config options



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
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsOptions(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsOptions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsOptions`: IntegrationOptions
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsOptions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsOptionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IntegrationOptions**](IntegrationOptions.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsRemove

> Integration IntegrationsRemove(ctx, id).Execute()

Disconnect an integration



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
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsRemove(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsRemove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsRemove`: Integration
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsRemove`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsRemoveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Integration**](Integration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsSync

> IntegrationSyncResult IntegrationsSync(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Sync an integration now



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
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsSync(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsSync``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsSync`: IntegrationSyncResult
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsSync`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsSyncRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**IntegrationSyncResult**](IntegrationSyncResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IntegrationsUpdate

> Integration IntegrationsUpdate(ctx, id).IntegrationUpdateParams(integrationUpdateParams).Execute()

Update an integration



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
	integrationUpdateParams := *openapiclient.NewIntegrationUpdateParams(*openapiclient.NewIntegrationConfig()) // IntegrationUpdateParams | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IntegrationsAPI.IntegrationsUpdate(context.Background(), id).IntegrationUpdateParams(integrationUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IntegrationsAPI.IntegrationsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IntegrationsUpdate`: Integration
	fmt.Fprintf(os.Stdout, "Response from `IntegrationsAPI.IntegrationsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIntegrationsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **integrationUpdateParams** | [**IntegrationUpdateParams**](IntegrationUpdateParams.md) |  | 

### Return type

[**Integration**](Integration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

