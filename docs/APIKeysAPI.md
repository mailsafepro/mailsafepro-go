# \APIKeysAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateApiKeyApiKeysPost**](APIKeysAPI.md#CreateApiKeyApiKeysPost) | **Post** /api-keys | Create Api Key
[**CreateApiKeyApiKeysPost_0**](APIKeysAPI.md#CreateApiKeyApiKeysPost_0) | **Post** /api-keys | Create Api Key
[**ForceSyncApiKeysForceSyncPost**](APIKeysAPI.md#ForceSyncApiKeysForceSyncPost) | **Post** /api-keys/force-sync | Force Sync
[**ForceSyncApiKeysForceSyncPost_0**](APIKeysAPI.md#ForceSyncApiKeysForceSyncPost_0) | **Post** /api-keys/force-sync | Force Sync
[**GetApiKeyValueApiKeysKeyHashValueGet**](APIKeysAPI.md#GetApiKeyValueApiKeysKeyHashValueGet) | **Get** /api-keys/{key_hash}/value | Get Api Key Value
[**GetApiKeyValueApiKeysKeyHashValueGet_0**](APIKeysAPI.md#GetApiKeyValueApiKeysKeyHashValueGet_0) | **Get** /api-keys/{key_hash}/value | Get Api Key Value
[**GetUsageApiKeysUsageGet**](APIKeysAPI.md#GetUsageApiKeysUsageGet) | **Get** /api-keys/usage | Get Usage
[**GetUsageApiKeysUsageGet_0**](APIKeysAPI.md#GetUsageApiKeysUsageGet_0) | **Get** /api-keys/usage | Get Usage
[**ListApiKeysApiKeysGet**](APIKeysAPI.md#ListApiKeysApiKeysGet) | **Get** /api-keys | List Api Keys
[**ListApiKeysApiKeysGet_0**](APIKeysAPI.md#ListApiKeysApiKeysGet_0) | **Get** /api-keys | List Api Keys
[**RepairUserDataEndpointApiKeysRepairDataPost**](APIKeysAPI.md#RepairUserDataEndpointApiKeysRepairDataPost) | **Post** /api-keys/repair-data | Repair User Data Endpoint
[**RepairUserDataEndpointApiKeysRepairDataPost_0**](APIKeysAPI.md#RepairUserDataEndpointApiKeysRepairDataPost_0) | **Post** /api-keys/repair-data | Repair User Data Endpoint
[**RevokeApiKeyApiKeysKeyHashRevokeDelete**](APIKeysAPI.md#RevokeApiKeyApiKeysKeyHashRevokeDelete) | **Delete** /api-keys/{key_hash}/revoke | Revoke Api Key
[**RevokeApiKeyApiKeysKeyHashRevokeDelete_0**](APIKeysAPI.md#RevokeApiKeyApiKeysKeyHashRevokeDelete_0) | **Delete** /api-keys/{key_hash}/revoke | Revoke Api Key
[**RotateApiKeyApiKeysKeyHashRotatePost**](APIKeysAPI.md#RotateApiKeyApiKeysKeyHashRotatePost) | **Post** /api-keys/{key_hash}/rotate | Rotate Api Key
[**RotateApiKeyApiKeysKeyHashRotatePost_0**](APIKeysAPI.md#RotateApiKeyApiKeysKeyHashRotatePost_0) | **Post** /api-keys/{key_hash}/rotate | Rotate Api Key
[**SyncPlanKeysApiKeysSyncPlanKeysPost**](APIKeysAPI.md#SyncPlanKeysApiKeysSyncPlanKeysPost) | **Post** /api-keys/sync-plan-keys | Sync Plan Keys
[**SyncPlanKeysApiKeysSyncPlanKeysPost_0**](APIKeysAPI.md#SyncPlanKeysApiKeysSyncPlanKeysPost_0) | **Post** /api-keys/sync-plan-keys | Sync Plan Keys



## CreateApiKeyApiKeysPost

> map[string]interface{} CreateApiKeyApiKeysPost(ctx).APIKeyCreateRequest(aPIKeyCreateRequest).Execute()

Create Api Key



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
	aPIKeyCreateRequest := *openapiclient.NewAPIKeyCreateRequest() // APIKeyCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.CreateApiKeyApiKeysPost(context.Background()).APIKeyCreateRequest(aPIKeyCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.CreateApiKeyApiKeysPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateApiKeyApiKeysPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.CreateApiKeyApiKeysPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateApiKeyApiKeysPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aPIKeyCreateRequest** | [**APIKeyCreateRequest**](APIKeyCreateRequest.md) |  | 

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


## CreateApiKeyApiKeysPost_0

> map[string]interface{} CreateApiKeyApiKeysPost_0(ctx).APIKeyCreateRequest(aPIKeyCreateRequest).Execute()

Create Api Key



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
	aPIKeyCreateRequest := *openapiclient.NewAPIKeyCreateRequest() // APIKeyCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.CreateApiKeyApiKeysPost_0(context.Background()).APIKeyCreateRequest(aPIKeyCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.CreateApiKeyApiKeysPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateApiKeyApiKeysPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.CreateApiKeyApiKeysPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateApiKeyApiKeysPost_1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aPIKeyCreateRequest** | [**APIKeyCreateRequest**](APIKeyCreateRequest.md) |  | 

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


## ForceSyncApiKeysForceSyncPost

> map[string]interface{} ForceSyncApiKeysForceSyncPost(ctx).Execute()

Force Sync



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
	resp, r, err := apiClient.APIKeysAPI.ForceSyncApiKeysForceSyncPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.ForceSyncApiKeysForceSyncPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ForceSyncApiKeysForceSyncPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.ForceSyncApiKeysForceSyncPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiForceSyncApiKeysForceSyncPostRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ForceSyncApiKeysForceSyncPost_0

> map[string]interface{} ForceSyncApiKeysForceSyncPost_0(ctx).Execute()

Force Sync



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
	resp, r, err := apiClient.APIKeysAPI.ForceSyncApiKeysForceSyncPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.ForceSyncApiKeysForceSyncPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ForceSyncApiKeysForceSyncPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.ForceSyncApiKeysForceSyncPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiForceSyncApiKeysForceSyncPost_2Request struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetApiKeyValueApiKeysKeyHashValueGet

> map[string]interface{} GetApiKeyValueApiKeysKeyHashValueGet(ctx, keyHash).Execute()

Get Api Key Value



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetApiKeyValueApiKeysKeyHashValueGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiKeyValueApiKeysKeyHashValueGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetApiKeyValueApiKeysKeyHashValueGet_0

> map[string]interface{} GetApiKeyValueApiKeysKeyHashValueGet_0(ctx, keyHash).Execute()

Get Api Key Value



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet_0(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetApiKeyValueApiKeysKeyHashValueGet_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.GetApiKeyValueApiKeysKeyHashValueGet_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiKeyValueApiKeysKeyHashValueGet_3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsageApiKeysUsageGet

> map[string]interface{} GetUsageApiKeysUsageGet(ctx).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get Usage



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
	resp, r, err := apiClient.APIKeysAPI.GetUsageApiKeysUsageGet(context.Background()).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.GetUsageApiKeysUsageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsageApiKeysUsageGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.GetUsageApiKeysUsageGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageApiKeysUsageGetRequest struct via the builder pattern


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


## GetUsageApiKeysUsageGet_0

> map[string]interface{} GetUsageApiKeysUsageGet_0(ctx).XAPIKey(xAPIKey).Authorization(authorization).Execute()

Get Usage



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
	resp, r, err := apiClient.APIKeysAPI.GetUsageApiKeysUsageGet_0(context.Background()).XAPIKey(xAPIKey).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.GetUsageApiKeysUsageGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsageApiKeysUsageGet_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.GetUsageApiKeysUsageGet_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageApiKeysUsageGet_4Request struct via the builder pattern


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


## ListApiKeysApiKeysGet

> APIKeyListResponse ListApiKeysApiKeysGet(ctx).Execute()

List Api Keys



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
	resp, r, err := apiClient.APIKeysAPI.ListApiKeysApiKeysGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.ListApiKeysApiKeysGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListApiKeysApiKeysGet`: APIKeyListResponse
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.ListApiKeysApiKeysGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListApiKeysApiKeysGetRequest struct via the builder pattern


### Return type

[**APIKeyListResponse**](APIKeyListResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListApiKeysApiKeysGet_0

> APIKeyListResponse ListApiKeysApiKeysGet_0(ctx).Execute()

List Api Keys



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
	resp, r, err := apiClient.APIKeysAPI.ListApiKeysApiKeysGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.ListApiKeysApiKeysGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListApiKeysApiKeysGet_0`: APIKeyListResponse
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.ListApiKeysApiKeysGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListApiKeysApiKeysGet_5Request struct via the builder pattern


### Return type

[**APIKeyListResponse**](APIKeyListResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepairUserDataEndpointApiKeysRepairDataPost

> map[string]string RepairUserDataEndpointApiKeysRepairDataPost(ctx).Execute()

Repair User Data Endpoint



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
	resp, r, err := apiClient.APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairUserDataEndpointApiKeysRepairDataPost`: map[string]string
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRepairUserDataEndpointApiKeysRepairDataPostRequest struct via the builder pattern


### Return type

**map[string]string**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepairUserDataEndpointApiKeysRepairDataPost_0

> map[string]string RepairUserDataEndpointApiKeysRepairDataPost_0(ctx).Execute()

Repair User Data Endpoint



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
	resp, r, err := apiClient.APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairUserDataEndpointApiKeysRepairDataPost_0`: map[string]string
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RepairUserDataEndpointApiKeysRepairDataPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRepairUserDataEndpointApiKeysRepairDataPost_6Request struct via the builder pattern


### Return type

**map[string]string**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeApiKeyApiKeysKeyHashRevokeDelete

> interface{} RevokeApiKeyApiKeysKeyHashRevokeDelete(ctx, keyHash).Execute()

Revoke Api Key



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeApiKeyApiKeysKeyHashRevokeDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeApiKeyApiKeysKeyHashRevokeDeleteRequest struct via the builder pattern


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


## RevokeApiKeyApiKeysKeyHashRevokeDelete_0

> interface{} RevokeApiKeyApiKeysKeyHashRevokeDelete_0(ctx, keyHash).Execute()

Revoke Api Key



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete_0(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeApiKeyApiKeysKeyHashRevokeDelete_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RevokeApiKeyApiKeysKeyHashRevokeDelete_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeApiKeyApiKeysKeyHashRevokeDelete_7Request struct via the builder pattern


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


## RotateApiKeyApiKeysKeyHashRotatePost

> map[string]interface{} RotateApiKeyApiKeysKeyHashRotatePost(ctx, keyHash).Execute()

Rotate Api Key



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateApiKeyApiKeysKeyHashRotatePost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotateApiKeyApiKeysKeyHashRotatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotateApiKeyApiKeysKeyHashRotatePost_0

> map[string]interface{} RotateApiKeyApiKeysKeyHashRotatePost_0(ctx, keyHash).Execute()

Rotate Api Key



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
	keyHash := "keyHash_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost_0(context.Background(), keyHash).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateApiKeyApiKeysKeyHashRotatePost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.RotateApiKeyApiKeysKeyHashRotatePost_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyHash** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotateApiKeyApiKeysKeyHashRotatePost_8Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SyncPlanKeysApiKeysSyncPlanKeysPost

> map[string]interface{} SyncPlanKeysApiKeysSyncPlanKeysPost(ctx).Execute()

Sync Plan Keys



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
	resp, r, err := apiClient.APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SyncPlanKeysApiKeysSyncPlanKeysPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSyncPlanKeysApiKeysSyncPlanKeysPostRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SyncPlanKeysApiKeysSyncPlanKeysPost_0

> map[string]interface{} SyncPlanKeysApiKeysSyncPlanKeysPost_0(ctx).Execute()

Sync Plan Keys



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
	resp, r, err := apiClient.APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SyncPlanKeysApiKeysSyncPlanKeysPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `APIKeysAPI.SyncPlanKeysApiKeysSyncPlanKeysPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSyncPlanKeysApiKeysSyncPlanKeysPost_9Request struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

