# ProgramPauseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rate** | **float32** | The measured rate that tripped the pause, as a percent. | 
**Threshold** | **float32** | The threshold it crossed, as a percent. | 

## Methods

### NewProgramPauseMeta

`func NewProgramPauseMeta(rate float32, threshold float32, ) *ProgramPauseMeta`

NewProgramPauseMeta instantiates a new ProgramPauseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramPauseMetaWithDefaults

`func NewProgramPauseMetaWithDefaults() *ProgramPauseMeta`

NewProgramPauseMetaWithDefaults instantiates a new ProgramPauseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRate

`func (o *ProgramPauseMeta) GetRate() float32`

GetRate returns the Rate field if non-nil, zero value otherwise.

### GetRateOk

`func (o *ProgramPauseMeta) GetRateOk() (*float32, bool)`

GetRateOk returns a tuple with the Rate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRate

`func (o *ProgramPauseMeta) SetRate(v float32)`

SetRate sets Rate field to given value.


### GetThreshold

`func (o *ProgramPauseMeta) GetThreshold() float32`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *ProgramPauseMeta) GetThresholdOk() (*float32, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *ProgramPauseMeta) SetThreshold(v float32)`

SetThreshold sets Threshold field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


