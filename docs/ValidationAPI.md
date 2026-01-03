# \ValidationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BatchValidateEmailsValidateBatchPost**](ValidationAPI.md#BatchValidateEmailsValidateBatchPost) | **Post** /validate/batch | Batch Email Validation
[**BatchValidateUploadValidateBatchUploadPost**](ValidationAPI.md#BatchValidateUploadValidateBatchUploadPost) | **Post** /validate/batch/upload | Batch Email Validation via File Upload
[**GetCacheStatsValidateStatsCacheGet**](ValidationAPI.md#GetCacheStatsValidateStatsCacheGet) | **Get** /validate/stats/cache | Get Cache Stats
[**GetUsageStatsValidateStatsUsageGet**](ValidationAPI.md#GetUsageStatsValidateStatsUsageGet) | **Get** /validate/stats/usage | Get Usage Stats
[**HealthCheckValidateHealthGet**](ValidationAPI.md#HealthCheckValidateHealthGet) | **Get** /validate/health | Health Check
[**HealthCheckValidateHealthHead**](ValidationAPI.md#HealthCheckValidateHealthHead) | **Head** /validate/health | Health Check
[**ValidateEmailEndpointValidateEmailPost**](ValidationAPI.md#ValidateEmailEndpointValidateEmailPost) | **Post** /validate/email | Validate Email Endpoint



## BatchValidateEmailsValidateBatchPost

> BatchEmailResponse BatchValidateEmailsValidateBatchPost(ctx).BatchValidationRequest(batchValidationRequest).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Batch Email Validation



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {
	batchValidationRequest := *openapiclient.NewBatchValidationRequest([]string{"Emails_example"}) // BatchValidationRequest | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.BatchValidateEmailsValidateBatchPost(context.Background()).BatchValidationRequest(batchValidationRequest).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.BatchValidateEmailsValidateBatchPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BatchValidateEmailsValidateBatchPost`: BatchEmailResponse
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.BatchValidateEmailsValidateBatchPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBatchValidateEmailsValidateBatchPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **batchValidationRequest** | [**BatchValidationRequest**](BatchValidationRequest.md) |  | 
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**BatchEmailResponse**](BatchEmailResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BatchValidateUploadValidateBatchUploadPost

> interface{} BatchValidateUploadValidateBatchUploadPost(ctx).File(file).XAPIKey(xAPIKey).Authorization(authorization).Column(column).IncludeRawDns(includeRawDns).CheckSmtp(checkSmtp).Execute()

Batch Email Validation via File Upload

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {
	file := os.NewFile(1234, "some_file") // *os.File | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)
	column := "column_example" // string |  (optional)
	includeRawDns := true // bool |  (optional) (default to false)
	checkSmtp := true // bool |  (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.BatchValidateUploadValidateBatchUploadPost(context.Background()).File(file).XAPIKey(xAPIKey).Authorization(authorization).Column(column).IncludeRawDns(includeRawDns).CheckSmtp(checkSmtp).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.BatchValidateUploadValidateBatchUploadPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BatchValidateUploadValidateBatchUploadPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.BatchValidateUploadValidateBatchUploadPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBatchValidateUploadValidateBatchUploadPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** |  | 
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 
 **column** | **string** |  | 
 **includeRawDns** | **bool** |  | [default to false]
 **checkSmtp** | **bool** |  | [default to false]

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCacheStatsValidateStatsCacheGet

> map[string]interface{} GetCacheStatsValidateStatsCacheGet(ctx).Execute()

Get Cache Stats



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.GetCacheStatsValidateStatsCacheGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.GetCacheStatsValidateStatsCacheGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCacheStatsValidateStatsCacheGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.GetCacheStatsValidateStatsCacheGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCacheStatsValidateStatsCacheGetRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsageStatsValidateStatsUsageGet

> map[string]interface{} GetUsageStatsValidateStatsUsageGet(ctx).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get Usage Stats



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.GetUsageStatsValidateStatsUsageGet(context.Background()).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.GetUsageStatsValidateStatsUsageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsageStatsValidateStatsUsageGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.GetUsageStatsValidateStatsUsageGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageStatsValidateStatsUsageGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthCheckValidateHealthGet

> map[string]interface{} HealthCheckValidateHealthGet(ctx).Execute()

Health Check



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.HealthCheckValidateHealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.HealthCheckValidateHealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthCheckValidateHealthGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.HealthCheckValidateHealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthCheckValidateHealthGetRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthCheckValidateHealthHead

> map[string]interface{} HealthCheckValidateHealthHead(ctx).Execute()

Health Check



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.HealthCheckValidateHealthHead(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.HealthCheckValidateHealthHead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthCheckValidateHealthHead`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.HealthCheckValidateHealthHead`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthCheckValidateHealthHeadRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidateEmailEndpointValidateEmailPost

> interface{} ValidateEmailEndpointValidateEmailPost(ctx).EmailValidationRequest(emailValidationRequest).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Validate Email Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {
	emailValidationRequest := *openapiclient.NewEmailValidationRequest("Email_example") // EmailValidationRequest | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ValidationAPI.ValidateEmailEndpointValidateEmailPost(context.Background()).EmailValidationRequest(emailValidationRequest).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ValidationAPI.ValidateEmailEndpointValidateEmailPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateEmailEndpointValidateEmailPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `ValidationAPI.ValidateEmailEndpointValidateEmailPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidateEmailEndpointValidateEmailPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **emailValidationRequest** | [**EmailValidationRequest**](EmailValidationRequest.md) |  | 
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

