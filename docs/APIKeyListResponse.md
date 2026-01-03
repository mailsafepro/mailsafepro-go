# APIKeyListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Keys** | [**[]APIKeyMeta**](APIKeyMeta.md) | List of API keys | 
**TotalCount** | **int32** | Total number of keys | 
**ActiveCount** | **int32** | Number of active keys | 

## Methods

### NewAPIKeyListResponse

`func NewAPIKeyListResponse(keys []APIKeyMeta, totalCount int32, activeCount int32, ) *APIKeyListResponse`

NewAPIKeyListResponse instantiates a new APIKeyListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIKeyListResponseWithDefaults

`func NewAPIKeyListResponseWithDefaults() *APIKeyListResponse`

NewAPIKeyListResponseWithDefaults instantiates a new APIKeyListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKeys

`func (o *APIKeyListResponse) GetKeys() []APIKeyMeta`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *APIKeyListResponse) GetKeysOk() (*[]APIKeyMeta, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *APIKeyListResponse) SetKeys(v []APIKeyMeta)`

SetKeys sets Keys field to given value.


### GetTotalCount

`func (o *APIKeyListResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *APIKeyListResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *APIKeyListResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetActiveCount

`func (o *APIKeyListResponse) GetActiveCount() int32`

GetActiveCount returns the ActiveCount field if non-nil, zero value otherwise.

### GetActiveCountOk

`func (o *APIKeyListResponse) GetActiveCountOk() (*int32, bool)`

GetActiveCountOk returns a tuple with the ActiveCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveCount

`func (o *APIKeyListResponse) SetActiveCount(v int32)`

SetActiveCount sets ActiveCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


