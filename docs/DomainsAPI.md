# \DomainsAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DomainsArchive**](DomainsAPI.md#DomainsArchive) | **Delete** /domains/{id} | Archive a domain
[**DomainsCreate**](DomainsAPI.md#DomainsCreate) | **Post** /domains | Create a domain
[**DomainsFind**](DomainsAPI.md#DomainsFind) | **Get** /domains/{id} | Get a domain
[**DomainsList**](DomainsAPI.md#DomainsList) | **Get** /domains | List domains
[**DomainsRestore**](DomainsAPI.md#DomainsRestore) | **Post** /domains/{id}/restore | Restore an archived domain
[**DomainsShare**](DomainsAPI.md#DomainsShare) | **Post** /domains/{id}/share | Share the DMARC report
[**DomainsUpdate**](DomainsAPI.md#DomainsUpdate) | **Patch** /domains/{id} | Update a domain



## DomainsArchive

> Domain DomainsArchive(ctx, id).Execute()

Archive a domain



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
	resp, r, err := apiClient.DomainsAPI.DomainsArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsArchive`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Domain**](Domain.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsCreate

> Domain DomainsCreate(ctx).DomainCreateParams(domainCreateParams).IdempotencyKey(idempotencyKey).Execute()

Create a domain



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
	domainCreateParams := *openapiclient.NewDomainCreateParams("Domain_example") // DomainCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsCreate(context.Background()).DomainCreateParams(domainCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsCreate`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainCreateParams** | [**DomainCreateParams**](DomainCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Domain**](Domain.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsFind

> DomainDetail DomainsFind(ctx, id).Expand(expand).Execute()

Get a domain



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
	expand := []string{[]string{"Expand_example"}} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsFind(context.Background(), id).Expand(expand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsFind`: DomainDetail
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expand** | **[][]string** |  | 

### Return type

[**DomainDetail**](DomainDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsList

> DomainList DomainsList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Capability(capability).ProgramId(programId).Execute()

List domains



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
	capability := "capability_example" // string |  (optional)
	programId := "programId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Capability(capability).ProgramId(programId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsList`: DomainList
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 
 **capability** | **string** |  | 
 **programId** | **string** |  | 

### Return type

[**DomainList**](DomainList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsRestore

> Domain DomainsRestore(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Restore an archived domain



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
	resp, r, err := apiClient.DomainsAPI.DomainsRestore(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsRestore`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Domain**](Domain.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsShare

> ReportShare DomainsShare(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Share the DMARC report



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
	resp, r, err := apiClient.DomainsAPI.DomainsShare(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsShare``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsShare`: ReportShare
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsShare`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsShareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**ReportShare**](ReportShare.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsUpdate

> Domain DomainsUpdate(ctx, id).DomainUpdateParams(domainUpdateParams).Execute()

Update a domain



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
	domainUpdateParams := *openapiclient.NewDomainUpdateParams(int32(123)) // DomainUpdateParams | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsUpdate(context.Background(), id).DomainUpdateParams(domainUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsUpdate`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **domainUpdateParams** | [**DomainUpdateParams**](DomainUpdateParams.md) |  | 

### Return type

[**Domain**](Domain.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

