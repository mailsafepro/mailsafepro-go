# KeyRotationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OldKey** | **string** | Current API key to rotate from | 
**NewKey** | **string** | New API key to rotate to | 
**GracePeriod** | Pointer to **int32** | Grace period in seconds (max 30 days) | [optional] [default to 86400]

## Methods

### NewKeyRotationRequest

`func NewKeyRotationRequest(oldKey string, newKey string, ) *KeyRotationRequest`

NewKeyRotationRequest instantiates a new KeyRotationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKeyRotationRequestWithDefaults

`func NewKeyRotationRequestWithDefaults() *KeyRotationRequest`

NewKeyRotationRequestWithDefaults instantiates a new KeyRotationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOldKey

`func (o *KeyRotationRequest) GetOldKey() string`

GetOldKey returns the OldKey field if non-nil, zero value otherwise.

### GetOldKeyOk

`func (o *KeyRotationRequest) GetOldKeyOk() (*string, bool)`

GetOldKeyOk returns a tuple with the OldKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldKey

`func (o *KeyRotationRequest) SetOldKey(v string)`

SetOldKey sets OldKey field to given value.


### GetNewKey

`func (o *KeyRotationRequest) GetNewKey() string`

GetNewKey returns the NewKey field if non-nil, zero value otherwise.

### GetNewKeyOk

`func (o *KeyRotationRequest) GetNewKeyOk() (*string, bool)`

GetNewKeyOk returns a tuple with the NewKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewKey

`func (o *KeyRotationRequest) SetNewKey(v string)`

SetNewKey sets NewKey field to given value.


### GetGracePeriod

`func (o *KeyRotationRequest) GetGracePeriod() int32`

GetGracePeriod returns the GracePeriod field if non-nil, zero value otherwise.

### GetGracePeriodOk

`func (o *KeyRotationRequest) GetGracePeriodOk() (*int32, bool)`

GetGracePeriodOk returns a tuple with the GracePeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGracePeriod

`func (o *KeyRotationRequest) SetGracePeriod(v int32)`

SetGracePeriod sets GracePeriod field to given value.

### HasGracePeriod

`func (o *KeyRotationRequest) HasGracePeriod() bool`

HasGracePeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


