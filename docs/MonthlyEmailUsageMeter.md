# MonthlyEmailUsageMeter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Level** | **string** | &#x60;ok&#x60;, &#x60;near&#x60; (~80% of the cap used) or &#x60;reached&#x60; (at/over the cap). Example: &#x60;near&#x60;. | 
**Limit** | **NullableInt32** |  | 
**Used** | **int32** | Current usage against the cap. Example: 4. | 
**Month** | **string** | UTC calendar month being counted. Example: \&quot;2026-07\&quot;. | 

## Methods

### NewMonthlyEmailUsageMeter

`func NewMonthlyEmailUsageMeter(level string, limit NullableInt32, used int32, month string, ) *MonthlyEmailUsageMeter`

NewMonthlyEmailUsageMeter instantiates a new MonthlyEmailUsageMeter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMonthlyEmailUsageMeterWithDefaults

`func NewMonthlyEmailUsageMeterWithDefaults() *MonthlyEmailUsageMeter`

NewMonthlyEmailUsageMeterWithDefaults instantiates a new MonthlyEmailUsageMeter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLevel

`func (o *MonthlyEmailUsageMeter) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *MonthlyEmailUsageMeter) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *MonthlyEmailUsageMeter) SetLevel(v string)`

SetLevel sets Level field to given value.


### GetLimit

`func (o *MonthlyEmailUsageMeter) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *MonthlyEmailUsageMeter) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *MonthlyEmailUsageMeter) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### SetLimitNil

`func (o *MonthlyEmailUsageMeter) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *MonthlyEmailUsageMeter) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUsed

`func (o *MonthlyEmailUsageMeter) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *MonthlyEmailUsageMeter) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *MonthlyEmailUsageMeter) SetUsed(v int32)`

SetUsed sets Used field to given value.


### GetMonth

`func (o *MonthlyEmailUsageMeter) GetMonth() string`

GetMonth returns the Month field if non-nil, zero value otherwise.

### GetMonthOk

`func (o *MonthlyEmailUsageMeter) GetMonthOk() (*string, bool)`

GetMonthOk returns a tuple with the Month field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonth

`func (o *MonthlyEmailUsageMeter) SetMonth(v string)`

SetMonth sets Month field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


