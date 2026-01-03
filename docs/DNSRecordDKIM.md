# DNSRecordDKIM

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **NullableString** |  | [optional] 
**Selector** | Pointer to **NullableString** |  | [optional] 
**KeyType** | Pointer to **NullableString** |  | [optional] 
**KeyLength** | Pointer to **NullableInt32** |  | [optional] 
**Record** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDNSRecordDKIM

`func NewDNSRecordDKIM() *DNSRecordDKIM`

NewDNSRecordDKIM instantiates a new DNSRecordDKIM object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDNSRecordDKIMWithDefaults

`func NewDNSRecordDKIMWithDefaults() *DNSRecordDKIM`

NewDNSRecordDKIMWithDefaults instantiates a new DNSRecordDKIM object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *DNSRecordDKIM) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DNSRecordDKIM) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DNSRecordDKIM) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DNSRecordDKIM) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *DNSRecordDKIM) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *DNSRecordDKIM) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSelector

`func (o *DNSRecordDKIM) GetSelector() string`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *DNSRecordDKIM) GetSelectorOk() (*string, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *DNSRecordDKIM) SetSelector(v string)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *DNSRecordDKIM) HasSelector() bool`

HasSelector returns a boolean if a field has been set.

### SetSelectorNil

`func (o *DNSRecordDKIM) SetSelectorNil(b bool)`

 SetSelectorNil sets the value for Selector to be an explicit nil

### UnsetSelector
`func (o *DNSRecordDKIM) UnsetSelector()`

UnsetSelector ensures that no value is present for Selector, not even an explicit nil
### GetKeyType

`func (o *DNSRecordDKIM) GetKeyType() string`

GetKeyType returns the KeyType field if non-nil, zero value otherwise.

### GetKeyTypeOk

`func (o *DNSRecordDKIM) GetKeyTypeOk() (*string, bool)`

GetKeyTypeOk returns a tuple with the KeyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyType

`func (o *DNSRecordDKIM) SetKeyType(v string)`

SetKeyType sets KeyType field to given value.

### HasKeyType

`func (o *DNSRecordDKIM) HasKeyType() bool`

HasKeyType returns a boolean if a field has been set.

### SetKeyTypeNil

`func (o *DNSRecordDKIM) SetKeyTypeNil(b bool)`

 SetKeyTypeNil sets the value for KeyType to be an explicit nil

### UnsetKeyType
`func (o *DNSRecordDKIM) UnsetKeyType()`

UnsetKeyType ensures that no value is present for KeyType, not even an explicit nil
### GetKeyLength

`func (o *DNSRecordDKIM) GetKeyLength() int32`

GetKeyLength returns the KeyLength field if non-nil, zero value otherwise.

### GetKeyLengthOk

`func (o *DNSRecordDKIM) GetKeyLengthOk() (*int32, bool)`

GetKeyLengthOk returns a tuple with the KeyLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyLength

`func (o *DNSRecordDKIM) SetKeyLength(v int32)`

SetKeyLength sets KeyLength field to given value.

### HasKeyLength

`func (o *DNSRecordDKIM) HasKeyLength() bool`

HasKeyLength returns a boolean if a field has been set.

### SetKeyLengthNil

`func (o *DNSRecordDKIM) SetKeyLengthNil(b bool)`

 SetKeyLengthNil sets the value for KeyLength to be an explicit nil

### UnsetKeyLength
`func (o *DNSRecordDKIM) UnsetKeyLength()`

UnsetKeyLength ensures that no value is present for KeyLength, not even an explicit nil
### GetRecord

`func (o *DNSRecordDKIM) GetRecord() string`

GetRecord returns the Record field if non-nil, zero value otherwise.

### GetRecordOk

`func (o *DNSRecordDKIM) GetRecordOk() (*string, bool)`

GetRecordOk returns a tuple with the Record field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecord

`func (o *DNSRecordDKIM) SetRecord(v string)`

SetRecord sets Record field to given value.

### HasRecord

`func (o *DNSRecordDKIM) HasRecord() bool`

HasRecord returns a boolean if a field has been set.

### SetRecordNil

`func (o *DNSRecordDKIM) SetRecordNil(b bool)`

 SetRecordNil sets the value for Record to be an explicit nil

### UnsetRecord
`func (o *DNSRecordDKIM) UnsetRecord()`

UnsetRecord ensures that no value is present for Record, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


