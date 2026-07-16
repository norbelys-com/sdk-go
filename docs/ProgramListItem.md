# ProgramListItem

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

## Methods

### NewProgramListItem

`func NewProgramListItem(activeDays []int32, addUnsubscribe bool, autoPauseOnCompanyReply bool, bouncePauseThreshold float32, id string, jitterMaxSeconds int32, jitterMinSeconds int32, kind string, name string, newPerDay int32, pausedMeta NullableProgramPauseMeta, pausedReason NullableString, plainTextMode bool, sendIntervalMinutes int32, spamPauseThreshold float32, status string, stopCondition string, timezone string, trackClicks bool, trackingDomainId NullableString, trackOpens bool, unsubscribeText NullableString, variantDistribution string, windowFrom NullableString, windowTo NullableString, stats ProgramStats, ) *ProgramListItem`

NewProgramListItem instantiates a new ProgramListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramListItemWithDefaults

`func NewProgramListItemWithDefaults() *ProgramListItem`

NewProgramListItemWithDefaults instantiates a new ProgramListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveDays

`func (o *ProgramListItem) GetActiveDays() []int32`

GetActiveDays returns the ActiveDays field if non-nil, zero value otherwise.

### GetActiveDaysOk

`func (o *ProgramListItem) GetActiveDaysOk() (*[]int32, bool)`

GetActiveDaysOk returns a tuple with the ActiveDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDays

`func (o *ProgramListItem) SetActiveDays(v []int32)`

SetActiveDays sets ActiveDays field to given value.


### SetActiveDaysNil

`func (o *ProgramListItem) SetActiveDaysNil(b bool)`

 SetActiveDaysNil sets the value for ActiveDays to be an explicit nil

### UnsetActiveDays
`func (o *ProgramListItem) UnsetActiveDays()`

UnsetActiveDays ensures that no value is present for ActiveDays, not even an explicit nil
### GetAddUnsubscribe

`func (o *ProgramListItem) GetAddUnsubscribe() bool`

GetAddUnsubscribe returns the AddUnsubscribe field if non-nil, zero value otherwise.

### GetAddUnsubscribeOk

`func (o *ProgramListItem) GetAddUnsubscribeOk() (*bool, bool)`

GetAddUnsubscribeOk returns a tuple with the AddUnsubscribe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddUnsubscribe

`func (o *ProgramListItem) SetAddUnsubscribe(v bool)`

SetAddUnsubscribe sets AddUnsubscribe field to given value.


### GetArchivedAt

`func (o *ProgramListItem) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ProgramListItem) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ProgramListItem) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *ProgramListItem) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *ProgramListItem) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ProgramListItem) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAutoPauseOnCompanyReply

`func (o *ProgramListItem) GetAutoPauseOnCompanyReply() bool`

GetAutoPauseOnCompanyReply returns the AutoPauseOnCompanyReply field if non-nil, zero value otherwise.

### GetAutoPauseOnCompanyReplyOk

`func (o *ProgramListItem) GetAutoPauseOnCompanyReplyOk() (*bool, bool)`

GetAutoPauseOnCompanyReplyOk returns a tuple with the AutoPauseOnCompanyReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPauseOnCompanyReply

`func (o *ProgramListItem) SetAutoPauseOnCompanyReply(v bool)`

SetAutoPauseOnCompanyReply sets AutoPauseOnCompanyReply field to given value.


### GetBouncePauseThreshold

`func (o *ProgramListItem) GetBouncePauseThreshold() float32`

GetBouncePauseThreshold returns the BouncePauseThreshold field if non-nil, zero value otherwise.

### GetBouncePauseThresholdOk

`func (o *ProgramListItem) GetBouncePauseThresholdOk() (*float32, bool)`

GetBouncePauseThresholdOk returns a tuple with the BouncePauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePauseThreshold

`func (o *ProgramListItem) SetBouncePauseThreshold(v float32)`

SetBouncePauseThreshold sets BouncePauseThreshold field to given value.


### GetCreatedAt

`func (o *ProgramListItem) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProgramListItem) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProgramListItem) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProgramListItem) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *ProgramListItem) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ProgramListItem) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *ProgramListItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProgramListItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProgramListItem) SetId(v string)`

SetId sets Id field to given value.


### GetJitterMaxSeconds

`func (o *ProgramListItem) GetJitterMaxSeconds() int32`

GetJitterMaxSeconds returns the JitterMaxSeconds field if non-nil, zero value otherwise.

### GetJitterMaxSecondsOk

`func (o *ProgramListItem) GetJitterMaxSecondsOk() (*int32, bool)`

GetJitterMaxSecondsOk returns a tuple with the JitterMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMaxSeconds

`func (o *ProgramListItem) SetJitterMaxSeconds(v int32)`

SetJitterMaxSeconds sets JitterMaxSeconds field to given value.


### GetJitterMinSeconds

`func (o *ProgramListItem) GetJitterMinSeconds() int32`

GetJitterMinSeconds returns the JitterMinSeconds field if non-nil, zero value otherwise.

### GetJitterMinSecondsOk

`func (o *ProgramListItem) GetJitterMinSecondsOk() (*int32, bool)`

GetJitterMinSecondsOk returns a tuple with the JitterMinSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMinSeconds

`func (o *ProgramListItem) SetJitterMinSeconds(v int32)`

SetJitterMinSeconds sets JitterMinSeconds field to given value.


### GetKind

`func (o *ProgramListItem) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProgramListItem) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProgramListItem) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *ProgramListItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProgramListItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProgramListItem) SetName(v string)`

SetName sets Name field to given value.


### GetNewPerDay

`func (o *ProgramListItem) GetNewPerDay() int32`

GetNewPerDay returns the NewPerDay field if non-nil, zero value otherwise.

### GetNewPerDayOk

`func (o *ProgramListItem) GetNewPerDayOk() (*int32, bool)`

GetNewPerDayOk returns a tuple with the NewPerDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPerDay

`func (o *ProgramListItem) SetNewPerDay(v int32)`

SetNewPerDay sets NewPerDay field to given value.


### GetObject

`func (o *ProgramListItem) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ProgramListItem) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ProgramListItem) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *ProgramListItem) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *ProgramListItem) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *ProgramListItem) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPausedAt

