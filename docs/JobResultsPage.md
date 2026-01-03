# JobResultsPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobId** | **string** |  | 
**Page** | **int32** |  | 
**Size** | **int32** |  | 
**TotalPages** | **int32** |  | 
**Results** | [**[]JobResultEntry**](JobResultEntry.md) |  | 

## Methods

### NewJobResultsPage

`func NewJobResultsPage(jobId string, page int32, size int32, totalPages int32, results []JobResultEntry, ) *JobResultsPage`

NewJobResultsPage instantiates a new JobResultsPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobResultsPageWithDefaults

`func NewJobResultsPageWithDefaults() *JobResultsPage`

NewJobResultsPageWithDefaults instantiates a new JobResultsPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobId

`func (o *JobResultsPage) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *JobResultsPage) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *JobResultsPage) SetJobId(v string)`

SetJobId sets JobId field to given value.


### GetPage

`func (o *JobResultsPage) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *JobResultsPage) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *JobResultsPage) SetPage(v int32)`

SetPage sets Page field to given value.


### GetSize

`func (o *JobResultsPage) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *JobResultsPage) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *JobResultsPage) SetSize(v int32)`

SetSize sets Size field to given value.


### GetTotalPages

`func (o *JobResultsPage) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *JobResultsPage) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *JobResultsPage) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.


### GetResults

`func (o *JobResultsPage) GetResults() []JobResultEntry`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *JobResultsPage) GetResultsOk() (*[]JobResultEntry, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *JobResultsPage) SetResults(v []JobResultEntry)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


