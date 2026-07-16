# ProgramDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveDays** | **[]int32** |  | 
**AddUnsubscribe** | **bool** | Attach RFC 8058 one-click unsubscribe headers + footer. | 
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**AutoPauseOnCompanyReply** | **bool** | Pause every lead at a company once one of them replies. | 
**BouncePauseThreshold** | **float32** | Auto-pause when the bounce rate reaches this percent; 0 disables. | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The program id. | 
**JitterMaxSeconds** | **int32** | Random extra wait per send, upper bound (seconds). | 
**JitterMinSeconds** | **int32** | Random extra wait per send, lower bound (seconds). | 
**Kind** | **string** | Kind of sending; &#x60;cold_sequence&#x60; is the only kind today. | 
**Name** | **string** | Display name. | 
**NewPerDay** | **int32** | New leads started per day for the WHOLE campaign, shared across all its mailboxes (follow-ups are not counted). 0 &#x3D; no daily cap — new leads flow at mailbox capacity. Real throughput is always bounded by the mailboxes&#39; own daily limits. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**PausedAt** | Pointer to **interface{}** |  | [optional] 
**PausedMeta** | [**NullableProgramPauseMeta**](ProgramPauseMeta.md) |  | 
**PausedReason** | **NullableString** |  | 
**PlainTextMode** | **bool** | Send the body as plain text only: no HTML part, open pixel, or link tracking. | 
**SendIntervalMinutes** | **int32** | Minutes between sends from one mailbox. | 
**SpamPauseThreshold** | **float32** | Auto-pause when the spam-complaint rate reaches this percent; 0 disables. | 
**StartDate** | Pointer to **interface{}** |  | [optional] 
**Status** | **string** | Lifecycle status: &#x60;draft&#x60;, &#x60;active&#x60;, &#x60;paused&#x60;, &#x60;done&#x60;. | 
**StopCondition** | **string** | Engagement that pulls a lead out of the cadence: &#x60;reply&#x60;, &#x60;click&#x60;, &#x60;open&#x60;, &#x60;none&#x60;. | 
**Timezone** | **string** | IANA timezone the window applies in. | 
**TrackClicks** | **bool** | Rewrite links to track clicks. | 
**TrackingDomainId** | **NullableString** |  | 
**TrackOpens** | **bool** | Insert the open pixel. | 
**UnsubscribeText** | **NullableString** |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 
**VariantDistribution** | **string** | How A/B arms are spread across leads with no decided winner: &#x60;pattern&#x60; (deterministic per-lead hash) or &#x60;random&#x60; (independent roll per lead). | 
**WindowFrom** | **NullableString** |  | 
**WindowTo** | **NullableString** |  | 
**Stats** | [**ProgramStats**](ProgramStats.md) |  | 
**Senders** | Pointer to [**[]ProgramSenderRef**](ProgramSenderRef.md) | The attached mailboxes — present when expand[]&#x3D;senders. | [optional] 
**Steps** | Pointer to [**[]StepWithVariants**](StepWithVariants.md) | The cadence with arms — present when expand[]&#x3D;steps (always returned by create/update). | [optional] 

## Methods

### NewProgramDetail

`func NewProgramDetail(activeDays []int32, addUnsubscribe bool, autoPauseOnCompanyReply bool, bouncePauseThreshold float32, id string, jitterMaxSeconds int32, jitterMinSeconds int32, kind string, name string, newPerDay int32, pausedMeta NullableProgramPauseMeta, pausedReason NullableString, plainTextMode bool, sendIntervalMinutes int32, spamPauseThreshold float32, status string, stopCondition string, timezone string, trackClicks bool, trackingDomainId NullableString, trackOpens bool, unsubscribeText NullableString, variantDistribution string, windowFrom NullableString, windowTo NullableString, stats ProgramStats, ) *ProgramDetail`

NewProgramDetail instantiates a new ProgramDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramDetailWithDefaults

`func NewProgramDetailWithDefaults() *ProgramDetail`

NewProgramDetailWithDefaults instantiates a new ProgramDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveDays

`func (o *ProgramDetail) GetActiveDays() []int32`

GetActiveDays returns the ActiveDays field if non-nil, zero value otherwise.

### GetActiveDaysOk

`func (o *ProgramDetail) GetActiveDaysOk() (*[]int32, bool)`

GetActiveDaysOk returns a tuple with the ActiveDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDays

`func (o *ProgramDetail) SetActiveDays(v []int32)`

SetActiveDays sets ActiveDays field to given value.


### SetActiveDaysNil

`func (o *ProgramDetail) SetActiveDaysNil(b bool)`

 SetActiveDaysNil sets the value for ActiveDays to be an explicit nil

### UnsetActiveDays
`func (o *ProgramDetail) UnsetActiveDays()`

