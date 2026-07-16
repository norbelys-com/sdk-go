# DomainSendingPolicyParams

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

### NewDomainSendingPolicyParams

`func NewDomainSendingPolicyParams() *DomainSendingPolicyParams`

NewDomainSendingPolicyParams instantiates a new DomainSendingPolicyParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainSendingPolicyParamsWithDefaults

`func NewDomainSendingPolicyParamsWithDefaults() *DomainSendingPolicyParams`

NewDomainSendingPolicyParamsWithDefaults instantiates a new DomainSendingPolicyParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowPauseAll

`func (o *DomainSendingPolicyParams) GetAllowPauseAll() bool`

GetAllowPauseAll returns the AllowPauseAll field if non-nil, zero value otherwise.

### GetAllowPauseAllOk

`func (o *DomainSendingPolicyParams) GetAllowPauseAllOk() (*bool, bool)`

GetAllowPauseAllOk returns a tuple with the AllowPauseAll field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseAll

`func (o *DomainSendingPolicyParams) SetAllowPauseAll(v bool)`

SetAllowPauseAll sets AllowPauseAll field to given value.

### HasAllowPauseAll

`func (o *DomainSendingPolicyParams) HasAllowPauseAll() bool`

HasAllowPauseAll returns a boolean if a field has been set.

### GetAllowPauseFirstTouches

`func (o *DomainSendingPolicyParams) GetAllowPauseFirstTouches() bool`

GetAllowPauseFirstTouches returns the AllowPauseFirstTouches field if non-nil, zero value otherwise.

### GetAllowPauseFirstTouchesOk

`func (o *DomainSendingPolicyParams) GetAllowPauseFirstTouchesOk() (*bool, bool)`

GetAllowPauseFirstTouchesOk returns a tuple with the AllowPauseFirstTouches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowPauseFirstTouches

`func (o *DomainSendingPolicyParams) SetAllowPauseFirstTouches(v bool)`

SetAllowPauseFirstTouches sets AllowPauseFirstTouches field to given value.

### HasAllowPauseFirstTouches

`func (o *DomainSendingPolicyParams) HasAllowPauseFirstTouches() bool`

HasAllowPauseFirstTouches returns a boolean if a field has been set.

### GetAutopilotMax

`func (o *DomainSendingPolicyParams) GetAutopilotMax() int32`

GetAutopilotMax returns the AutopilotMax field if non-nil, zero value otherwise.

### GetAutopilotMaxOk

`func (o *DomainSendingPolicyParams) GetAutopilotMaxOk() (*int32, bool)`

GetAutopilotMaxOk returns a tuple with the AutopilotMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMax

`func (o *DomainSendingPolicyParams) SetAutopilotMax(v int32)`

SetAutopilotMax sets AutopilotMax field to given value.

### HasAutopilotMax

`func (o *DomainSendingPolicyParams) HasAutopilotMax() bool`

HasAutopilotMax returns a boolean if a field has been set.

### SetAutopilotMaxNil

`func (o *DomainSendingPolicyParams) SetAutopilotMaxNil(b bool)`

 SetAutopilotMaxNil sets the value for AutopilotMax to be an explicit nil

### UnsetAutopilotMax
`func (o *DomainSendingPolicyParams) UnsetAutopilotMax()`

UnsetAutopilotMax ensures that no value is present for AutopilotMax, not even an explicit nil
### GetAutopilotMin

`func (o *DomainSendingPolicyParams) GetAutopilotMin() int32`

GetAutopilotMin returns the AutopilotMin field if non-nil, zero value otherwise.

### GetAutopilotMinOk

`func (o *DomainSendingPolicyParams) GetAutopilotMinOk() (*int32, bool)`

GetAutopilotMinOk returns a tuple with the AutopilotMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilotMin

`func (o *DomainSendingPolicyParams) SetAutopilotMin(v int32)`

SetAutopilotMin sets AutopilotMin field to given value.

### HasAutopilotMin

`func (o *DomainSendingPolicyParams) HasAutopilotMin() bool`

HasAutopilotMin returns a boolean if a field has been set.

### SetAutopilotMinNil

`func (o *DomainSendingPolicyParams) SetAutopilotMinNil(b bool)`

 SetAutopilotMinNil sets the value for AutopilotMin to be an explicit nil

### UnsetAutopilotMin
`func (o *DomainSendingPolicyParams) UnsetAutopilotMin()`

UnsetAutopilotMin ensures that no value is present for AutopilotMin, not even an explicit nil
### GetConfiguredDailyCap

`func (o *DomainSendingPolicyParams) GetConfiguredDailyCap() int32`

GetConfiguredDailyCap returns the ConfiguredDailyCap field if non-nil, zero value otherwise.

### GetConfiguredDailyCapOk

`func (o *DomainSendingPolicyParams) GetConfiguredDailyCapOk() (*int32, bool)`

GetConfiguredDailyCapOk returns a tuple with the ConfiguredDailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguredDailyCap

`func (o *DomainSendingPolicyParams) SetConfiguredDailyCap(v int32)`

SetConfiguredDailyCap sets ConfiguredDailyCap field to given value.

### HasConfiguredDailyCap

`func (o *DomainSendingPolicyParams) HasConfiguredDailyCap() bool`

HasConfiguredDailyCap returns a boolean if a field has been set.

### SetConfiguredDailyCapNil

`func (o *DomainSendingPolicyParams) SetConfiguredDailyCapNil(b bool)`

 SetConfiguredDailyCapNil sets the value for ConfiguredDailyCap to be an explicit nil

### UnsetConfiguredDailyCap
`func (o *DomainSendingPolicyParams) UnsetConfiguredDailyCap()`

UnsetConfiguredDailyCap ensures that no value is present for ConfiguredDailyCap, not even an explicit nil
### GetMaxDailyGrowthPercent

`func (o *DomainSendingPolicyParams) GetMaxDailyGrowthPercent() int32`

GetMaxDailyGrowthPercent returns the MaxDailyGrowthPercent field if non-nil, zero value otherwise.

### GetMaxDailyGrowthPercentOk

`func (o *DomainSendingPolicyParams) GetMaxDailyGrowthPercentOk() (*int32, bool)`

GetMaxDailyGrowthPercentOk returns a tuple with the MaxDailyGrowthPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDailyGrowthPercent

`func (o *DomainSendingPolicyParams) SetMaxDailyGrowthPercent(v int32)`

SetMaxDailyGrowthPercent sets MaxDailyGrowthPercent field to given value.

### HasMaxDailyGrowthPercent

`func (o *DomainSendingPolicyParams) HasMaxDailyGrowthPercent() bool`

HasMaxDailyGrowthPercent returns a boolean if a field has been set.

### SetMaxDailyGrowthPercentNil

`func (o *DomainSendingPolicyParams) SetMaxDailyGrowthPercentNil(b bool)`

 SetMaxDailyGrowthPercentNil sets the value for MaxDailyGrowthPercent to be an explicit nil

### UnsetMaxDailyGrowthPercent
`func (o *DomainSendingPolicyParams) UnsetMaxDailyGrowthPercent()`

UnsetMaxDailyGrowthPercent ensures that no value is present for MaxDailyGrowthPercent, not even an explicit nil
### GetMode

`func (o *DomainSendingPolicyParams) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *DomainSendingPolicyParams) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *DomainSendingPolicyParams) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *DomainSendingPolicyParams) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetTimezone

`func (o *DomainSendingPolicyParams) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *DomainSendingPolicyParams) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *DomainSendingPolicyParams) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *DomainSendingPolicyParams) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


