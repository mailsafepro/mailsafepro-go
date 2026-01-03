# \WebhooksManagementAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateWebhookWebhooksManagementWebhooksPost**](WebhooksManagementAPI.md#CreateWebhookWebhooksManagementWebhooksPost) | **Post** /webhooks-management/webhooks/ | Create Webhook
[**DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete**](WebhooksManagementAPI.md#DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete) | **Delete** /webhooks-management/webhooks/{webhook_id} | Delete Webhook
[**GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet**](WebhooksManagementAPI.md#GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet) | **Get** /webhooks-management/webhooks/{webhook_id}/deliveries | Get Deliveries
[**GetWebhookWebhooksManagementWebhooksWebhookIdGet**](WebhooksManagementAPI.md#GetWebhookWebhooksManagementWebhooksWebhookIdGet) | **Get** /webhooks-management/webhooks/{webhook_id} | Get Webhook
[**ListWebhooksWebhooksManagementWebhooksGet**](WebhooksManagementAPI.md#ListWebhooksWebhooksManagementWebhooksGet) | **Get** /webhooks-management/webhooks/ | List Webhooks
[**TestWebhookWebhooksManagementWebhooksWebhookIdTestPost**](WebhooksManagementAPI.md#TestWebhookWebhooksManagementWebhooksWebhookIdTestPost) | **Post** /webhooks-management/webhooks/{webhook_id}/test | Test Webhook
[**UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch**](WebhooksManagementAPI.md#UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch) | **Patch** /webhooks-management/webhooks/{webhook_id} | Update Webhook



## CreateWebhookWebhooksManagementWebhooksPost

> interface{} CreateWebhookWebhooksManagementWebhooksPost(ctx).WebhookCreate(webhookCreate).Execute()

Create Webhook



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
	webhookCreate := *openapiclient.NewWebhookCreate("Url_example") // WebhookCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.CreateWebhookWebhooksManagementWebhooksPost(context.Background()).WebhookCreate(webhookCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.CreateWebhookWebhooksManagementWebhooksPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWebhookWebhooksManagementWebhooksPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.CreateWebhookWebhooksManagementWebhooksPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateWebhookWebhooksManagementWebhooksPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webhookCreate** | [**WebhookCreate**](WebhookCreate.md) |  | 

### Return type

**interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete

> interface{} DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete(ctx, webhookId).Execute()

Delete Webhook



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
	webhookId := "webhookId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**webhookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWebhookWebhooksManagementWebhooksWebhookIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet

> interface{} GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet(ctx, webhookId).Limit(limit).Execute()

Get Deliveries



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
	webhookId := "webhookId_example" // string | 
	limit := int32(56) // int32 |  (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet(context.Background(), webhookId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**webhookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | [default to 100]

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


## GetWebhookWebhooksManagementWebhooksWebhookIdGet

> interface{} GetWebhookWebhooksManagementWebhooksWebhookIdGet(ctx, webhookId).Execute()

Get Webhook



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
	webhookId := "webhookId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWebhookWebhooksManagementWebhooksWebhookIdGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**webhookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWebhookWebhooksManagementWebhooksWebhookIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## ListWebhooksWebhooksManagementWebhooksGet

> interface{} ListWebhooksWebhooksManagementWebhooksGet(ctx).Execute()

List Webhooks



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
	resp, r, err := apiClient.WebhooksManagementAPI.ListWebhooksWebhooksManagementWebhooksGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.ListWebhooksWebhooksManagementWebhooksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWebhooksWebhooksManagementWebhooksGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.ListWebhooksWebhooksManagementWebhooksGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListWebhooksWebhooksManagementWebhooksGetRequest struct via the builder pattern


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


## TestWebhookWebhooksManagementWebhooksWebhookIdTestPost

> interface{} TestWebhookWebhooksManagementWebhooksWebhookIdTestPost(ctx, webhookId).Execute()

Test Webhook



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
	webhookId := "webhookId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestWebhookWebhooksManagementWebhooksWebhookIdTestPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**webhookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTestWebhookWebhooksManagementWebhooksWebhookIdTestPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch

> interface{} UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch(ctx, webhookId).WebhookUpdate(webhookUpdate).Execute()

Update Webhook



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
	webhookId := "webhookId_example" // string | 
	webhookUpdate := *openapiclient.NewWebhookUpdate() // WebhookUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksManagementAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch(context.Background(), webhookId).WebhookUpdate(webhookUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksManagementAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksManagementAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**webhookId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateWebhookWebhooksManagementWebhooksWebhookIdPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **webhookUpdate** | [**WebhookUpdate**](WebhookUpdate.md) |  | 

### Return type

**interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

