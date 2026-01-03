# \WebhooksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateWebhookWebhooksManagementWebhooksPost**](WebhooksAPI.md#CreateWebhookWebhooksManagementWebhooksPost) | **Post** /webhooks-management/webhooks/ | Create Webhook
[**DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete**](WebhooksAPI.md#DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete) | **Delete** /webhooks-management/webhooks/{webhook_id} | Delete Webhook
[**GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet**](WebhooksAPI.md#GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet) | **Get** /webhooks-management/webhooks/{webhook_id}/deliveries | Get Deliveries
[**GetWebhookWebhooksManagementWebhooksWebhookIdGet**](WebhooksAPI.md#GetWebhookWebhooksManagementWebhooksWebhookIdGet) | **Get** /webhooks-management/webhooks/{webhook_id} | Get Webhook
[**ListWebhooksWebhooksManagementWebhooksGet**](WebhooksAPI.md#ListWebhooksWebhooksManagementWebhooksGet) | **Get** /webhooks-management/webhooks/ | List Webhooks
[**RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost**](WebhooksAPI.md#RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost) | **Post** /webhooks/v1/webhooks/endpoints/register | Register Endpoint
[**RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0**](WebhooksAPI.md#RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0) | **Post** /webhooks/v1/webhooks/endpoints/register | Register Endpoint
[**RotateSecretWebhooksV1WebhooksEndpointsRotatePost**](WebhooksAPI.md#RotateSecretWebhooksV1WebhooksEndpointsRotatePost) | **Post** /webhooks/v1/webhooks/endpoints/rotate | Rotate Secret
[**RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0**](WebhooksAPI.md#RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0) | **Post** /webhooks/v1/webhooks/endpoints/rotate | Rotate Secret
[**TestWebhookWebhooksManagementWebhooksWebhookIdTestPost**](WebhooksAPI.md#TestWebhookWebhooksManagementWebhooksWebhookIdTestPost) | **Post** /webhooks-management/webhooks/{webhook_id}/test | Test Webhook
[**UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch**](WebhooksAPI.md#UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch) | **Patch** /webhooks-management/webhooks/{webhook_id} | Update Webhook



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
	resp, r, err := apiClient.WebhooksAPI.CreateWebhookWebhooksManagementWebhooksPost(context.Background()).WebhookCreate(webhookCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.CreateWebhookWebhooksManagementWebhooksPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWebhookWebhooksManagementWebhooksPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.CreateWebhookWebhooksManagementWebhooksPost`: %v\n", resp)
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
	resp, r, err := apiClient.WebhooksAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.DeleteWebhookWebhooksManagementWebhooksWebhookIdDelete`: %v\n", resp)
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
	resp, r, err := apiClient.WebhooksAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet(context.Background(), webhookId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.GetDeliveriesWebhooksManagementWebhooksWebhookIdDeliveriesGet`: %v\n", resp)
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
	resp, r, err := apiClient.WebhooksAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWebhookWebhooksManagementWebhooksWebhookIdGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.GetWebhookWebhooksManagementWebhooksWebhookIdGet`: %v\n", resp)
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
	resp, r, err := apiClient.WebhooksAPI.ListWebhooksWebhooksManagementWebhooksGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.ListWebhooksWebhooksManagementWebhooksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWebhooksWebhooksManagementWebhooksGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.ListWebhooksWebhooksManagementWebhooksGet`: %v\n", resp)
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


## RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost

> interface{} RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost(ctx).RegisterEndpoint(registerEndpoint).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Register Endpoint

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
	registerEndpoint := *openapiclient.NewRegisterEndpoint("CallbackUrl_example") // RegisterEndpoint | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost(context.Background()).RegisterEndpoint(registerEndpoint).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterEndpointWebhooksV1WebhooksEndpointsRegisterPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registerEndpoint** | [**RegisterEndpoint**](RegisterEndpoint.md) |  | 
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


## RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0

> interface{} RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0(ctx).RegisterEndpoint(registerEndpoint).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Register Endpoint

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
	registerEndpoint := *openapiclient.NewRegisterEndpoint("CallbackUrl_example") // RegisterEndpoint | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0(context.Background()).RegisterEndpoint(registerEndpoint).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.RegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterEndpointWebhooksV1WebhooksEndpointsRegisterPost_1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registerEndpoint** | [**RegisterEndpoint**](RegisterEndpoint.md) |  | 
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


## RotateSecretWebhooksV1WebhooksEndpointsRotatePost

> interface{} RotateSecretWebhooksV1WebhooksEndpointsRotatePost(ctx).RotateSecret(rotateSecret).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Rotate Secret

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
	rotateSecret := *openapiclient.NewRotateSecret("EndpointId_example") // RotateSecret | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost(context.Background()).RotateSecret(rotateSecret).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateSecretWebhooksV1WebhooksEndpointsRotatePost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRotateSecretWebhooksV1WebhooksEndpointsRotatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rotateSecret** | [**RotateSecret**](RotateSecret.md) |  | 
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


## RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0

> interface{} RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0(ctx).RotateSecret(rotateSecret).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Rotate Secret

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
	rotateSecret := *openapiclient.NewRotateSecret("EndpointId_example") // RotateSecret | 
	xAPIKey := "xAPIKey_example" // string |  (optional)
	authorization := "authorization_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0(context.Background()).RotateSecret(rotateSecret).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.RotateSecretWebhooksV1WebhooksEndpointsRotatePost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRotateSecretWebhooksV1WebhooksEndpointsRotatePost_2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rotateSecret** | [**RotateSecret**](RotateSecret.md) |  | 
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
	resp, r, err := apiClient.WebhooksAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost(context.Background(), webhookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestWebhookWebhooksManagementWebhooksWebhookIdTestPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.TestWebhookWebhooksManagementWebhooksWebhookIdTestPost`: %v\n", resp)
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
	resp, r, err := apiClient.WebhooksAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch(context.Background(), webhookId).WebhookUpdate(webhookUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.UpdateWebhookWebhooksManagementWebhooksWebhookIdPatch`: %v\n", resp)
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

