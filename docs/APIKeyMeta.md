# APIKeyMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique key identifier | 
**KeyHash** | **string** | Hashed key value | 
**Plan** | [**PlanEnum**](PlanEnum.md) | Associated plan | 
**CreatedAt** | **time.Time** | Creation timestamp | 
**Revoked** | **bool** | Revocation status | 
**RevokedAt** | Pointer to **NullableTime** |  | [optional] 
**Scopes** | Pointer to **[]string** | Access scopes | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**LastUsed** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewAPIKeyMeta

`func NewAPIKeyMeta(id string, keyHash string, plan PlanEnum, createdAt time.Time, revoked bool, ) *APIKeyMeta`

NewAPIKeyMeta instantiates a new APIKeyMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyMetaWithDefaults

`func NewAPIKeyMetaWithDefaults() *APIKeyMeta`

NewAPIKeyMetaWithDefaults instantiates a new APIKeyMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *APIKeyMeta) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *APIKeyMeta) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *APIKeyMeta) SetId(v string)`

SetId sets Id field to given value.


### GetKeyHash

`func (o *APIKeyMeta) GetKeyHash() string`

GetKeyHash returns the KeyHash field if non-nil, zero value otherwise.

### GetKeyHashOk

`func (o *APIKeyMeta) GetKeyHashOk() (*string, bool)`

GetKeyHashOk returns a tuple with the KeyHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyHash

`func (o *APIKeyMeta) SetKeyHash(v string)`

SetKeyHash sets KeyHash field to given value.


### GetPlan

`func (o *APIKeyMeta) GetPlan() PlanEnum`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *APIKeyMeta) GetPlanOk() (*PlanEnum, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *APIKeyMeta) SetPlan(v PlanEnum)`

SetPlan sets Plan field to given value.


### GetCreatedAt

`func (o *APIKeyMeta) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *APIKeyMeta) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *APIKeyMeta) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetRevoked

`func (o *APIKeyMeta) GetRevoked() bool`

GetRevoked returns the Revoked field if non-nil, zero value otherwise.

### GetRevokedOk

`func (o *APIKeyMeta) GetRevokedOk() (*bool, bool)`

GetRevokedOk returns a tuple with the Revoked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevoked

`func (o *APIKeyMeta) SetRevoked(v bool)`

SetRevoked sets Revoked field to given value.


### GetRevokedAt

`func (o *APIKeyMeta) GetRevokedAt() time.Time`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *APIKeyMeta) GetRevokedAtOk() (*time.Time, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *APIKeyMeta) SetRevokedAt(v time.Time)`

SetRevokedAt sets RevokedAt field to given value.

### HasRevokedAt

`func (o *APIKeyMeta) HasRevokedAt() bool`

HasRevokedAt returns a boolean if a field has been set.

### SetRevokedAtNil

`func (o *APIKeyMeta) SetRevokedAtNil(b bool)`

 SetRevokedAtNil sets the value for RevokedAt to be an explicit nil

### UnsetRevokedAt
`func (o *APIKeyMeta) UnsetRevokedAt()`

UnsetRevokedAt ensures that no value is present for RevokedAt, not even an explicit nil
### GetScopes

`func (o *APIKeyMeta) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *APIKeyMeta) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *APIKeyMeta) SetScopes(v []string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *APIKeyMeta) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### GetName

`func (o *APIKeyMeta) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *APIKeyMeta) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *APIKeyMeta) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *APIKeyMeta) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *APIKeyMeta) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *APIKeyMeta) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetLastUsed

`func (o *APIKeyMeta) GetLastUsed() time.Time`

GetLastUsed returns the LastUsed field if non-nil, zero value otherwise.

### GetLastUsedOk

`func (o *APIKeyMeta) GetLastUsedOk() (*time.Time, bool)`

GetLastUsedOk returns a tuple with the LastUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsed

`func (o *APIKeyMeta) SetLastUsed(v time.Time)`

SetLastUsed sets LastUsed field to given value.

### HasLastUsed

`func (o *APIKeyMeta) HasLastUsed() bool`

HasLastUsed returns a boolean if a field has been set.

### SetLastUsedNil

`func (o *APIKeyMeta) SetLastUsedNil(b bool)`

 SetLastUsedNil sets the value for LastUsed to be an explicit nil

### UnsetLastUsed
`func (o *APIKeyMeta) UnsetLastUsed()`

UnsetLastUsed ensures that no value is present for LastUsed, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


