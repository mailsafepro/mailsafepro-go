# BatchValidationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Emails** | **[]string** | List of email addresses to validate (can include invalid formats) | 
**CheckSmtp** | Pointer to **bool** | Perform SMTP verification for all emails | [optional] [default to false]
**IncludeRawDns** | Pointer to **bool** | Include raw DNS records in responses | [optional] [default to false]
**BatchSize** | Pointer to **int32** | Number of emails to process in each batch | [optional] [default to 100]
**ConcurrentRequests** | Pointer to **int32** | Maximum concurrent validation requests | [optional] [default to 5]

## Methods

### NewBatchValidationRequest

`func NewBatchValidationRequest(emails []string, ) *BatchValidationRequest`

NewBatchValidationRequest instantiates a new BatchValidationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchValidationRequestWithDefaults

`func NewBatchValidationRequestWithDefaults() *BatchValidationRequest`

NewBatchValidationRequestWithDefaults instantiates a new BatchValidationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmails

`func (o *BatchValidationRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *BatchValidationRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *BatchValidationRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.


### GetCheckSmtp

`func (o *BatchValidationRequest) GetCheckSmtp() bool`

GetCheckSmtp returns the CheckSmtp field if non-nil, zero value otherwise.

### GetCheckSmtpOk

`func (o *BatchValidationRequest) GetCheckSmtpOk() (*bool, bool)`

GetCheckSmtpOk returns a tuple with the CheckSmtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckSmtp

`func (o *BatchValidationRequest) SetCheckSmtp(v bool)`

SetCheckSmtp sets CheckSmtp field to given value.

### HasCheckSmtp

`func (o *BatchValidationRequest) HasCheckSmtp() bool`

HasCheckSmtp returns a boolean if a field has been set.

### GetIncludeRawDns

`func (o *BatchValidationRequest) GetIncludeRawDns() bool`

GetIncludeRawDns returns the IncludeRawDns field if non-nil, zero value otherwise.

### GetIncludeRawDnsOk

`func (o *BatchValidationRequest) GetIncludeRawDnsOk() (*bool, bool)`

GetIncludeRawDnsOk returns a tuple with the IncludeRawDns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeRawDns

`func (o *BatchValidationRequest) SetIncludeRawDns(v bool)`

SetIncludeRawDns sets IncludeRawDns field to given value.

### HasIncludeRawDns

`func (o *BatchValidationRequest) HasIncludeRawDns() bool`

HasIncludeRawDns returns a boolean if a field has been set.

### GetBatchSize

`func (o *BatchValidationRequest) GetBatchSize() int32`

GetBatchSize returns the BatchSize field if non-nil, zero value otherwise.

### GetBatchSizeOk

`func (o *BatchValidationRequest) GetBatchSizeOk() (*int32, bool)`

GetBatchSizeOk returns a tuple with the BatchSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchSize

`func (o *BatchValidationRequest) SetBatchSize(v int32)`

SetBatchSize sets BatchSize field to given value.

### HasBatchSize

`func (o *BatchValidationRequest) HasBatchSize() bool`

HasBatchSize returns a boolean if a field has been set.

### GetConcurrentRequests

`func (o *BatchValidationRequest) GetConcurrentRequests() int32`

GetConcurrentRequests returns the ConcurrentRequests field if non-nil, zero value otherwise.

### GetConcurrentRequestsOk

`func (o *BatchValidationRequest) GetConcurrentRequestsOk() (*int32, bool)`

GetConcurrentRequestsOk returns a tuple with the ConcurrentRequests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConcurrentRequests

`func (o *BatchValidationRequest) SetConcurrentRequests(v int32)`

SetConcurrentRequests sets ConcurrentRequests field to given value.

### HasConcurrentRequests

`func (o *BatchValidationRequest) HasConcurrentRequests() bool`

HasConcurrentRequests returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