`func (o *ProgramListItem) GetPausedAt() interface{}`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ProgramListItem) GetPausedAtOk() (*interface{}, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ProgramListItem) SetPausedAt(v interface{})`

SetPausedAt sets PausedAt field to given value.

### HasPausedAt

`func (o *ProgramListItem) HasPausedAt() bool`

HasPausedAt returns a boolean if a field has been set.

### SetPausedAtNil

`func (o *ProgramListItem) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ProgramListItem) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedMeta

`func (o *ProgramListItem) GetPausedMeta() ProgramPauseMeta`

GetPausedMeta returns the PausedMeta field if non-nil, zero value otherwise.

### GetPausedMetaOk

`func (o *ProgramListItem) GetPausedMetaOk() (*ProgramPauseMeta, bool)`

GetPausedMetaOk returns a tuple with the PausedMeta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedMeta

`func (o *ProgramListItem) SetPausedMeta(v ProgramPauseMeta)`

SetPausedMeta sets PausedMeta field to given value.


### SetPausedMetaNil

`func (o *ProgramListItem) SetPausedMetaNil(b bool)`

 SetPausedMetaNil sets the value for PausedMeta to be an explicit nil

### UnsetPausedMeta
`func (o *ProgramListItem) UnsetPausedMeta()`

UnsetPausedMeta ensures that no value is present for PausedMeta, not even an explicit nil
### GetPausedReason

`func (o *ProgramListItem) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *ProgramListItem) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *ProgramListItem) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.


### SetPausedReasonNil

`func (o *ProgramListItem) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *ProgramListItem) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetPlainTextMode

`func (o *ProgramListItem) GetPlainTextMode() bool`

GetPlainTextMode returns the PlainTextMode field if non-nil, zero value otherwise.

### GetPlainTextModeOk

`func (o *ProgramListItem) GetPlainTextModeOk() (*bool, bool)`

GetPlainTextModeOk returns a tuple with the PlainTextMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainTextMode

`func (o *ProgramListItem) SetPlainTextMode(v bool)`

SetPlainTextMode sets PlainTextMode field to given value.


### GetSendIntervalMinutes

`func (o *ProgramListItem) GetSendIntervalMinutes() int32`

GetSendIntervalMinutes returns the SendIntervalMinutes field if non-nil, zero value otherwise.

### GetSendIntervalMinutesOk

`func (o *ProgramListItem) GetSendIntervalMinutesOk() (*int32, bool)`

GetSendIntervalMinutesOk returns a tuple with the SendIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendIntervalMinutes

`func (o *ProgramListItem) SetSendIntervalMinutes(v int32)`

SetSendIntervalMinutes sets SendIntervalMinutes field to given value.


### GetSpamPauseThreshold

`func (o *ProgramListItem) GetSpamPauseThreshold() float32`

GetSpamPauseThreshold returns the SpamPauseThreshold field if non-nil, zero value otherwise.

### GetSpamPauseThresholdOk

`func (o *ProgramListItem) GetSpamPauseThresholdOk() (*float32, bool)`

GetSpamPauseThresholdOk returns a tuple with the SpamPauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpamPauseThreshold

`func (o *ProgramListItem) SetSpamPauseThreshold(v float32)`

SetSpamPauseThreshold sets SpamPauseThreshold field to given value.


### GetStartDate

