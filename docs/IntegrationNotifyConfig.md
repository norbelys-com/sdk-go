# IntegrationNotifyConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignAutoPaused** | Pointer to **bool** | Notify when a campaign auto-pauses (e.g. its bounce-rate gate trips); on by default. | [optional] 
**MeetingBooked** | Pointer to **bool** | Notify when a meeting is booked; on by default. | [optional] 
**PositiveReply** | Pointer to **bool** | Notify when an incoming reply is classified as positive; on by default. | [optional] 
**Reply** | Pointer to **bool** | Notify on every incoming reply; off by default. | [optional] 

## Methods

### NewIntegrationNotifyConfig

`func NewIntegrationNotifyConfig() *IntegrationNotifyConfig`

NewIntegrationNotifyConfig instantiates a new IntegrationNotifyConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationNotifyConfigWithDefaults

`func NewIntegrationNotifyConfigWithDefaults() *IntegrationNotifyConfig`

NewIntegrationNotifyConfigWithDefaults instantiates a new IntegrationNotifyConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaignAutoPaused

`func (o *IntegrationNotifyConfig) GetCampaignAutoPaused() bool`

GetCampaignAutoPaused returns the CampaignAutoPaused field if non-nil, zero value otherwise.

### GetCampaignAutoPausedOk

`func (o *IntegrationNotifyConfig) GetCampaignAutoPausedOk() (*bool, bool)`

GetCampaignAutoPausedOk returns a tuple with the CampaignAutoPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignAutoPaused

`func (o *IntegrationNotifyConfig) SetCampaignAutoPaused(v bool)`

SetCampaignAutoPaused sets CampaignAutoPaused field to given value.

### HasCampaignAutoPaused

`func (o *IntegrationNotifyConfig) HasCampaignAutoPaused() bool`

HasCampaignAutoPaused returns a boolean if a field has been set.

### GetMeetingBooked

`func (o *IntegrationNotifyConfig) GetMeetingBooked() bool`

GetMeetingBooked returns the MeetingBooked field if non-nil, zero value otherwise.

### GetMeetingBookedOk

`func (o *IntegrationNotifyConfig) GetMeetingBookedOk() (*bool, bool)`

GetMeetingBookedOk returns a tuple with the MeetingBooked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeetingBooked

`func (o *IntegrationNotifyConfig) SetMeetingBooked(v bool)`

SetMeetingBooked sets MeetingBooked field to given value.

### HasMeetingBooked

`func (o *IntegrationNotifyConfig) HasMeetingBooked() bool`

HasMeetingBooked returns a boolean if a field has been set.

### GetPositiveReply

`func (o *IntegrationNotifyConfig) GetPositiveReply() bool`

GetPositiveReply returns the PositiveReply field if non-nil, zero value otherwise.

### GetPositiveReplyOk

`func (o *IntegrationNotifyConfig) GetPositiveReplyOk() (*bool, bool)`

GetPositiveReplyOk returns a tuple with the PositiveReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveReply

`func (o *IntegrationNotifyConfig) SetPositiveReply(v bool)`

SetPositiveReply sets PositiveReply field to given value.

### HasPositiveReply

`func (o *IntegrationNotifyConfig) HasPositiveReply() bool`

HasPositiveReply returns a boolean if a field has been set.

### GetReply

`func (o *IntegrationNotifyConfig) GetReply() bool`

GetReply returns the Reply field if non-nil, zero value otherwise.

### GetReplyOk

`func (o *IntegrationNotifyConfig) GetReplyOk() (*bool, bool)`

GetReplyOk returns a tuple with the Reply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReply

`func (o *IntegrationNotifyConfig) SetReply(v bool)`

SetReply sets Reply field to given value.

### HasReply

`func (o *IntegrationNotifyConfig) HasReply() bool`

HasReply returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


