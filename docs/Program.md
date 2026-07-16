# Program

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

## Methods

### NewProgram

`func NewProgram(activeDays []int32, addUnsubscribe bool, autoPauseOnCompanyReply bool, bouncePauseThreshold float32, id string, jitterMaxSeconds int32, jitterMinSeconds int32, kind string, name string, newPerDay int32, pausedMeta NullableProgramPauseMeta, pausedReason NullableString, plainTextMode bool, sendIntervalMinutes int32, spamPauseThreshold float32, status string, stopCondition string, timezone string, trackClicks bool, trackingDomainId NullableString, trackOpens bool, unsubscribeText NullableString, variantDistribution string, windowFrom NullableString, windowTo NullableString, ) *Program`

NewProgram instantiates a new Program object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramWithDefaults

`func NewProgramWithDefaults() *Program`

NewProgramWithDefaults instantiates a new Program object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveDays

`func (o *Program) GetActiveDays() []int32`

GetActiveDays returns the ActiveDays field if non-nil, zero value otherwise.

### GetActiveDaysOk

`func (o *Program) GetActiveDaysOk() (*[]int32, bool)`

GetActiveDaysOk returns a tuple with the ActiveDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDays

`func (o *Program) SetActiveDays(v []int32)`

SetActiveDays sets ActiveDays field to given value.


### SetActiveDaysNil

`func (o *Program) SetActiveDaysNil(b bool)`

 SetActiveDaysNil sets the value for ActiveDays to be an explicit nil

### UnsetActiveDays
`func (o *Program) UnsetActiveDays()`

UnsetActiveDays ensures that no value is present for ActiveDays, not even an explicit nil
### GetAddUnsubscribe

`func (o *Program) GetAddUnsubscribe() bool`

GetAddUnsubscribe returns the AddUnsubscribe field if non-nil, zero value otherwise.

### GetAddUnsubscribeOk

`func (o *Program) GetAddUnsubscribeOk() (*bool, bool)`

GetAddUnsubscribeOk returns a tuple with the AddUnsubscribe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddUnsubscribe

`func (o *Program) SetAddUnsubscribe(v bool)`

SetAddUnsubscribe sets AddUnsubscribe field to given value.


### GetArchivedAt

`func (o *Program) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Program) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Program) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Program) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Program) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Program) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAutoPauseOnCompanyReply

`func (o *Program) GetAutoPauseOnCompanyReply() bool`

GetAutoPauseOnCompanyReply returns the AutoPauseOnCompanyReply field if non-nil, zero value otherwise.

### GetAutoPauseOnCompanyReplyOk

`func (o *Program) GetAutoPauseOnCompanyReplyOk() (*bool, bool)`

GetAutoPauseOnCompanyReplyOk returns a tuple with the AutoPauseOnCompanyReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPauseOnCompanyReply

`func (o *Program) SetAutoPauseOnCompanyReply(v bool)`

SetAutoPauseOnCompanyReply sets AutoPauseOnCompanyReply field to given value.


### GetBouncePauseThreshold

`func (o *Program) GetBouncePauseThreshold() float32`

GetBouncePauseThreshold returns the BouncePauseThreshold field if non-nil, zero value otherwise.

### GetBouncePauseThresholdOk

`func (o *Program) GetBouncePauseThresholdOk() (*float32, bool)`

GetBouncePauseThresholdOk returns a tuple with the BouncePauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePauseThreshold

`func (o *Program) SetBouncePauseThreshold(v float32)`

SetBouncePauseThreshold sets BouncePauseThreshold field to given value.


### GetCreatedAt

`func (o *Program) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Program) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Program) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Program) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Program) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Program) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *Program) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Program) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Program) SetId(v string)`

SetId sets Id field to given value.


### GetJitterMaxSeconds

`func (o *Program) GetJitterMaxSeconds() int32`

GetJitterMaxSeconds returns the JitterMaxSeconds field if non-nil, zero value otherwise.

### GetJitterMaxSecondsOk

`func (o *Program) GetJitterMaxSecondsOk() (*int32, bool)`

GetJitterMaxSecondsOk returns a tuple with the JitterMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMaxSeconds

`func (o *Program) SetJitterMaxSeconds(v int32)`

SetJitterMaxSeconds sets JitterMaxSeconds field to given value.


### GetJitterMinSeconds

`func (o *Program) GetJitterMinSeconds() int32`

GetJitterMinSeconds returns the JitterMinSeconds field if non-nil, zero value otherwise.

### GetJitterMinSecondsOk

`func (o *Program) GetJitterMinSecondsOk() (*int32, bool)`

GetJitterMinSecondsOk returns a tuple with the JitterMinSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitterMinSeconds

`func (o *Program) SetJitterMinSeconds(v int32)`

SetJitterMinSeconds sets JitterMinSeconds field to given value.


### GetKind

`func (o *Program) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Program) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Program) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *Program) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Program) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Program) SetName(v string)`

SetName sets Name field to given value.


### GetNewPerDay

`func (o *Program) GetNewPerDay() int32`

GetNewPerDay returns the NewPerDay field if non-nil, zero value otherwise.

### GetNewPerDayOk

`func (o *Program) GetNewPerDayOk() (*int32, bool)`

GetNewPerDayOk returns a tuple with the NewPerDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPerDay

`func (o *Program) SetNewPerDay(v int32)`

SetNewPerDay sets NewPerDay field to given value.


### GetObject

`func (o *Program) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Program) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Program) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Program) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Program) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Program) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPausedAt

