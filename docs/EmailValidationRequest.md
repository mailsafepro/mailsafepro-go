# EmailValidationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | Email address to validate (RFC 5321 compliant) | 
**CheckSmtp** | Pointer to **bool** | Enable SMTP mailbox verification | [optional] [default to false]
**IncludeRawDns** | Pointer to **bool** | Include raw DNS records | [optional] [default to false]
**TestingMode** | Pointer to **bool** | Enable testing mode (allows special TLDs like .test, .example, etc.) | [optional] [default to false]
**Priority** | Pointer to [**PriorityEnum**](PriorityEnum.md) | Validation priority level | [optional] [default to STANDARD]

## Methods

### NewEmailValidationRequest

`func NewEmailValidationRequest(email string, ) *EmailValidationRequest`

NewEmailValidationRequest instantiates a new EmailValidationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailValidationRequestWithDefaults

`func NewEmailValidationRequestWithDefaults() *EmailValidationRequest`

NewEmailValidationRequestWithDefaults instantiates a new EmailValidationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *EmailValidationRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmailValidationRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmailValidationRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetCheckSmtp

`func (o *EmailValidationRequest) GetCheckSmtp() bool`

GetCheckSmtp returns the CheckSmtp field if non-nil, zero value otherwise.

### GetCheckSmtpOk

`func (o *EmailValidationRequest) GetCheckSmtpOk() (*bool, bool)`

GetCheckSmtpOk returns a tuple with the CheckSmtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckSmtp

`func (o *EmailValidationRequest) SetCheckSmtp(v bool)`

SetCheckSmtp sets CheckSmtp field to given value.

### HasCheckSmtp

`func (o *EmailValidationRequest) HasCheckSmtp() bool`

HasCheckSmtp returns a boolean if a field has been set.

### GetIncludeRawDns

`func (o *EmailValidationRequest) GetIncludeRawDns() bool`

GetIncludeRawDns returns the IncludeRawDns field if non-nil, zero value otherwise.

### GetIncludeRawDnsOk

`func (o *EmailValidationRequest) GetIncludeRawDnsOk() (*bool, bool)`

GetIncludeRawDnsOk returns a tuple with the IncludeRawDns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeRawDns

`func (o *EmailValidationRequest) SetIncludeRawDns(v bool)`

SetIncludeRawDns sets IncludeRawDns field to given value.

### HasIncludeRawDns

`func (o *EmailValidationRequest) HasIncludeRawDns() bool`

HasIncludeRawDns returns a boolean if a field has been set.

### GetTestingMode

`func (o *EmailValidationRequest) GetTestingMode() bool`

GetTestingMode returns the TestingMode field if non-nil, zero value otherwise.

### GetTestingModeOk

`func (o *EmailValidationRequest) GetTestingModeOk() (*bool, bool)`

GetTestingModeOk returns a tuple with the TestingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTestingMode

`func (o *EmailValidationRequest) SetTestingMode(v bool)`

SetTestingMode sets TestingMode field to given value.

### HasTestingMode

`func (o *EmailValidationRequest) HasTestingMode() bool`

HasTestingMode returns a boolean if a field has been set.

### GetPriority

`func (o *EmailValidationRequest) GetPriority() PriorityEnum`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *EmailValidationRequest) GetPriorityOk() (*PriorityEnum, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *EmailValidationRequest) SetPriority(v PriorityEnum)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *EmailValidationRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


