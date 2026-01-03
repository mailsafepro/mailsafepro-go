# DNSInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Spf** | Pointer to [**NullableDNSRecordSPF**](DNSRecordSPF.md) |  | [optional] 
**Dkim** | Pointer to [**NullableDNSRecordDKIM**](DNSRecordDKIM.md) |  | [optional] 
**Dmarc** | Pointer to [**NullableDNSRecordDMARC**](DNSRecordDMARC.md) |  | [optional] 
**MxRecords** | Pointer to **[]string** | MX records | [optional] 
**NsRecords** | Pointer to **[]string** | Name servers | [optional] 

## Methods

### NewDNSInfo

`func NewDNSInfo() *DNSInfo`

NewDNSInfo instantiates a new DNSInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDNSInfoWithDefaults

`func NewDNSInfoWithDefaults() *DNSInfo`

NewDNSInfoWithDefaults instantiates a new DNSInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSpf

`func (o *DNSInfo) GetSpf() DNSRecordSPF`

GetSpf returns the Spf field if non-nil, zero value otherwise.

### GetSpfOk

`func (o *DNSInfo) GetSpfOk() (*DNSRecordSPF, bool)`

GetSpfOk returns a tuple with the Spf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpf

`func (o *DNSInfo) SetSpf(v DNSRecordSPF)`

SetSpf sets Spf field to given value.

### HasSpf

`func (o *DNSInfo) HasSpf() bool`

HasSpf returns a boolean if a field has been set.

### SetSpfNil

`func (o *DNSInfo) SetSpfNil(b bool)`

 SetSpfNil sets the value for Spf to be an explicit nil

### UnsetSpf
`func (o *DNSInfo) UnsetSpf()`

UnsetSpf ensures that no value is present for Spf, not even an explicit nil
### GetDkim

`func (o *DNSInfo) GetDkim() DNSRecordDKIM`

GetDkim returns the Dkim field if non-nil, zero value otherwise.

### GetDkimOk

`func (o *DNSInfo) GetDkimOk() (*DNSRecordDKIM, bool)`

GetDkimOk returns a tuple with the Dkim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDkim

`func (o *DNSInfo) SetDkim(v DNSRecordDKIM)`

SetDkim sets Dkim field to given value.

### HasDkim

`func (o *DNSInfo) HasDkim() bool`

HasDkim returns a boolean if a field has been set.

### SetDkimNil

`func (o *DNSInfo) SetDkimNil(b bool)`

 SetDkimNil sets the value for Dkim to be an explicit nil

### UnsetDkim
`func (o *DNSInfo) UnsetDkim()`

UnsetDkim ensures that no value is present for Dkim, not even an explicit nil
### GetDmarc

`func (o *DNSInfo) GetDmarc() DNSRecordDMARC`

GetDmarc returns the Dmarc field if non-nil, zero value otherwise.

### GetDmarcOk

`func (o *DNSInfo) GetDmarcOk() (*DNSRecordDMARC, bool)`

GetDmarcOk returns a tuple with the Dmarc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDmarc

`func (o *DNSInfo) SetDmarc(v DNSRecordDMARC)`

SetDmarc sets Dmarc field to given value.

### HasDmarc

`func (o *DNSInfo) HasDmarc() bool`

HasDmarc returns a boolean if a field has been set.

### SetDmarcNil

`func (o *DNSInfo) SetDmarcNil(b bool)`

 SetDmarcNil sets the value for Dmarc to be an explicit nil

### UnsetDmarc
`func (o *DNSInfo) UnsetDmarc()`

UnsetDmarc ensures that no value is present for Dmarc, not even an explicit nil
### GetMxRecords

`func (o *DNSInfo) GetMxRecords() []string`

GetMxRecords returns the MxRecords field if non-nil, zero value otherwise.

### GetMxRecordsOk

`func (o *DNSInfo) GetMxRecordsOk() (*[]string, bool)`

GetMxRecordsOk returns a tuple with the MxRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMxRecords

`func (o *DNSInfo) SetMxRecords(v []string)`

SetMxRecords sets MxRecords field to given value.

### HasMxRecords

`func (o *DNSInfo) HasMxRecords() bool`

HasMxRecords returns a boolean if a field has been set.

### GetNsRecords

`func (o *DNSInfo) GetNsRecords() []string`

GetNsRecords returns the NsRecords field if non-nil, zero value otherwise.

### GetNsRecordsOk

`func (o *DNSInfo) GetNsRecordsOk() (*[]string, bool)`

GetNsRecordsOk returns a tuple with the NsRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNsRecords

`func (o *DNSInfo) SetNsRecords(v []string)`

SetNsRecords sets NsRecords field to given value.

### HasNsRecords

`func (o *DNSInfo) HasNsRecords() bool`

HasNsRecords returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