UnsetActiveDays ensures that no value is present for ActiveDays, not even an explicit nil
### GetAddUnsubscribe

`func (o *ProgramDetail) GetAddUnsubscribe() bool`

GetAddUnsubscribe returns the AddUnsubscribe field if non-nil, zero value otherwise.

### GetAddUnsubscribeOk

`func (o *ProgramDetail) GetAddUnsubscribeOk() (*bool, bool)`

GetAddUnsubscribeOk returns a tuple with the AddUnsubscribe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddUnsubscribe

`func (o *ProgramDetail) SetAddUnsubscribe(v bool)`

SetAddUnsubscribe sets AddUnsubscribe field to given value.


### GetArchivedAt

`func (o *ProgramDetail) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ProgramDetail) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ProgramDetail) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *ProgramDetail) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *ProgramDetail) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ProgramDetail) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAutoPauseOnCompanyReply

`func (o *ProgramDetail) GetAutoPauseOnCompanyReply() bool`

GetAutoPauseOnCompanyReply returns the AutoPauseOnCompanyReply field if non-nil, zero value otherwise.

### GetAutoPauseOnCompanyReplyOk

`func (o *ProgramDetail) GetAutoPauseOnCompanyReplyOk() (*bool, bool)`

GetAutoPauseOnCompanyReplyOk returns a tuple with the AutoPauseOnCompanyReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPauseOnCompanyReply

`func (o *ProgramDetail) SetAutoPauseOnCompanyReply(v bool)`

SetAutoPauseOnCompanyReply sets AutoPauseOnCompanyReply field to given value.


### GetBouncePauseThreshold

`func (o *ProgramDetail) GetBouncePauseThreshold() float32`

GetBouncePauseThreshold returns the BouncePauseThreshold field if non-nil, zero value otherwise.

### GetBouncePauseThresholdOk

`func (o *ProgramDetail) GetBouncePauseThresholdOk() (*float32, bool)`

GetBouncePauseThresholdOk returns a tuple with the BouncePauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePauseThreshold

`func (o *ProgramDetail) SetBouncePauseThreshold(v float32)`

SetBouncePauseThreshold sets BouncePauseThreshold field to given value.


### GetCreatedAt

`func (o *ProgramDetail) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProgramDetail) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProgramDetail) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProgramDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *ProgramDetail) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ProgramDetail) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *ProgramDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProgramDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProgramDetail) SetId(v string)`

SetId sets Id field to given value.


### GetJitterMaxSeconds

`func (o *ProgramDetail) GetJitterMaxSeconds() int32`

GetJitterMaxSeconds returns the JitterMaxSeconds field if non-nil, zero value otherwise.

### GetJitterMaxSecondsOk

`func (o *ProgramDetail) GetJitterMaxSecondsOk() (*int32, bool)`

GetJitterMaxSecondsOk returns a tuple with the JitterMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMaxSeconds

`func (o *ProgramDetail) SetJitterMaxSeconds(v int32)`

SetJitterMaxSeconds sets JitterMaxSeconds field to given value.


### GetJitterMinSeconds

`func (o *ProgramDetail) GetJitterMinSeconds() int32`

GetJitterMinSeconds returns the JitterMinSeconds field if non-nil, zero value otherwise.

### GetJitterMinSecondsOk

`func (o *ProgramDetail) GetJitterMinSecondsOk() (*int32, bool)`

GetJitterMinSecondsOk returns a tuple with the JitterMinSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMinSeconds

`func (o *ProgramDetail) SetJitterMinSeconds(v int32)`

SetJitterMinSeconds sets JitterMinSeconds field to given value.


### GetKind

`func (o *ProgramDetail) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProgramDetail) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProgramDetail) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *ProgramDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProgramDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProgramDetail) SetName(v string)`

SetName sets Name field to given value.


### GetNewPerDay

`func (o *ProgramDetail) GetNewPerDay() int32`

GetNewPerDay returns the NewPerDay field if non-nil, zero value otherwise.

### GetNewPerDayOk

`func (o *ProgramDetail) GetNewPerDayOk() (*int32, bool)`

GetNewPerDayOk returns a tuple with the NewPerDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPerDay

`func (o *ProgramDetail) SetNewPerDay(v int32)`

SetNewPerDay sets NewPerDay field to given value.


### GetObject

`func (o *ProgramDetail) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ProgramDetail) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ProgramDetail) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *ProgramDetail) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *ProgramDetail) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *ProgramDetail) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPausedAt

