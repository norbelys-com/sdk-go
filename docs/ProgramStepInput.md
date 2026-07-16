# ProgramStepInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AbMinSample** | Pointer to **int32** | Minimum sends before a winner can be decided. | [optional] 
**AbMode** | Pointer to **string** | How the A/B winner is decided: manual, even, ai_percentage. | [optional] 
**AbTestPct** | Pointer to **int32** | Percent of leads in the test group while the A/B test holds. | [optional] 
**AbWinningMetric** | Pointer to **string** | Metric the winner is decided by: reply, positive_reply, click, open. | [optional] 
**Channel** | Pointer to **string** | Send channel for this step; defaults to &#x60;email&#x60;. | [optional] 
**OrderIdx** | Pointer to **int32** | Position in the cadence (0-based); defaults to array order. | [optional] 
**WaitDays** | Pointer to **int32** | Days to wait after the previous step before this one sends. | [optional] 
**AbWinnerVariantId** | Pointer to **NullableString** |  | [optional] 
**Archived** | Pointer to **bool** | Set true (with id) to archive this step. | [optional] 
**Id** | Pointer to **string** | Existing step id to edit; omit to create a new step. | [optional] 
**Variants** | Pointer to [**[]ProgramVariantInput**](ProgramVariantInput.md) | The step&#39;s arms — one for a plain step, several for an A/B test. | [optional] 

## Methods

### NewProgramStepInput

`func NewProgramStepInput() *ProgramStepInput`

NewProgramStepInput instantiates a new ProgramStepInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramStepInputWithDefaults

`func NewProgramStepInputWithDefaults() *ProgramStepInput`

NewProgramStepInputWithDefaults instantiates a new ProgramStepInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbMinSample

`func (o *ProgramStepInput) GetAbMinSample() int32`

GetAbMinSample returns the AbMinSample field if non-nil, zero value otherwise.

### GetAbMinSampleOk

`func (o *ProgramStepInput) GetAbMinSampleOk() (*int32, bool)`

GetAbMinSampleOk returns a tuple with the AbMinSample field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbMinSample

`func (o *ProgramStepInput) SetAbMinSample(v int32)`

SetAbMinSample sets AbMinSample field to given value.

### HasAbMinSample

`func (o *ProgramStepInput) HasAbMinSample() bool`

HasAbMinSample returns a boolean if a field has been set.

### GetAbMode

`func (o *ProgramStepInput) GetAbMode() string`

GetAbMode returns the AbMode field if non-nil, zero value otherwise.

### GetAbModeOk

`func (o *ProgramStepInput) GetAbModeOk() (*string, bool)`

GetAbModeOk returns a tuple with the AbMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbMode

`func (o *ProgramStepInput) SetAbMode(v string)`

SetAbMode sets AbMode field to given value.

### HasAbMode

`func (o *ProgramStepInput) HasAbMode() bool`

HasAbMode returns a boolean if a field has been set.

### GetAbTestPct

`func (o *ProgramStepInput) GetAbTestPct() int32`

GetAbTestPct returns the AbTestPct field if non-nil, zero value otherwise.

### GetAbTestPctOk

`func (o *ProgramStepInput) GetAbTestPctOk() (*int32, bool)`

GetAbTestPctOk returns a tuple with the AbTestPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbTestPct

`func (o *ProgramStepInput) SetAbTestPct(v int32)`

SetAbTestPct sets AbTestPct field to given value.

### HasAbTestPct

`func (o *ProgramStepInput) HasAbTestPct() bool`

HasAbTestPct returns a boolean if a field has been set.

### GetAbWinningMetric

`func (o *ProgramStepInput) GetAbWinningMetric() string`

GetAbWinningMetric returns the AbWinningMetric field if non-nil, zero value otherwise.

### GetAbWinningMetricOk

`func (o *ProgramStepInput) GetAbWinningMetricOk() (*string, bool)`

