# DomainSendingPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowPauseAll** | **bool** | Whether the platform may pause ALL sends from this domain when health is critical. | 
**AllowPauseFirstTouches** | **bool** | Whether the platform may pause first-touch (cold) sends while replies keep flowing. | 
**AutopilotMax** | **NullableInt32** |  | 
**AutopilotMin** | **NullableInt32** |  | 
**ConfiguredDailyCap** | **NullableInt32** |  | 
**EffectiveDailyCap** | **NullableInt32** |  | 
**MaxDailyGrowthPercent** | **NullableInt32** |  | 
**Mode** | **string** | Budget control mode: &#x60;legacy&#x60;, &#x60;manual&#x60;, or &#x60;autopilot&#x60;. | 
**RecommendedDailyCap** | **NullableInt32** |  | 
**Timezone** | **string** | IANA timezone the daily window and reset are computed in. | 

## Methods

### NewDomainSendingPolicy

`func NewDomainSendingPolicy(allowPauseAll bool, allowPauseFirstTouches bool, autopilotMax NullableInt32, autopilotMin NullableInt32, configuredDailyCap NullableInt32, effectiveDailyCap NullableInt32, maxDailyGrowthPercent NullableInt32, mode string, recommendedDailyCap NullableInt32, timezone string, ) *DomainSendingPolicy`

NewDomainSendingPolicy instantiates a new DomainSendingPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainSendingPolicyWithDefaults

`func NewDomainSendingPolicyWithDefaults() *DomainSendingPolicy`

NewDomainSendingPolicyWithDefaults instantiates a new DomainSendingPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowPauseAll

`func (o *DomainSendingPolicy) GetAllowPauseAll() bool`

GetAllowPauseAll returns the AllowPauseAll field if non-nil, zero value otherwise.

### GetAllowPauseAllOk

`func (o *DomainSendingPolicy) GetAllowPauseAllOk() (*bool, bool)`

GetAllowPauseAllOk returns a tuple with the AllowPauseAll field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseAll

`func (o *DomainSendingPolicy) SetAllowPauseAll(v bool)`

SetAllowPauseAll sets AllowPauseAll field to given value.


### GetAllowPauseFirstTouches

`func (o *DomainSendingPolicy) GetAllowPauseFirstTouches() bool`

GetAllowPauseFirstTouches returns the AllowPauseFirstTouches field if non-nil, zero value otherwise.

### GetAllowPauseFirstTouchesOk

`func (o *DomainSendingPolicy) GetAllowPauseFirstTouchesOk() (*bool, bool)`

GetAllowPauseFirstTouchesOk returns a tuple with the AllowPauseFirstTouches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseFirstTouches

`func (o *DomainSendingPolicy) SetAllowPauseFirstTouches(v bool)`

SetAllowPauseFirstTouches sets AllowPauseFirstTouches field to given value.


### GetAutopilotMax

`func (o *DomainSendingPolicy) GetAutopilotMax() int32`

GetAutopilotMax returns the AutopilotMax field if non-nil, zero value otherwise.

### GetAutopilotMaxOk

`func (o *DomainSendingPolicy) GetAutopilotMaxOk() (*int32, bool)`

GetAutopilotMaxOk returns a tuple with the AutopilotMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMax

`func (o *DomainSendingPolicy) SetAutopilotMax(v int32)`

SetAutopilotMax sets AutopilotMax field to given value.


### SetAutopilotMaxNil

`func (o *DomainSendingPolicy) SetAutopilotMaxNil(b bool)`

 SetAutopilotMaxNil sets the value for AutopilotMax to be an explicit nil

### UnsetAutopilotMax
`func (o *DomainSendingPolicy) UnsetAutopilotMax()`

UnsetAutopilotMax ensures that no value is present for AutopilotMax, not even an explicit nil
### GetAutopilotMin

`func (o *DomainSendingPolicy) GetAutopilotMin() int32`

GetAutopilotMin returns the AutopilotMin field if non-nil, zero value otherwise.

### GetAutopilotMinOk

`func (o *DomainSendingPolicy) GetAutopilotMinOk() (*int32, bool)`

GetAutopilotMinOk returns a tuple with the AutopilotMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMin

`func (o *DomainSendingPolicy) SetAutopilotMin(v int32)`

SetAutopilotMin sets AutopilotMin field to given value.


### SetAutopilotMinNil

`func (o *DomainSendingPolicy) SetAutopilotMinNil(b bool)`

 SetAutopilotMinNil sets the value for AutopilotMin to be an explicit nil

### UnsetAutopilotMin
`func (o *DomainSendingPolicy) UnsetAutopilotMin()`

UnsetAutopilotMin ensures that no value is present for AutopilotMin, not even an explicit nil
### GetConfiguredDailyCap

