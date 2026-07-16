# PulseSenderFleet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domains** | **float32** | Distinct sending domains in use. Example: 4 | 
**Healthy** | **float32** | Mailboxes in the healthy state. Example: 10 | 
**Paused** | **float32** | Mailboxes paused. Example: 1 | 
**ReputationBad** | **float32** | Mailboxes with bad reputation. Example: 0 | 
**ReputationWarning** | **float32** | Mailboxes with warning reputation. Example: 2 | 
**Throttled** | **float32** | Mailboxes throttled. Example: 1 | 
**Total** | **float32** | Live (non-archived) mailboxes. Example: 12 | 

## Methods

### NewPulseSenderFleet

`func NewPulseSenderFleet(domains float32, healthy float32, paused float32, reputationBad float32, reputationWarning float32, throttled float32, total float32, ) *PulseSenderFleet`

NewPulseSenderFleet instantiates a new PulseSenderFleet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPulseSenderFleetWithDefaults

`func NewPulseSenderFleetWithDefaults() *PulseSenderFleet`

NewPulseSenderFleetWithDefaults instantiates a new PulseSenderFleet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomains

`func (o *PulseSenderFleet) GetDomains() float32`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *PulseSenderFleet) GetDomainsOk() (*float32, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *PulseSenderFleet) SetDomains(v float32)`

SetDomains sets Domains field to given value.


### GetHealthy

`func (o *PulseSenderFleet) GetHealthy() float32`

GetHealthy returns the Healthy field if non-nil, zero value otherwise.

### GetHealthyOk

`func (o *PulseSenderFleet) GetHealthyOk() (*float32, bool)`

GetHealthyOk returns a tuple with the Healthy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthy

`func (o *PulseSenderFleet) SetHealthy(v float32)`

SetHealthy sets Healthy field to given value.


### GetPaused

`func (o *PulseSenderFleet) GetPaused() float32`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *PulseSenderFleet) GetPausedOk() (*float32, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *PulseSenderFleet) SetPaused(v float32)`

SetPaused sets Paused field to given value.


### GetReputationBad

`func (o *PulseSenderFleet) GetReputationBad() float32`

GetReputationBad returns the ReputationBad field if non-nil, zero value otherwise.

### GetReputationBadOk

`func (o *PulseSenderFleet) GetReputationBadOk() (*float32, bool)`

GetReputationBadOk returns a tuple with the ReputationBad field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputationBad

`func (o *PulseSenderFleet) SetReputationBad(v float32)`

SetReputationBad sets ReputationBad field to given value.


### GetReputationWarning

`func (o *PulseSenderFleet) GetReputationWarning() float32`

GetReputationWarning returns the ReputationWarning field if non-nil, zero value otherwise.

### GetReputationWarningOk

`func (o *PulseSenderFleet) GetReputationWarningOk() (*float32, bool)`

GetReputationWarningOk returns a tuple with the ReputationWarning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputationWarning

`func (o *PulseSenderFleet) SetReputationWarning(v float32)`

SetReputationWarning sets ReputationWarning field to given value.


### GetThrottled

`func (o *PulseSenderFleet) GetThrottled() float32`

GetThrottled returns the Throttled field if non-nil, zero value otherwise.

### GetThrottledOk

`func (o *PulseSenderFleet) GetThrottledOk() (*float32, bool)`

GetThrottledOk returns a tuple with the Throttled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrottled

`func (o *PulseSenderFleet) SetThrottled(v float32)`

SetThrottled sets Throttled field to given value.


### GetTotal

`func (o *PulseSenderFleet) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PulseSenderFleet) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PulseSenderFleet) SetTotal(v float32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