GetAbWinningMetricOk returns a tuple with the AbWinningMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbWinningMetric

`func (o *ProgramStepInput) SetAbWinningMetric(v string)`

SetAbWinningMetric sets AbWinningMetric field to given value.

### HasAbWinningMetric

`func (o *ProgramStepInput) HasAbWinningMetric() bool`

HasAbWinningMetric returns a boolean if a field has been set.

### GetChannel

`func (o *ProgramStepInput) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *ProgramStepInput) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *ProgramStepInput) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *ProgramStepInput) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetOrderIdx

`func (o *ProgramStepInput) GetOrderIdx() int32`

GetOrderIdx returns the OrderIdx field if non-nil, zero value otherwise.

### GetOrderIdxOk

`func (o *ProgramStepInput) GetOrderIdxOk() (*int32, bool)`

GetOrderIdxOk returns a tuple with the OrderIdx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderIdx

`func (o *ProgramStepInput) SetOrderIdx(v int32)`

SetOrderIdx sets OrderIdx field to given value.

### HasOrderIdx

`func (o *ProgramStepInput) HasOrderIdx() bool`

HasOrderIdx returns a boolean if a field has been set.

### GetWaitDays

`func (o *ProgramStepInput) GetWaitDays() int32`

GetWaitDays returns the WaitDays field if non-nil, zero value otherwise.

### GetWaitDaysOk

`func (o *ProgramStepInput) GetWaitDaysOk() (*int32, bool)`

GetWaitDaysOk returns a tuple with the WaitDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitDays

`func (o *ProgramStepInput) SetWaitDays(v int32)`

SetWaitDays sets WaitDays field to given value.

### HasWaitDays

`func (o *ProgramStepInput) HasWaitDays() bool`

HasWaitDays returns a boolean if a field has been set.

### GetAbWinnerVariantId

`func (o *ProgramStepInput) GetAbWinnerVariantId() string`

GetAbWinnerVariantId returns the AbWinnerVariantId field if non-nil, zero value otherwise.

### GetAbWinnerVariantIdOk

`func (o *ProgramStepInput) GetAbWinnerVariantIdOk() (*string, bool)`

GetAbWinnerVariantIdOk returns a tuple with the AbWinnerVariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbWinnerVariantId

`func (o *ProgramStepInput) SetAbWinnerVariantId(v string)`

SetAbWinnerVariantId sets AbWinnerVariantId field to given value.

### HasAbWinnerVariantId

`func (o *ProgramStepInput) HasAbWinnerVariantId() bool`

HasAbWinnerVariantId returns a boolean if a field has been set.

### SetAbWinnerVariantIdNil

`func (o *ProgramStepInput) SetAbWinnerVariantIdNil(b bool)`

 SetAbWinnerVariantIdNil sets the value for AbWinnerVariantId to be an explicit nil

### UnsetAbWinnerVariantId
`func (o *ProgramStepInput) UnsetAbWinnerVariantId()`

UnsetAbWinnerVariantId ensures that no value is present for AbWinnerVariantId, not even an explicit nil
### GetArchived

`func (o *ProgramStepInput) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *ProgramStepInput) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *ProgramStepInput) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *ProgramStepInput) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetId

`func (o *ProgramStepInput) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProgramStepInput) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProgramStepInput) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProgramStepInput) HasId() bool`

HasId returns a boolean if a field has been set.

### GetVariants

`func (o *ProgramStepInput) GetVariants() []ProgramVariantInput`

GetVariants returns the Variants field if non-nil, zero value otherwise.

### GetVariantsOk

`func (o *ProgramStepInput) GetVariantsOk() (*[]ProgramVariantInput, bool)`

GetVariantsOk returns a tuple with the Variants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariants

`func (o *ProgramStepInput) SetVariants(v []ProgramVariantInput)`

SetVariants sets Variants field to given value.

### HasVariants

`func (o *ProgramStepInput) HasVariants() bool`

HasVariants returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