`func (o *ProgramDetail) GetPausedAt() interface{}`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ProgramDetail) GetPausedAtOk() (*interface{}, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ProgramDetail) SetPausedAt(v interface{})`

SetPausedAt sets PausedAt field to given value.

### HasPausedAt

`func (o *ProgramDetail) HasPausedAt() bool`

HasPausedAt returns a boolean if a field has been set.

### SetPausedAtNil

`func (o *ProgramDetail) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ProgramDetail) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedMeta

`func (o *ProgramDetail) GetPausedMeta() ProgramPauseMeta`

GetPausedMeta returns the PausedMeta field if non-nil, zero value otherwise.

### GetPausedMetaOk

`func (o *ProgramDetail) GetPausedMetaOk() (*ProgramPauseMeta, bool)`

GetPausedMetaOk returns a tuple with the PausedMeta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedMeta

`func (o *ProgramDetail) SetPausedMeta(v ProgramPauseMeta)`

SetPausedMeta sets PausedMeta field to given value.


### SetPausedMetaNil

`func (o *ProgramDetail) SetPausedMetaNil(b bool)`

 SetPausedMetaNil sets the value for PausedMeta to be an explicit nil

### UnsetPausedMeta
`func (o *ProgramDetail) UnsetPausedMeta()`

UnsetPausedMeta ensures that no value is present for PausedMeta, not even an explicit nil
### GetPausedReason

`func (o *ProgramDetail) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *ProgramDetail) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *ProgramDetail) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.


### SetPausedReasonNil

`func (o *ProgramDetail) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *ProgramDetail) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetPlainTextMode

`func (o *ProgramDetail) GetPlainTextMode() bool`

GetPlainTextMode returns the PlainTextMode field if non-nil, zero value otherwise.

### GetPlainTextModeOk

`func (o *ProgramDetail) GetPlainTextModeOk() (*bool, bool)`

GetPlainTextModeOk returns a tuple with the PlainTextMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainTextMode

`func (o *ProgramDetail) SetPlainTextMode(v bool)`

SetPlainTextMode sets PlainTextMode field to given value.


### GetSendIntervalMinutes

`func (o *ProgramDetail) GetSendIntervalMinutes() int32`

GetSendIntervalMinutes returns the SendIntervalMinutes field if non-nil, zero value otherwise.

### GetSendIntervalMinutesOk

`func (o *ProgramDetail) GetSendIntervalMinutesOk() (*int32, bool)`

GetSendIntervalMinutesOk returns a tuple with the SendIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendIntervalMinutes

`func (o *ProgramDetail) SetSendIntervalMinutes(v int32)`

SetSendIntervalMinutes sets SendIntervalMinutes field to given value.


### GetSpamPauseThreshold

`func (o *ProgramDetail) GetSpamPauseThreshold() float32`

GetSpamPauseThreshold returns the SpamPauseThreshold field if non-nil, zero value otherwise.

### GetSpamPauseThresholdOk

`func (o *ProgramDetail) GetSpamPauseThresholdOk() (*float32, bool)`

GetSpamPauseThresholdOk returns a tuple with the SpamPauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpamPauseThreshold

`func (o *ProgramDetail) SetSpamPauseThreshold(v float32)`

SetSpamPauseThreshold sets SpamPauseThreshold field to given value.


### GetStartDate

`func (o *ProgramDetail) GetStartDate() interface{}`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ProgramDetail) GetStartDateOk() (*interface{}, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ProgramDetail) SetStartDate(v interface{})`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ProgramDetail) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ProgramDetail) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ProgramDetail) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetStatus

`func (o *ProgramDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProgramDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProgramDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopCondition

`func (o *ProgramDetail) GetStopCondition() string`

GetStopCondition returns the StopCondition field if non-nil, zero value otherwise.

### GetStopConditionOk

`func (o *ProgramDetail) GetStopConditionOk() (*string, bool)`

GetStopConditionOk returns a tuple with the StopCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopCondition

`func (o *ProgramDetail) SetStopCondition(v string)`

SetStopCondition sets StopCondition field to given value.


### GetTimezone

`func (o *ProgramDetail) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ProgramDetail) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ProgramDetail) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetTrackClicks

`func (o *ProgramDetail) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *ProgramDetail) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *ProgramDetail) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.


### GetTrackingDomainId

`func (o *ProgramDetail) GetTrackingDomainId() string`

GetTrackingDomainId returns the TrackingDomainId field if non-nil, zero value otherwise.

### GetTrackingDomainIdOk

`func (o *ProgramDetail) GetTrackingDomainIdOk() (*string, bool)`

GetTrackingDomainIdOk returns a tuple with the TrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingDomainId

`func (o *ProgramDetail) SetTrackingDomainId(v string)`

SetTrackingDomainId sets TrackingDomainId field to given value.


### SetTrackingDomainIdNil

`func (o *ProgramDetail) SetTrackingDomainIdNil(b bool)`

 SetTrackingDomainIdNil sets the value for TrackingDomainId to be an explicit nil

