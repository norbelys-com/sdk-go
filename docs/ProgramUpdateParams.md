# ProgramUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveDays** | Pointer to **[]int32** |  | [optional] 
**AddUnsubscribe** | Pointer to **bool** | Attach RFC 8058 one-click unsubscribe headers + footer. Defaults off (opt-in). | [optional] 
**AutoPauseOnCompanyReply** | Pointer to **bool** | Pause every lead at a company once one of them replies. | [optional] 
**BouncePauseThreshold** | Pointer to **float32** | Auto-pause when the bounce rate reaches this percent; 0 disables. Default 2. | [optional] 
**JitterMaxSeconds** | Pointer to **int32** | Random extra wait per send, upper bound (seconds). | [optional] 
**JitterMinSeconds** | Pointer to **int32** | Random extra wait per send, lower bound (seconds). | [optional] 
**Kind** | Pointer to **string** | Defaults to \&quot;cold_sequence\&quot;. | [optional] 
**Name** | Pointer to **string** | Display name. | [optional] 
**NewPerDay** | Pointer to **int32** | New leads started per day for the whole campaign, shared across all its mailboxes (follow-ups excluded); 0 &#x3D; uncapped. | [optional] 
**PlainTextMode** | Pointer to **bool** | Send the body as plain text only: no HTML part, open pixel, or link tracking. | [optional] 
**SendIntervalMinutes** | Pointer to **int32** | Minutes between sends from one mailbox (cold-email floor is 3). | [optional] 
**SpamPauseThreshold** | Pointer to **float32** | Auto-pause when the spam-complaint rate reaches this percent; 0 disables. Default 0.3. | [optional] 
**StartDate** | Pointer to **NullableInt32** |  | [optional] 
**Steps** | Pointer to [**[]ProgramStepInput**](ProgramStepInput.md) | Build the whole cadence in one call: ordered steps, each with its arms. Omit to start empty and add steps later via programs.update. | [optional] 
**StopCondition** | Pointer to **string** | Engagement that pulls a lead out of the cadence: &#x60;reply&#x60;, &#x60;click&#x60;, &#x60;open&#x60;, &#x60;none&#x60;. | [optional] 
**Timezone** | Pointer to **string** | IANA timezone. | [optional] 
**TrackClicks** | Pointer to **bool** | Rewrite links to track clicks. | [optional] 
**TrackingDomainId** | Pointer to **NullableString** |  | [optional] 
**TrackOpens** | Pointer to **bool** | Insert the open pixel. | [optional] 
**UnsubscribeText** | Pointer to **string** | Custom unsubscribe footer copy. | [optional] 
**VariantDistribution** | Pointer to **string** | How A/B arms are spread across leads with no decided winner: &#x60;pattern&#x60; (deterministic per-lead hash) or &#x60;random&#x60; (independent roll per lead). | [optional] 
**WindowFrom** | Pointer to **NullableString** |  | [optional] 
**WindowTo** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProgramUpdateParams

`func NewProgramUpdateParams() *ProgramUpdateParams`

NewProgramUpdateParams instantiates a new ProgramUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramUpdateParamsWithDefaults

`func NewProgramUpdateParamsWithDefaults() *ProgramUpdateParams`

NewProgramUpdateParamsWithDefaults instantiates a new ProgramUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveDays

`func (o *ProgramUpdateParams) GetActiveDays() []int32`

GetActiveDays returns the ActiveDays field if non-nil, zero value otherwise.

### GetActiveDaysOk

`func (o *ProgramUpdateParams) GetActiveDaysOk() (*[]int32, bool)`

GetActiveDaysOk returns a tuple with the ActiveDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDays

`func (o *ProgramUpdateParams) SetActiveDays(v []int32)`

SetActiveDays sets ActiveDays field to given value.

### HasActiveDays

`func (o *ProgramUpdateParams) HasActiveDays() bool`

HasActiveDays returns a boolean if a field has been set.

### SetActiveDaysNil

`func (o *ProgramUpdateParams) SetActiveDaysNil(b bool)`

 SetActiveDaysNil sets the value for ActiveDays to be an explicit nil

### UnsetActiveDays
`func (o *ProgramUpdateParams) UnsetActiveDays()`

UnsetActiveDays ensures that no value is present for ActiveDays, not even an explicit nil
### GetAddUnsubscribe

`func (o *ProgramUpdateParams) GetAddUnsubscribe() bool`

GetAddUnsubscribe returns the AddUnsubscribe field if non-nil, zero value otherwise.

### GetAddUnsubscribeOk

