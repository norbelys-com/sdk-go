# AnalyticsQueryParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | Pointer to **string** | The outbound message id. Required by the message_events query; returns every event for that one send. | [optional] 
**Days** | Pointer to **int32** | Lookback window in days (alternative to since/until). | [optional] 
**Dir** | Pointer to **string** | Sort direction for activity_feed (default desc). | [optional] 
**Domain** | Pointer to **string** | The monitored domain name. Required by dmarc_summary / dmarc_sources; optional on dmarc_reports / dmarc_receivers — omit for the account-wide feed. Example: acme.com | [optional] 
**ExcludeMachine** | Pointer to **bool** | activity_feed only: exclude machine-generated engagement — opens not classified as human (e.g. automated inbox prefetches) and any bot-classified event. | [optional] 
**Limit** | Pointer to **int32** | Max rows returned. | [optional] 
**Offset** | Pointer to **int32** | Rows to skip (activity_feed paging). | [optional] 
**OrderBy** | Pointer to **string** | Sort column for activity_feed. Example: occurred_at | [optional] 
**Person** | Pointer to **string** | Scope to one person (person id). Used by: contact_events. | [optional] 
**Program** | Pointer to **string** | Scope to one campaign (program id). Used by: activity_feed, program_funnel, sender_breakdown, variant_performance. | [optional] 
**Receiver** | Pointer to **string** | Narrow the DMARC queries to ONE reporter (receiver) — &#39;show me only what Gmail saw&#39;. Used by: dmarc_summary, dmarc_sources, dmarc_geo, dmarc_reports. | [optional] 
**Search** | Pointer to **string** | Free-text search (activity_feed: matches recipient/subject). | [optional] 
**Sender** | Pointer to **string** | Scope to one sender — by id (\&quot;snd_…\&quot;) or by its from address (\&quot;receipts@hola.com\&quot;); both filter identically. Used by: activity_feed, sender_health, warmup_placement. | [optional] 
**Since** | Pointer to **string** | Window start (ISO 8601). Most queries default to the last 30 days. | [optional] 
**Thread** | Pointer to **string** | A conversation (thread) id — narrows agent_trace to one conversation. | [optional] 
**Type** | Pointer to **string** | Filter to one event type. | [optional] 
**Until** | Pointer to **string** | Window end (ISO 8601). | [optional] 

## Methods

### NewAnalyticsQueryParams

`func NewAnalyticsQueryParams() *AnalyticsQueryParams`

NewAnalyticsQueryParams instantiates a new AnalyticsQueryParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsQueryParamsWithDefaults

`func NewAnalyticsQueryParamsWithDefaults() *AnalyticsQueryParams`

NewAnalyticsQueryParamsWithDefaults instantiates a new AnalyticsQueryParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivity

`func (o *AnalyticsQueryParams) GetActivity() string`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *AnalyticsQueryParams) GetActivityOk() (*string, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *AnalyticsQueryParams) SetActivity(v string)`

SetActivity sets Activity field to given value.

### HasActivity

`func (o *AnalyticsQueryParams) HasActivity() bool`

HasActivity returns a boolean if a field has been set.

### GetDays

`func (o *AnalyticsQueryParams) GetDays() int32`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *AnalyticsQueryParams) GetDaysOk() (*int32, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *AnalyticsQueryParams) SetDays(v int32)`

SetDays sets Days field to given value.

### HasDays

`func (o *AnalyticsQueryParams) HasDays() bool`

HasDays returns a boolean if a field has been set.

### GetDir

`func (o *AnalyticsQueryParams) GetDir() string`

GetDir returns the Dir field if non-nil, zero value otherwise.

### GetDirOk

`func (o *AnalyticsQueryParams) GetDirOk() (*string, bool)`

GetDirOk returns a tuple with the Dir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDir

`func (o *AnalyticsQueryParams) SetDir(v string)`

SetDir sets Dir field to given value.

### HasDir

`func (o *AnalyticsQueryParams) HasDir() bool`

HasDir returns a boolean if a field has been set.

### GetDomain

`func (o *AnalyticsQueryParams) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AnalyticsQueryParams) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AnalyticsQueryParams) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *AnalyticsQueryParams) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetExcludeMachine

`func (o *AnalyticsQueryParams) GetExcludeMachine() bool`

GetExcludeMachine returns the ExcludeMachine field if non-nil, zero value otherwise.

### GetExcludeMachineOk

`func (o *AnalyticsQueryParams) GetExcludeMachineOk() (*bool, bool)`

GetExcludeMachineOk returns a tuple with the ExcludeMachine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeMachine

`func (o *AnalyticsQueryParams) SetExcludeMachine(v bool)`

SetExcludeMachine sets ExcludeMachine field to given value.

### HasExcludeMachine

`func (o *AnalyticsQueryParams) HasExcludeMachine() bool`

HasExcludeMachine returns a boolean if a field has been set.

### GetLimit

`func (o *AnalyticsQueryParams) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AnalyticsQueryParams) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AnalyticsQueryParams) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AnalyticsQueryParams) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *AnalyticsQueryParams) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *AnalyticsQueryParams) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *AnalyticsQueryParams) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *AnalyticsQueryParams) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetOrderBy

