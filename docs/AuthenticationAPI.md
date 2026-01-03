# \AuthenticationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AuthHealthCheckAuthHealthAuthGet**](AuthenticationAPI.md#AuthHealthCheckAuthHealthAuthGet) | **Get** /auth/health/auth | Auth Health Check
[**AuthHealthCheckAuthHealthAuthGet_0**](AuthenticationAPI.md#AuthHealthCheckAuthHealthAuthGet_0) | **Get** /auth/health/auth | Auth Health Check
[**AuthHealthCheckAuthHealthAuthHead**](AuthenticationAPI.md#AuthHealthCheckAuthHealthAuthHead) | **Head** /auth/health/auth | Auth Health Check
[**AuthHealthCheckAuthHealthAuthHead_0**](AuthenticationAPI.md#AuthHealthCheckAuthHealthAuthHead_0) | **Head** /auth/health/auth | Auth Health Check
[**DeleteAccountAuthDeleteDelete**](AuthenticationAPI.md#DeleteAccountAuthDeleteDelete) | **Delete** /auth/delete | Delete Account
[**DeleteAccountAuthDeleteDelete_0**](AuthenticationAPI.md#DeleteAccountAuthDeleteDelete_0) | **Delete** /auth/delete | Delete Account
[**GetCurrentUserAuthMeGet**](AuthenticationAPI.md#GetCurrentUserAuthMeGet) | **Get** /auth/me | Get Current User
[**GetCurrentUserAuthMeGet_0**](AuthenticationAPI.md#GetCurrentUserAuthMeGet_0) | **Get** /auth/me | Get Current User
[**LoginWebUserAuthLoginPost**](AuthenticationAPI.md#LoginWebUserAuthLoginPost) | **Post** /auth/login | Login Web User
[**LoginWebUserAuthLoginPost_0**](AuthenticationAPI.md#LoginWebUserAuthLoginPost_0) | **Post** /auth/login | Login Web User
[**LogoutAuthLogoutPost**](AuthenticationAPI.md#LogoutAuthLogoutPost) | **Post** /auth/logout | Logout
[**LogoutAuthLogoutPost_0**](AuthenticationAPI.md#LogoutAuthLogoutPost_0) | **Post** /auth/logout | Logout
[**RefreshTokenAuthRefreshPost**](AuthenticationAPI.md#RefreshTokenAuthRefreshPost) | **Post** /auth/refresh | Refresh Token
[**RefreshTokenAuthRefreshPost_0**](AuthenticationAPI.md#RefreshTokenAuthRefreshPost_0) | **Post** /auth/refresh | Refresh Token
[**RegisterWebUserAuthRegisterPost**](AuthenticationAPI.md#RegisterWebUserAuthRegisterPost) | **Post** /auth/register | Register Web User
[**RegisterWebUserAuthRegisterPost_0**](AuthenticationAPI.md#RegisterWebUserAuthRegisterPost_0) | **Post** /auth/register | Register Web User
[**RotateApiKeyAuthRotateKeyPost**](AuthenticationAPI.md#RotateApiKeyAuthRotateKeyPost) | **Post** /auth/rotate-key | Rotate Api Key
[**RotateApiKeyAuthRotateKeyPost_0**](AuthenticationAPI.md#RotateApiKeyAuthRotateKeyPost_0) | **Post** /auth/rotate-key | Rotate Api Key



## AuthHealthCheckAuthHealthAuthGet

> interface{} AuthHealthCheckAuthHealthAuthGet(ctx).Execute()

Auth Health Check



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
	resp, r, err := apiClient.AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuthHealthCheckAuthHealthAuthGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAuthHealthCheckAuthHealthAuthGetRequest struct via the builder pattern


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


## AuthHealthCheckAuthHealthAuthGet_0

> interface{} AuthHealthCheckAuthHealthAuthGet_0(ctx).Execute()

Auth Health Check



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
	resp, r, err := apiClient.AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuthHealthCheckAuthHealthAuthGet_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.AuthHealthCheckAuthHealthAuthGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAuthHealthCheckAuthHealthAuthGet_1Request struct via the builder pattern


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


## AuthHealthCheckAuthHealthAuthHead

> interface{} AuthHealthCheckAuthHealthAuthHead(ctx).Execute()

Auth Health Check



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
	resp, r, err := apiClient.AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuthHealthCheckAuthHealthAuthHead`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAuthHealthCheckAuthHealthAuthHeadRequest struct via the builder pattern


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


## AuthHealthCheckAuthHealthAuthHead_0

> interface{} AuthHealthCheckAuthHealthAuthHead_0(ctx).Execute()

Auth Health Check



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
	resp, r, err := apiClient.AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuthHealthCheckAuthHealthAuthHead_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.AuthHealthCheckAuthHealthAuthHead_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAuthHealthCheckAuthHealthAuthHead_2Request struct via the builder pattern


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


## DeleteAccountAuthDeleteDelete

> interface{} DeleteAccountAuthDeleteDelete(ctx).Execute()

Delete Account



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
	resp, r, err := apiClient.AuthenticationAPI.DeleteAccountAuthDeleteDelete(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.DeleteAccountAuthDeleteDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAccountAuthDeleteDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.DeleteAccountAuthDeleteDelete`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAccountAuthDeleteDeleteRequest struct via the builder pattern


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


## DeleteAccountAuthDeleteDelete_0

> interface{} DeleteAccountAuthDeleteDelete_0(ctx).Execute()

Delete Account



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
	resp, r, err := apiClient.AuthenticationAPI.DeleteAccountAuthDeleteDelete_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.DeleteAccountAuthDeleteDelete_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAccountAuthDeleteDelete_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.DeleteAccountAuthDeleteDelete_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAccountAuthDeleteDelete_3Request struct via the builder pattern


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


## GetCurrentUserAuthMeGet

> map[string]interface{} GetCurrentUserAuthMeGet(ctx).Execute()

Get Current User



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
	resp, r, err := apiClient.AuthenticationAPI.GetCurrentUserAuthMeGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.GetCurrentUserAuthMeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentUserAuthMeGet`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.GetCurrentUserAuthMeGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentUserAuthMeGetRequest struct via the builder pattern


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


## GetCurrentUserAuthMeGet_0

> map[string]interface{} GetCurrentUserAuthMeGet_0(ctx).Execute()

Get Current User



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
	resp, r, err := apiClient.AuthenticationAPI.GetCurrentUserAuthMeGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.GetCurrentUserAuthMeGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentUserAuthMeGet_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.GetCurrentUserAuthMeGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentUserAuthMeGet_4Request struct via the builder pattern


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


## LoginWebUserAuthLoginPost

> map[string]interface{} LoginWebUserAuthLoginPost(ctx).UserLogin(userLogin).Execute()

Login Web User



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
	userLogin := *openapiclient.NewUserLogin("Email_example", "Password_example") // UserLogin | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.LoginWebUserAuthLoginPost(context.Background()).UserLogin(userLogin).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.LoginWebUserAuthLoginPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LoginWebUserAuthLoginPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.LoginWebUserAuthLoginPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLoginWebUserAuthLoginPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userLogin** | [**UserLogin**](UserLogin.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LoginWebUserAuthLoginPost_0

> map[string]interface{} LoginWebUserAuthLoginPost_0(ctx).UserLogin(userLogin).Execute()

Login Web User



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
	userLogin := *openapiclient.NewUserLogin("Email_example", "Password_example") // UserLogin | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.LoginWebUserAuthLoginPost_0(context.Background()).UserLogin(userLogin).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.LoginWebUserAuthLoginPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LoginWebUserAuthLoginPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.LoginWebUserAuthLoginPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLoginWebUserAuthLoginPost_5Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userLogin** | [**UserLogin**](UserLogin.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LogoutAuthLogoutPost

> interface{} LogoutAuthLogoutPost(ctx).Execute()

Logout



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
	resp, r, err := apiClient.AuthenticationAPI.LogoutAuthLogoutPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.LogoutAuthLogoutPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LogoutAuthLogoutPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.LogoutAuthLogoutPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLogoutAuthLogoutPostRequest struct via the builder pattern


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


## LogoutAuthLogoutPost_0

> interface{} LogoutAuthLogoutPost_0(ctx).Execute()

Logout



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
	resp, r, err := apiClient.AuthenticationAPI.LogoutAuthLogoutPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.LogoutAuthLogoutPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LogoutAuthLogoutPost_0`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.LogoutAuthLogoutPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLogoutAuthLogoutPost_6Request struct via the builder pattern


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


## RefreshTokenAuthRefreshPost

> map[string]interface{} RefreshTokenAuthRefreshPost(ctx).Execute()

Refresh Token



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
	resp, r, err := apiClient.AuthenticationAPI.RefreshTokenAuthRefreshPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RefreshTokenAuthRefreshPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshTokenAuthRefreshPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RefreshTokenAuthRefreshPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRefreshTokenAuthRefreshPostRequest struct via the builder pattern


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


## RefreshTokenAuthRefreshPost_0

> map[string]interface{} RefreshTokenAuthRefreshPost_0(ctx).Execute()

Refresh Token



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
	resp, r, err := apiClient.AuthenticationAPI.RefreshTokenAuthRefreshPost_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RefreshTokenAuthRefreshPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshTokenAuthRefreshPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RefreshTokenAuthRefreshPost_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRefreshTokenAuthRefreshPost_7Request struct via the builder pattern


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


## RegisterWebUserAuthRegisterPost

> map[string]interface{} RegisterWebUserAuthRegisterPost(ctx).UserRegister(userRegister).Execute()

Register Web User



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
	userRegister := *openapiclient.NewUserRegister("Email_example", "Password_example") // UserRegister | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.RegisterWebUserAuthRegisterPost(context.Background()).UserRegister(userRegister).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RegisterWebUserAuthRegisterPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterWebUserAuthRegisterPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RegisterWebUserAuthRegisterPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterWebUserAuthRegisterPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userRegister** | [**UserRegister**](UserRegister.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterWebUserAuthRegisterPost_0

> map[string]interface{} RegisterWebUserAuthRegisterPost_0(ctx).UserRegister(userRegister).Execute()

Register Web User



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
	userRegister := *openapiclient.NewUserRegister("Email_example", "Password_example") // UserRegister | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.RegisterWebUserAuthRegisterPost_0(context.Background()).UserRegister(userRegister).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RegisterWebUserAuthRegisterPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterWebUserAuthRegisterPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RegisterWebUserAuthRegisterPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterWebUserAuthRegisterPost_8Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userRegister** | [**UserRegister**](UserRegister.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotateApiKeyAuthRotateKeyPost

> map[string]interface{} RotateApiKeyAuthRotateKeyPost(ctx).KeyRotationRequest(keyRotationRequest).Execute()

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
	keyRotationRequest := *openapiclient.NewKeyRotationRequest("OldKey_example", "NewKey_example") // KeyRotationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.RotateApiKeyAuthRotateKeyPost(context.Background()).KeyRotationRequest(keyRotationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RotateApiKeyAuthRotateKeyPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateApiKeyAuthRotateKeyPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RotateApiKeyAuthRotateKeyPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRotateApiKeyAuthRotateKeyPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **keyRotationRequest** | [**KeyRotationRequest**](KeyRotationRequest.md) |  | 

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


## RotateApiKeyAuthRotateKeyPost_0

> map[string]interface{} RotateApiKeyAuthRotateKeyPost_0(ctx).KeyRotationRequest(keyRotationRequest).Execute()

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
	keyRotationRequest := *openapiclient.NewKeyRotationRequest("OldKey_example", "NewKey_example") // KeyRotationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.RotateApiKeyAuthRotateKeyPost_0(context.Background()).KeyRotationRequest(keyRotationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.RotateApiKeyAuthRotateKeyPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateApiKeyAuthRotateKeyPost_0`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.RotateApiKeyAuthRotateKeyPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRotateApiKeyAuthRotateKeyPost_9Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **keyRotationRequest** | [**KeyRotationRequest**](KeyRotationRequest.md) |  | 

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

