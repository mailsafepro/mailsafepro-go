# SMTPInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checked** | **bool** | SMTP check was performed | 
**MailboxExists** | Pointer to **NullableBool** |  | [optional] 
**MxServer** | Pointer to **NullableString** |  | [optional] 
**ResponseTime** | Pointer to **NullableFloat32** |  | [optional] 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSMTPInfo

`func NewSMTPInfo(checked bool, ) *SMTPInfo`

NewSMTPInfo instantiates a new SMTPInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMTPInfoWithDefaults

`func NewSMTPInfoWithDefaults() *SMTPInfo`

NewSMTPInfoWithDefaults instantiates a new SMTPInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecked

`func (o *SMTPInfo) GetChecked() bool`

GetChecked returns the Checked field if non-nil, zero value otherwise.

### GetCheckedOk

`func (o *SMTPInfo) GetCheckedOk() (*bool, bool)`

GetCheckedOk returns a tuple with the Checked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecked

`func (o *SMTPInfo) SetChecked(v bool)`

SetChecked sets Checked field to given value.


### GetMailboxExists

`func (o *SMTPInfo) GetMailboxExists() bool`

GetMailboxExists returns the MailboxExists field if non-nil, zero value otherwise.

### GetMailboxExistsOk

`func (o *SMTPInfo) GetMailboxExistsOk() (*bool, bool)`

GetMailboxExistsOk returns a tuple with the MailboxExists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxExists

`func (o *SMTPInfo) SetMailboxExists(v bool)`

SetMailboxExists sets MailboxExists field to given value.

### HasMailboxExists

`func (o *SMTPInfo) HasMailboxExists() bool`

HasMailboxExists returns a boolean if a field has been set.

### SetMailboxExistsNil

`func (o *SMTPInfo) SetMailboxExistsNil(b bool)`

 SetMailboxExistsNil sets the value for MailboxExists to be an explicit nil

### UnsetMailboxExists
`func (o *SMTPInfo) UnsetMailboxExists()`

UnsetMailboxExists ensures that no value is present for MailboxExists, not even an explicit nil
### GetMxServer

`func (o *SMTPInfo) GetMxServer() string`

GetMxServer returns the MxServer field if non-nil, zero value otherwise.

### GetMxServerOk

`func (o *SMTPInfo) GetMxServerOk() (*string, bool)`

GetMxServerOk returns a tuple with the MxServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMxServer

`func (o *SMTPInfo) SetMxServer(v string)`

SetMxServer sets MxServer field to given value.

### HasMxServer

`func (o *SMTPInfo) HasMxServer() bool`

HasMxServer returns a boolean if a field has been set.

### SetMxServerNil

`func (o *SMTPInfo) SetMxServerNil(b bool)`

 SetMxServerNil sets the value for MxServer to be an explicit nil

### UnsetMxServer
`func (o *SMTPInfo) UnsetMxServer()`

UnsetMxServer ensures that no value is present for MxServer, not even an explicit nil
### GetResponseTime

`func (o *SMTPInfo) GetResponseTime() float32`

GetResponseTime returns the ResponseTime field if non-nil, zero value otherwise.

### GetResponseTimeOk

`func (o *SMTPInfo) GetResponseTimeOk() (*float32, bool)`

GetResponseTimeOk returns a tuple with the ResponseTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTime

`func (o *SMTPInfo) SetResponseTime(v float32)`

SetResponseTime sets ResponseTime field to given value.

### HasResponseTime

`func (o *SMTPInfo) HasResponseTime() bool`

HasResponseTime returns a boolean if a field has been set.

### SetResponseTimeNil

`func (o *SMTPInfo) SetResponseTimeNil(b bool)`

 SetResponseTimeNil sets the value for ResponseTime to be an explicit nil

### UnsetResponseTime
`func (o *SMTPInfo) UnsetResponseTime()`

UnsetResponseTime ensures that no value is present for ResponseTime, not even an explicit nil
### GetErrorMessage

`func (o *SMTPInfo) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *SMTPInfo) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *SMTPInfo) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *SMTPInfo) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *SMTPInfo) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *SMTPInfo) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


