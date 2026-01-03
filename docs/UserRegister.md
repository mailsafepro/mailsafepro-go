# UserRegister

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | User email address | 
**Password** | **string** | User password | 
**Plan** | Pointer to [**PlanEnum**](PlanEnum.md) | Subscription plan | [optional] [default to FREE]

## Methods

### NewUserRegister

`func NewUserRegister(email string, password string, ) *UserRegister`

NewUserRegister instantiates a new UserRegister object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserRegisterWithDefaults

`func NewUserRegisterWithDefaults() *UserRegister`

NewUserRegisterWithDefaults instantiates a new UserRegister object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *UserRegister) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserRegister) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserRegister) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetPassword

`func (o *UserRegister) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserRegister) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserRegister) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetPlan

`func (o *UserRegister) GetPlan() PlanEnum`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *UserRegister) GetPlanOk() (*PlanEnum, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *UserRegister) SetPlan(v PlanEnum)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *UserRegister) HasPlan() bool`

HasPlan returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


