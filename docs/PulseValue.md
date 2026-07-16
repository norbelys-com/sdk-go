# PulseValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meetings** | **float32** | Meetings booked in the window (calendar integrations + meeting-commitment replies). Example: 7 | 
**PositiveReplies** | **float32** | Replies classified as interested. Example: 15 | 
**Replies** | **float32** | Total replies in the window. Example: 48 | 
**Sent** | **float32** | Messages sent in the window. Example: 2100 | 
**Unsubscribes** | **float32** | Unsubscribes in the window. Example: 6 | 

## Methods

### NewPulseValue

`func NewPulseValue(meetings float32, positiveReplies float32, replies float32, sent float32, unsubscribes float32, ) *PulseValue`

NewPulseValue instantiates a new PulseValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPulseValueWithDefaults

`func NewPulseValueWithDefaults() *PulseValue`

NewPulseValueWithDefaults instantiates a new PulseValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeetings

`func (o *PulseValue) GetMeetings() float32`

GetMeetings returns the Meetings field if non-nil, zero value otherwise.

### GetMeetingsOk

`func (o *PulseValue) GetMeetingsOk() (*float32, bool)`

GetMeetingsOk returns a tuple with the Meetings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeetings

`func (o *PulseValue) SetMeetings(v float32)`

SetMeetings sets Meetings field to given value.


### GetPositiveReplies

`func (o *PulseValue) GetPositiveReplies() float32`

GetPositiveReplies returns the PositiveReplies field if non-nil, zero value otherwise.

### GetPositiveRepliesOk

`func (o *PulseValue) GetPositiveRepliesOk() (*float32, bool)`

GetPositiveRepliesOk returns a tuple with the PositiveReplies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveReplies

`func (o *PulseValue) SetPositiveReplies(v float32)`

SetPositiveReplies sets PositiveReplies field to given value.


### GetReplies

`func (o *PulseValue) GetReplies() float32`

GetReplies returns the Replies field if non-nil, zero value otherwise.

### GetRepliesOk

`func (o *PulseValue) GetRepliesOk() (*float32, bool)`

GetRepliesOk returns a tuple with the Replies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplies

`func (o *PulseValue) SetReplies(v float32)`

SetReplies sets Replies field to given value.


### GetSent

`func (o *PulseValue) GetSent() float32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *PulseValue) GetSentOk() (*float32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *PulseValue) SetSent(v float32)`

SetSent sets Sent field to given value.


### GetUnsubscribes

`func (o *PulseValue) GetUnsubscribes() float32`

GetUnsubscribes returns the Unsubscribes field if non-nil, zero value otherwise.

### GetUnsubscribesOk

`func (o *PulseValue) GetUnsubscribesOk() (*float32, bool)`

GetUnsubscribesOk returns a tuple with the Unsubscribes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribes

`func (o *PulseValue) SetUnsubscribes(v float32)`

SetUnsubscribes sets Unsubscribes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


