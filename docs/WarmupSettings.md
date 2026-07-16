# WarmupSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AutoAdjust** | **bool** | Automatically adapt warmup volume and matching over time. | 
**CustomTemplates** | Pointer to [**[]WarmupTemplate**](WarmupTemplate.md) | Your own copy to warm — used for a share of daily openers. | [optional] 
**DailyMax** | **int32** | Ramp ceiling (max warmup sends per day). | 
**DailyTarget** | **int32** | Warmup sends targeted today. | 
**Enabled** | **bool** | Whether warmup is active for this mailbox. | 
**Language** | Pointer to **string** | Language for stock warmup conversations: English or Spanish (default en). | [optional] 
**RampupEnabled** | **bool** | Grow the daily target over time. | 
**RampupIncrement** | **int32** | Daily increase applied to the target while ramping. | 
**ReplyRate** | **float32** | Fraction of warmup mail replied to, from 0 to 1. | 
**Timezone** | Pointer to **string** | IANA timezone the sending window is evaluated in. | [optional] 
**Topics** | Pointer to **[]string** | Optional topics woven into stock warmup openers. | [optional] 
**WeekdaysOnly** | **bool** | Skip weekends. | 
**WindowFrom** | Pointer to **string** | Window open, \&quot;HH:MM\&quot; in the mailbox timezone. | [optional] 
**WindowTo** | Pointer to **string** | Window close, \&quot;HH:MM\&quot; in the mailbox timezone. | [optional] 

## Methods

### NewWarmupSettings

`func NewWarmupSettings(autoAdjust bool, dailyMax int32, dailyTarget int32, enabled bool, rampupEnabled bool, rampupIncrement int32, replyRate float32, weekdaysOnly bool, ) *WarmupSettings`

NewWarmupSettings instantiates a new WarmupSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarmupSettingsWithDefaults

`func NewWarmupSettingsWithDefaults() *WarmupSettings`

NewWarmupSettingsWithDefaults instantiates a new WarmupSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAutoAdjust

`func (o *WarmupSettings) GetAutoAdjust() bool`

GetAutoAdjust returns the AutoAdjust field if non-nil, zero value otherwise.

### GetAutoAdjustOk

`func (o *WarmupSettings) GetAutoAdjustOk() (*bool, bool)`

GetAutoAdjustOk returns a tuple with the AutoAdjust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoAdjust

`func (o *WarmupSettings) SetAutoAdjust(v bool)`

SetAutoAdjust sets AutoAdjust field to given value.


### GetCustomTemplates

`func (o *WarmupSettings) GetCustomTemplates() []WarmupTemplate`

GetCustomTemplates returns the CustomTemplates field if non-nil, zero value otherwise.

### GetCustomTemplatesOk

`func (o *WarmupSettings) GetCustomTemplatesOk() (*[]WarmupTemplate, bool)`

GetCustomTemplatesOk returns a tuple with the CustomTemplates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomTemplates

`func (o *WarmupSettings) SetCustomTemplates(v []WarmupTemplate)`

SetCustomTemplates sets CustomTemplates field to given value.

### HasCustomTemplates

`func (o *WarmupSettings) HasCustomTemplates() bool`

HasCustomTemplates returns a boolean if a field has been set.

### GetDailyMax

`func (o *WarmupSettings) GetDailyMax() int32`

GetDailyMax returns the DailyMax field if non-nil, zero value otherwise.

### GetDailyMaxOk

`func (o *WarmupSettings) GetDailyMaxOk() (*int32, bool)`

GetDailyMaxOk returns a tuple with the DailyMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyMax

`func (o *WarmupSettings) SetDailyMax(v int32)`

SetDailyMax sets DailyMax field to given value.


### GetDailyTarget

`func (o *WarmupSettings) GetDailyTarget() int32`

GetDailyTarget returns the DailyTarget field if non-nil, zero value otherwise.

### GetDailyTargetOk

`func (o *WarmupSettings) GetDailyTargetOk() (*int32, bool)`

GetDailyTargetOk returns a tuple with the DailyTarget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyTarget

`func (o *WarmupSettings) SetDailyTarget(v int32)`

SetDailyTarget sets DailyTarget field to given value.


