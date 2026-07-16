# WarmupTodayTally

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Failed** | **int32** | Warmup sends that failed today. | 
**Planned** | **int32** | Warmup sends planned for today. | 
**Sent** | **int32** | Warmup sends completed today. | 

## Methods

### NewWarmupTodayTally

`func NewWarmupTodayTally(failed int32, planned int32, sent int32, ) *WarmupTodayTally`

NewWarmupTodayTally instantiates a new WarmupTodayTally object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarmupTodayTallyWithDefaults

`func NewWarmupTodayTallyWithDefaults() *WarmupTodayTally`

NewWarmupTodayTallyWithDefaults instantiates a new WarmupTodayTally object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFailed

`func (o *WarmupTodayTally) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *WarmupTodayTally) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *WarmupTodayTally) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetPlanned

`func (o *WarmupTodayTally) GetPlanned() int32`

GetPlanned returns the Planned field if non-nil, zero value otherwise.

### GetPlannedOk

`func (o *WarmupTodayTally) GetPlannedOk() (*int32, bool)`

GetPlannedOk returns a tuple with the Planned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanned

`func (o *WarmupTodayTally) SetPlanned(v int32)`

SetPlanned sets Planned field to given value.


### GetSent

`func (o *WarmupTodayTally) GetSent() int32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *WarmupTodayTally) GetSentOk() (*int32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *WarmupTodayTally) SetSent(v int32)`

SetSent sets Sent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


