# JobResultEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**Valid** | **bool** |  | 
**Riskscore** | Pointer to **NullableFloat32** |  | [optional] 
**Qualityscore** | Pointer to **NullableFloat32** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**Reputation** | Pointer to **NullableFloat32** |  | [optional] 
**Smtp** | Pointer to **map[string]interface{}** |  | [optional] 
**Dns** | Pointer to **map[string]interface{}** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewJobResultEntry

`func NewJobResultEntry(email string, valid bool, ) *JobResultEntry`

NewJobResultEntry instantiates a new JobResultEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobResultEntryWithDefaults

`func NewJobResultEntryWithDefaults() *JobResultEntry`

NewJobResultEntryWithDefaults instantiates a new JobResultEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *JobResultEntry) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *JobResultEntry) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *JobResultEntry) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetValid

`func (o *JobResultEntry) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *JobResultEntry) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *JobResultEntry) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetRiskscore

`func (o *JobResultEntry) GetRiskscore() float32`

GetRiskscore returns the Riskscore field if non-nil, zero value otherwise.

### GetRiskscoreOk

`func (o *JobResultEntry) GetRiskscoreOk() (*float32, bool)`

GetRiskscoreOk returns a tuple with the Riskscore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskscore

`func (o *JobResultEntry) SetRiskscore(v float32)`

SetRiskscore sets Riskscore field to given value.

### HasRiskscore

`func (o *JobResultEntry) HasRiskscore() bool`

HasRiskscore returns a boolean if a field has been set.

### SetRiskscoreNil

`func (o *JobResultEntry) SetRiskscoreNil(b bool)`

 SetRiskscoreNil sets the value for Riskscore to be an explicit nil

### UnsetRiskscore
`func (o *JobResultEntry) UnsetRiskscore()`

UnsetRiskscore ensures that no value is present for Riskscore, not even an explicit nil
### GetQualityscore

`func (o *JobResultEntry) GetQualityscore() float32`

GetQualityscore returns the Qualityscore field if non-nil, zero value otherwise.

### GetQualityscoreOk

`func (o *JobResultEntry) GetQualityscoreOk() (*float32, bool)`

GetQualityscoreOk returns a tuple with the Qualityscore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualityscore

`func (o *JobResultEntry) SetQualityscore(v float32)`

SetQualityscore sets Qualityscore field to given value.

### HasQualityscore

`func (o *JobResultEntry) HasQualityscore() bool`

HasQualityscore returns a boolean if a field has been set.

### SetQualityscoreNil

`func (o *JobResultEntry) SetQualityscoreNil(b bool)`

 SetQualityscoreNil sets the value for Qualityscore to be an explicit nil

### UnsetQualityscore
`func (o *JobResultEntry) UnsetQualityscore()`

UnsetQualityscore ensures that no value is present for Qualityscore, not even an explicit nil
### GetProvider

`func (o *JobResultEntry) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *JobResultEntry) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *JobResultEntry) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *JobResultEntry) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *JobResultEntry) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *JobResultEntry) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetReputation

`func (o *JobResultEntry) GetReputation() float32`

GetReputation returns the Reputation field if non-nil, zero value otherwise.

### GetReputationOk

`func (o *JobResultEntry) GetReputationOk() (*float32, bool)`

GetReputationOk returns a tuple with the Reputation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputation

`func (o *JobResultEntry) SetReputation(v float32)`

SetReputation sets Reputation field to given value.

### HasReputation

`func (o *JobResultEntry) HasReputation() bool`

HasReputation returns a boolean if a field has been set.

### SetReputationNil

`func (o *JobResultEntry) SetReputationNil(b bool)`

 SetReputationNil sets the value for Reputation to be an explicit nil

### UnsetReputation
`func (o *JobResultEntry) UnsetReputation()`

UnsetReputation ensures that no value is present for Reputation, not even an explicit nil
### GetSmtp

`func (o *JobResultEntry) GetSmtp() map[string]interface{}`

GetSmtp returns the Smtp field if non-nil, zero value otherwise.

### GetSmtpOk

`func (o *JobResultEntry) GetSmtpOk() (*map[string]interface{}, bool)`

GetSmtpOk returns a tuple with the Smtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtp

`func (o *JobResultEntry) SetSmtp(v map[string]interface{})`

SetSmtp sets Smtp field to given value.

### HasSmtp

`func (o *JobResultEntry) HasSmtp() bool`

HasSmtp returns a boolean if a field has been set.

### GetDns

`func (o *JobResultEntry) GetDns() map[string]interface{}`

GetDns returns the Dns field if non-nil, zero value otherwise.

### GetDnsOk

`func (o *JobResultEntry) GetDnsOk() (*map[string]interface{}, bool)`

GetDnsOk returns a tuple with the Dns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDns

`func (o *JobResultEntry) SetDns(v map[string]interface{})`

SetDns sets Dns field to given value.

### HasDns

`func (o *JobResultEntry) HasDns() bool`

HasDns returns a boolean if a field has been set.

### GetMetadata

`func (o *JobResultEntry) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *JobResultEntry) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *JobResultEntry) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *JobResultEntry) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


