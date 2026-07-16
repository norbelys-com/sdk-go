# StepWithVariants

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AbMinSample** | **int32** | Minimum sends before a winner can be decided. | 
**AbMode** | **string** | How the A/B winner is decided: &#x60;manual&#x60;, &#x60;even&#x60;, &#x60;ai_percentage&#x60;. | 
**AbTestPct** | **int32** | Percent of leads in the test group while the test holds. | 
**AbWinnerVariantId** | **NullableString** |  | 
**AbWinningMetric** | **string** | Metric the winner is decided by: &#x60;reply&#x60;, &#x60;positive_reply&#x60;, &#x60;click&#x60;, &#x60;open&#x60;. | 
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**Channel** | **string** | Send channel: &#x60;email&#x60;, &#x60;call&#x60;, &#x60;sms&#x60;, &#x60;linkedin&#x60;. | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The step id. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**OrderIdx** | **int32** | Position in the cadence, 0-based. | 
**ProgramId** | **string** | The owning program&#39;s id. | 
**Type** | **string** | Step type: &#x60;email&#x60;, &#x60;wait&#x60;, &#x60;condition&#x60;, &#x60;call&#x60;. | 
**WaitDays** | **int32** | Days to wait after the previous step before this one sends. | 
**Variants** | [**[]Variant**](Variant.md) | The step&#39;s live (un-archived) arms, in creation order. | 

## Methods

### NewStepWithVariants

`func NewStepWithVariants(abMinSample int32, abMode string, abTestPct int32, abWinnerVariantId NullableString, abWinningMetric string, channel string, id string, orderIdx int32, programId string, type_ string, waitDays int32, variants []Variant, ) *StepWithVariants`

NewStepWithVariants instantiates a new StepWithVariants object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStepWithVariantsWithDefaults

`func NewStepWithVariantsWithDefaults() *StepWithVariants`

NewStepWithVariantsWithDefaults instantiates a new StepWithVariants object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbMinSample

`func (o *StepWithVariants) GetAbMinSample() int32`

GetAbMinSample returns the AbMinSample field if non-nil, zero value otherwise.

### GetAbMinSampleOk

`func (o *StepWithVariants) GetAbMinSampleOk() (*int32, bool)`

GetAbMinSampleOk returns a tuple with the AbMinSample field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbMinSample

`func (o *StepWithVariants) SetAbMinSample(v int32)`

SetAbMinSample sets AbMinSample field to given value.


### GetAbMode

`func (o *StepWithVariants) GetAbMode() string`

GetAbMode returns the AbMode field if non-nil, zero value otherwise.

### GetAbModeOk

`func (o *StepWithVariants) GetAbModeOk() (*string, bool)`

GetAbModeOk returns a tuple with the AbMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbMode

`func (o *StepWithVariants) SetAbMode(v string)`

SetAbMode sets AbMode field to given value.


### GetAbTestPct

`func (o *StepWithVariants) GetAbTestPct() int32`

GetAbTestPct returns the AbTestPct field if non-nil, zero value otherwise.

### GetAbTestPctOk

`func (o *StepWithVariants) GetAbTestPctOk() (*int32, bool)`

GetAbTestPctOk returns a tuple with the AbTestPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbTestPct

`func (o *StepWithVariants) SetAbTestPct(v int32)`

SetAbTestPct sets AbTestPct field to given value.


### GetAbWinnerVariantId

`func (o *StepWithVariants) GetAbWinnerVariantId() string`

GetAbWinnerVariantId returns the AbWinnerVariantId field if non-nil, zero value otherwise.

### GetAbWinnerVariantIdOk

`func (o *StepWithVariants) GetAbWinnerVariantIdOk() (*string, bool)`

GetAbWinnerVariantIdOk returns a tuple with the AbWinnerVariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbWinnerVariantId

`func (o *StepWithVariants) SetAbWinnerVariantId(v string)`

SetAbWinnerVariantId sets AbWinnerVariantId field to given value.


### SetAbWinnerVariantIdNil

`func (o *StepWithVariants) SetAbWinnerVariantIdNil(b bool)`

 SetAbWinnerVariantIdNil sets the value for AbWinnerVariantId to be an explicit nil

### UnsetAbWinnerVariantId
`func (o *StepWithVariants) UnsetAbWinnerVariantId()`

UnsetAbWinnerVariantId ensures that no value is present for AbWinnerVariantId, not even an explicit nil
### GetAbWinningMetric

`func (o *StepWithVariants) GetAbWinningMetric() string`

GetAbWinningMetric returns the AbWinningMetric field if non-nil, zero value otherwise.

### GetAbWinningMetricOk

`func (o *StepWithVariants) GetAbWinningMetricOk() (*string, bool)`

GetAbWinningMetricOk returns a tuple with the AbWinningMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbWinningMetric

`func (o *StepWithVariants) SetAbWinningMetric(v string)`

SetAbWinningMetric sets AbWinningMetric field to given value.


### GetArchivedAt

`func (o *StepWithVariants) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *StepWithVariants) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *StepWithVariants) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *StepWithVariants) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *StepWithVariants) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *StepWithVariants) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetChannel

`func (o *StepWithVariants) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *StepWithVariants) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *StepWithVariants) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetCreatedAt

`func (o *StepWithVariants) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StepWithVariants) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StepWithVariants) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *StepWithVariants) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *StepWithVariants) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *StepWithVariants) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *StepWithVariants) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StepWithVariants) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StepWithVariants) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *StepWithVariants) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *StepWithVariants) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *StepWithVariants) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *StepWithVariants) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *StepWithVariants) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *StepWithVariants) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetOrderIdx

`func (o *StepWithVariants) GetOrderIdx() int32`

GetOrderIdx returns the OrderIdx field if non-nil, zero value otherwise.

### GetOrderIdxOk

`func (o *StepWithVariants) GetOrderIdxOk() (*int32, bool)`

GetOrderIdxOk returns a tuple with the OrderIdx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderIdx

`func (o *StepWithVariants) SetOrderIdx(v int32)`

SetOrderIdx sets OrderIdx field to given value.


### GetProgramId

`func (o *StepWithVariants) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *StepWithVariants) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *StepWithVariants) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetType

`func (o *StepWithVariants) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StepWithVariants) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StepWithVariants) SetType(v string)`

SetType sets Type field to given value.


### GetWaitDays

`func (o *StepWithVariants) GetWaitDays() int32`

GetWaitDays returns the WaitDays field if non-nil, zero value otherwise.

### GetWaitDaysOk

`func (o *StepWithVariants) GetWaitDaysOk() (*int32, bool)`

GetWaitDaysOk returns a tuple with the WaitDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitDays

`func (o *StepWithVariants) SetWaitDays(v int32)`

SetWaitDays sets WaitDays field to given value.


### GetVariants

`func (o *StepWithVariants) GetVariants() []Variant`

GetVariants returns the Variants field if non-nil, zero value otherwise.

### GetVariantsOk

`func (o *StepWithVariants) GetVariantsOk() (*[]Variant, bool)`

GetVariantsOk returns a tuple with the Variants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariants

`func (o *StepWithVariants) SetVariants(v []Variant)`

SetVariants sets Variants field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


