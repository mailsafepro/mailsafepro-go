# EmailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | Validated email address | 
**Valid** | **bool** | Overall validation result | 
**Detail** | Pointer to **string** | Validation details summary | [optional] [default to ""]
**ProcessingTime** | Pointer to **NullableFloat32** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**Reputation** | Pointer to **NullableFloat32** |  | [optional] 
**Fingerprint** | Pointer to **NullableString** |  | [optional] 
**QualityScore** | Pointer to **NullableFloat32** |  | [optional] 
**RiskLevel** | Pointer to [**NullableRiskLevelEnum**](RiskLevelEnum.md) |  | [optional] 
**Suggestions** | Pointer to **[]string** | Improvement suggestions | [optional] 
**Smtp** | Pointer to [**NullableSMTPInfo**](SMTPInfo.md) |  | [optional] 
**Dns** | Pointer to [**NullableDNSInfo**](DNSInfo.md) |  | [optional] 
**RiskScore** | Pointer to **NullableFloat32** |  | [optional] 
**ValidationTier** | Pointer to **NullableString** |  | [optional] 
**SuggestedAction** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewEmailResponse

`func NewEmailResponse(email string, valid bool, ) *EmailResponse`

NewEmailResponse instantiates a new EmailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailResponseWithDefaults

`func NewEmailResponseWithDefaults() *EmailResponse`

NewEmailResponseWithDefaults instantiates a new EmailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *EmailResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmailResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmailResponse) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetValid

`func (o *EmailResponse) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *EmailResponse) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *EmailResponse) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetDetail

`func (o *EmailResponse) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *EmailResponse) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *EmailResponse) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *EmailResponse) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### GetProcessingTime

`func (o *EmailResponse) GetProcessingTime() float32`

GetProcessingTime returns the ProcessingTime field if non-nil, zero value otherwise.

### GetProcessingTimeOk

`func (o *EmailResponse) GetProcessingTimeOk() (*float32, bool)`

GetProcessingTimeOk returns a tuple with the ProcessingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTime

`func (o *EmailResponse) SetProcessingTime(v float32)`

SetProcessingTime sets ProcessingTime field to given value.

### HasProcessingTime

`func (o *EmailResponse) HasProcessingTime() bool`

HasProcessingTime returns a boolean if a field has been set.

### SetProcessingTimeNil

`func (o *EmailResponse) SetProcessingTimeNil(b bool)`

 SetProcessingTimeNil sets the value for ProcessingTime to be an explicit nil

### UnsetProcessingTime
`func (o *EmailResponse) UnsetProcessingTime()`

UnsetProcessingTime ensures that no value is present for ProcessingTime, not even an explicit nil
### GetProvider

`func (o *EmailResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *EmailResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *EmailResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *EmailResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *EmailResponse) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *EmailResponse) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetReputation

`func (o *EmailResponse) GetReputation() float32`

GetReputation returns the Reputation field if non-nil, zero value otherwise.

### GetReputationOk

`func (o *EmailResponse) GetReputationOk() (*float32, bool)`

GetReputationOk returns a tuple with the Reputation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputation

`func (o *EmailResponse) SetReputation(v float32)`

SetReputation sets Reputation field to given value.

### HasReputation

`func (o *EmailResponse) HasReputation() bool`

HasReputation returns a boolean if a field has been set.

### SetReputationNil

`func (o *EmailResponse) SetReputationNil(b bool)`

 SetReputationNil sets the value for Reputation to be an explicit nil

### UnsetReputation
`func (o *EmailResponse) UnsetReputation()`

UnsetReputation ensures that no value is present for Reputation, not even an explicit nil
### GetFingerprint

`func (o *EmailResponse) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *EmailResponse) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *EmailResponse) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.

### HasFingerprint

`func (o *EmailResponse) HasFingerprint() bool`

HasFingerprint returns a boolean if a field has been set.

### SetFingerprintNil

`func (o *EmailResponse) SetFingerprintNil(b bool)`

 SetFingerprintNil sets the value for Fingerprint to be an explicit nil

### UnsetFingerprint
`func (o *EmailResponse) UnsetFingerprint()`

UnsetFingerprint ensures that no value is present for Fingerprint, not even an explicit nil
### GetQualityScore

`func (o *EmailResponse) GetQualityScore() float32`

GetQualityScore returns the QualityScore field if non-nil, zero value otherwise.

### GetQualityScoreOk

`func (o *EmailResponse) GetQualityScoreOk() (*float32, bool)`

GetQualityScoreOk returns a tuple with the QualityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualityScore

`func (o *EmailResponse) SetQualityScore(v float32)`

SetQualityScore sets QualityScore field to given value.

### HasQualityScore

`func (o *EmailResponse) HasQualityScore() bool`

HasQualityScore returns a boolean if a field has been set.

### SetQualityScoreNil

`func (o *EmailResponse) SetQualityScoreNil(b bool)`

 SetQualityScoreNil sets the value for QualityScore to be an explicit nil

### UnsetQualityScore
`func (o *EmailResponse) UnsetQualityScore()`

UnsetQualityScore ensures that no value is present for QualityScore, not even an explicit nil
### GetRiskLevel

`func (o *EmailResponse) GetRiskLevel() RiskLevelEnum`

GetRiskLevel returns the RiskLevel field if non-nil, zero value otherwise.

### GetRiskLevelOk

`func (o *EmailResponse) GetRiskLevelOk() (*RiskLevelEnum, bool)`

GetRiskLevelOk returns a tuple with the RiskLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskLevel

`func (o *EmailResponse) SetRiskLevel(v RiskLevelEnum)`

