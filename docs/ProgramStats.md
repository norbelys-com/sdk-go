# ProgramStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Completion** | **float32** | Fraction of leads in a terminal state (0-1). | 
**LeadCount** | **int32** | Live (non-archived) enrollments. | 
**NextSendAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewProgramStats

`func NewProgramStats(completion float32, leadCount int32, ) *ProgramStats`

NewProgramStats instantiates a new ProgramStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramStatsWithDefaults

`func NewProgramStatsWithDefaults() *ProgramStats`

NewProgramStatsWithDefaults instantiates a new ProgramStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletion

`func (o *ProgramStats) GetCompletion() float32`

GetCompletion returns the Completion field if non-nil, zero value otherwise.

### GetCompletionOk

`func (o *ProgramStats) GetCompletionOk() (*float32, bool)`

GetCompletionOk returns a tuple with the Completion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletion

`func (o *ProgramStats) SetCompletion(v float32)`

SetCompletion sets Completion field to given value.


### GetLeadCount

`func (o *ProgramStats) GetLeadCount() int32`

GetLeadCount returns the LeadCount field if non-nil, zero value otherwise.

### GetLeadCountOk

`func (o *ProgramStats) GetLeadCountOk() (*int32, bool)`

GetLeadCountOk returns a tuple with the LeadCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadCount

`func (o *ProgramStats) SetLeadCount(v int32)`

SetLeadCount sets LeadCount field to given value.


### GetNextSendAt

`func (o *ProgramStats) GetNextSendAt() interface{}`

GetNextSendAt returns the NextSendAt field if non-nil, zero value otherwise.

### GetNextSendAtOk

`func (o *ProgramStats) GetNextSendAtOk() (*interface{}, bool)`

GetNextSendAtOk returns a tuple with the NextSendAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextSendAt

`func (o *ProgramStats) SetNextSendAt(v interface{})`

SetNextSendAt sets NextSendAt field to given value.

### HasNextSendAt

`func (o *ProgramStats) HasNextSendAt() bool`

HasNextSendAt returns a boolean if a field has been set.

### SetNextSendAtNil

`func (o *ProgramStats) SetNextSendAtNil(b bool)`

 SetNextSendAtNil sets the value for NextSendAt to be an explicit nil

### UnsetNextSendAt
`func (o *ProgramStats) UnsetNextSendAt()`

UnsetNextSendAt ensures that no value is present for NextSendAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