`func (o *ProgramListItem) GetStartDate() interface{}`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ProgramListItem) GetStartDateOk() (*interface{}, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ProgramListItem) SetStartDate(v interface{})`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ProgramListItem) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ProgramListItem) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ProgramListItem) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetStatus

`func (o *ProgramListItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProgramListItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProgramListItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopCondition

`func (o *ProgramListItem) GetStopCondition() string`

GetStopCondition returns the StopCondition field if non-nil, zero value otherwise.

### GetStopConditionOk

`func (o *ProgramListItem) GetStopConditionOk() (*string, bool)`

GetStopConditionOk returns a tuple with the StopCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopCondition

`func (o *ProgramListItem) SetStopCondition(v string)`

SetStopCondition sets StopCondition field to given value.


### GetTimezone

`func (o *ProgramListItem) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ProgramListItem) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ProgramListItem) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetTrackClicks

`func (o *ProgramListItem) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *ProgramListItem) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *ProgramListItem) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.


### GetTrackingDomainId

`func (o *ProgramListItem) GetTrackingDomainId() string`

GetTrackingDomainId returns the TrackingDomainId field if non-nil, zero value otherwise.

### GetTrackingDomainIdOk

`func (o *ProgramListItem) GetTrackingDomainIdOk() (*string, bool)`

GetTrackingDomainIdOk returns a tuple with the TrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingDomainId

`func (o *ProgramListItem) SetTrackingDomainId(v string)`

SetTrackingDomainId sets TrackingDomainId field to given value.


### SetTrackingDomainIdNil

`func (o *ProgramListItem) SetTrackingDomainIdNil(b bool)`

 SetTrackingDomainIdNil sets the value for TrackingDomainId to be an explicit nil

### UnsetTrackingDomainId
`func (o *ProgramListItem) UnsetTrackingDomainId()`

UnsetTrackingDomainId ensures that no value is present for TrackingDomainId, not even an explicit nil
### GetTrackOpens

`func (o *ProgramListItem) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *ProgramListItem) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *ProgramListItem) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.


### GetUnsubscribeText

`func (o *ProgramListItem) GetUnsubscribeText() string`

GetUnsubscribeText returns the UnsubscribeText field if non-nil, zero value otherwise.

### GetUnsubscribeTextOk

`func (o *ProgramListItem) GetUnsubscribeTextOk() (*string, bool)`

GetUnsubscribeTextOk returns a tuple with the UnsubscribeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribeText

`func (o *ProgramListItem) SetUnsubscribeText(v string)`

SetUnsubscribeText sets UnsubscribeText field to given value.


### SetUnsubscribeTextNil

`func (o *ProgramListItem) SetUnsubscribeTextNil(b bool)`

 SetUnsubscribeTextNil sets the value for UnsubscribeText to be an explicit nil

### UnsetUnsubscribeText
`func (o *ProgramListItem) UnsetUnsubscribeText()`

UnsetUnsubscribeText ensures that no value is present for UnsubscribeText, not even an explicit nil
### GetUpdatedAt

`func (o *ProgramListItem) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProgramListItem) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProgramListItem) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProgramListItem) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ProgramListItem) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ProgramListItem) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetVariantDistribution

`func (o *ProgramListItem) GetVariantDistribution() string`

GetVariantDistribution returns the VariantDistribution field if non-nil, zero value otherwise.

### GetVariantDistributionOk

`func (o *ProgramListItem) GetVariantDistributionOk() (*string, bool)`

GetVariantDistributionOk returns a tuple with the VariantDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantDistribution

`func (o *ProgramListItem) SetVariantDistribution(v string)`

SetVariantDistribution sets VariantDistribution field to given value.


### GetWindowFrom

`func (o *ProgramListItem) GetWindowFrom() string`

GetWindowFrom returns the WindowFrom field if non-nil, zero value otherwise.

### GetWindowFromOk

`func (o *ProgramListItem) GetWindowFromOk() (*string, bool)`

GetWindowFromOk returns a tuple with the WindowFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowFrom

`func (o *ProgramListItem) SetWindowFrom(v string)`

SetWindowFrom sets WindowFrom field to given value.


### SetWindowFromNil

`func (o *ProgramListItem) SetWindowFromNil(b bool)`

 SetWindowFromNil sets the value for WindowFrom to be an explicit nil

### UnsetWindowFrom
`func (o *ProgramListItem) UnsetWindowFrom()`

UnsetWindowFrom ensures that no value is present for WindowFrom, not even an explicit nil
### GetWindowTo

`func (o *ProgramListItem) GetWindowTo() string`

GetWindowTo returns the WindowTo field if non-nil, zero value otherwise.

### GetWindowToOk

`func (o *ProgramListItem) GetWindowToOk() (*string, bool)`

GetWindowToOk returns a tuple with the WindowTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTo

`func (o *ProgramListItem) SetWindowTo(v string)`

SetWindowTo sets WindowTo field to given value.


### SetWindowToNil

`func (o *ProgramListItem) SetWindowToNil(b bool)`

 SetWindowToNil sets the value for WindowTo to be an explicit nil

### UnsetWindowTo
`func (o *ProgramListItem) UnsetWindowTo()`

UnsetWindowTo ensures that no value is present for WindowTo, not even an explicit nil
### GetStats

`func (o *ProgramListItem) GetStats() ProgramStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *ProgramListItem) GetStatsOk() (*ProgramStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *ProgramListItem) SetStats(v ProgramStats)`

SetStats sets Stats field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