`func (o *ProgramUpdateParams) GetAddUnsubscribeOk() (*bool, bool)`

GetAddUnsubscribeOk returns a tuple with the AddUnsubscribe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddUnsubscribe

`func (o *ProgramUpdateParams) SetAddUnsubscribe(v bool)`

SetAddUnsubscribe sets AddUnsubscribe field to given value.

### HasAddUnsubscribe

`func (o *ProgramUpdateParams) HasAddUnsubscribe() bool`

HasAddUnsubscribe returns a boolean if a field has been set.

### GetAutoPauseOnCompanyReply

`func (o *ProgramUpdateParams) GetAutoPauseOnCompanyReply() bool`

GetAutoPauseOnCompanyReply returns the AutoPauseOnCompanyReply field if non-nil, zero value otherwise.

### GetAutoPauseOnCompanyReplyOk

`func (o *ProgramUpdateParams) GetAutoPauseOnCompanyReplyOk() (*bool, bool)`

GetAutoPauseOnCompanyReplyOk returns a tuple with the AutoPauseOnCompanyReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPauseOnCompanyReply

`func (o *ProgramUpdateParams) SetAutoPauseOnCompanyReply(v bool)`

SetAutoPauseOnCompanyReply sets AutoPauseOnCompanyReply field to given value.

### HasAutoPauseOnCompanyReply

`func (o *ProgramUpdateParams) HasAutoPauseOnCompanyReply() bool`

HasAutoPauseOnCompanyReply returns a boolean if a field has been set.

### GetBouncePauseThreshold

`func (o *ProgramUpdateParams) GetBouncePauseThreshold() float32`

GetBouncePauseThreshold returns the BouncePauseThreshold field if non-nil, zero value otherwise.

### GetBouncePauseThresholdOk

`func (o *ProgramUpdateParams) GetBouncePauseThresholdOk() (*float32, bool)`

GetBouncePauseThresholdOk returns a tuple with the BouncePauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePauseThreshold

`func (o *ProgramUpdateParams) SetBouncePauseThreshold(v float32)`

SetBouncePauseThreshold sets BouncePauseThreshold field to given value.

### HasBouncePauseThreshold

`func (o *ProgramUpdateParams) HasBouncePauseThreshold() bool`

HasBouncePauseThreshold returns a boolean if a field has been set.

### GetJitterMaxSeconds

`func (o *ProgramUpdateParams) GetJitterMaxSeconds() int32`

GetJitterMaxSeconds returns the JitterMaxSeconds field if non-nil, zero value otherwise.

### GetJitterMaxSecondsOk

`func (o *ProgramUpdateParams) GetJitterMaxSecondsOk() (*int32, bool)`

GetJitterMaxSecondsOk returns a tuple with the JitterMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMaxSeconds

`func (o *ProgramUpdateParams) SetJitterMaxSeconds(v int32)`

SetJitterMaxSeconds sets JitterMaxSeconds field to given value.

### HasJitterMaxSeconds

`func (o *ProgramUpdateParams) HasJitterMaxSeconds() bool`

HasJitterMaxSeconds returns a boolean if a field has been set.

### GetJitterMinSeconds

`func (o *ProgramUpdateParams) GetJitterMinSeconds() int32`

GetJitterMinSeconds returns the JitterMinSeconds field if non-nil, zero value otherwise.

### GetJitterMinSecondsOk

`func (o *ProgramUpdateParams) GetJitterMinSecondsOk() (*int32, bool)`

GetJitterMinSecondsOk returns a tuple with the JitterMinSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMinSeconds

`func (o *ProgramUpdateParams) SetJitterMinSeconds(v int32)`

SetJitterMinSeconds sets JitterMinSeconds field to given value.

### HasJitterMinSeconds

`func (o *ProgramUpdateParams) HasJitterMinSeconds() bool`

HasJitterMinSeconds returns a boolean if a field has been set.

### GetKind

`func (o *ProgramUpdateParams) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProgramUpdateParams) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProgramUpdateParams) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *ProgramUpdateParams) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetName

`func (o *ProgramUpdateParams) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProgramUpdateParams) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProgramUpdateParams) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProgramUpdateParams) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNewPerDay

`func (o *ProgramUpdateParams) GetNewPerDay() int32`

GetNewPerDay returns the NewPerDay field if non-nil, zero value otherwise.

### GetNewPerDayOk

`func (o *ProgramUpdateParams) GetNewPerDayOk() (*int32, bool)`

GetNewPerDayOk returns a tuple with the NewPerDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPerDay

`func (o *ProgramUpdateParams) SetNewPerDay(v int32)`

SetNewPerDay sets NewPerDay field to given value.

### HasNewPerDay

`func (o *ProgramUpdateParams) HasNewPerDay() bool`

HasNewPerDay returns a boolean if a field has been set.

### GetPlainTextMode

`func (o *ProgramUpdateParams) GetPlainTextMode() bool`

GetPlainTextMode returns the PlainTextMode field if non-nil, zero value otherwise.

### GetPlainTextModeOk

`func (o *ProgramUpdateParams) GetPlainTextModeOk() (*bool, bool)`

GetPlainTextModeOk returns a tuple with the PlainTextMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainTextMode

`func (o *ProgramUpdateParams) SetPlainTextMode(v bool)`

SetPlainTextMode sets PlainTextMode field to given value.

### HasPlainTextMode

`func (o *ProgramUpdateParams) HasPlainTextMode() bool`

HasPlainTextMode returns a boolean if a field has been set.

### GetSendIntervalMinutes

`func (o *ProgramUpdateParams) GetSendIntervalMinutes() int32`

GetSendIntervalMinutes returns the SendIntervalMinutes field if non-nil, zero value otherwise.

### GetSendIntervalMinutesOk

`func (o *ProgramUpdateParams) GetSendIntervalMinutesOk() (*int32, bool)`

GetSendIntervalMinutesOk returns a tuple with the SendIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendIntervalMinutes

`func (o *ProgramUpdateParams) SetSendIntervalMinutes(v int32)`

SetSendIntervalMinutes sets SendIntervalMinutes field to given value.

### HasSendIntervalMinutes

`func (o *ProgramUpdateParams) HasSendIntervalMinutes() bool`

HasSendIntervalMinutes returns a boolean if a field has been set.

### GetSpamPauseThreshold

`func (o *ProgramUpdateParams) GetSpamPauseThreshold() float32`

GetSpamPauseThreshold returns the SpamPauseThreshold field if non-nil, zero value otherwise.

### GetSpamPauseThresholdOk

`func (o *ProgramUpdateParams) GetSpamPauseThresholdOk() (*float32, bool)`

GetSpamPauseThresholdOk returns a tuple with the SpamPauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpamPauseThreshold

`func (o *ProgramUpdateParams) SetSpamPauseThreshold(v float32)`

SetSpamPauseThreshold sets SpamPauseThreshold field to given value.

### HasSpamPauseThreshold

`func (o *ProgramUpdateParams) HasSpamPauseThreshold() bool`

HasSpamPauseThreshold returns a boolean if a field has been set.

### GetStartDate

`func (o *ProgramUpdateParams) GetStartDate() int32`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ProgramUpdateParams) GetStartDateOk() (*int32, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ProgramUpdateParams) SetStartDate(v int32)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ProgramUpdateParams) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ProgramUpdateParams) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ProgramUpdateParams) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetSteps

`func (o *ProgramUpdateParams) GetSteps() []ProgramStepInput`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *ProgramUpdateParams) GetStepsOk() (*[]ProgramStepInput, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *ProgramUpdateParams) SetSteps(v []ProgramStepInput)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *ProgramUpdateParams) HasSteps() bool`

HasSteps returns a boolean if a field has been set.

### GetStopCondition

`func (o *ProgramUpdateParams) GetStopCondition() string`

GetStopCondition returns the StopCondition field if non-nil, zero value otherwise.

### GetStopConditionOk

`func (o *ProgramUpdateParams) GetStopConditionOk() (*string, bool)`

GetStopConditionOk returns a tuple with the StopCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopCondition

`func (o *ProgramUpdateParams) SetStopCondition(v string)`

SetStopCondition sets StopCondition field to given value.

### HasStopCondition

`func (o *ProgramUpdateParams) HasStopCondition() bool`

HasStopCondition returns a boolean if a field has been set.

### GetTimezone

`func (o *ProgramUpdateParams) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ProgramUpdateParams) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ProgramUpdateParams) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *ProgramUpdateParams) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetTrackClicks

