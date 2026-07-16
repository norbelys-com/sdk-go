# IntegrationConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Notify** | Pointer to [**IntegrationNotifyConfig**](IntegrationNotifyConfig.md) |  | [optional] 
**PushOut** | Pointer to **bool** | Whether to push outcomes (replies) back to this provider&#39;s timeline; on unless set to false. | [optional] 
**SlackChannelId** | Pointer to **NullableString** |  | [optional] 
**SlackChannelName** | Pointer to **NullableString** |  | [optional] 
**SyncIn** | Pointer to **bool** | Whether to pull leads/deals (CRM) or meetings (Calendly) in from this provider; on unless set to false. | [optional] 

## Methods

### NewIntegrationConfig

`func NewIntegrationConfig() *IntegrationConfig`

NewIntegrationConfig instantiates a new IntegrationConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationConfigWithDefaults

`func NewIntegrationConfigWithDefaults() *IntegrationConfig`

NewIntegrationConfigWithDefaults instantiates a new IntegrationConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotify

`func (o *IntegrationConfig) GetNotify() IntegrationNotifyConfig`

GetNotify returns the Notify field if non-nil, zero value otherwise.

### GetNotifyOk

`func (o *IntegrationConfig) GetNotifyOk() (*IntegrationNotifyConfig, bool)`

GetNotifyOk returns a tuple with the Notify field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotify

`func (o *IntegrationConfig) SetNotify(v IntegrationNotifyConfig)`

SetNotify sets Notify field to given value.

### HasNotify

`func (o *IntegrationConfig) HasNotify() bool`

HasNotify returns a boolean if a field has been set.

### GetPushOut

`func (o *IntegrationConfig) GetPushOut() bool`

GetPushOut returns the PushOut field if non-nil, zero value otherwise.

### GetPushOutOk

`func (o *IntegrationConfig) GetPushOutOk() (*bool, bool)`

GetPushOutOk returns a tuple with the PushOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPushOut

`func (o *IntegrationConfig) SetPushOut(v bool)`

SetPushOut sets PushOut field to given value.

### HasPushOut

`func (o *IntegrationConfig) HasPushOut() bool`

HasPushOut returns a boolean if a field has been set.

### GetSlackChannelId

`func (o *IntegrationConfig) GetSlackChannelId() string`

GetSlackChannelId returns the SlackChannelId field if non-nil, zero value otherwise.

### GetSlackChannelIdOk

`func (o *IntegrationConfig) GetSlackChannelIdOk() (*string, bool)`

GetSlackChannelIdOk returns a tuple with the SlackChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelId

`func (o *IntegrationConfig) SetSlackChannelId(v string)`

SetSlackChannelId sets SlackChannelId field to given value.

### HasSlackChannelId

`func (o *IntegrationConfig) HasSlackChannelId() bool`

HasSlackChannelId returns a boolean if a field has been set.

### SetSlackChannelIdNil

`func (o *IntegrationConfig) SetSlackChannelIdNil(b bool)`

 SetSlackChannelIdNil sets the value for SlackChannelId to be an explicit nil

### UnsetSlackChannelId
`func (o *IntegrationConfig) UnsetSlackChannelId()`

UnsetSlackChannelId ensures that no value is present for SlackChannelId, not even an explicit nil
### GetSlackChannelName

`func (o *IntegrationConfig) GetSlackChannelName() string`

GetSlackChannelName returns the SlackChannelName field if non-nil, zero value otherwise.

### GetSlackChannelNameOk

`func (o *IntegrationConfig) GetSlackChannelNameOk() (*string, bool)`

GetSlackChannelNameOk returns a tuple with the SlackChannelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelName

`func (o *IntegrationConfig) SetSlackChannelName(v string)`

SetSlackChannelName sets SlackChannelName field to given value.

### HasSlackChannelName

`func (o *IntegrationConfig) HasSlackChannelName() bool`

HasSlackChannelName returns a boolean if a field has been set.

### SetSlackChannelNameNil

`func (o *IntegrationConfig) SetSlackChannelNameNil(b bool)`

 SetSlackChannelNameNil sets the value for SlackChannelName to be an explicit nil

### UnsetSlackChannelName
`func (o *IntegrationConfig) UnsetSlackChannelName()`

UnsetSlackChannelName ensures that no value is present for SlackChannelName, not even an explicit nil
### GetSyncIn

`func (o *IntegrationConfig) GetSyncIn() bool`

GetSyncIn returns the SyncIn field if non-nil, zero value otherwise.

### GetSyncInOk

`func (o *IntegrationConfig) GetSyncInOk() (*bool, bool)`

GetSyncInOk returns a tuple with the SyncIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncIn

`func (o *IntegrationConfig) SetSyncIn(v bool)`

SetSyncIn sets SyncIn field to given value.

### HasSyncIn

`func (o *IntegrationConfig) HasSyncIn() bool`

HasSyncIn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