`func (o *Program) GetPausedAt() interface{}`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *Program) GetPausedAtOk() (*interface{}, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *Program) SetPausedAt(v interface{})`

SetPausedAt sets PausedAt field to given value.

### HasPausedAt

`func (o *Program) HasPausedAt() bool`

HasPausedAt returns a boolean if a field has been set.

### SetPausedAtNil

`func (o *Program) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *Program) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedMeta

`func (o *Program) GetPausedMeta() ProgramPauseMeta`

GetPausedMeta returns the PausedMeta field if non-nil, zero value otherwise.

### GetPausedMetaOk

`func (o *Program) GetPausedMetaOk() (*ProgramPauseMeta, bool)`

GetPausedMetaOk returns a tuple with the PausedMeta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedMeta

`func (o *Program) SetPausedMeta(v ProgramPauseMeta)`

SetPausedMeta sets PausedMeta field to given value.


### SetPausedMetaNil

`func (o *Program) SetPausedMetaNil(b bool)`

 SetPausedMetaNil sets the value for PausedMeta to be an explicit nil

### UnsetPausedMeta
`func (o *Program) UnsetPausedMeta()`

UnsetPausedMeta ensures that no value is present for PausedMeta, not even an explicit nil
### GetPausedReason

`func (o *Program) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *Program) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *Program) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.


### SetPausedReasonNil

`func (o *Program) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *Program) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetPlainTextMode

`func (o *Program) GetPlainTextMode() bool`

GetPlainTextMode returns the PlainTextMode field if non-nil, zero value otherwise.

### GetPlainTextModeOk

`func (o *Program) GetPlainTextModeOk() (*bool, bool)`

GetPlainTextModeOk returns a tuple with the PlainTextMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlainTextMode

`func (o *Program) SetPlainTextMode(v bool)`

SetPlainTextMode sets PlainTextMode field to given value.


### GetSendIntervalMinutes

`func (o *Program) GetSendIntervalMinutes() int32`

GetSendIntervalMinutes returns the SendIntervalMinutes field if non-nil, zero value otherwise.

### GetSendIntervalMinutesOk

`func (o *Program) GetSendIntervalMinutesOk() (*int32, bool)`

GetSendIntervalMinutesOk returns a tuple with the SendIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendIntervalMinutes

`func (o *Program) SetSendIntervalMinutes(v int32)`

SetSendIntervalMinutes sets SendIntervalMinutes field to given value.


### GetSpamPauseThreshold

`func (o *Program) GetSpamPauseThreshold() float32`

GetSpamPauseThreshold returns the SpamPauseThreshold field if non-nil, zero value otherwise.

### GetSpamPauseThresholdOk

`func (o *Program) GetSpamPauseThresholdOk() (*float32, bool)`

GetSpamPauseThresholdOk returns a tuple with the SpamPauseThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpamPauseThreshold

`func (o *Program) SetSpamPauseThreshold(v float32)`

SetSpamPauseThreshold sets SpamPauseThreshold field to given value.


### GetStartDate

`func (o *Program) GetStartDate() interface{}`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *Program) GetStartDateOk() (*interface{}, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *Program) SetStartDate(v interface{})`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *Program) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *Program) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *Program) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetStatus

`func (o *Program) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Program) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Program) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopCondition

