# \SendersAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SendersBulk**](SendersAPI.md#SendersBulk) | **Post** /senders/bulk | Bulk-update senders
[**SendersCreate**](SendersAPI.md#SendersCreate) | **Post** /senders | Connect a sender
[**SendersFind**](SendersAPI.md#SendersFind) | **Get** /senders/{id} | Get a sender
[**SendersList**](SendersAPI.md#SendersList) | **Get** /senders | List senders
[**SendersRemove**](SendersAPI.md#SendersRemove) | **Delete** /senders/{id} | Delete or archive a sender
[**SendersRestore**](SendersAPI.md#SendersRestore) | **Post** /senders/{id}/restore | Restore an archived sender
[**SendersUpdate**](SendersAPI.md#SendersUpdate) | **Patch** /senders/{id} | Update a sender



## SendersBulk

> BulkUpdateSendersResult SendersBulk(ctx).BulkUpdateSendersInput(bulkUpdateSendersInput).IdempotencyKey(idempotencyKey).Execute()

Bulk-update senders



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
	bulkUpdateSendersInput := *openapiclient.NewBulkUpdateSendersInput([]string{"Ids_example"}, *openapiclient.NewBulkUpdateSenderPatch()) // BulkUpdateSendersInput | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SendersAPI.SendersBulk(context.Background()).BulkUpdateSendersInput(bulkUpdateSendersInput).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersBulk`: BulkUpdateSendersResult
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersBulk`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendersBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkUpdateSendersInput** | [**BulkUpdateSendersInput**](BulkUpdateSendersInput.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**BulkUpdateSendersResult**](BulkUpdateSendersResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersCreate

> Sender SendersCreate(ctx).CreateSenderInput(createSenderInput).IdempotencyKey(idempotencyKey).Execute()

Connect a sender



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
	createSenderInput := *openapiclient.NewCreateSenderInput("FromEmail_example", "FromName_example", *openapiclient.NewSmtpConnectionSettings("Host_example", int32(123)), interface{}(123), "TransportProvider_example") // CreateSenderInput | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SendersAPI.SendersCreate(context.Background()).CreateSenderInput(createSenderInput).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersCreate`: Sender
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendersCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createSenderInput** | [**CreateSenderInput**](CreateSenderInput.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Sender**](Sender.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersFind

> SenderDetail SendersFind(ctx, id).Expand(expand).Execute()

Get a sender



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
	resp, r, err := apiClient.SendersAPI.SendersFind(context.Background(), id).Expand(expand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersFind`: SenderDetail
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendersFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expand** | **[][]string** |  | 

### Return type

[**SenderDetail**](SenderDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersList

> SenderList SendersList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Reputation(reputation).Search(search).SendingDomainId(sendingDomainId).State(state).Execute()

List senders



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
	reputation := []string{[]string{"Reputation_example"}} // []string |  (optional)
	search := "search_example" // string |  (optional)
	sendingDomainId := "sendingDomainId_example" // string |  (optional)
	state := []string{[]string{"State_example"}} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SendersAPI.SendersList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Reputation(reputation).Search(search).SendingDomainId(sendingDomainId).State(state).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersList`: SenderList
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendersListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 
 **reputation** | **[][]string** |  | 
 **search** | **string** |  | 
 **sendingDomainId** | **string** |  | 
 **state** | **[][]string** |  | 

### Return type

[**SenderList**](SenderList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersRemove

> SenderRemoveResult SendersRemove(ctx, id).Execute()

Delete or archive a sender



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
	resp, r, err := apiClient.SendersAPI.SendersRemove(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersRemove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersRemove`: SenderRemoveResult
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersRemove`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendersRemoveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SenderRemoveResult**](SenderRemoveResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersRestore

> Sender SendersRestore(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Restore an archived sender



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
	resp, r, err := apiClient.SendersAPI.SendersRestore(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersRestore`: Sender
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendersRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Sender**](Sender.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendersUpdate

> Sender SendersUpdate(ctx, id).UpdateSenderInput(updateSenderInput).Execute()

Update a sender



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
	updateSenderInput := *openapiclient.NewUpdateSenderInput() // UpdateSenderInput |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SendersAPI.SendersUpdate(context.Background(), id).UpdateSenderInput(updateSenderInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendersAPI.SendersUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendersUpdate`: Sender
	fmt.Fprintf(os.Stdout, "Response from `SendersAPI.SendersUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendersUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateSenderInput** | [**UpdateSenderInput**](UpdateSenderInput.md) |  | 

### Return type

[**Sender**](Sender.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

