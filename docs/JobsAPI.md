# \JobsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateJobJobsV1JobsPost**](JobsAPI.md#CreateJobJobsV1JobsPost) | **Post** /jobs/v1/jobs | Create validation job
[**CreateJobJobsV1JobsPost_0**](JobsAPI.md#CreateJobJobsV1JobsPost_0) | **Post** /jobs/v1/jobs | Create validation job
[**GetJobResultsJobsV1JobsJobIdResultsGet**](JobsAPI.md#GetJobResultsJobsV1JobsJobIdResultsGet) | **Get** /jobs/v1/jobs/{job_id}/results | Get job results (paged)
[**GetJobResultsJobsV1JobsJobIdResultsGet_0**](JobsAPI.md#GetJobResultsJobsV1JobsJobIdResultsGet_0) | **Get** /jobs/v1/jobs/{job_id}/results | Get job results (paged)
[**GetJobStatusJobsV1JobsJobIdGet**](JobsAPI.md#GetJobStatusJobsV1JobsJobIdGet) | **Get** /jobs/v1/jobs/{job_id} | Get job status
[**GetJobStatusJobsV1JobsJobIdGet_0**](JobsAPI.md#GetJobStatusJobsV1JobsJobIdGet_0) | **Get** /jobs/v1/jobs/{job_id} | Get job status



## CreateJobJobsV1JobsPost

> JobCreateResponse CreateJobJobsV1JobsPost(ctx).JobCreateRequest(jobCreateRequest).XIdempotencyKey(xIdempotencyKey).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Create validation job

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
	jobCreateRequest := *openapiclient.NewJobCreateRequest("Source_example") // JobCreateRequest | 
	xIdempotencyKey := "xIdempotencyKey_example" // string |  (optional)
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.CreateJobJobsV1JobsPost(context.Background()).JobCreateRequest(jobCreateRequest).XIdempotencyKey(xIdempotencyKey).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.CreateJobJobsV1JobsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateJobJobsV1JobsPost`: JobCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.CreateJobJobsV1JobsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateJobJobsV1JobsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jobCreateRequest** | [**JobCreateRequest**](JobCreateRequest.md) |  | 
 **xIdempotencyKey** | **string** |  | 
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobCreateResponse**](JobCreateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateJobJobsV1JobsPost_0

> JobCreateResponse CreateJobJobsV1JobsPost_0(ctx).JobCreateRequest(jobCreateRequest).XIdempotencyKey(xIdempotencyKey).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Create validation job

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
	jobCreateRequest := *openapiclient.NewJobCreateRequest("Source_example") // JobCreateRequest | 
	xIdempotencyKey := "xIdempotencyKey_example" // string |  (optional)
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.CreateJobJobsV1JobsPost_0(context.Background()).JobCreateRequest(jobCreateRequest).XIdempotencyKey(xIdempotencyKey).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.CreateJobJobsV1JobsPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateJobJobsV1JobsPost_0`: JobCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.CreateJobJobsV1JobsPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateJobJobsV1JobsPost_1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jobCreateRequest** | [**JobCreateRequest**](JobCreateRequest.md) |  | 
 **xIdempotencyKey** | **string** |  | 
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobCreateResponse**](JobCreateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobResultsJobsV1JobsJobIdResultsGet

> JobResultsPage GetJobResultsJobsV1JobsJobIdResultsGet(ctx, jobId).Page(page).Size(size).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get job results (paged)

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
	jobId := "jobId_example" // string | 
	page := int32(56) // int32 |  (optional) (default to 1)
	size := int32(56) // int32 |  (optional) (default to 500)
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet(context.Background(), jobId).Page(page).Size(size).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobResultsJobsV1JobsJobIdResultsGet`: JobResultsPage
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobResultsJobsV1JobsJobIdResultsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** |  | [default to 1]
 **size** | **int32** |  | [default to 500]
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobResultsPage**](JobResultsPage.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobResultsJobsV1JobsJobIdResultsGet_0

> JobResultsPage GetJobResultsJobsV1JobsJobIdResultsGet_0(ctx, jobId).Page(page).Size(size).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get job results (paged)

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
	jobId := "jobId_example" // string | 
	page := int32(56) // int32 |  (optional) (default to 1)
	size := int32(56) // int32 |  (optional) (default to 500)
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet_0(context.Background(), jobId).Page(page).Size(size).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobResultsJobsV1JobsJobIdResultsGet_0`: JobResultsPage
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobResultsJobsV1JobsJobIdResultsGet_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobResultsJobsV1JobsJobIdResultsGet_2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** |  | [default to 1]
 **size** | **int32** |  | [default to 500]
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobResultsPage**](JobResultsPage.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobStatusJobsV1JobsJobIdGet

> JobStatusResponse GetJobStatusJobsV1JobsJobIdGet(ctx, jobId).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get job status

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
	jobId := "jobId_example" // string | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobStatusJobsV1JobsJobIdGet(context.Background(), jobId).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobStatusJobsV1JobsJobIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobStatusJobsV1JobsJobIdGet`: JobStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobStatusJobsV1JobsJobIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobStatusJobsV1JobsJobIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobStatusResponse**](JobStatusResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobStatusJobsV1JobsJobIdGet_0

> JobStatusResponse GetJobStatusJobsV1JobsJobIdGet_0(ctx, jobId).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get job status

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
	jobId := "jobId_example" // string | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobStatusJobsV1JobsJobIdGet_0(context.Background(), jobId).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobStatusJobsV1JobsJobIdGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobStatusJobsV1JobsJobIdGet_0`: JobStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobStatusJobsV1JobsJobIdGet_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobStatusJobsV1JobsJobIdGet_3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**JobStatusResponse**](JobStatusResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

