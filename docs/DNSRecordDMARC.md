# DNSRecordDMARC

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **NullableString** |  | [optional] 
**Policy** | Pointer to **NullableString** |  | [optional] 
**Record** | Pointer to **NullableString** |  | [optional] 
**Pct** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewDNSRecordDMARC

`func NewDNSRecordDMARC() *DNSRecordDMARC`

NewDNSRecordDMARC instantiates a new DNSRecordDMARC object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDNSRecordDMARCWithDefaults

`func NewDNSRecordDMARCWithDefaults() *DNSRecordDMARC`

NewDNSRecordDMARCWithDefaults instantiates a new DNSRecordDMARC object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *DNSRecordDMARC) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DNSRecordDMARC) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DNSRecordDMARC) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DNSRecordDMARC) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *DNSRecordDMARC) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *DNSRecordDMARC) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetPolicy

`func (o *DNSRecordDMARC) GetPolicy() string`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *DNSRecordDMARC) GetPolicyOk() (*string, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *DNSRecordDMARC) SetPolicy(v string)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *DNSRecordDMARC) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### SetPolicyNil

`func (o *DNSRecordDMARC) SetPolicyNil(b bool)`

 SetPolicyNil sets the value for Policy to be an explicit nil

### UnsetPolicy
`func (o *DNSRecordDMARC) UnsetPolicy()`

UnsetPolicy ensures that no value is present for Policy, not even an explicit nil
### GetRecord

`func (o *DNSRecordDMARC) GetRecord() string`

GetRecord returns the Record field if non-nil, zero value otherwise.

### GetRecordOk

`func (o *DNSRecordDMARC) GetRecordOk() (*string, bool)`

GetRecordOk returns a tuple with the Record field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecord

`func (o *DNSRecordDMARC) SetRecord(v string)`

SetRecord sets Record field to given value.

### HasRecord

`func (o *DNSRecordDMARC) HasRecord() bool`

HasRecord returns a boolean if a field has been set.

### SetRecordNil

`func (o *DNSRecordDMARC) SetRecordNil(b bool)`

 SetRecordNil sets the value for Record to be an explicit nil

### UnsetRecord
`func (o *DNSRecordDMARC) UnsetRecord()`

UnsetRecord ensures that no value is present for Record, not even an explicit nil
### GetPct

`func (o *DNSRecordDMARC) GetPct() int32`

GetPct returns the Pct field if non-nil, zero value otherwise.

### GetPctOk

`func (o *DNSRecordDMARC) GetPctOk() (*int32, bool)`

GetPctOk returns a tuple with the Pct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPct

`func (o *DNSRecordDMARC) SetPct(v int32)`

SetPct sets Pct field to given value.

### HasPct

`func (o *DNSRecordDMARC) HasPct() bool`

HasPct returns a boolean if a field has been set.

### SetPctNil

`func (o *DNSRecordDMARC) SetPctNil(b bool)`

 SetPctNil sets the value for Pct to be an explicit nil

### UnsetPct
`func (o *DNSRecordDMARC) UnsetPct()`

UnsetPct ensures that no value is present for Pct, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


