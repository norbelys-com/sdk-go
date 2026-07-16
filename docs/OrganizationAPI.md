# \OrganizationAPI

All URIs are relative to *https://api.norbelys.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrganizationFeatures**](OrganizationAPI.md#OrganizationFeatures) | **Get** /organization/features | Get the organization&#39;s feature flags
[**OrganizationFind**](OrganizationAPI.md#OrganizationFind) | **Get** /organization | Get the organization
[**OrganizationPulse**](OrganizationAPI.md#OrganizationPulse) | **Get** /organization/pulse | Get the workspace pulse
[**OrganizationUpdate**](OrganizationAPI.md#OrganizationUpdate) | **Patch** /organization | Update the organization
[**OrganizationUsage**](OrganizationAPI.md#OrganizationUsage) | **Get** /organization/usage | Get the organization&#39;s plan usage



## OrganizationFeatures

> Features OrganizationFeatures(ctx).Execute()

Get the organization's feature flags



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationAPI.OrganizationFeatures(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationAPI.OrganizationFeatures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganizationFeatures`: Features
	fmt.Fprintf(os.Stdout, "Response from `OrganizationAPI.OrganizationFeatures`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOrganizationFeaturesRequest struct via the builder pattern


### Return type

[**Features**](Features.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganizationFind

> Organization OrganizationFind(ctx).Execute()

Get the organization



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationAPI.OrganizationFind(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationAPI.OrganizationFind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganizationFind`: Organization
	fmt.Fprintf(os.Stdout, "Response from `OrganizationAPI.OrganizationFind`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOrganizationFindRequest struct via the builder pattern


### Return type

[**Organization**](Organization.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganizationPulse

> OrganizationPulse OrganizationPulse(ctx).Days(days).Execute()

Get the workspace pulse



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
	days := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationAPI.OrganizationPulse(context.Background()).Days(days).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationAPI.OrganizationPulse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganizationPulse`: OrganizationPulse
	fmt.Fprintf(os.Stdout, "Response from `OrganizationAPI.OrganizationPulse`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrganizationPulseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **days** | **int32** |  | 

### Return type

[**OrganizationPulse**](OrganizationPulse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganizationUpdate

> Organization OrganizationUpdate(ctx).OrganizationUpdateParams(organizationUpdateParams).Execute()

Update the organization



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
	organizationUpdateParams := *openapiclient.NewOrganizationUpdateParams() // OrganizationUpdateParams | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationAPI.OrganizationUpdate(context.Background()).OrganizationUpdateParams(organizationUpdateParams).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationAPI.OrganizationUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganizationUpdate`: Organization
	fmt.Fprintf(os.Stdout, "Response from `OrganizationAPI.OrganizationUpdate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrganizationUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationUpdateParams** | [**OrganizationUpdateParams**](OrganizationUpdateParams.md) |  | 

### Return type

[**Organization**](Organization.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrganizationUsage

> OrganizationUsage OrganizationUsage(ctx).Execute()

Get the organization's plan usage



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationAPI.OrganizationUsage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationAPI.OrganizationUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrganizationUsage`: OrganizationUsage
	fmt.Fprintf(os.Stdout, "Response from `OrganizationAPI.OrganizationUsage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOrganizationUsageRequest struct via the builder pattern


### Return type

[**OrganizationUsage**](OrganizationUsage.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

