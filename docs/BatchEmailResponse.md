# BatchEmailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | Total emails processed | 
**ValidCount** | **int32** | Number of valid emails | 
**InvalidCount** | **int32** | Number of invalid emails | 
**ProcessingTime** | **float32** | Total processing time in seconds | 
**AverageTime** | **float32** | Average processing time per email | 
**Results** | [**[]EmailResponse**](EmailResponse.md) | Individual validation results | 

## Methods

### NewBatchEmailResponse

`func NewBatchEmailResponse(count int32, validCount int32, invalidCount int32, processingTime float32, averageTime float32, results []EmailResponse, ) *BatchEmailResponse`

NewBatchEmailResponse instantiates a new BatchEmailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchEmailResponseWithDefaults

`func NewBatchEmailResponseWithDefaults() *BatchEmailResponse`

NewBatchEmailResponseWithDefaults instantiates a new BatchEmailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *BatchEmailResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *BatchEmailResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *BatchEmailResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetValidCount

`func (o *BatchEmailResponse) GetValidCount() int32`

GetValidCount returns the ValidCount field if non-nil, zero value otherwise.

### GetValidCountOk

`func (o *BatchEmailResponse) GetValidCountOk() (*int32, bool)`

GetValidCountOk returns a tuple with the ValidCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidCount

`func (o *BatchEmailResponse) SetValidCount(v int32)`

SetValidCount sets ValidCount field to given value.


### GetInvalidCount

`func (o *BatchEmailResponse) GetInvalidCount() int32`

GetInvalidCount returns the InvalidCount field if non-nil, zero value otherwise.

### GetInvalidCountOk

`func (o *BatchEmailResponse) GetInvalidCountOk() (*int32, bool)`

GetInvalidCountOk returns a tuple with the InvalidCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidCount

`func (o *BatchEmailResponse) SetInvalidCount(v int32)`

SetInvalidCount sets InvalidCount field to given value.


### GetProcessingTime

`func (o *BatchEmailResponse) GetProcessingTime() float32`

GetProcessingTime returns the ProcessingTime field if non-nil, zero value otherwise.

### GetProcessingTimeOk

`func (o *BatchEmailResponse) GetProcessingTimeOk() (*float32, bool)`

GetProcessingTimeOk returns a tuple with the ProcessingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTime

`func (o *BatchEmailResponse) SetProcessingTime(v float32)`

SetProcessingTime sets ProcessingTime field to given value.


### GetAverageTime

`func (o *BatchEmailResponse) GetAverageTime() float32`

GetAverageTime returns the AverageTime field if non-nil, zero value otherwise.

### GetAverageTimeOk

`func (o *BatchEmailResponse) GetAverageTimeOk() (*float32, bool)`

GetAverageTimeOk returns a tuple with the AverageTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageTime

`func (o *BatchEmailResponse) SetAverageTime(v float32)`

SetAverageTime sets AverageTime field to given value.


### GetResults

`func (o *BatchEmailResponse) GetResults() []EmailResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *BatchEmailResponse) GetResultsOk() (*[]EmailResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *BatchEmailResponse) SetResults(v []EmailResponse)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


