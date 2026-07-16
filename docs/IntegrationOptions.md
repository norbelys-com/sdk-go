# IntegrationOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Channels** | [**[]SlackChannel**](SlackChannel.md) | Slack channels you can post notifications to. | 

## Methods

### NewIntegrationOptions

`func NewIntegrationOptions(channels []SlackChannel, ) *IntegrationOptions`

NewIntegrationOptions instantiates a new IntegrationOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationOptionsWithDefaults

`func NewIntegrationOptionsWithDefaults() *IntegrationOptions`

NewIntegrationOptionsWithDefaults instantiates a new IntegrationOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannels

`func (o *IntegrationOptions) GetChannels() []SlackChannel`

GetChannels returns the Channels field if non-nil, zero value otherwise.

### GetChannelsOk

`func (o *IntegrationOptions) GetChannelsOk() (*[]SlackChannel, bool)`

GetChannelsOk returns a tuple with the Channels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannels

`func (o *IntegrationOptions) SetChannels(v []SlackChannel)`

SetChannels sets Channels field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


