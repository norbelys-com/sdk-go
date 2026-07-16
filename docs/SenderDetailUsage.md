# SenderDetailUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Campaigns** | **int32** | Campaigns it is attached to. | 
**HasData** | **bool** | Whether the mailbox has any send/receive/campaign history. | 
**Received** | **int32** | Replies received on it. | 
**Sent** | **int32** | Messages sent from it. | 

## Methods

### NewSenderDetailUsage

`func NewSenderDetailUsage(campaigns int32, hasData bool, received int32, sent int32, ) *SenderDetailUsage`

NewSenderDetailUsage instantiates a new SenderDetailUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderDetailUsageWithDefaults

`func NewSenderDetailUsageWithDefaults() *SenderDetailUsage`

NewSenderDetailUsageWithDefaults instantiates a new SenderDetailUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaigns

`func (o *SenderDetailUsage) GetCampaigns() int32`

GetCampaigns returns the Campaigns field if non-nil, zero value otherwise.

### GetCampaignsOk

`func (o *SenderDetailUsage) GetCampaignsOk() (*int32, bool)`

GetCampaignsOk returns a tuple with the Campaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaigns

`func (o *SenderDetailUsage) SetCampaigns(v int32)`

SetCampaigns sets Campaigns field to given value.


### GetHasData

`func (o *SenderDetailUsage) GetHasData() bool`

GetHasData returns the HasData field if non-nil, zero value otherwise.

### GetHasDataOk

`func (o *SenderDetailUsage) GetHasDataOk() (*bool, bool)`

GetHasDataOk returns a tuple with the HasData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasData

`func (o *SenderDetailUsage) SetHasData(v bool)`

SetHasData sets HasData field to given value.


### GetReceived

`func (o *SenderDetailUsage) GetReceived() int32`

GetReceived returns the Received field if non-nil, zero value otherwise.

### GetReceivedOk

`func (o *SenderDetailUsage) GetReceivedOk() (*int32, bool)`

GetReceivedOk returns a tuple with the Received field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceived

`func (o *SenderDetailUsage) SetReceived(v int32)`

SetReceived sets Received field to given value.


### GetSent

`func (o *SenderDetailUsage) GetSent() int32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *SenderDetailUsage) GetSentOk() (*int32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *SenderDetailUsage) SetSent(v int32)`

SetSent sets Sent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


