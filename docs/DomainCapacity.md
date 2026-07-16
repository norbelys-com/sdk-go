# DomainCapacity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignUsed** | **int32** | Sends already used today by the filtered campaign. | 
**DomainRemaining** | **NullableInt32** |  | 
**LimitingReason** | **NullableString** |  | 
**MailboxCapacity** | **int32** | Total daily capacity across the domain&#39;s mailboxes. | 
**NextResetAt** | Pointer to **interface{}** |  | [optional] 
**WarmupReserved** | **int32** | Daily capacity reserved for warmup and unavailable to campaigns. | 

## Methods

### NewDomainCapacity

`func NewDomainCapacity(campaignUsed int32, domainRemaining NullableInt32, limitingReason NullableString, mailboxCapacity int32, warmupReserved int32, ) *DomainCapacity`

NewDomainCapacity instantiates a new DomainCapacity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainCapacityWithDefaults

`func NewDomainCapacityWithDefaults() *DomainCapacity`

NewDomainCapacityWithDefaults instantiates a new DomainCapacity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaignUsed

`func (o *DomainCapacity) GetCampaignUsed() int32`

GetCampaignUsed returns the CampaignUsed field if non-nil, zero value otherwise.

### GetCampaignUsedOk

`func (o *DomainCapacity) GetCampaignUsedOk() (*int32, bool)`

GetCampaignUsedOk returns a tuple with the CampaignUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignUsed

`func (o *DomainCapacity) SetCampaignUsed(v int32)`

SetCampaignUsed sets CampaignUsed field to given value.


### GetDomainRemaining

`func (o *DomainCapacity) GetDomainRemaining() int32`

GetDomainRemaining returns the DomainRemaining field if non-nil, zero value otherwise.

### GetDomainRemainingOk

`func (o *DomainCapacity) GetDomainRemainingOk() (*int32, bool)`

GetDomainRemainingOk returns a tuple with the DomainRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainRemaining

`func (o *DomainCapacity) SetDomainRemaining(v int32)`

SetDomainRemaining sets DomainRemaining field to given value.


### SetDomainRemainingNil

`func (o *DomainCapacity) SetDomainRemainingNil(b bool)`

 SetDomainRemainingNil sets the value for DomainRemaining to be an explicit nil

### UnsetDomainRemaining
`func (o *DomainCapacity) UnsetDomainRemaining()`

UnsetDomainRemaining ensures that no value is present for DomainRemaining, not even an explicit nil
### GetLimitingReason

`func (o *DomainCapacity) GetLimitingReason() string`

GetLimitingReason returns the LimitingReason field if non-nil, zero value otherwise.

### GetLimitingReasonOk

`func (o *DomainCapacity) GetLimitingReasonOk() (*string, bool)`

GetLimitingReasonOk returns a tuple with the LimitingReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitingReason

`func (o *DomainCapacity) SetLimitingReason(v string)`

SetLimitingReason sets LimitingReason field to given value.


### SetLimitingReasonNil

`func (o *DomainCapacity) SetLimitingReasonNil(b bool)`

 SetLimitingReasonNil sets the value for LimitingReason to be an explicit nil

### UnsetLimitingReason
`func (o *DomainCapacity) UnsetLimitingReason()`

UnsetLimitingReason ensures that no value is present for LimitingReason, not even an explicit nil
### GetMailboxCapacity

`func (o *DomainCapacity) GetMailboxCapacity() int32`

GetMailboxCapacity returns the MailboxCapacity field if non-nil, zero value otherwise.

### GetMailboxCapacityOk

`func (o *DomainCapacity) GetMailboxCapacityOk() (*int32, bool)`

GetMailboxCapacityOk returns a tuple with the MailboxCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxCapacity

`func (o *DomainCapacity) SetMailboxCapacity(v int32)`

SetMailboxCapacity sets MailboxCapacity field to given value.


### GetNextResetAt

`func (o *DomainCapacity) GetNextResetAt() interface{}`

GetNextResetAt returns the NextResetAt field if non-nil, zero value otherwise.

### GetNextResetAtOk

`func (o *DomainCapacity) GetNextResetAtOk() (*interface{}, bool)`

GetNextResetAtOk returns a tuple with the NextResetAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextResetAt

`func (o *DomainCapacity) SetNextResetAt(v interface{})`

SetNextResetAt sets NextResetAt field to given value.

### HasNextResetAt

`func (o *DomainCapacity) HasNextResetAt() bool`

HasNextResetAt returns a boolean if a field has been set.

### SetNextResetAtNil

`func (o *DomainCapacity) SetNextResetAtNil(b bool)`

 SetNextResetAtNil sets the value for NextResetAt to be an explicit nil

### UnsetNextResetAt
`func (o *DomainCapacity) UnsetNextResetAt()`

UnsetNextResetAt ensures that no value is present for NextResetAt, not even an explicit nil
### GetWarmupReserved

`func (o *DomainCapacity) GetWarmupReserved() int32`

GetWarmupReserved returns the WarmupReserved field if non-nil, zero value otherwise.

### GetWarmupReservedOk

`func (o *DomainCapacity) GetWarmupReservedOk() (*int32, bool)`

GetWarmupReservedOk returns a tuple with the WarmupReserved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmupReserved

`func (o *DomainCapacity) SetWarmupReserved(v int32)`

SetWarmupReserved sets WarmupReserved field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


