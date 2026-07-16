# \MessagesAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MessagesAttachment**](MessagesAPI.md#MessagesAttachment) | **Get** /messages/{id}/attachments/{attachmentId} | Download a message attachment
[**MessagesAttachments**](MessagesAPI.md#MessagesAttachments) | **Get** /messages/{id}/attachments | List a message&#39;s attachments
[**MessagesCreate**](MessagesAPI.md#MessagesCreate) | **Post** /messages | Send a message
[**MessagesFind**](MessagesAPI.md#MessagesFind) | **Get** /messages/{id} | Get a message
[**MessagesList**](MessagesAPI.md#MessagesList) | **Get** /messages | List messages
[**MessagesSource**](MessagesAPI.md#MessagesSource) | **Get** /messages/{id}/source | Get a sent message&#39;s source
[**MessagesUpdate**](MessagesAPI.md#MessagesUpdate) | **Patch** /messages/{id} | Triage an inbound message



## MessagesAttachment

> MessageAttachmentDownload MessagesAttachment(ctx, id, attachmentId).Execute()

Download a message attachment



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
	attachmentId := "attachmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesAPI.MessagesAttachment(context.Background(), id, attachmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesAttachment`: MessageAttachmentDownload
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**attachmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMessagesAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**MessageAttachmentDownload**](MessageAttachmentDownload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesAttachments

> MessageAttachmentList MessagesAttachments(ctx, id).Execute()

List a message's attachments



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
	resp, r, err := apiClient.MessagesAPI.MessagesAttachments(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesAttachments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesAttachments`: MessageAttachmentList
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesAttachments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMessagesAttachmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageAttachmentList**](MessageAttachmentList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesCreate

> Message MessagesCreate(ctx).MessageCreateParams(messageCreateParams).IdempotencyKey(idempotencyKey).Execute()

Send a message



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
	messageCreateParams := *openapiclient.NewMessageCreateParams("From_example", "To_example", "Sequence_example", "InReplyTo_example", interface{}(123)) // MessageCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesAPI.MessagesCreate(context.Background()).MessageCreateParams(messageCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesCreate`: Message
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMessagesCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **messageCreateParams** | [**MessageCreateParams**](MessageCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Message**](Message.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesFind

> Message MessagesFind(ctx, id).Execute()

Get a message



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
	resp, r, err := apiClient.MessagesAPI.MessagesFind(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesFind`: Message
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMessagesFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Message**](Message.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesList

> MessageList MessagesList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Channel(channel).Classification(classification).Dir(dir).Direction(direction).Email(email).IsRead(isRead).Limit(limit).OrderBy(orderBy).Page(page).PersonId(personId).ProgramId(programId).Search(search).SenderId(senderId).Status(status).StepId(stepId).ThreadId(threadId).Execute()

List messages



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
	channel := "channel_example" // string |  (optional)
	classification := "classification_example" // string |  (optional)
	dir := "dir_example" // string |  (optional)
	direction := "direction_example" // string |  (optional)
	email := "email_example" // string |  (optional)
	isRead := true // bool |  (optional)
	limit := int32(56) // int32 |  (optional)
	orderBy := "orderBy_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	personId := "personId_example" // string |  (optional)
	programId := "programId_example" // string |  (optional)
	search := "search_example" // string |  (optional)
	senderId := "senderId_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	stepId := "stepId_example" // string |  (optional)
	threadId := "threadId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesAPI.MessagesList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Channel(channel).Classification(classification).Dir(dir).Direction(direction).Email(email).IsRead(isRead).Limit(limit).OrderBy(orderBy).Page(page).PersonId(personId).ProgramId(programId).Search(search).SenderId(senderId).Status(status).StepId(stepId).ThreadId(threadId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesList`: MessageList
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMessagesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **channel** | **string** |  | 
 **classification** | **string** |  | 
 **dir** | **string** |  | 
 **direction** | **string** |  | 
 **email** | **string** |  | 
 **isRead** | **bool** |  | 
 **limit** | **int32** |  | 
 **orderBy** | **string** |  | 
 **page** | **int32** |  | 
 **personId** | **string** |  | 
 **programId** | **string** |  | 
 **search** | **string** |  | 
 **senderId** | **string** |  | 
 **status** | **string** |  | 
 **stepId** | **string** |  | 
 **threadId** | **string** |  | 

### Return type

[**MessageList**](MessageList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesSource

> MessageSource MessagesSource(ctx, id).Execute()

Get a sent message's source



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
	resp, r, err := apiClient.MessagesAPI.MessagesSource(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesSource`: MessageSource
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMessagesSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageSource**](MessageSource.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MessagesUpdate

> Message MessagesUpdate(ctx, id).MessageUpdateParams(messageUpdateParams).Execute()

Triage an inbound message



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
	messageUpdateParams := *openapiclient.NewMessageUpdateParams() // MessageUpdateParams |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesAPI.MessagesUpdate(context.Background(), id).MessageUpdateParams(messageUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.MessagesUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MessagesUpdate`: Message
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.MessagesUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMessagesUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **messageUpdateParams** | [**MessageUpdateParams**](MessageUpdateParams.md) |  | 

### Return type

[**Message**](Message.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

