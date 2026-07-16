# PulseDeliverability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BounceRate** | **float32** | All bounces ÷ sent (0-1). Example: 0.02 | 
**Bounces** | **float32** | Hard + soft bounces in the window. Example: 14 | 
**Complaints** | **float32** | Spam complaints in the window. Example: 1 | 
**HardBounceRate** | **float32** | Hard bounces ÷ sent (0-1). Example: 0.01 | 
**Sent** | **float32** | Messages sent in the window. Example: 2100 | 
**SpamRate** | **float32** | Complaints ÷ sent (0-1). Example: 0.0005 | 
**Unsubscribes** | **float32** | Unsubscribes in the window. Example: 6 | 

## Methods

### NewPulseDeliverability

`func NewPulseDeliverability(bounceRate float32, bounces float32, complaints float32, hardBounceRate float32, sent float32, spamRate float32, unsubscribes float32, ) *PulseDeliverability`

NewPulseDeliverability instantiates a new PulseDeliverability object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPulseDeliverabilityWithDefaults

`func NewPulseDeliverabilityWithDefaults() *PulseDeliverability`

NewPulseDeliverabilityWithDefaults instantiates a new PulseDeliverability object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBounceRate

`func (o *PulseDeliverability) GetBounceRate() float32`

GetBounceRate returns the BounceRate field if non-nil, zero value otherwise.

### GetBounceRateOk

`func (o *PulseDeliverability) GetBounceRateOk() (*float32, bool)`

GetBounceRateOk returns a tuple with the BounceRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBounceRate

`func (o *PulseDeliverability) SetBounceRate(v float32)`

SetBounceRate sets BounceRate field to given value.


### GetBounces

`func (o *PulseDeliverability) GetBounces() float32`

GetBounces returns the Bounces field if non-nil, zero value otherwise.

### GetBouncesOk

`func (o *PulseDeliverability) GetBouncesOk() (*float32, bool)`

GetBouncesOk returns a tuple with the Bounces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBounces

`func (o *PulseDeliverability) SetBounces(v float32)`

SetBounces sets Bounces field to given value.


### GetComplaints

`func (o *PulseDeliverability) GetComplaints() float32`

GetComplaints returns the Complaints field if non-nil, zero value otherwise.

### GetComplaintsOk

`func (o *PulseDeliverability) GetComplaintsOk() (*float32, bool)`

GetComplaintsOk returns a tuple with the Complaints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplaints

`func (o *PulseDeliverability) SetComplaints(v float32)`

SetComplaints sets Complaints field to given value.


### GetHardBounceRate

`func (o *PulseDeliverability) GetHardBounceRate() float32`

GetHardBounceRate returns the HardBounceRate field if non-nil, zero value otherwise.

### GetHardBounceRateOk

`func (o *PulseDeliverability) GetHardBounceRateOk() (*float32, bool)`

GetHardBounceRateOk returns a tuple with the HardBounceRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHardBounceRate

`func (o *PulseDeliverability) SetHardBounceRate(v float32)`

SetHardBounceRate sets HardBounceRate field to given value.


### GetSent

`func (o *PulseDeliverability) GetSent() float32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *PulseDeliverability) GetSentOk() (*float32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *PulseDeliverability) SetSent(v float32)`

SetSent sets Sent field to given value.


### GetSpamRate

`func (o *PulseDeliverability) GetSpamRate() float32`

GetSpamRate returns the SpamRate field if non-nil, zero value otherwise.

### GetSpamRateOk

`func (o *PulseDeliverability) GetSpamRateOk() (*float32, bool)`

GetSpamRateOk returns a tuple with the SpamRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpamRate

`func (o *PulseDeliverability) SetSpamRate(v float32)`

SetSpamRate sets SpamRate field to given value.


### GetUnsubscribes

`func (o *PulseDeliverability) GetUnsubscribes() float32`

GetUnsubscribes returns the Unsubscribes field if non-nil, zero value otherwise.

### GetUnsubscribesOk

`func (o *PulseDeliverability) GetUnsubscribesOk() (*float32, bool)`

GetUnsubscribesOk returns a tuple with the Unsubscribes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribes

`func (o *PulseDeliverability) SetUnsubscribes(v float32)`

SetUnsubscribes sets Unsubscribes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


