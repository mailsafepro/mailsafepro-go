# \DefaultAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AskGeminiGeminiGet**](DefaultAPI.md#AskGeminiGeminiGet) | **Get** /gemini | Ask Gemini
[**RunAuditAdminAuditProjectPost**](DefaultAPI.md#RunAuditAdminAuditProjectPost) | **Post** /admin/audit_project | Run Audit



## AskGeminiGeminiGet

> interface{} AskGeminiGeminiGet(ctx).Prompt(prompt).Execute()

Ask Gemini



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
	prompt := "prompt_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.AskGeminiGeminiGet(context.Background()).Prompt(prompt).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.AskGeminiGeminiGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AskGeminiGeminiGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.AskGeminiGeminiGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAskGeminiGeminiGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **prompt** | **string** |  | 

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


## RunAuditAdminAuditProjectPost

> interface{} RunAuditAdminAuditProjectPost(ctx).Path(path).XAuditToken(xAuditToken).Execute()

Run Audit



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
	path := "path_example" // string |  (optional) (default to ".")
	xAuditToken := "xAuditToken_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RunAuditAdminAuditProjectPost(context.Background()).Path(path).XAuditToken(xAuditToken).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RunAuditAdminAuditProjectPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunAuditAdminAuditProjectPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RunAuditAdminAuditProjectPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRunAuditAdminAuditProjectPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **path** | **string** |  | [default to &quot;.&quot;]
 **xAuditToken** | **string** |  | 

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

