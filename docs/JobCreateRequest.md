# JobCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | **string** | Origen de los datos | 
**Emails** | Pointer to **[]string** |  | [optional] 
**FileToken** | Pointer to **NullableString** |  | [optional] 
**Checksmtp** | Pointer to **bool** |  | [optional] [default to false]
**Includerawdns** | Pointer to **bool** |  | [optional] [default to false]
**CallbackUrl** | Pointer to **NullableString** |  | [optional] 
**Sandbox** | Pointer to **bool** |  | [optional] [default to false]
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewJobCreateRequest

`func NewJobCreateRequest(source string, ) *JobCreateRequest`

NewJobCreateRequest instantiates a new JobCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobCreateRequestWithDefaults

`func NewJobCreateRequestWithDefaults() *JobCreateRequest`

NewJobCreateRequestWithDefaults instantiates a new JobCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *JobCreateRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *JobCreateRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *JobCreateRequest) SetSource(v string)`

SetSource sets Source field to given value.


### GetEmails

`func (o *JobCreateRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *JobCreateRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *JobCreateRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *JobCreateRequest) HasEmails() bool`

HasEmails returns a boolean if a field has been set.

### SetEmailsNil

`func (o *JobCreateRequest) SetEmailsNil(b bool)`

 SetEmailsNil sets the value for Emails to be an explicit nil

### UnsetEmails
`func (o *JobCreateRequest) UnsetEmails()`

UnsetEmails ensures that no value is present for Emails, not even an explicit nil
### GetFileToken

`func (o *JobCreateRequest) GetFileToken() string`

GetFileToken returns the FileToken field if non-nil, zero value otherwise.

### GetFileTokenOk

`func (o *JobCreateRequest) GetFileTokenOk() (*string, bool)`

GetFileTokenOk returns a tuple with the FileToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileToken

`func (o *JobCreateRequest) SetFileToken(v string)`

SetFileToken sets FileToken field to given value.

### HasFileToken

`func (o *JobCreateRequest) HasFileToken() bool`

HasFileToken returns a boolean if a field has been set.

### SetFileTokenNil

`func (o *JobCreateRequest) SetFileTokenNil(b bool)`

 SetFileTokenNil sets the value for FileToken to be an explicit nil

### UnsetFileToken
`func (o *JobCreateRequest) UnsetFileToken()`

UnsetFileToken ensures that no value is present for FileToken, not even an explicit nil
### GetChecksmtp

`func (o *JobCreateRequest) GetChecksmtp() bool`

GetChecksmtp returns the Checksmtp field if non-nil, zero value otherwise.

### GetChecksmtpOk

`func (o *JobCreateRequest) GetChecksmtpOk() (*bool, bool)`

GetChecksmtpOk returns a tuple with the Checksmtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksmtp

`func (o *JobCreateRequest) SetChecksmtp(v bool)`

SetChecksmtp sets Checksmtp field to given value.

### HasChecksmtp

`func (o *JobCreateRequest) HasChecksmtp() bool`

HasChecksmtp returns a boolean if a field has been set.

### GetIncluderawdns

`func (o *JobCreateRequest) GetIncluderawdns() bool`

GetIncluderawdns returns the Includerawdns field if non-nil, zero value otherwise.

### GetIncluderawdnsOk

`func (o *JobCreateRequest) GetIncluderawdnsOk() (*bool, bool)`

GetIncluderawdnsOk returns a tuple with the Includerawdns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncluderawdns

`func (o *JobCreateRequest) SetIncluderawdns(v bool)`

SetIncluderawdns sets Includerawdns field to given value.

### HasIncluderawdns

`func (o *JobCreateRequest) HasIncluderawdns() bool`

HasIncluderawdns returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *JobCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *JobCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *JobCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *JobCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *JobCreateRequest) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *JobCreateRequest) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetSandbox

`func (o *JobCreateRequest) GetSandbox() bool`

GetSandbox returns the Sandbox field if non-nil, zero value otherwise.

### GetSandboxOk

`func (o *JobCreateRequest) GetSandboxOk() (*bool, bool)`

GetSandboxOk returns a tuple with the Sandbox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSandbox

`func (o *JobCreateRequest) SetSandbox(v bool)`

SetSandbox sets Sandbox field to given value.

### HasSandbox

`func (o *JobCreateRequest) HasSandbox() bool`

HasSandbox returns a boolean if a field has been set.

### GetMetadata

`func (o *JobCreateRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *JobCreateRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *JobCreateRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *JobCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *JobCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *JobCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