`func (o *ProgramUpdateParams) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *ProgramUpdateParams) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *ProgramUpdateParams) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.

### HasTrackClicks

`func (o *ProgramUpdateParams) HasTrackClicks() bool`

HasTrackClicks returns a boolean if a field has been set.

### GetTrackingDomainId

`func (o *ProgramUpdateParams) GetTrackingDomainId() string`

GetTrackingDomainId returns the TrackingDomainId field if non-nil, zero value otherwise.

### GetTrackingDomainIdOk

`func (o *ProgramUpdateParams) GetTrackingDomainIdOk() (*string, bool)`

GetTrackingDomainIdOk returns a tuple with the TrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingDomainId

`func (o *ProgramUpdateParams) SetTrackingDomainId(v string)`

SetTrackingDomainId sets TrackingDomainId field to given value.

### HasTrackingDomainId

`func (o *ProgramUpdateParams) HasTrackingDomainId() bool`

HasTrackingDomainId returns a boolean if a field has been set.

### SetTrackingDomainIdNil

`func (o *ProgramUpdateParams) SetTrackingDomainIdNil(b bool)`

 SetTrackingDomainIdNil sets the value for TrackingDomainId to be an explicit nil

### UnsetTrackingDomainId
`func (o *ProgramUpdateParams) UnsetTrackingDomainId()`

UnsetTrackingDomainId ensures that no value is present for TrackingDomainId, not even an explicit nil
### GetTrackOpens

`func (o *ProgramUpdateParams) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *ProgramUpdateParams) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *ProgramUpdateParams) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.

### HasTrackOpens

`func (o *ProgramUpdateParams) HasTrackOpens() bool`

HasTrackOpens returns a boolean if a field has been set.

### GetUnsubscribeText

`func (o *ProgramUpdateParams) GetUnsubscribeText() string`

GetUnsubscribeText returns the UnsubscribeText field if non-nil, zero value otherwise.

### GetUnsubscribeTextOk

`func (o *ProgramUpdateParams) GetUnsubscribeTextOk() (*string, bool)`

GetUnsubscribeTextOk returns a tuple with the UnsubscribeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribeText

`func (o *ProgramUpdateParams) SetUnsubscribeText(v string)`

SetUnsubscribeText sets UnsubscribeText field to given value.

### HasUnsubscribeText

`func (o *ProgramUpdateParams) HasUnsubscribeText() bool`

HasUnsubscribeText returns a boolean if a field has been set.

### GetVariantDistribution

`func (o *ProgramUpdateParams) GetVariantDistribution() string`

GetVariantDistribution returns the VariantDistribution field if non-nil, zero value otherwise.

### GetVariantDistributionOk

`func (o *ProgramUpdateParams) GetVariantDistributionOk() (*string, bool)`

GetVariantDistributionOk returns a tuple with the VariantDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantDistribution

`func (o *ProgramUpdateParams) SetVariantDistribution(v string)`

SetVariantDistribution sets VariantDistribution field to given value.

### HasVariantDistribution

`func (o *ProgramUpdateParams) HasVariantDistribution() bool`

HasVariantDistribution returns a boolean if a field has been set.

### GetWindowFrom

`func (o *ProgramUpdateParams) GetWindowFrom() string`

GetWindowFrom returns the WindowFrom field if non-nil, zero value otherwise.

### GetWindowFromOk

`func (o *ProgramUpdateParams) GetWindowFromOk() (*string, bool)`

GetWindowFromOk returns a tuple with the WindowFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowFrom

`func (o *ProgramUpdateParams) SetWindowFrom(v string)`

SetWindowFrom sets WindowFrom field to given value.

### HasWindowFrom

`func (o *ProgramUpdateParams) HasWindowFrom() bool`

HasWindowFrom returns a boolean if a field has been set.

### SetWindowFromNil

`func (o *ProgramUpdateParams) SetWindowFromNil(b bool)`

 SetWindowFromNil sets the value for WindowFrom to be an explicit nil

### UnsetWindowFrom
`func (o *ProgramUpdateParams) UnsetWindowFrom()`

UnsetWindowFrom ensures that no value is present for WindowFrom, not even an explicit nil
### GetWindowTo

`func (o *ProgramUpdateParams) GetWindowTo() string`

GetWindowTo returns the WindowTo field if non-nil, zero value otherwise.

### GetWindowToOk

`func (o *ProgramUpdateParams) GetWindowToOk() (*string, bool)`

GetWindowToOk returns a tuple with the WindowTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTo

`func (o *ProgramUpdateParams) SetWindowTo(v string)`

SetWindowTo sets WindowTo field to given value.

### HasWindowTo

`func (o *ProgramUpdateParams) HasWindowTo() bool`

HasWindowTo returns a boolean if a field has been set.

### SetWindowToNil

`func (o *ProgramUpdateParams) SetWindowToNil(b bool)`

 SetWindowToNil sets the value for WindowTo to be an explicit nil

### UnsetWindowTo
`func (o *ProgramUpdateParams) UnsetWindowTo()`

UnsetWindowTo ensures that no value is present for WindowTo, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


