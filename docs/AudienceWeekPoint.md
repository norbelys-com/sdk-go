# AudienceWeekPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Period** | **string** | ISO date (YYYY-MM-DD) for the Monday starting this week. | 
**Value** | **int32** | Current audience members created during this week. | 

## Methods

### NewAudienceWeekPoint

`func NewAudienceWeekPoint(period string, value int32, ) *AudienceWeekPoint`

NewAudienceWeekPoint instantiates a new AudienceWeekPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceWeekPointWithDefaults

`func NewAudienceWeekPointWithDefaults() *AudienceWeekPoint`

NewAudienceWeekPointWithDefaults instantiates a new AudienceWeekPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriod

`func (o *AudienceWeekPoint) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AudienceWeekPoint) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AudienceWeekPoint) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetValue

`func (o *AudienceWeekPoint) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AudienceWeekPoint) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AudienceWeekPoint) SetValue(v int32)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


