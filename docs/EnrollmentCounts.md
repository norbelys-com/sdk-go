# EnrollmentCounts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | **int32** | Active leads. | 
**Bounced** | **int32** | Leads that bounced. | 
**ByStep** | Pointer to **map[string]int32** | Active leads waiting at each cadence step (&#x60;currentStepId&#x60; → count) — who sits between which emails right now. | [optional] 
**Cancelled** | **int32** | Leads whose run was cancelled by archiving the campaign. | 
**Finished** | **int32** | Leads that finished the cadence. | 
**InProgress** | **int32** | Active leads mid-cadence. | 
**NextSendAt** | Pointer to **interface{}** |  | [optional] 
**NotStarted** | **int32** | Active leads not yet contacted. | 
**Paused** | **int32** | Paused leads. | 
**Replied** | **int32** | Leads that replied. | 
**Skipped** | **int32** | Leads skipped because they were suppressed at send time. | 
**Stopped** | **int32** | Leads pulled out by an engagement stop (open/click). | 
**Total** | **int32** | All enrollments in scope. | 
**Unsubscribed** | **int32** | Leads that unsubscribed. | 

## Methods

### NewEnrollmentCounts

`func NewEnrollmentCounts(active int32, bounced int32, cancelled int32, finished int32, inProgress int32, notStarted int32, paused int32, replied int32, skipped int32, stopped int32, total int32, unsubscribed int32, ) *EnrollmentCounts`

NewEnrollmentCounts instantiates a new EnrollmentCounts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrollmentCountsWithDefaults

`func NewEnrollmentCountsWithDefaults() *EnrollmentCounts`

NewEnrollmentCountsWithDefaults instantiates a new EnrollmentCounts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *EnrollmentCounts) GetActive() int32`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EnrollmentCounts) GetActiveOk() (*int32, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EnrollmentCounts) SetActive(v int32)`

SetActive sets Active field to given value.


### GetBounced

`func (o *EnrollmentCounts) GetBounced() int32`

GetBounced returns the Bounced field if non-nil, zero value otherwise.

### GetBouncedOk

`func (o *EnrollmentCounts) GetBouncedOk() (*int32, bool)`

GetBouncedOk returns a tuple with the Bounced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBounced

`func (o *EnrollmentCounts) SetBounced(v int32)`

SetBounced sets Bounced field to given value.


### GetByStep

`func (o *EnrollmentCounts) GetByStep() map[string]int32`

GetByStep returns the ByStep field if non-nil, zero value otherwise.

### GetByStepOk

`func (o *EnrollmentCounts) GetByStepOk() (*map[string]int32, bool)`

GetByStepOk returns a tuple with the ByStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByStep

`func (o *EnrollmentCounts) SetByStep(v map[string]int32)`

SetByStep sets ByStep field to given value.

### HasByStep

`func (o *EnrollmentCounts) HasByStep() bool`

HasByStep returns a boolean if a field has been set.

### GetCancelled

`func (o *EnrollmentCounts) GetCancelled() int32`

GetCancelled returns the Cancelled field if non-nil, zero value otherwise.

### GetCancelledOk

`func (o *EnrollmentCounts) GetCancelledOk() (*int32, bool)`

GetCancelledOk returns a tuple with the Cancelled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelled

`func (o *EnrollmentCounts) SetCancelled(v int32)`

SetCancelled sets Cancelled field to given value.


### GetFinished

`func (o *EnrollmentCounts) GetFinished() int32`

GetFinished returns the Finished field if non-nil, zero value otherwise.

### GetFinishedOk

`func (o *EnrollmentCounts) GetFinishedOk() (*int32, bool)`

GetFinishedOk returns a tuple with the Finished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinished

`func (o *EnrollmentCounts) SetFinished(v int32)`

SetFinished sets Finished field to given value.


### GetInProgress

`func (o *EnrollmentCounts) GetInProgress() int32`

GetInProgress returns the InProgress field if non-nil, zero value otherwise.

### GetInProgressOk

`func (o *EnrollmentCounts) GetInProgressOk() (*int32, bool)`

GetInProgressOk returns a tuple with the InProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInProgress

`func (o *EnrollmentCounts) SetInProgress(v int32)`

SetInProgress sets InProgress field to given value.


### GetNextSendAt

`func (o *EnrollmentCounts) GetNextSendAt() interface{}`

GetNextSendAt returns the NextSendAt field if non-nil, zero value otherwise.

### GetNextSendAtOk

`func (o *EnrollmentCounts) GetNextSendAtOk() (*interface{}, bool)`

GetNextSendAtOk returns a tuple with the NextSendAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextSendAt

`func (o *EnrollmentCounts) SetNextSendAt(v interface{})`

SetNextSendAt sets NextSendAt field to given value.

### HasNextSendAt

`func (o *EnrollmentCounts) HasNextSendAt() bool`

HasNextSendAt returns a boolean if a field has been set.

### SetNextSendAtNil

`func (o *EnrollmentCounts) SetNextSendAtNil(b bool)`

 SetNextSendAtNil sets the value for NextSendAt to be an explicit nil

### UnsetNextSendAt
`func (o *EnrollmentCounts) UnsetNextSendAt()`

UnsetNextSendAt ensures that no value is present for NextSendAt, not even an explicit nil
### GetNotStarted

`func (o *EnrollmentCounts) GetNotStarted() int32`

GetNotStarted returns the NotStarted field if non-nil, zero value otherwise.

### GetNotStartedOk

`func (o *EnrollmentCounts) GetNotStartedOk() (*int32, bool)`

GetNotStartedOk returns a tuple with the NotStarted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotStarted

`func (o *EnrollmentCounts) SetNotStarted(v int32)`

SetNotStarted sets NotStarted field to given value.


### GetPaused

`func (o *EnrollmentCounts) GetPaused() int32`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *EnrollmentCounts) GetPausedOk() (*int32, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *EnrollmentCounts) SetPaused(v int32)`

SetPaused sets Paused field to given value.


### GetReplied

`func (o *EnrollmentCounts) GetReplied() int32`

GetReplied returns the Replied field if non-nil, zero value otherwise.

### GetRepliedOk

`func (o *EnrollmentCounts) GetRepliedOk() (*int32, bool)`

GetRepliedOk returns a tuple with the Replied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplied

`func (o *EnrollmentCounts) SetReplied(v int32)`

SetReplied sets Replied field to given value.


### GetSkipped

`func (o *EnrollmentCounts) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *EnrollmentCounts) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *EnrollmentCounts) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.


### GetStopped

`func (o *EnrollmentCounts) GetStopped() int32`

GetStopped returns the Stopped field if non-nil, zero value otherwise.

### GetStoppedOk

`func (o *EnrollmentCounts) GetStoppedOk() (*int32, bool)`

GetStoppedOk returns a tuple with the Stopped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopped

`func (o *EnrollmentCounts) SetStopped(v int32)`

SetStopped sets Stopped field to given value.


### GetTotal

`func (o *EnrollmentCounts) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *EnrollmentCounts) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *EnrollmentCounts) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetUnsubscribed

`func (o *EnrollmentCounts) GetUnsubscribed() int32`

GetUnsubscribed returns the Unsubscribed field if non-nil, zero value otherwise.

### GetUnsubscribedOk

`func (o *EnrollmentCounts) GetUnsubscribedOk() (*int32, bool)`

GetUnsubscribedOk returns a tuple with the Unsubscribed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribed

`func (o *EnrollmentCounts) SetUnsubscribed(v int32)`

SetUnsubscribed sets Unsubscribed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


