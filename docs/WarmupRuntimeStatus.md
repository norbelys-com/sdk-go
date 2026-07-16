# WarmupRuntimeStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveConversations** | **int32** | Warmup conversations currently in flight for this mailbox. | 
**CohortId** | **NullableString** |  | 
**CohortSize** | **int32** | Number of peer mailboxes in the current cohort (0–10). | 
**Health** | **string** | Engine-computed warmup health: &#x60;healthy&#x60;, &#x60;degraded&#x60;, &#x60;saturated&#x60;, &#x60;auth_broken&#x60;, &#x60;bouncing&#x60;, or &#x60;insufficient_peers&#x60;. | 
**NextRotationAt** | Pointer to **interface{}** |  | [optional] 
**Phase** | **string** | Current warmup lifecycle phase: &#x60;pending&#x60;, &#x60;stable&#x60;, &#x60;rotating&#x60;, &#x60;paused&#x60;, or &#x60;blocked&#x60;. | 
**RampDay** | **int32** | How many days into the warmup ramp this mailbox has progressed. | 
**Today** | [**WarmupTodayTally**](WarmupTodayTally.md) |  | 

## Methods

### NewWarmupRuntimeStatus

`func NewWarmupRuntimeStatus(activeConversations int32, cohortId NullableString, cohortSize int32, health string, phase string, rampDay int32, today WarmupTodayTally, ) *WarmupRuntimeStatus`

NewWarmupRuntimeStatus instantiates a new WarmupRuntimeStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarmupRuntimeStatusWithDefaults

`func NewWarmupRuntimeStatusWithDefaults() *WarmupRuntimeStatus`

NewWarmupRuntimeStatusWithDefaults instantiates a new WarmupRuntimeStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveConversations

`func (o *WarmupRuntimeStatus) GetActiveConversations() int32`

GetActiveConversations returns the ActiveConversations field if non-nil, zero value otherwise.

### GetActiveConversationsOk

`func (o *WarmupRuntimeStatus) GetActiveConversationsOk() (*int32, bool)`

GetActiveConversationsOk returns a tuple with the ActiveConversations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveConversations

`func (o *WarmupRuntimeStatus) SetActiveConversations(v int32)`

SetActiveConversations sets ActiveConversations field to given value.


### GetCohortId

`func (o *WarmupRuntimeStatus) GetCohortId() string`

GetCohortId returns the CohortId field if non-nil, zero value otherwise.

### GetCohortIdOk

`func (o *WarmupRuntimeStatus) GetCohortIdOk() (*string, bool)`

GetCohortIdOk returns a tuple with the CohortId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCohortId

`func (o *WarmupRuntimeStatus) SetCohortId(v string)`

SetCohortId sets CohortId field to given value.


### SetCohortIdNil

`func (o *WarmupRuntimeStatus) SetCohortIdNil(b bool)`

 SetCohortIdNil sets the value for CohortId to be an explicit nil

### UnsetCohortId
`func (o *WarmupRuntimeStatus) UnsetCohortId()`

UnsetCohortId ensures that no value is present for CohortId, not even an explicit nil
### GetCohortSize

`func (o *WarmupRuntimeStatus) GetCohortSize() int32`

GetCohortSize returns the CohortSize field if non-nil, zero value otherwise.

### GetCohortSizeOk

`func (o *WarmupRuntimeStatus) GetCohortSizeOk() (*int32, bool)`

GetCohortSizeOk returns a tuple with the CohortSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCohortSize

`func (o *WarmupRuntimeStatus) SetCohortSize(v int32)`

SetCohortSize sets CohortSize field to given value.


### GetHealth

`func (o *WarmupRuntimeStatus) GetHealth() string`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *WarmupRuntimeStatus) GetHealthOk() (*string, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *WarmupRuntimeStatus) SetHealth(v string)`

SetHealth sets Health field to given value.


### GetNextRotationAt

`func (o *WarmupRuntimeStatus) GetNextRotationAt() interface{}`

GetNextRotationAt returns the NextRotationAt field if non-nil, zero value otherwise.

### GetNextRotationAtOk

`func (o *WarmupRuntimeStatus) GetNextRotationAtOk() (*interface{}, bool)`

GetNextRotationAtOk returns a tuple with the NextRotationAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRotationAt

`func (o *WarmupRuntimeStatus) SetNextRotationAt(v interface{})`

SetNextRotationAt sets NextRotationAt field to given value.

### HasNextRotationAt

`func (o *WarmupRuntimeStatus) HasNextRotationAt() bool`

HasNextRotationAt returns a boolean if a field has been set.

### SetNextRotationAtNil

`func (o *WarmupRuntimeStatus) SetNextRotationAtNil(b bool)`

 SetNextRotationAtNil sets the value for NextRotationAt to be an explicit nil

### UnsetNextRotationAt
`func (o *WarmupRuntimeStatus) UnsetNextRotationAt()`

UnsetNextRotationAt ensures that no value is present for NextRotationAt, not even an explicit nil
### GetPhase

`func (o *WarmupRuntimeStatus) GetPhase() string`

GetPhase returns the Phase field if non-nil, zero value otherwise.

### GetPhaseOk

`func (o *WarmupRuntimeStatus) GetPhaseOk() (*string, bool)`

GetPhaseOk returns a tuple with the Phase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhase

`func (o *WarmupRuntimeStatus) SetPhase(v string)`

SetPhase sets Phase field to given value.


### GetRampDay

`func (o *WarmupRuntimeStatus) GetRampDay() int32`

GetRampDay returns the RampDay field if non-nil, zero value otherwise.

### GetRampDayOk

`func (o *WarmupRuntimeStatus) GetRampDayOk() (*int32, bool)`

GetRampDayOk returns a tuple with the RampDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRampDay

`func (o *WarmupRuntimeStatus) SetRampDay(v int32)`

SetRampDay sets RampDay field to given value.


### GetToday

`func (o *WarmupRuntimeStatus) GetToday() WarmupTodayTally`

GetToday returns the Today field if non-nil, zero value otherwise.

### GetTodayOk

`func (o *WarmupRuntimeStatus) GetTodayOk() (*WarmupTodayTally, bool)`

GetTodayOk returns a tuple with the Today field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToday

`func (o *WarmupRuntimeStatus) SetToday(v WarmupTodayTally)`

SetToday sets Today field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