`func (o *DomainSendingPolicy) GetConfiguredDailyCap() int32`

GetConfiguredDailyCap returns the ConfiguredDailyCap field if non-nil, zero value otherwise.

### GetConfiguredDailyCapOk

`func (o *DomainSendingPolicy) GetConfiguredDailyCapOk() (*int32, bool)`

GetConfiguredDailyCapOk returns a tuple with the ConfiguredDailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguredDailyCap

`func (o *DomainSendingPolicy) SetConfiguredDailyCap(v int32)`

SetConfiguredDailyCap sets ConfiguredDailyCap field to given value.


### SetConfiguredDailyCapNil

`func (o *DomainSendingPolicy) SetConfiguredDailyCapNil(b bool)`

 SetConfiguredDailyCapNil sets the value for ConfiguredDailyCap to be an explicit nil

### UnsetConfiguredDailyCap
`func (o *DomainSendingPolicy) UnsetConfiguredDailyCap()`

UnsetConfiguredDailyCap ensures that no value is present for ConfiguredDailyCap, not even an explicit nil
### GetEffectiveDailyCap

`func (o *DomainSendingPolicy) GetEffectiveDailyCap() int32`

GetEffectiveDailyCap returns the EffectiveDailyCap field if non-nil, zero value otherwise.

### GetEffectiveDailyCapOk

`func (o *DomainSendingPolicy) GetEffectiveDailyCapOk() (*int32, bool)`

GetEffectiveDailyCapOk returns a tuple with the EffectiveDailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveDailyCap

`func (o *DomainSendingPolicy) SetEffectiveDailyCap(v int32)`

SetEffectiveDailyCap sets EffectiveDailyCap field to given value.


### SetEffectiveDailyCapNil

`func (o *DomainSendingPolicy) SetEffectiveDailyCapNil(b bool)`

 SetEffectiveDailyCapNil sets the value for EffectiveDailyCap to be an explicit nil

### UnsetEffectiveDailyCap
`func (o *DomainSendingPolicy) UnsetEffectiveDailyCap()`

UnsetEffectiveDailyCap ensures that no value is present for EffectiveDailyCap, not even an explicit nil
### GetMaxDailyGrowthPercent

`func (o *DomainSendingPolicy) GetMaxDailyGrowthPercent() int32`

GetMaxDailyGrowthPercent returns the MaxDailyGrowthPercent field if non-nil, zero value otherwise.

### GetMaxDailyGrowthPercentOk

`func (o *DomainSendingPolicy) GetMaxDailyGrowthPercentOk() (*int32, bool)`

GetMaxDailyGrowthPercentOk returns a tuple with the MaxDailyGrowthPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDailyGrowthPercent

`func (o *DomainSendingPolicy) SetMaxDailyGrowthPercent(v int32)`

SetMaxDailyGrowthPercent sets MaxDailyGrowthPercent field to given value.


### SetMaxDailyGrowthPercentNil

`func (o *DomainSendingPolicy) SetMaxDailyGrowthPercentNil(b bool)`

 SetMaxDailyGrowthPercentNil sets the value for MaxDailyGrowthPercent to be an explicit nil

### UnsetMaxDailyGrowthPercent
`func (o *DomainSendingPolicy) UnsetMaxDailyGrowthPercent()`

UnsetMaxDailyGrowthPercent ensures that no value is present for MaxDailyGrowthPercent, not even an explicit nil
### GetMode

`func (o *DomainSendingPolicy) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *DomainSendingPolicy) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *DomainSendingPolicy) SetMode(v string)`

SetMode sets Mode field to given value.


### GetRecommendedDailyCap

`func (o *DomainSendingPolicy) GetRecommendedDailyCap() int32`

GetRecommendedDailyCap returns the RecommendedDailyCap field if non-nil, zero value otherwise.

### GetRecommendedDailyCapOk

`func (o *DomainSendingPolicy) GetRecommendedDailyCapOk() (*int32, bool)`

GetRecommendedDailyCapOk returns a tuple with the RecommendedDailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedDailyCap

`func (o *DomainSendingPolicy) SetRecommendedDailyCap(v int32)`

SetRecommendedDailyCap sets RecommendedDailyCap field to given value.


### SetRecommendedDailyCapNil

`func (o *DomainSendingPolicy) SetRecommendedDailyCapNil(b bool)`

 SetRecommendedDailyCapNil sets the value for RecommendedDailyCap to be an explicit nil

### UnsetRecommendedDailyCap
`func (o *DomainSendingPolicy) UnsetRecommendedDailyCap()`

UnsetRecommendedDailyCap ensures that no value is present for RecommendedDailyCap, not even an explicit nil
### GetTimezone

`func (o *DomainSendingPolicy) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *DomainSendingPolicy) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *DomainSendingPolicy) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


