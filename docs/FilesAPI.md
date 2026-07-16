# \FilesAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FilesCreate**](FilesAPI.md#FilesCreate) | **Post** /files | Upload a public file



## FilesCreate

> FileObject FilesCreate(ctx).FileUpload(fileUpload).IdempotencyKey(idempotencyKey).Execute()

Upload a public file



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
	fileUpload := *openapiclient.NewFileUpload("Content_example", "ContentType_example", "Filename_example") // FileUpload | 
	idempotencyKey := "idempotencyKey_example" // string | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.FilesCreate(context.Background()).FileUpload(fileUpload).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.FilesCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FilesCreate`: FileObject
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.FilesCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFilesCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fileUpload** | [**FileUpload**](FileUpload.md) |  | 
 **idempotencyKey** | **string** | Opt-in idempotency for a safely retried write: reuse the same key to replay the original result for 24h instead of re-executing. Recommended on every POST. | 

### Return type

[**FileObject**](FileObject.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

