# \HealthAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BasicHealthHealthGet**](HealthAPI.md#BasicHealthHealthGet) | **Get** /health | Basic health check
[**BasicHealthHealthGet_0**](HealthAPI.md#BasicHealthHealthGet_0) | **Get** /health | Basic health check
[**CircuitBreakerStatusAdminCircuitBreakerStatusGet**](HealthAPI.md#CircuitBreakerStatusAdminCircuitBreakerStatusGet) | **Get** /admin/circuit-breaker-status | Circuit Breaker Status
[**DetailedHealthHealthDetailedGet**](HealthAPI.md#DetailedHealthHealthDetailedGet) | **Get** /health/detailed | Detailed health check
[**DetailedHealthHealthDetailedGet_0**](HealthAPI.md#DetailedHealthHealthDetailedGet_0) | **Get** /health/detailed | Detailed health check
[**HealthcheckHealthcheckGet**](HealthAPI.md#HealthcheckHealthcheckGet) | **Get** /healthcheck | Healthcheck
[**HealthcheckHealthcheckHead**](HealthAPI.md#HealthcheckHealthcheckHead) | **Head** /healthcheck | Healthcheck
[**LivenessCheckHealthLivenessGet**](HealthAPI.md#LivenessCheckHealthLivenessGet) | **Get** /health/liveness | Liveness Check
[**LivenessHealthLiveGet**](HealthAPI.md#LivenessHealthLiveGet) | **Get** /health/live | Liveness probe (Kubernetes)
[**LivenessHealthLiveGet_0**](HealthAPI.md#LivenessHealthLiveGet_0) | **Get** /health/live | Liveness probe (Kubernetes)
[**ReadinessCheckHealthReadinessGet**](HealthAPI.md#ReadinessCheckHealthReadinessGet) | **Get** /health/readiness | Readiness Check
[**ReadinessHealthReadyGet**](HealthAPI.md#ReadinessHealthReadyGet) | **Get** /health/ready | Readiness probe (Kubernetes)
[**ReadinessHealthReadyGet_0**](HealthAPI.md#ReadinessHealthReadyGet_0) | **Get** /health/ready | Readiness probe (Kubernetes)
[**ServiceStatusStatusGet**](HealthAPI.md#ServiceStatusStatusGet) | **Get** /status | Service Status
[**StartupCheckHealthStartupGet**](HealthAPI.md#StartupCheckHealthStartupGet) | **Get** /health/startup | Startup Check



## BasicHealthHealthGet

> interface{} BasicHealthHealthGet(ctx).Execute()

Basic health check



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
	resp, r, err := apiClient.HealthAPI.BasicHealthHealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.BasicHealthHealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BasicHealthHealthGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.BasicHealthHealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiBasicHealthHealthGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BasicHealthHealthGet_0

> interface{} BasicHealthHealthGet_0(ctx).Execute()

Basic health check



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
	resp, r, err := apiClient.HealthAPI.BasicHealthHealthGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.BasicHealthHealthGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BasicHealthHealthGet_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.BasicHealthHealthGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiBasicHealthHealthGet_1Request struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CircuitBreakerStatusAdminCircuitBreakerStatusGet

> interface{} CircuitBreakerStatusAdminCircuitBreakerStatusGet(ctx).Execute()

Circuit Breaker Status



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
	resp, r, err := apiClient.HealthAPI.CircuitBreakerStatusAdminCircuitBreakerStatusGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.CircuitBreakerStatusAdminCircuitBreakerStatusGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CircuitBreakerStatusAdminCircuitBreakerStatusGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.CircuitBreakerStatusAdminCircuitBreakerStatusGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCircuitBreakerStatusAdminCircuitBreakerStatusGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DetailedHealthHealthDetailedGet

> interface{} DetailedHealthHealthDetailedGet(ctx).Execute()

Detailed health check



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
	resp, r, err := apiClient.HealthAPI.DetailedHealthHealthDetailedGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.DetailedHealthHealthDetailedGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetailedHealthHealthDetailedGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.DetailedHealthHealthDetailedGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDetailedHealthHealthDetailedGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DetailedHealthHealthDetailedGet_0

> interface{} DetailedHealthHealthDetailedGet_0(ctx).Execute()

Detailed health check



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
	resp, r, err := apiClient.HealthAPI.DetailedHealthHealthDetailedGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.DetailedHealthHealthDetailedGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetailedHealthHealthDetailedGet_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.DetailedHealthHealthDetailedGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDetailedHealthHealthDetailedGet_2Request struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthcheckHealthcheckGet

> interface{} HealthcheckHealthcheckGet(ctx).Execute()

Healthcheck



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
	resp, r, err := apiClient.HealthAPI.HealthcheckHealthcheckGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.HealthcheckHealthcheckGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthcheckHealthcheckGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.HealthcheckHealthcheckGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthcheckHealthcheckGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthcheckHealthcheckHead

> interface{} HealthcheckHealthcheckHead(ctx).Execute()

Healthcheck



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
	resp, r, err := apiClient.HealthAPI.HealthcheckHealthcheckHead(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.HealthcheckHealthcheckHead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthcheckHealthcheckHead`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.HealthcheckHealthcheckHead`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthcheckHealthcheckHeadRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LivenessCheckHealthLivenessGet

> interface{} LivenessCheckHealthLivenessGet(ctx).Execute()

Liveness Check



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
	resp, r, err := apiClient.HealthAPI.LivenessCheckHealthLivenessGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.LivenessCheckHealthLivenessGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LivenessCheckHealthLivenessGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.LivenessCheckHealthLivenessGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLivenessCheckHealthLivenessGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LivenessHealthLiveGet

> interface{} LivenessHealthLiveGet(ctx).Execute()

Liveness probe (Kubernetes)



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
	resp, r, err := apiClient.HealthAPI.LivenessHealthLiveGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.LivenessHealthLiveGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LivenessHealthLiveGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.LivenessHealthLiveGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLivenessHealthLiveGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LivenessHealthLiveGet_0

> interface{} LivenessHealthLiveGet_0(ctx).Execute()

Liveness probe (Kubernetes)



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
	resp, r, err := apiClient.HealthAPI.LivenessHealthLiveGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.LivenessHealthLiveGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LivenessHealthLiveGet_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.LivenessHealthLiveGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLivenessHealthLiveGet_3Request struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReadinessCheckHealthReadinessGet

> interface{} ReadinessCheckHealthReadinessGet(ctx).Execute()

Readiness Check



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
	resp, r, err := apiClient.HealthAPI.ReadinessCheckHealthReadinessGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.ReadinessCheckHealthReadinessGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReadinessCheckHealthReadinessGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.ReadinessCheckHealthReadinessGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiReadinessCheckHealthReadinessGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReadinessHealthReadyGet

> interface{} ReadinessHealthReadyGet(ctx).Execute()

Readiness probe (Kubernetes)



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
	resp, r, err := apiClient.HealthAPI.ReadinessHealthReadyGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.ReadinessHealthReadyGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReadinessHealthReadyGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.ReadinessHealthReadyGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiReadinessHealthReadyGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReadinessHealthReadyGet_0

> interface{} ReadinessHealthReadyGet_0(ctx).Execute()

Readiness probe (Kubernetes)



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
	resp, r, err := apiClient.HealthAPI.ReadinessHealthReadyGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.ReadinessHealthReadyGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReadinessHealthReadyGet_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.ReadinessHealthReadyGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiReadinessHealthReadyGet_4Request struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ServiceStatusStatusGet

> interface{} ServiceStatusStatusGet(ctx).Execute()

Service Status



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
	resp, r, err := apiClient.HealthAPI.ServiceStatusStatusGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.ServiceStatusStatusGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ServiceStatusStatusGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.ServiceStatusStatusGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiServiceStatusStatusGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartupCheckHealthStartupGet

> interface{} StartupCheckHealthStartupGet(ctx).Execute()

Startup Check



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
	resp, r, err := apiClient.HealthAPI.StartupCheckHealthStartupGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.StartupCheckHealthStartupGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartupCheckHealthStartupGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.StartupCheckHealthStartupGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiStartupCheckHealthStartupGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