`func (o *AnalyticsQueryParams) GetOrderBy() string`

GetOrderBy returns the OrderBy field if non-nil, zero value otherwise.

### GetOrderByOk

`func (o *AnalyticsQueryParams) GetOrderByOk() (*string, bool)`

GetOrderByOk returns a tuple with the OrderBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBy

`func (o *AnalyticsQueryParams) SetOrderBy(v string)`

SetOrderBy sets OrderBy field to given value.

### HasOrderBy

`func (o *AnalyticsQueryParams) HasOrderBy() bool`

HasOrderBy returns a boolean if a field has been set.

### GetPerson

`func (o *AnalyticsQueryParams) GetPerson() string`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *AnalyticsQueryParams) GetPersonOk() (*string, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *AnalyticsQueryParams) SetPerson(v string)`

SetPerson sets Person field to given value.

### HasPerson

`func (o *AnalyticsQueryParams) HasPerson() bool`

HasPerson returns a boolean if a field has been set.

### GetProgram

`func (o *AnalyticsQueryParams) GetProgram() string`

GetProgram returns the Program field if non-nil, zero value otherwise.

### GetProgramOk

`func (o *AnalyticsQueryParams) GetProgramOk() (*string, bool)`

GetProgramOk returns a tuple with the Program field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgram

`func (o *AnalyticsQueryParams) SetProgram(v string)`

SetProgram sets Program field to given value.

### HasProgram

`func (o *AnalyticsQueryParams) HasProgram() bool`

HasProgram returns a boolean if a field has been set.

### GetReceiver

`func (o *AnalyticsQueryParams) GetReceiver() string`

GetReceiver returns the Receiver field if non-nil, zero value otherwise.

### GetReceiverOk

`func (o *AnalyticsQueryParams) GetReceiverOk() (*string, bool)`

GetReceiverOk returns a tuple with the Receiver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiver

`func (o *AnalyticsQueryParams) SetReceiver(v string)`

SetReceiver sets Receiver field to given value.

### HasReceiver

`func (o *AnalyticsQueryParams) HasReceiver() bool`

HasReceiver returns a boolean if a field has been set.

### GetSearch

`func (o *AnalyticsQueryParams) GetSearch() string`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *AnalyticsQueryParams) GetSearchOk() (*string, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *AnalyticsQueryParams) SetSearch(v string)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *AnalyticsQueryParams) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### GetSender

`func (o *AnalyticsQueryParams) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *AnalyticsQueryParams) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *AnalyticsQueryParams) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *AnalyticsQueryParams) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetSince

`func (o *AnalyticsQueryParams) GetSince() string`

GetSince returns the Since field if non-nil, zero value otherwise.

### GetSinceOk

`func (o *AnalyticsQueryParams) GetSinceOk() (*string, bool)`

GetSinceOk returns a tuple with the Since field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSince

`func (o *AnalyticsQueryParams) SetSince(v string)`

SetSince sets Since field to given value.

### HasSince

`func (o *AnalyticsQueryParams) HasSince() bool`

HasSince returns a boolean if a field has been set.

### GetThread

`func (o *AnalyticsQueryParams) GetThread() string`

GetThread returns the Thread field if non-nil, zero value otherwise.

### GetThreadOk

`func (o *AnalyticsQueryParams) GetThreadOk() (*string, bool)`

GetThreadOk returns a tuple with the Thread field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThread

`func (o *AnalyticsQueryParams) SetThread(v string)`

SetThread sets Thread field to given value.

### HasThread

`func (o *AnalyticsQueryParams) HasThread() bool`

HasThread returns a boolean if a field has been set.

### GetType

`func (o *AnalyticsQueryParams) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AnalyticsQueryParams) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AnalyticsQueryParams) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AnalyticsQueryParams) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUntil

`func (o *AnalyticsQueryParams) GetUntil() string`

GetUntil returns the Until field if non-nil, zero value otherwise.

### GetUntilOk

`func (o *AnalyticsQueryParams) GetUntilOk() (*string, bool)`

GetUntilOk returns a tuple with the Until field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUntil

`func (o *AnalyticsQueryParams) SetUntil(v string)`

SetUntil sets Until field to given value.

### HasUntil

`func (o *AnalyticsQueryParams) HasUntil() bool`

HasUntil returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


