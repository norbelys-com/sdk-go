# \ProgramsAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProgramsArchive**](ProgramsAPI.md#ProgramsArchive) | **Delete** /programs/{id} | Archive a program
[**ProgramsAudienceList**](ProgramsAPI.md#ProgramsAudienceList) | **Get** /programs/{id}/audience | List a program&#39;s audience sources
[**ProgramsCreate**](ProgramsAPI.md#ProgramsCreate) | **Post** /programs | Create a program
[**ProgramsEnroll**](ProgramsAPI.md#ProgramsEnroll) | **Post** /programs/{id}/enroll | Enroll people into a program
[**ProgramsEnrollmentsFind**](ProgramsAPI.md#ProgramsEnrollmentsFind) | **Get** /programs/{programId}/enrollments/{id} | Get an enrollment
[**ProgramsEnrollmentsList**](ProgramsAPI.md#ProgramsEnrollmentsList) | **Get** /programs/{programId}/enrollments | List a program&#39;s leads
[**ProgramsFind**](ProgramsAPI.md#ProgramsFind) | **Get** /programs/{id} | Get a program
[**ProgramsLaunch**](ProgramsAPI.md#ProgramsLaunch) | **Post** /programs/{id}/launch | Launch a program
[**ProgramsList**](ProgramsAPI.md#ProgramsList) | **Get** /programs | List programs
[**ProgramsPause**](ProgramsAPI.md#ProgramsPause) | **Post** /programs/{id}/pause | Pause a program&#39;s sending
[**ProgramsRestore**](ProgramsAPI.md#ProgramsRestore) | **Post** /programs/{id}/restore | Restore an archived program
[**ProgramsResume**](ProgramsAPI.md#ProgramsResume) | **Post** /programs/{id}/resume | Resume a paused program
[**ProgramsSendersAdd**](ProgramsAPI.md#ProgramsSendersAdd) | **Post** /programs/{id}/senders | Attach a sender to a program
[**ProgramsSendersList**](ProgramsAPI.md#ProgramsSendersList) | **Get** /programs/{id}/senders | List a program&#39;s senders
[**ProgramsSendersRemove**](ProgramsAPI.md#ProgramsSendersRemove) | **Delete** /programs/{id}/senders/{relId} | Detach a sender from a program
[**ProgramsShare**](ProgramsAPI.md#ProgramsShare) | **Post** /programs/{id}/share | Share the campaign report
[**ProgramsUpdate**](ProgramsAPI.md#ProgramsUpdate) | **Patch** /programs/{id} | Update a program



## ProgramsArchive

> Program ProgramsArchive(ctx, id).Execute()

Archive a program



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsArchive`: Program
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Program**](Program.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsAudienceList

> ProgramsAudienceList ProgramsAudienceList(ctx, id).Execute()

List a program's audience sources



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsAudienceList(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsAudienceList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsAudienceList`: ProgramsAudienceList
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsAudienceList`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsAudienceListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProgramsAudienceList**](ProgramsAudienceList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsCreate

> ProgramDetail ProgramsCreate(ctx).ProgramCreateParams(programCreateParams).IdempotencyKey(idempotencyKey).Execute()

Create a program



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
	programCreateParams := *openapiclient.NewProgramCreateParams("Name_example") // ProgramCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsCreate(context.Background()).ProgramCreateParams(programCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsCreate`: ProgramDetail
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProgramsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **programCreateParams** | [**ProgramCreateParams**](ProgramCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**ProgramDetail**](ProgramDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsEnroll

> EnrollProgramResult ProgramsEnroll(ctx, id).IdempotencyKey(idempotencyKey).EnrollProgramParams(enrollProgramParams).Execute()

Enroll people into a program



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
	enrollProgramParams := *openapiclient.NewEnrollProgramParams() // EnrollProgramParams |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsEnroll(context.Background(), id).IdempotencyKey(idempotencyKey).EnrollProgramParams(enrollProgramParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsEnroll``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsEnroll`: EnrollProgramResult
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsEnroll`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsEnrollRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 
 **enrollProgramParams** | [**EnrollProgramParams**](EnrollProgramParams.md) |  | 

### Return type

[**EnrollProgramResult**](EnrollProgramResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsEnrollmentsFind

> Enrollment ProgramsEnrollmentsFind(ctx, programId, id).Execute()

Get an enrollment

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
	programId := "programId_example" // string | 
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsEnrollmentsFind(context.Background(), programId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsEnrollmentsFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsEnrollmentsFind`: Enrollment
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsEnrollmentsFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsEnrollmentsFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Enrollment**](Enrollment.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsEnrollmentsList

> EnrollmentList ProgramsEnrollmentsList(ctx, programId).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Dir(dir).Page(page).Q(q).Sort(sort).Status(status).Execute()

List a program's leads



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
	programId := "programId_example" // string | 
	cursor := "cursor_example" // string |  (optional)
	includeArchived := true // bool |  (optional)
	limit := int32(56) // int32 |  (optional)
	dir := "dir_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	q := "q_example" // string |  (optional)
	sort := "sort_example" // string |  (optional)
	status := []string{[]string{"Status_example"}} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsEnrollmentsList(context.Background(), programId).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Dir(dir).Page(page).Q(q).Sort(sort).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsEnrollmentsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsEnrollmentsList`: EnrollmentList
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsEnrollmentsList`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**programId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsEnrollmentsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 
 **dir** | **string** |  | 
 **page** | **int32** |  | 
 **q** | **string** |  | 
 **sort** | **string** |  | 
 **status** | **[][]string** |  | 

### Return type

[**EnrollmentList**](EnrollmentList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsFind

> ProgramDetail ProgramsFind(ctx, id).Expand(expand).Execute()

Get a program



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsFind(context.Background(), id).Expand(expand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsFind`: ProgramDetail
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expand** | **[][]string** |  | 

### Return type

[**ProgramDetail**](ProgramDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsLaunch

> LaunchProgramResult ProgramsLaunch(ctx, id).IdempotencyKey(idempotencyKey).LaunchProgramParams(launchProgramParams).Execute()

Launch a program



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
	launchProgramParams := *openapiclient.NewLaunchProgramParams() // LaunchProgramParams |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsLaunch(context.Background(), id).IdempotencyKey(idempotencyKey).LaunchProgramParams(launchProgramParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsLaunch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsLaunch`: LaunchProgramResult
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsLaunch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsLaunchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 
 **launchProgramParams** | [**LaunchProgramParams**](LaunchProgramParams.md) |  | 

### Return type

[**LaunchProgramResult**](LaunchProgramResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsList

> ProgramList ProgramsList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Dir(dir).Page(page).Archived(archived).Q(q).SenderId(senderId).Sort(sort).Status(status).Execute()

List programs



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
	dir := "dir_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	archived := true // bool |  (optional)
	q := "q_example" // string |  (optional)
	senderId := "senderId_example" // string |  (optional)
	sort := "sort_example" // string |  (optional)
	status := []string{[]string{"Status_example"}} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Limit(limit).Dir(dir).Page(page).Archived(archived).Q(q).SenderId(senderId).Sort(sort).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsList`: ProgramList
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProgramsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **limit** | **int32** |  | 
 **dir** | **string** |  | 
 **page** | **int32** |  | 
 **archived** | **bool** |  | 
 **q** | **string** |  | 
 **senderId** | **string** |  | 
 **sort** | **string** |  | 
 **status** | **[][]string** |  | 

### Return type

[**ProgramList**](ProgramList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsPause

> Program ProgramsPause(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Pause a program's sending



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsPause(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsPause``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsPause`: Program
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsPause`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsPauseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Program**](Program.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsRestore

> Program ProgramsRestore(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Restore an archived program



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsRestore(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsRestore`: Program
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Program**](Program.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsResume

> Program ProgramsResume(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Resume a paused program



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsResume(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsResume``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsResume`: Program
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsResume`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsResumeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Program**](Program.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsSendersAdd

> ProgramSenderRef ProgramsSendersAdd(ctx, id).AddProgramSenderParams(addProgramSenderParams).IdempotencyKey(idempotencyKey).Execute()

Attach a sender to a program



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
	addProgramSenderParams := *openapiclient.NewAddProgramSenderParams("SenderId_example") // AddProgramSenderParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsSendersAdd(context.Background(), id).AddProgramSenderParams(addProgramSenderParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsSendersAdd``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsSendersAdd`: ProgramSenderRef
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsSendersAdd`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsSendersAddRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addProgramSenderParams** | [**AddProgramSenderParams**](AddProgramSenderParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**ProgramSenderRef**](ProgramSenderRef.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsSendersList

> ProgramsSendersList ProgramsSendersList(ctx, id).Execute()

List a program's senders



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsSendersList(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsSendersList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsSendersList`: ProgramsSendersList
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsSendersList`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsSendersListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProgramsSendersList**](ProgramsSendersList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsSendersRemove

> DetachResult ProgramsSendersRemove(ctx, id, relId).Execute()

Detach a sender from a program



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
	relId := "relId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsSendersRemove(context.Background(), id, relId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsSendersRemove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsSendersRemove`: DetachResult
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsSendersRemove`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**relId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsSendersRemoveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DetachResult**](DetachResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsShare

> CampaignReportShare ProgramsShare(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Share the campaign report



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
	resp, r, err := apiClient.ProgramsAPI.ProgramsShare(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsShare``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsShare`: CampaignReportShare
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsShare`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsShareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**CampaignReportShare**](CampaignReportShare.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProgramsUpdate

> ProgramDetail ProgramsUpdate(ctx, id).ProgramUpdateParams(programUpdateParams).Execute()

Update a program



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
	programUpdateParams := *openapiclient.NewProgramUpdateParams() // ProgramUpdateParams |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProgramsAPI.ProgramsUpdate(context.Background(), id).ProgramUpdateParams(programUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProgramsAPI.ProgramsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProgramsUpdate`: ProgramDetail
	fmt.Fprintf(os.Stdout, "Response from `ProgramsAPI.ProgramsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgramsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **programUpdateParams** | [**ProgramUpdateParams**](ProgramUpdateParams.md) |  | 

### Return type

[**ProgramDetail**](ProgramDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

