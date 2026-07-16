# PulseProgram

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bounces** | **float32** | Hard bounces in the window. Example: 3 | 
**Clicks** | **float32** | Clicks in the window. Example: 58 | 
**Completion** | **float32** | Fraction of leads in a terminal state (0-1). Example: 0.35 | 
**Id** | **string** | The program id. Example: prg_8kd0f2n1x7q4 | 
**Leads** | **float32** | Live (non-archived) enrollments. Example: 1240 | 
**Name** | **string** | The campaign&#39;s display name. Example: Q3 Outbound — Founders | 
**NextSendAt** | Pointer to **interface{}** |  | [optional] 
**OpenRate** | **float32** | Opens ÷ delivered in the window (0-1). Example: 0.42 | 
**Opens** | **float32** | Opens in the window. Example: 312 | 
**Replies** | **float32** | Replies in the window. Example: 24 | 
**ReplyRate** | **float32** | Replies ÷ delivered in the window (0-1). Example: 0.08 | 
**Sent** | **float32** | Messages sent in the window. Example: 740 | 
**Status** | **string** | Campaign status: draft, active, paused, or done. Example: active | 

## Methods

### NewPulseProgram

`func NewPulseProgram(bounces float32, clicks float32, completion float32, id string, leads float32, name string, openRate float32, opens float32, replies float32, replyRate float32, sent float32, status string, ) *PulseProgram`

NewPulseProgram instantiates a new PulseProgram object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPulseProgramWithDefaults

`func NewPulseProgramWithDefaults() *PulseProgram`

NewPulseProgramWithDefaults instantiates a new PulseProgram object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBounces

`func (o *PulseProgram) GetBounces() float32`

GetBounces returns the Bounces field if non-nil, zero value otherwise.

### GetBouncesOk

`func (o *PulseProgram) GetBouncesOk() (*float32, bool)`

GetBouncesOk returns a tuple with the Bounces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBounces

`func (o *PulseProgram) SetBounces(v float32)`

SetBounces sets Bounces field to given value.


### GetClicks

`func (o *PulseProgram) GetClicks() float32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *PulseProgram) GetClicksOk() (*float32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *PulseProgram) SetClicks(v float32)`

SetClicks sets Clicks field to given value.


### GetCompletion

`func (o *PulseProgram) GetCompletion() float32`

GetCompletion returns the Completion field if non-nil, zero value otherwise.

### GetCompletionOk

`func (o *PulseProgram) GetCompletionOk() (*float32, bool)`

GetCompletionOk returns a tuple with the Completion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletion

`func (o *PulseProgram) SetCompletion(v float32)`

SetCompletion sets Completion field to given value.


### GetId

`func (o *PulseProgram) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PulseProgram) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PulseProgram) SetId(v string)`

SetId sets Id field to given value.


### GetLeads

`func (o *PulseProgram) GetLeads() float32`

GetLeads returns the Leads field if non-nil, zero value otherwise.

### GetLeadsOk

`func (o *PulseProgram) GetLeadsOk() (*float32, bool)`

GetLeadsOk returns a tuple with the Leads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeads

`func (o *PulseProgram) SetLeads(v float32)`

SetLeads sets Leads field to given value.


### GetName

`func (o *PulseProgram) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PulseProgram) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PulseProgram) SetName(v string)`

SetName sets Name field to given value.


### GetNextSendAt

`func (o *PulseProgram) GetNextSendAt() interface{}`

GetNextSendAt returns the NextSendAt field if non-nil, zero value otherwise.

### GetNextSendAtOk

`func (o *PulseProgram) GetNextSendAtOk() (*interface{}, bool)`

GetNextSendAtOk returns a tuple with the NextSendAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextSendAt

`func (o *PulseProgram) SetNextSendAt(v interface{})`

SetNextSendAt sets NextSendAt field to given value.

### HasNextSendAt

`func (o *PulseProgram) HasNextSendAt() bool`

HasNextSendAt returns a boolean if a field has been set.

### SetNextSendAtNil

`func (o *PulseProgram) SetNextSendAtNil(b bool)`

 SetNextSendAtNil sets the value for NextSendAt to be an explicit nil

### UnsetNextSendAt
`func (o *PulseProgram) UnsetNextSendAt()`

UnsetNextSendAt ensures that no value is present for NextSendAt, not even an explicit nil
### GetOpenRate

`func (o *PulseProgram) GetOpenRate() float32`

GetOpenRate returns the OpenRate field if non-nil, zero value otherwise.

### GetOpenRateOk

`func (o *PulseProgram) GetOpenRateOk() (*float32, bool)`

GetOpenRateOk returns a tuple with the OpenRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenRate

`func (o *PulseProgram) SetOpenRate(v float32)`

SetOpenRate sets OpenRate field to given value.


### GetOpens

`func (o *PulseProgram) GetOpens() float32`

GetOpens returns the Opens field if non-nil, zero value otherwise.

### GetOpensOk

`func (o *PulseProgram) GetOpensOk() (*float32, bool)`

GetOpensOk returns a tuple with the Opens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpens

`func (o *PulseProgram) SetOpens(v float32)`

SetOpens sets Opens field to given value.


### GetReplies

`func (o *PulseProgram) GetReplies() float32`

GetReplies returns the Replies field if non-nil, zero value otherwise.

### GetRepliesOk

`func (o *PulseProgram) GetRepliesOk() (*float32, bool)`

GetRepliesOk returns a tuple with the Replies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplies

`func (o *PulseProgram) SetReplies(v float32)`

SetReplies sets Replies field to given value.


### GetReplyRate

`func (o *PulseProgram) GetReplyRate() float32`

GetReplyRate returns the ReplyRate field if non-nil, zero value otherwise.

### GetReplyRateOk

`func (o *PulseProgram) GetReplyRateOk() (*float32, bool)`

GetReplyRateOk returns a tuple with the ReplyRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyRate

`func (o *PulseProgram) SetReplyRate(v float32)`

SetReplyRate sets ReplyRate field to given value.


### GetSent

`func (o *PulseProgram) GetSent() float32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *PulseProgram) GetSentOk() (*float32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *PulseProgram) SetSent(v float32)`

SetSent sets Sent field to given value.


### GetStatus

`func (o *PulseProgram) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PulseProgram) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PulseProgram) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