### GetEnabled

`func (o *WarmupSettings) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WarmupSettings) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WarmupSettings) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetLanguage

`func (o *WarmupSettings) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *WarmupSettings) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *WarmupSettings) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *WarmupSettings) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetRampupEnabled

`func (o *WarmupSettings) GetRampupEnabled() bool`

GetRampupEnabled returns the RampupEnabled field if non-nil, zero value otherwise.

### GetRampupEnabledOk

`func (o *WarmupSettings) GetRampupEnabledOk() (*bool, bool)`

GetRampupEnabledOk returns a tuple with the RampupEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRampupEnabled

`func (o *WarmupSettings) SetRampupEnabled(v bool)`

SetRampupEnabled sets RampupEnabled field to given value.


### GetRampupIncrement

`func (o *WarmupSettings) GetRampupIncrement() int32`

GetRampupIncrement returns the RampupIncrement field if non-nil, zero value otherwise.

### GetRampupIncrementOk

`func (o *WarmupSettings) GetRampupIncrementOk() (*int32, bool)`

GetRampupIncrementOk returns a tuple with the RampupIncrement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRampupIncrement

`func (o *WarmupSettings) SetRampupIncrement(v int32)`

SetRampupIncrement sets RampupIncrement field to given value.


### GetReplyRate

`func (o *WarmupSettings) GetReplyRate() float32`

GetReplyRate returns the ReplyRate field if non-nil, zero value otherwise.

### GetReplyRateOk

`func (o *WarmupSettings) GetReplyRateOk() (*float32, bool)`

GetReplyRateOk returns a tuple with the ReplyRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyRate

`func (o *WarmupSettings) SetReplyRate(v float32)`

SetReplyRate sets ReplyRate field to given value.


### GetTimezone

`func (o *WarmupSettings) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *WarmupSettings) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *WarmupSettings) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *WarmupSettings) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetTopics

`func (o *WarmupSettings) GetTopics() []string`

GetTopics returns the Topics field if non-nil, zero value otherwise.

### GetTopicsOk

`func (o *WarmupSettings) GetTopicsOk() (*[]string, bool)`

GetTopicsOk returns a tuple with the Topics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopics

`func (o *WarmupSettings) SetTopics(v []string)`

SetTopics sets Topics field to given value.

### HasTopics

`func (o *WarmupSettings) HasTopics() bool`

HasTopics returns a boolean if a field has been set.

### GetWeekdaysOnly

`func (o *WarmupSettings) GetWeekdaysOnly() bool`

GetWeekdaysOnly returns the WeekdaysOnly field if non-nil, zero value otherwise.

### GetWeekdaysOnlyOk

`func (o *WarmupSettings) GetWeekdaysOnlyOk() (*bool, bool)`

GetWeekdaysOnlyOk returns a tuple with the WeekdaysOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeekdaysOnly

`func (o *WarmupSettings) SetWeekdaysOnly(v bool)`

SetWeekdaysOnly sets WeekdaysOnly field to given value.


### GetWindowFrom

`func (o *WarmupSettings) GetWindowFrom() string`

GetWindowFrom returns the WindowFrom field if non-nil, zero value otherwise.

### GetWindowFromOk

`func (o *WarmupSettings) GetWindowFromOk() (*string, bool)`

GetWindowFromOk returns a tuple with the WindowFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowFrom

`func (o *WarmupSettings) SetWindowFrom(v string)`

SetWindowFrom sets WindowFrom field to given value.

### HasWindowFrom

`func (o *WarmupSettings) HasWindowFrom() bool`

HasWindowFrom returns a boolean if a field has been set.

### GetWindowTo

`func (o *WarmupSettings) GetWindowTo() string`

GetWindowTo returns the WindowTo field if non-nil, zero value otherwise.

### GetWindowToOk

`func (o *WarmupSettings) GetWindowToOk() (*string, bool)`

GetWindowToOk returns a tuple with the WindowTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTo

`func (o *WarmupSettings) SetWindowTo(v string)`

SetWindowTo sets WindowTo field to given value.

### HasWindowTo

`func (o *WarmupSettings) HasWindowTo() bool`

HasWindowTo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


