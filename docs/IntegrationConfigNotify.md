# IntegrationConfigNotify

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignAutoPaused** | Pointer to **bool** | Notify when a campaign auto-pauses (e.g. its bounce-rate gate trips); on by default. | [optional] 
**MeetingBooked** | Pointer to **bool** | Notify when a meeting is booked; on by default. | [optional] 
**PositiveReply** | Pointer to **bool** | Notify when an incoming reply is classified as positive; on by default. | [optional] 
**Reply** | Pointer to **bool** | Notify on every incoming reply; off by default. | [optional] 

## Methods

### NewIntegrationConfigNotify

`func NewIntegrationConfigNotify() *IntegrationConfigNotify`

NewIntegrationConfigNotify instantiates a new IntegrationConfigNotify object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationConfigNotifyWithDefaults

`func NewIntegrationConfigNotifyWithDefaults() *IntegrationConfigNotify`

NewIntegrationConfigNotifyWithDefaults instantiates a new IntegrationConfigNotify object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaignAutoPaused

`func (o *IntegrationConfigNotify) GetCampaignAutoPaused() bool`

GetCampaignAutoPaused returns the CampaignAutoPaused field if non-nil, zero value otherwise.

### GetCampaignAutoPausedOk

`func (o *IntegrationConfigNotify) GetCampaignAutoPausedOk() (*bool, bool)`

GetCampaignAutoPausedOk returns a tuple with the CampaignAutoPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignAutoPaused

`func (o *IntegrationConfigNotify) SetCampaignAutoPaused(v bool)`

SetCampaignAutoPaused sets CampaignAutoPaused field to given value.

### HasCampaignAutoPaused

`func (o *IntegrationConfigNotify) HasCampaignAutoPaused() bool`

HasCampaignAutoPaused returns a boolean if a field has been set.

### GetMeetingBooked

`func (o *IntegrationConfigNotify) GetMeetingBooked() bool`

GetMeetingBooked returns the MeetingBooked field if non-nil, zero value otherwise.

### GetMeetingBookedOk

`func (o *IntegrationConfigNotify) GetMeetingBookedOk() (*bool, bool)`

GetMeetingBookedOk returns a tuple with the MeetingBooked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeetingBooked

`func (o *IntegrationConfigNotify) SetMeetingBooked(v bool)`

SetMeetingBooked sets MeetingBooked field to given value.

### HasMeetingBooked

`func (o *IntegrationConfigNotify) HasMeetingBooked() bool`

HasMeetingBooked returns a boolean if a field has been set.

### GetPositiveReply

`func (o *IntegrationConfigNotify) GetPositiveReply() bool`

GetPositiveReply returns the PositiveReply field if non-nil, zero value otherwise.

### GetPositiveReplyOk

`func (o *IntegrationConfigNotify) GetPositiveReplyOk() (*bool, bool)`

GetPositiveReplyOk returns a tuple with the PositiveReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveReply

`func (o *IntegrationConfigNotify) SetPositiveReply(v bool)`

SetPositiveReply sets PositiveReply field to given value.

### HasPositiveReply

`func (o *IntegrationConfigNotify) HasPositiveReply() bool`

HasPositiveReply returns a boolean if a field has been set.

### GetReply

`func (o *IntegrationConfigNotify) GetReply() bool`

GetReply returns the Reply field if non-nil, zero value otherwise.

### GetReplyOk

`func (o *IntegrationConfigNotify) GetReplyOk() (*bool, bool)`

GetReplyOk returns a tuple with the Reply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReply

`func (o *IntegrationConfigNotify) SetReply(v bool)`

SetReply sets Reply field to given value.

### HasReply

`func (o *IntegrationConfigNotify) HasReply() bool`

HasReply returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


