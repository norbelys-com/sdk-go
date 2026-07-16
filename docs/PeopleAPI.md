# \PeopleAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PeopleArchive**](PeopleAPI.md#PeopleArchive) | **Delete** /people/{id} | Archive a person
[**PeopleAudienceSummary**](PeopleAPI.md#PeopleAudienceSummary) | **Get** /people/audience-summary | Get audience summary
[**PeopleBulkCreate**](PeopleAPI.md#PeopleBulkCreate) | **Post** /people/bulk | Bulk create people (verifies + suppresses in the background; optional group / campaign)
[**PeopleCreate**](PeopleAPI.md#PeopleCreate) | **Post** /people | Create a person
[**PeopleErase**](PeopleAPI.md#PeopleErase) | **Post** /people/{id}/erase | Erase a person (GDPR)
[**PeopleFind**](PeopleAPI.md#PeopleFind) | **Get** /people/{id} | Get a person
[**PeopleGetBulk**](PeopleAPI.md#PeopleGetBulk) | **Get** /people/bulk/{id} | Get a bulk import&#39;s verify stats (sendable / suppressed / pending)
[**PeopleList**](PeopleAPI.md#PeopleList) | **Get** /people | List people
[**PeopleUpdate**](PeopleAPI.md#PeopleUpdate) | **Patch** /people/{id} | Update a person



## PeopleArchive

> Person PeopleArchive(ctx, id).Execute()

Archive a person

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
	resp, r, err := apiClient.PeopleAPI.PeopleArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleArchive`: Person
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPeopleArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Person**](Person.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleAudienceSummary

> AudienceSummary PeopleAudienceSummary(ctx).Scope(scope).GroupId(groupId).SegmentId(segmentId).Execute()

Get audience summary



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
	scope := TODO // AnyOf | 
	groupId := "groupId_example" // string |  (optional)
	segmentId := "segmentId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PeopleAPI.PeopleAudienceSummary(context.Background()).Scope(scope).GroupId(groupId).SegmentId(segmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleAudienceSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleAudienceSummary`: AudienceSummary
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleAudienceSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPeopleAudienceSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope** | [**AnyOf**](AnyOf.md) |  | 
 **groupId** | **string** |  | 
 **segmentId** | **string** |  | 

### Return type

[**AudienceSummary**](AudienceSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleBulkCreate

> PeopleBulkCreateResult PeopleBulkCreate(ctx).PeopleBulkCreateParams(peopleBulkCreateParams).IdempotencyKey(idempotencyKey).Execute()

Bulk create people (verifies + suppresses in the background; optional group / campaign)

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
	peopleBulkCreateParams := *openapiclient.NewPeopleBulkCreateParams([]openapiclient.PersonImportItem{*openapiclient.NewPersonImportItem("Email_example")}) // PeopleBulkCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PeopleAPI.PeopleBulkCreate(context.Background()).PeopleBulkCreateParams(peopleBulkCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleBulkCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleBulkCreate`: PeopleBulkCreateResult
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleBulkCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPeopleBulkCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **peopleBulkCreateParams** | [**PeopleBulkCreateParams**](PeopleBulkCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**PeopleBulkCreateResult**](PeopleBulkCreateResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleCreate

> Person PeopleCreate(ctx).PersonCreateParams(personCreateParams).IdempotencyKey(idempotencyKey).Execute()

Create a person



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
	personCreateParams := *openapiclient.NewPersonCreateParams("Email_example") // PersonCreateParams | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PeopleAPI.PeopleCreate(context.Background()).PersonCreateParams(personCreateParams).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleCreate`: Person
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPeopleCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **personCreateParams** | [**PersonCreateParams**](PersonCreateParams.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**Person**](Person.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleErase

> PersonErased PeopleErase(ctx, id).IdempotencyKey(idempotencyKey).Execute()

Erase a person (GDPR)



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
	resp, r, err := apiClient.PeopleAPI.PeopleErase(context.Background(), id).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleErase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleErase`: PersonErased
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleErase`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPeopleEraseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**PersonErased**](PersonErased.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleFind

> PersonDetail PeopleFind(ctx, id).Expand(expand).Execute()

Get a person



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
	resp, r, err := apiClient.PeopleAPI.PeopleFind(context.Background(), id).Expand(expand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleFind`: PersonDetail
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleFind`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPeopleFindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expand** | **[][]string** |  | 

### Return type

[**PersonDetail**](PersonDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleGetBulk

> PersonImportStats PeopleGetBulk(ctx, id).Execute()

Get a bulk import's verify stats (sendable / suppressed / pending)

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
	resp, r, err := apiClient.PeopleAPI.PeopleGetBulk(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleGetBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleGetBulk`: PersonImportStats
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleGetBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPeopleGetBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PersonImportStats**](PersonImportStats.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleList

> PersonList PeopleList(ctx).Cursor(cursor).IncludeArchived(includeArchived).Dir(dir).Filter(filter).GroupId(groupId).Limit(limit).Page(page).Search(search).SegmentId(segmentId).Sort(sort).Source(source).Status(status).Execute()

List people



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
	dir := "dir_example" // string |  (optional)
	filter := *openapiclient.NewAudienceFilter() // AudienceFilter |  (optional)
	groupId := "groupId_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional)
	page := int32(56) // int32 |  (optional)
	search := "search_example" // string |  (optional)
	segmentId := "segmentId_example" // string |  (optional)
	sort := "sort_example" // string |  (optional)
	source := []string{[]string{"Source_example"}} // []string |  (optional)
	status := []string{[]string{"Status_example"}} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PeopleAPI.PeopleList(context.Background()).Cursor(cursor).IncludeArchived(includeArchived).Dir(dir).Filter(filter).GroupId(groupId).Limit(limit).Page(page).Search(search).SegmentId(segmentId).Sort(sort).Source(source).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleList`: PersonList
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPeopleListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **includeArchived** | **bool** |  | 
 **dir** | **string** |  | 
 **filter** | [**AudienceFilter**](AudienceFilter.md) |  | 
 **groupId** | **string** |  | 
 **limit** | **int32** |  | 
 **page** | **int32** |  | 
 **search** | **string** |  | 
 **segmentId** | **string** |  | 
 **sort** | **string** |  | 
 **source** | **[][]string** |  | 
 **status** | **[][]string** |  | 

### Return type

[**PersonList**](PersonList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PeopleUpdate

> PersonDetail PeopleUpdate(ctx, id).PersonUpdateParams(personUpdateParams).Execute()

Update a person



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
	personUpdateParams := *openapiclient.NewPersonUpdateParams() // PersonUpdateParams |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PeopleAPI.PeopleUpdate(context.Background(), id).PersonUpdateParams(personUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PeopleAPI.PeopleUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PeopleUpdate`: PersonDetail
	fmt.Fprintf(os.Stdout, "Response from `PeopleAPI.PeopleUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPeopleUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **personUpdateParams** | [**PersonUpdateParams**](PersonUpdateParams.md) |  | 

### Return type

[**PersonDetail**](PersonDetail.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

