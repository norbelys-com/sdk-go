# DomainUpdateParamsSendingPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowPauseAll** | Pointer to **bool** | Whether the platform may pause ALL sends from this domain when health is critical. | [optional] 
**AllowPauseFirstTouches** | Pointer to **bool** | Whether the platform may pause first-touch (cold) sends while replies keep flowing. | [optional] 
**AutopilotMax** | Pointer to **NullableInt32** |  | [optional] 
**AutopilotMin** | Pointer to **NullableInt32** |  | [optional] 
**ConfiguredDailyCap** | Pointer to **NullableInt32** |  | [optional] 
**MaxDailyGrowthPercent** | Pointer to **NullableInt32** |  | [optional] 
**Mode** | Pointer to **string** | Budget control mode: &#x60;legacy&#x60;, &#x60;manual&#x60;, or &#x60;autopilot&#x60;. | [optional] 
**Timezone** | Pointer to **string** | IANA timezone the daily window and reset are computed in. | [optional] 

## Methods

### NewDomainUpdateParamsSendingPolicy

`func NewDomainUpdateParamsSendingPolicy() *DomainUpdateParamsSendingPolicy`

NewDomainUpdateParamsSendingPolicy instantiates a new DomainUpdateParamsSendingPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainUpdateParamsSendingPolicyWithDefaults

`func NewDomainUpdateParamsSendingPolicyWithDefaults() *DomainUpdateParamsSendingPolicy`

NewDomainUpdateParamsSendingPolicyWithDefaults instantiates a new DomainUpdateParamsSendingPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowPauseAll

`func (o *DomainUpdateParamsSendingPolicy) GetAllowPauseAll() bool`

GetAllowPauseAll returns the AllowPauseAll field if non-nil, zero value otherwise.

### GetAllowPauseAllOk

`func (o *DomainUpdateParamsSendingPolicy) GetAllowPauseAllOk() (*bool, bool)`

GetAllowPauseAllOk returns a tuple with the AllowPauseAll field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseAll

`func (o *DomainUpdateParamsSendingPolicy) SetAllowPauseAll(v bool)`

SetAllowPauseAll sets AllowPauseAll field to given value.

### HasAllowPauseAll

`func (o *DomainUpdateParamsSendingPolicy) HasAllowPauseAll() bool`

HasAllowPauseAll returns a boolean if a field has been set.

### GetAllowPauseFirstTouches

`func (o *DomainUpdateParamsSendingPolicy) GetAllowPauseFirstTouches() bool`

GetAllowPauseFirstTouches returns the AllowPauseFirstTouches field if non-nil, zero value otherwise.

### GetAllowPauseFirstTouchesOk

`func (o *DomainUpdateParamsSendingPolicy) GetAllowPauseFirstTouchesOk() (*bool, bool)`

GetAllowPauseFirstTouchesOk returns a tuple with the AllowPauseFirstTouches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseFirstTouches

`func (o *DomainUpdateParamsSendingPolicy) SetAllowPauseFirstTouches(v bool)`

SetAllowPauseFirstTouches sets AllowPauseFirstTouches field to given value.

### HasAllowPauseFirstTouches

`func (o *DomainUpdateParamsSendingPolicy) HasAllowPauseFirstTouches() bool`

HasAllowPauseFirstTouches returns a boolean if a field has been set.

### GetAutopilotMax

`func (o *DomainUpdateParamsSendingPolicy) GetAutopilotMax() int32`

GetAutopilotMax returns the AutopilotMax field if non-nil, zero value otherwise.

### GetAutopilotMaxOk

`func (o *DomainUpdateParamsSendingPolicy) GetAutopilotMaxOk() (*int32, bool)`

GetAutopilotMaxOk returns a tuple with the AutopilotMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMax

`func (o *DomainUpdateParamsSendingPolicy) SetAutopilotMax(v int32)`

SetAutopilotMax sets AutopilotMax field to given value.

### HasAutopilotMax

`func (o *DomainUpdateParamsSendingPolicy) HasAutopilotMax() bool`

HasAutopilotMax returns a boolean if a field has been set.

### SetAutopilotMaxNil

`func (o *DomainUpdateParamsSendingPolicy) SetAutopilotMaxNil(b bool)`

 SetAutopilotMaxNil sets the value for AutopilotMax to be an explicit nil

### UnsetAutopilotMax
`func (o *DomainUpdateParamsSendingPolicy) UnsetAutopilotMax()`

UnsetAutopilotMax ensures that no value is present for AutopilotMax, not even an explicit nil
### GetAutopilotMin