SetRiskLevel sets RiskLevel field to given value.

### HasRiskLevel

`func (o *EmailResponse) HasRiskLevel() bool`

HasRiskLevel returns a boolean if a field has been set.

### SetRiskLevelNil

`func (o *EmailResponse) SetRiskLevelNil(b bool)`

 SetRiskLevelNil sets the value for RiskLevel to be an explicit nil

### UnsetRiskLevel
`func (o *EmailResponse) UnsetRiskLevel()`

UnsetRiskLevel ensures that no value is present for RiskLevel, not even an explicit nil
### GetSuggestions

`func (o *EmailResponse) GetSuggestions() []string`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *EmailResponse) GetSuggestionsOk() (*[]string, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *EmailResponse) SetSuggestions(v []string)`

SetSuggestions sets Suggestions field to given value.

### HasSuggestions

`func (o *EmailResponse) HasSuggestions() bool`

HasSuggestions returns a boolean if a field has been set.

### GetSmtp

`func (o *EmailResponse) GetSmtp() SMTPInfo`

GetSmtp returns the Smtp field if non-nil, zero value otherwise.

### GetSmtpOk

`func (o *EmailResponse) GetSmtpOk() (*SMTPInfo, bool)`

GetSmtpOk returns a tuple with the Smtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtp

`func (o *EmailResponse) SetSmtp(v SMTPInfo)`

SetSmtp sets Smtp field to given value.

### HasSmtp

`func (o *EmailResponse) HasSmtp() bool`

HasSmtp returns a boolean if a field has been set.

### SetSmtpNil

`func (o *EmailResponse) SetSmtpNil(b bool)`

 SetSmtpNil sets the value for Smtp to be an explicit nil

### UnsetSmtp
`func (o *EmailResponse) UnsetSmtp()`

UnsetSmtp ensures that no value is present for Smtp, not even an explicit nil
### GetDns

`func (o *EmailResponse) GetDns() DNSInfo`

GetDns returns the Dns field if non-nil, zero value otherwise.

### GetDnsOk

`func (o *EmailResponse) GetDnsOk() (*DNSInfo, bool)`

GetDnsOk returns a tuple with the Dns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDns

`func (o *EmailResponse) SetDns(v DNSInfo)`

SetDns sets Dns field to given value.

### HasDns

`func (o *EmailResponse) HasDns() bool`

HasDns returns a boolean if a field has been set.

### SetDnsNil

`func (o *EmailResponse) SetDnsNil(b bool)`

 SetDnsNil sets the value for Dns to be an explicit nil

### UnsetDns
`func (o *EmailResponse) UnsetDns()`

UnsetDns ensures that no value is present for Dns, not even an explicit nil
### GetRiskScore

`func (o *EmailResponse) GetRiskScore() float32`

GetRiskScore returns the RiskScore field if non-nil, zero value otherwise.

### GetRiskScoreOk

`func (o *EmailResponse) GetRiskScoreOk() (*float32, bool)`

GetRiskScoreOk returns a tuple with the RiskScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskScore

`func (o *EmailResponse) SetRiskScore(v float32)`

SetRiskScore sets RiskScore field to given value.

### HasRiskScore

`func (o *EmailResponse) HasRiskScore() bool`

HasRiskScore returns a boolean if a field has been set.

### SetRiskScoreNil

`func (o *EmailResponse) SetRiskScoreNil(b bool)`

 SetRiskScoreNil sets the value for RiskScore to be an explicit nil

### UnsetRiskScore
`func (o *EmailResponse) UnsetRiskScore()`

UnsetRiskScore ensures that no value is present for RiskScore, not even an explicit nil
### GetValidationTier

`func (o *EmailResponse) GetValidationTier() string`

GetValidationTier returns the ValidationTier field if non-nil, zero value otherwise.

### GetValidationTierOk

`func (o *EmailResponse) GetValidationTierOk() (*string, bool)`

GetValidationTierOk returns a tuple with the ValidationTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationTier

`func (o *EmailResponse) SetValidationTier(v string)`

SetValidationTier sets ValidationTier field to given value.

### HasValidationTier

`func (o *EmailResponse) HasValidationTier() bool`

HasValidationTier returns a boolean if a field has been set.

### SetValidationTierNil

`func (o *EmailResponse) SetValidationTierNil(b bool)`

 SetValidationTierNil sets the value for ValidationTier to be an explicit nil

### UnsetValidationTier
`func (o *EmailResponse) UnsetValidationTier()`

UnsetValidationTier ensures that no value is present for ValidationTier, not even an explicit nil
### GetSuggestedAction

`func (o *EmailResponse) GetSuggestedAction() string`

GetSuggestedAction returns the SuggestedAction field if non-nil, zero value otherwise.

### GetSuggestedActionOk

`func (o *EmailResponse) GetSuggestedActionOk() (*string, bool)`

GetSuggestedActionOk returns a tuple with the SuggestedAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedAction

`func (o *EmailResponse) SetSuggestedAction(v string)`

SetSuggestedAction sets SuggestedAction field to given value.

### HasSuggestedAction

`func (o *EmailResponse) HasSuggestedAction() bool`

HasSuggestedAction returns a boolean if a field has been set.

### SetSuggestedActionNil

`func (o *EmailResponse) SetSuggestedActionNil(b bool)`

 SetSuggestedActionNil sets the value for SuggestedAction to be an explicit nil

### UnsetSuggestedAction
`func (o *EmailResponse) UnsetSuggestedAction()`

UnsetSuggestedAction ensures that no value is present for SuggestedAction, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