### UnsetTrackingDomainId
`func (o *ProgramDetail) UnsetTrackingDomainId()`

UnsetTrackingDomainId ensures that no value is present for TrackingDomainId, not even an explicit nil
### GetTrackOpens

`func (o *ProgramDetail) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *ProgramDetail) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *ProgramDetail) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.


### GetUnsubscribeText

`func (o *ProgramDetail) GetUnsubscribeText() string`

GetUnsubscribeText returns the UnsubscribeText field if non-nil, zero value otherwise.

### GetUnsubscribeTextOk

`func (o *ProgramDetail) GetUnsubscribeTextOk() (*string, bool)`

GetUnsubscribeTextOk returns a tuple with the UnsubscribeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribeText

`func (o *ProgramDetail) SetUnsubscribeText(v string)`

SetUnsubscribeText sets UnsubscribeText field to given value.


### SetUnsubscribeTextNil

`func (o *ProgramDetail) SetUnsubscribeTextNil(b bool)`

 SetUnsubscribeTextNil sets the value for UnsubscribeText to be an explicit nil

### UnsetUnsubscribeText
`func (o *ProgramDetail) UnsetUnsubscribeText()`

UnsetUnsubscribeText ensures that no value is present for UnsubscribeText, not even an explicit nil
### GetUpdatedAt

`func (o *ProgramDetail) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProgramDetail) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProgramDetail) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProgramDetail) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ProgramDetail) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ProgramDetail) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetVariantDistribution

`func (o *ProgramDetail) GetVariantDistribution() string`

GetVariantDistribution returns the VariantDistribution field if non-nil, zero value otherwise.

### GetVariantDistributionOk

`func (o *ProgramDetail) GetVariantDistributionOk() (*string, bool)`

GetVariantDistributionOk returns a tuple with the VariantDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantDistribution

`func (o *ProgramDetail) SetVariantDistribution(v string)`

SetVariantDistribution sets VariantDistribution field to given value.


### GetWindowFrom

`func (o *ProgramDetail) GetWindowFrom() string`

GetWindowFrom returns the WindowFrom field if non-nil, zero value otherwise.

### GetWindowFromOk

`func (o *ProgramDetail) GetWindowFromOk() (*string, bool)`

GetWindowFromOk returns a tuple with the WindowFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowFrom

`func (o *ProgramDetail) SetWindowFrom(v string)`

SetWindowFrom sets WindowFrom field to given value.


### SetWindowFromNil

`func (o *ProgramDetail) SetWindowFromNil(b bool)`

 SetWindowFromNil sets the value for WindowFrom to be an explicit nil

### UnsetWindowFrom
`func (o *ProgramDetail) UnsetWindowFrom()`

UnsetWindowFrom ensures that no value is present for WindowFrom, not even an explicit nil
### GetWindowTo

`func (o *ProgramDetail) GetWindowTo() string`

GetWindowTo returns the WindowTo field if non-nil, zero value otherwise.

### GetWindowToOk

`func (o *ProgramDetail) GetWindowToOk() (*string, bool)`

GetWindowToOk returns a tuple with the WindowTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTo

`func (o *ProgramDetail) SetWindowTo(v string)`

SetWindowTo sets WindowTo field to given value.


### SetWindowToNil

`func (o *ProgramDetail) SetWindowToNil(b bool)`

 SetWindowToNil sets the value for WindowTo to be an explicit nil

### UnsetWindowTo
`func (o *ProgramDetail) UnsetWindowTo()`

UnsetWindowTo ensures that no value is present for WindowTo, not even an explicit nil
### GetStats

`func (o *ProgramDetail) GetStats() ProgramStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *ProgramDetail) GetStatsOk() (*ProgramStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *ProgramDetail) SetStats(v ProgramStats)`

SetStats sets Stats field to given value.


### GetSenders

`func (o *ProgramDetail) GetSenders() []ProgramSenderRef`

GetSenders returns the Senders field if non-nil, zero value otherwise.

### GetSendersOk

`func (o *ProgramDetail) GetSendersOk() (*[]ProgramSenderRef, bool)`

GetSendersOk returns a tuple with the Senders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenders

`func (o *ProgramDetail) SetSenders(v []ProgramSenderRef)`

SetSenders sets Senders field to given value.

### HasSenders

`func (o *ProgramDetail) HasSenders() bool`

HasSenders returns a boolean if a field has been set.

### GetSteps

`func (o *ProgramDetail) GetSteps() []StepWithVariants`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *ProgramDetail) GetStepsOk() (*[]StepWithVariants, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *ProgramDetail) SetSteps(v []StepWithVariants)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *ProgramDetail) HasSteps() bool`

HasSteps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


