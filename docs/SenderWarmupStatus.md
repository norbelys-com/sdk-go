# SenderWarmupStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Runtime** | [**NullableWarmupRuntimeStatus**](WarmupRuntimeStatus.md) |  | 
**Settings** | [**NullableWarmupSettings**](WarmupSettings.md) |  | 

## Methods

### NewSenderWarmupStatus

`func NewSenderWarmupStatus(runtime NullableWarmupRuntimeStatus, settings NullableWarmupSettings, ) *SenderWarmupStatus`

NewSenderWarmupStatus instantiates a new SenderWarmupStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderWarmupStatusWithDefaults

`func NewSenderWarmupStatusWithDefaults() *SenderWarmupStatus`

NewSenderWarmupStatusWithDefaults instantiates a new SenderWarmupStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRuntime

`func (o *SenderWarmupStatus) GetRuntime() WarmupRuntimeStatus`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *SenderWarmupStatus) GetRuntimeOk() (*WarmupRuntimeStatus, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *SenderWarmupStatus) SetRuntime(v WarmupRuntimeStatus)`

SetRuntime sets Runtime field to given value.


### SetRuntimeNil

`func (o *SenderWarmupStatus) SetRuntimeNil(b bool)`

 SetRuntimeNil sets the value for Runtime to be an explicit nil

### UnsetRuntime
`func (o *SenderWarmupStatus) UnsetRuntime()`

UnsetRuntime ensures that no value is present for Runtime, not even an explicit nil
### GetSettings

`func (o *SenderWarmupStatus) GetSettings() WarmupSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *SenderWarmupStatus) GetSettingsOk() (*WarmupSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *SenderWarmupStatus) SetSettings(v WarmupSettings)`

SetSettings sets Settings field to given value.


### SetSettingsNil

`func (o *SenderWarmupStatus) SetSettingsNil(b bool)`

 SetSettingsNil sets the value for Settings to be an explicit nil

### UnsetSettings
`func (o *SenderWarmupStatus) UnsetSettings()`

UnsetSettings ensures that no value is present for Settings, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