`func (o *Program) GetStopCondition() string`

GetStopCondition returns the StopCondition field if non-nil, zero value otherwise.

### GetStopConditionOk

`func (o *Program) GetStopConditionOk() (*string, bool)`

GetStopConditionOk returns a tuple with the StopCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopCondition

`func (o *Program) SetStopCondition(v string)`

SetStopCondition sets StopCondition field to given value.


### GetTimezone

`func (o *Program) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *Program) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *Program) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetTrackClicks

`func (o *Program) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *Program) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *Program) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.


### GetTrackingDomainId

`func (o *Program) GetTrackingDomainId() string`

GetTrackingDomainId returns the TrackingDomainId field if non-nil, zero value otherwise.

### GetTrackingDomainIdOk

`func (o *Program) GetTrackingDomainIdOk() (*string, bool)`

GetTrackingDomainIdOk returns a tuple with the TrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingDomainId

`func (o *Program) SetTrackingDomainId(v string)`

SetTrackingDomainId sets TrackingDomainId field to given value.


### SetTrackingDomainIdNil

`func (o *Program) SetTrackingDomainIdNil(b bool)`

 SetTrackingDomainIdNil sets the value for TrackingDomainId to be an explicit nil

### UnsetTrackingDomainId
`func (o *Program) UnsetTrackingDomainId()`

UnsetTrackingDomainId ensures that no value is present for TrackingDomainId, not even an explicit nil
### GetTrackOpens

`func (o *Program) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *Program) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *Program) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.


### GetUnsubscribeText

`func (o *Program) GetUnsubscribeText() string`

GetUnsubscribeText returns the UnsubscribeText field if non-nil, zero value otherwise.

### GetUnsubscribeTextOk

`func (o *Program) GetUnsubscribeTextOk() (*string, bool)`

GetUnsubscribeTextOk returns a tuple with the UnsubscribeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribeText

`func (o *Program) SetUnsubscribeText(v string)`

SetUnsubscribeText sets UnsubscribeText field to given value.


### SetUnsubscribeTextNil

`func (o *Program) SetUnsubscribeTextNil(b bool)`

 SetUnsubscribeTextNil sets the value for UnsubscribeText to be an explicit nil

### UnsetUnsubscribeText
`func (o *Program) UnsetUnsubscribeText()`

UnsetUnsubscribeText ensures that no value is present for UnsubscribeText, not even an explicit nil
### GetUpdatedAt

`func (o *Program) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Program) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Program) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Program) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Program) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Program) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetVariantDistribution

`func (o *Program) GetVariantDistribution() string`

GetVariantDistribution returns the VariantDistribution field if non-nil, zero value otherwise.

### GetVariantDistributionOk

`func (o *Program) GetVariantDistributionOk() (*string, bool)`

GetVariantDistributionOk returns a tuple with the VariantDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantDistribution

`func (o *Program) SetVariantDistribution(v string)`

SetVariantDistribution sets VariantDistribution field to given value.


### GetWindowFrom

`func (o *Program) GetWindowFrom() string`

GetWindowFrom returns the WindowFrom field if non-nil, zero value otherwise.

### GetWindowFromOk

`func (o *Program) GetWindowFromOk() (*string, bool)`

GetWindowFromOk returns a tuple with the WindowFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowFrom

`func (o *Program) SetWindowFrom(v string)`

SetWindowFrom sets WindowFrom field to given value.


### SetWindowFromNil

`func (o *Program) SetWindowFromNil(b bool)`

 SetWindowFromNil sets the value for WindowFrom to be an explicit nil

### UnsetWindowFrom
`func (o *Program) UnsetWindowFrom()`

UnsetWindowFrom ensures that no value is present for WindowFrom, not even an explicit nil
### GetWindowTo

`func (o *Program) GetWindowTo() string`

GetWindowTo returns the WindowTo field if non-nil, zero value otherwise.

### GetWindowToOk

`func (o *Program) GetWindowToOk() (*string, bool)`

GetWindowToOk returns a tuple with the WindowTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTo

`func (o *Program) SetWindowTo(v string)`

SetWindowTo sets WindowTo field to given value.


### SetWindowToNil

`func (o *Program) SetWindowToNil(b bool)`

 SetWindowToNil sets the value for WindowTo to be an explicit nil

### UnsetWindowTo
`func (o *Program) UnsetWindowTo()`

UnsetWindowTo ensures that no value is present for WindowTo, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


