# \LogsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClearRequestLogsLogsLogsRequestsDelete**](LogsAPI.md#ClearRequestLogsLogsLogsRequestsDelete) | **Delete** /logs/logs/requests | Clear Request Logs
[**GetRequestLogsLogsLogsRequestsGet**](LogsAPI.md#GetRequestLogsLogsLogsRequestsGet) | **Get** /logs/logs/requests | Get Request Logs



## ClearRequestLogsLogsLogsRequestsDelete

> interface{} ClearRequestLogsLogsLogsRequestsDelete(ctx).Execute()

Clear Request Logs



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
	resp, r, err := apiClient.LogsAPI.ClearRequestLogsLogsLogsRequestsDelete(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ClearRequestLogsLogsLogsRequestsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClearRequestLogsLogsLogsRequestsDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ClearRequestLogsLogsLogsRequestsDelete`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiClearRequestLogsLogsLogsRequestsDeleteRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRequestLogsLogsLogsRequestsGet

> interface{} GetRequestLogsLogsLogsRequestsGet(ctx).Limit(limit).StatusCode(statusCode).Endpoint(endpoint).Method(method).Since(since).Execute()

Get Request Logs



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/mailsafepro/mailsafepro-go"
)

func main() {
	limit := int32(56) // int32 | Max results to return (optional) (default to 100)
	statusCode := int32(56) // int32 | Filter by HTTP status code (optional)
	endpoint := "endpoint_example" // string | Filter by endpoint path (optional)
	method := "method_example" // string | Filter by HTTP method (GET, POST, etc) (optional)
	since := time.Now() // time.Time | Filter by timestamp (ISO 8601) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.GetRequestLogsLogsLogsRequestsGet(context.Background()).Limit(limit).StatusCode(statusCode).Endpoint(endpoint).Method(method).Since(since).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.GetRequestLogsLogsLogsRequestsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRequestLogsLogsLogsRequestsGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.GetRequestLogsLogsLogsRequestsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRequestLogsLogsLogsRequestsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Max results to return | [default to 100]
 **statusCode** | **int32** | Filter by HTTP status code | 
 **endpoint** | **string** | Filter by endpoint path | 
 **method** | **string** | Filter by HTTP method (GET, POST, etc) | 
 **since** | **time.Time** | Filter by timestamp (ISO 8601) | 

### Return type

**interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

