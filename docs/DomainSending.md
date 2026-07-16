# DomainSending

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Capacity** | [**DomainCapacity**](DomainCapacity.md) |  | 
**DefaultTrackingDomainId** | **NullableString** |  | 
**Health** | [**DomainHealth**](DomainHealth.md) |  | 
**Policy** | [**DomainSendingPolicy**](DomainSendingPolicy.md) |  | 
**SenderCount** | **int32** | Number of mailboxes attached to this sending domain. | 

## Methods

### NewDomainSending

`func NewDomainSending(capacity DomainCapacity, defaultTrackingDomainId NullableString, health DomainHealth, policy DomainSendingPolicy, senderCount int32, ) *DomainSending`

NewDomainSending instantiates a new DomainSending object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainSendingWithDefaults

`func NewDomainSendingWithDefaults() *DomainSending`

NewDomainSendingWithDefaults instantiates a new DomainSending object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCapacity

`func (o *DomainSending) GetCapacity() DomainCapacity`

GetCapacity returns the Capacity field if non-nil, zero value otherwise.

### GetCapacityOk

`func (o *DomainSending) GetCapacityOk() (*DomainCapacity, bool)`

GetCapacityOk returns a tuple with the Capacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacity

`func (o *DomainSending) SetCapacity(v DomainCapacity)`

SetCapacity sets Capacity field to given value.


### GetDefaultTrackingDomainId

`func (o *DomainSending) GetDefaultTrackingDomainId() string`

GetDefaultTrackingDomainId returns the DefaultTrackingDomainId field if non-nil, zero value otherwise.

### GetDefaultTrackingDomainIdOk

`func (o *DomainSending) GetDefaultTrackingDomainIdOk() (*string, bool)`

GetDefaultTrackingDomainIdOk returns a tuple with the DefaultTrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTrackingDomainId

`func (o *DomainSending) SetDefaultTrackingDomainId(v string)`

SetDefaultTrackingDomainId sets DefaultTrackingDomainId field to given value.


### SetDefaultTrackingDomainIdNil

`func (o *DomainSending) SetDefaultTrackingDomainIdNil(b bool)`

 SetDefaultTrackingDomainIdNil sets the value for DefaultTrackingDomainId to be an explicit nil

### UnsetDefaultTrackingDomainId
`func (o *DomainSending) UnsetDefaultTrackingDomainId()`

UnsetDefaultTrackingDomainId ensures that no value is present for DefaultTrackingDomainId, not even an explicit nil
### GetHealth

`func (o *DomainSending) GetHealth() DomainHealth`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *DomainSending) GetHealthOk() (*DomainHealth, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *DomainSending) SetHealth(v DomainHealth)`

SetHealth sets Health field to given value.


### GetPolicy

`func (o *DomainSending) GetPolicy() DomainSendingPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *DomainSending) GetPolicyOk() (*DomainSendingPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *DomainSending) SetPolicy(v DomainSendingPolicy)`

SetPolicy sets Policy field to given value.


### GetSenderCount

`func (o *DomainSending) GetSenderCount() int32`

GetSenderCount returns the SenderCount field if non-nil, zero value otherwise.

### GetSenderCountOk

`func (o *DomainSending) GetSenderCountOk() (*int32, bool)`

GetSenderCountOk returns a tuple with the SenderCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCount

`func (o *DomainSending) SetSenderCount(v int32)`

SetSenderCount sets SenderCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