`func (o *DomainUpdateParamsSendingPolicy) GetAutopilotMin() int32`

GetAutopilotMin returns the AutopilotMin field if non-nil, zero value otherwise.

### GetAutopilotMinOk

`func (o *DomainUpdateParamsSendingPolicy) GetAutopilotMinOk() (*int32, bool)`

GetAutopilotMinOk returns a tuple with the AutopilotMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMin

`func (o *DomainUpdateParamsSendingPolicy) SetAutopilotMin(v int32)`

SetAutopilotMin sets AutopilotMin field to given value.

### HasAutopilotMin

`func (o *DomainUpdateParamsSendingPolicy) HasAutopilotMin() bool`

HasAutopilotMin returns a boolean if a field has been set.

### SetAutopilotMinNil

`func (o *DomainUpdateParamsSendingPolicy) SetAutopilotMinNil(b bool)`

 SetAutopilotMinNil sets the value for AutopilotMin to be an explicit nil

### UnsetAutopilotMin
`func (o *DomainUpdateParamsSendingPolicy) UnsetAutopilotMin()`

UnsetAutopilotMin ensures that no value is present for AutopilotMin, not even an explicit nil
### GetConfiguredDailyCap

`func (o *DomainUpdateParamsSendingPolicy) GetConfiguredDailyCap() int32`

GetConfiguredDailyCap returns the ConfiguredDailyCap field if non-nil, zero value otherwise.

### GetConfiguredDailyCapOk

`func (o *DomainUpdateParamsSendingPolicy) GetConfiguredDailyCapOk() (*int32, bool)`

GetConfiguredDailyCapOk returns a tuple with the ConfiguredDailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguredDailyCap

`func (o *DomainUpdateParamsSendingPolicy) SetConfiguredDailyCap(v int32)`

SetConfiguredDailyCap sets ConfiguredDailyCap field to given value.

### HasConfiguredDailyCap

`func (o *DomainUpdateParamsSendingPolicy) HasConfiguredDailyCap() bool`

HasConfiguredDailyCap returns a boolean if a field has been set.

### SetConfiguredDailyCapNil

`func (o *DomainUpdateParamsSendingPolicy) SetConfiguredDailyCapNil(b bool)`

 SetConfiguredDailyCapNil sets the value for ConfiguredDailyCap to be an explicit nil

### UnsetConfiguredDailyCap
`func (o *DomainUpdateParamsSendingPolicy) UnsetConfiguredDailyCap()`

UnsetConfiguredDailyCap ensures that no value is present for ConfiguredDailyCap, not even an explicit nil
### GetMaxDailyGrowthPercent

`func (o *DomainUpdateParamsSendingPolicy) GetMaxDailyGrowthPercent() int32`

GetMaxDailyGrowthPercent returns the MaxDailyGrowthPercent field if non-nil, zero value otherwise.

### GetMaxDailyGrowthPercentOk

`func (o *DomainUpdateParamsSendingPolicy) GetMaxDailyGrowthPercentOk() (*int32, bool)`

GetMaxDailyGrowthPercentOk returns a tuple with the MaxDailyGrowthPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDailyGrowthPercent

`func (o *DomainUpdateParamsSendingPolicy) SetMaxDailyGrowthPercent(v int32)`

SetMaxDailyGrowthPercent sets MaxDailyGrowthPercent field to given value.

### HasMaxDailyGrowthPercent

`func (o *DomainUpdateParamsSendingPolicy) HasMaxDailyGrowthPercent() bool`

HasMaxDailyGrowthPercent returns a boolean if a field has been set.

### SetMaxDailyGrowthPercentNil

`func (o *DomainUpdateParamsSendingPolicy) SetMaxDailyGrowthPercentNil(b bool)`

 SetMaxDailyGrowthPercentNil sets the value for MaxDailyGrowthPercent to be an explicit nil

### UnsetMaxDailyGrowthPercent
`func (o *DomainUpdateParamsSendingPolicy) UnsetMaxDailyGrowthPercent()`

UnsetMaxDailyGrowthPercent ensures that no value is present for MaxDailyGrowthPercent, not even an explicit nil
### GetMode

`func (o *DomainUpdateParamsSendingPolicy) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *DomainUpdateParamsSendingPolicy) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *DomainUpdateParamsSendingPolicy) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *DomainUpdateParamsSendingPolicy) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetTimezone

`func (o *DomainUpdateParamsSendingPolicy) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *DomainUpdateParamsSendingPolicy) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *DomainUpdateParamsSendingPolicy) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *DomainUpdateParamsSendingPolicy) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


