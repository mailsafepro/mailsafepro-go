# \BillingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ChangePlanBillingBillingChangePlanPost**](BillingAPI.md#ChangePlanBillingBillingChangePlanPost) | **Post** /billing/billing/change-plan | Change Plan
[**ChangePlanBillingBillingChangePlanPost_0**](BillingAPI.md#ChangePlanBillingBillingChangePlanPost_0) | **Post** /billing/billing/change-plan | Change Plan
[**CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost**](BillingAPI.md#CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost) | **Post** /billing/billing/create-checkout-session | Create Checkout Session
[**CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0**](BillingAPI.md#CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0) | **Post** /billing/billing/create-checkout-session | Create Checkout Session
[**GetSubscriptionBillingBillingSubscriptionGet**](BillingAPI.md#GetSubscriptionBillingBillingSubscriptionGet) | **Get** /billing/billing/subscription | Get Subscription
[**GetSubscriptionBillingBillingSubscriptionGet_0**](BillingAPI.md#GetSubscriptionBillingBillingSubscriptionGet_0) | **Get** /billing/billing/subscription | Get Subscription
[**StripeWebhookBillingBillingWebhookPost**](BillingAPI.md#StripeWebhookBillingBillingWebhookPost) | **Post** /billing/billing/webhook | Stripe Webhook
[**StripeWebhookBillingBillingWebhookPost_0**](BillingAPI.md#StripeWebhookBillingBillingWebhookPost_0) | **Post** /billing/billing/webhook | Stripe Webhook
[**TestNotificationBillingBillingTestNotificationPost**](BillingAPI.md#TestNotificationBillingBillingTestNotificationPost) | **Post** /billing/billing/test-notification | Test Notification
[**TestNotificationBillingBillingTestNotificationPost_0**](BillingAPI.md#TestNotificationBillingBillingTestNotificationPost_0) | **Post** /billing/billing/test-notification | Test Notification



## ChangePlanBillingBillingChangePlanPost

> map[string]interface{} ChangePlanBillingBillingChangePlanPost(ctx).BodyChangePlanBillingBillingChangePlanPost(bodyChangePlanBillingBillingChangePlanPost).Execute()

Change Plan



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
	bodyChangePlanBillingBillingChangePlanPost := *openapiclient.NewBodyChangePlanBillingBillingChangePlanPost("Plan_example") // BodyChangePlanBillingBillingChangePlanPost | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ChangePlanBillingBillingChangePlanPost(context.Background()).BodyChangePlanBillingBillingChangePlanPost(bodyChangePlanBillingBillingChangePlanPost).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ChangePlanBillingBillingChangePlanPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChangePlanBillingBillingChangePlanPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ChangePlanBillingBillingChangePlanPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChangePlanBillingBillingChangePlanPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bodyChangePlanBillingBillingChangePlanPost** | [**BodyChangePlanBillingBillingChangePlanPost**](BodyChangePlanBillingBillingChangePlanPost.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChangePlanBillingBillingChangePlanPost_0

> map[string]interface{} ChangePlanBillingBillingChangePlanPost_0(ctx).BodyChangePlanBillingBillingChangePlanPost(bodyChangePlanBillingBillingChangePlanPost).Execute()

Change Plan



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
	bodyChangePlanBillingBillingChangePlanPost := *openapiclient.NewBodyChangePlanBillingBillingChangePlanPost("Plan_example") // BodyChangePlanBillingBillingChangePlanPost | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ChangePlanBillingBillingChangePlanPost_0(context.Background()).BodyChangePlanBillingBillingChangePlanPost(bodyChangePlanBillingBillingChangePlanPost).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ChangePlanBillingBillingChangePlanPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChangePlanBillingBillingChangePlanPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ChangePlanBillingBillingChangePlanPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChangePlanBillingBillingChangePlanPost_1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bodyChangePlanBillingBillingChangePlanPost** | [**BodyChangePlanBillingBillingChangePlanPost**](BodyChangePlanBillingBillingChangePlanPost.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost

> CheckoutSessionResponse CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost(ctx).CheckoutRequest(checkoutRequest).Execute()

Create Checkout Session



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
	checkoutRequest := *openapiclient.NewCheckoutRequest("Plan_example") // CheckoutRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost(context.Background()).CheckoutRequest(checkoutRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost`: CheckoutSessionResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCheckoutSessionBillingBillingCreateCheckoutSessionPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkoutRequest** | [**CheckoutRequest**](CheckoutRequest.md) |  | 

### Return type

[**CheckoutSessionResponse**](CheckoutSessionResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0

> CheckoutSessionResponse CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0(ctx).CheckoutRequest(checkoutRequest).Execute()

Create Checkout Session



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
	checkoutRequest := *openapiclient.NewCheckoutRequest("Plan_example") // CheckoutRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0(context.Background()).CheckoutRequest(checkoutRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0`: CheckoutSessionResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCheckoutSessionBillingBillingCreateCheckoutSessionPost_2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkoutRequest** | [**CheckoutRequest**](CheckoutRequest.md) |  | 

### Return type

[**CheckoutSessionResponse**](CheckoutSessionResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSubscriptionBillingBillingSubscriptionGet

> SubscriptionResponse GetSubscriptionBillingBillingSubscriptionGet(ctx).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get Subscription



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
	resp, r, err := apiClient.BillingAPI.GetSubscriptionBillingBillingSubscriptionGet(context.Background()).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetSubscriptionBillingBillingSubscriptionGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionBillingBillingSubscriptionGet`: SubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetSubscriptionBillingBillingSubscriptionGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionBillingBillingSubscriptionGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**SubscriptionResponse**](SubscriptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSubscriptionBillingBillingSubscriptionGet_0

> SubscriptionResponse GetSubscriptionBillingBillingSubscriptionGet_0(ctx).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get Subscription



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
	resp, r, err := apiClient.BillingAPI.GetSubscriptionBillingBillingSubscriptionGet_0(context.Background()).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetSubscriptionBillingBillingSubscriptionGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionBillingBillingSubscriptionGet_0`: SubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetSubscriptionBillingBillingSubscriptionGet_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionBillingBillingSubscriptionGet_3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xAPIKey** | **string** |  | 
 **authorization** | **string** |  | 

### Return type

[**SubscriptionResponse**](SubscriptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StripeWebhookBillingBillingWebhookPost

> WebhookResponse StripeWebhookBillingBillingWebhookPost(ctx).Execute()

Stripe Webhook



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
	resp, r, err := apiClient.BillingAPI.StripeWebhookBillingBillingWebhookPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.StripeWebhookBillingBillingWebhookPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StripeWebhookBillingBillingWebhookPost`: WebhookResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.StripeWebhookBillingBillingWebhookPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiStripeWebhookBillingBillingWebhookPostRequest struct via the builder pattern


### Return type

[**WebhookResponse**](WebhookResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StripeWebhookBillingBillingWebhookPost_0

> WebhookResponse StripeWebhookBillingBillingWebhookPost_0(ctx).Execute()

Stripe Webhook



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
	resp, r, err := apiClient.BillingAPI.StripeWebhookBillingBillingWebhookPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.StripeWebhookBillingBillingWebhookPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StripeWebhookBillingBillingWebhookPost_0`: WebhookResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.StripeWebhookBillingBillingWebhookPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiStripeWebhookBillingBillingWebhookPost_4Request struct via the builder pattern


### Return type

[**WebhookResponse**](WebhookResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestNotificationBillingBillingTestNotificationPost

> map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue TestNotificationBillingBillingTestNotificationPost(ctx).RequestBody(requestBody).Execute()

Test Notification



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
	requestBody := map[string]string{"key": "Inner_example"} // map[string]string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.TestNotificationBillingBillingTestNotificationPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.TestNotificationBillingBillingTestNotificationPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestNotificationBillingBillingTestNotificationPost`: map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.TestNotificationBillingBillingTestNotificationPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTestNotificationBillingBillingTestNotificationPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]string** |  | 

### Return type

[**map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue**](ResponseTestNotificationBillingBillingTestNotificationPostValue.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestNotificationBillingBillingTestNotificationPost_0

> map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue TestNotificationBillingBillingTestNotificationPost_0(ctx).RequestBody(requestBody).Execute()

Test Notification



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
	requestBody := map[string]string{"key": "Inner_example"} // map[string]string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.TestNotificationBillingBillingTestNotificationPost_0(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.TestNotificationBillingBillingTestNotificationPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestNotificationBillingBillingTestNotificationPost_0`: map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.TestNotificationBillingBillingTestNotificationPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTestNotificationBillingBillingTestNotificationPost_5Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]string** |  | 

### Return type

[**map[string]ResponseTestNotificationBillingBillingTestNotificationPostValue**](ResponseTestNotificationBillingBillingTestNotificationPostValue.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

