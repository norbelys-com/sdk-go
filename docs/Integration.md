# Integration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | [**NullableIntegrationConfig**](IntegrationConfig.md) |  | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The integration id. | 
**LastError** | **NullableString** |  | 
**LastSyncAt** | Pointer to **interface{}** |  | [optional] 
**Object** | Pointer to **interface{}** |  | [optional] 
**Provider** | [**IntegrationProvider**](IntegrationProvider.md) |  | 
**Status** | [**IntegrationStatus**](IntegrationStatus.md) |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewIntegration

`func NewIntegration(config NullableIntegrationConfig, id string, lastError NullableString, provider IntegrationProvider, status IntegrationStatus, ) *Integration`

NewIntegration instantiates a new Integration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationWithDefaults

`func NewIntegrationWithDefaults() *Integration`

NewIntegrationWithDefaults instantiates a new Integration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *Integration) GetConfig() IntegrationConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *Integration) GetConfigOk() (*IntegrationConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *Integration) SetConfig(v IntegrationConfig)`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *Integration) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *Integration) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetCreatedAt

`func (o *Integration) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Integration) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Integration) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Integration) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Integration) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Integration) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *Integration) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Integration) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Integration) SetId(v string)`

SetId sets Id field to given value.


### GetLastError

`func (o *Integration) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *Integration) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *Integration) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *Integration) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *Integration) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetLastSyncAt

`func (o *Integration) GetLastSyncAt() interface{}`

GetLastSyncAt returns the LastSyncAt field if non-nil, zero value otherwise.

### GetLastSyncAtOk

`func (o *Integration) GetLastSyncAtOk() (*interface{}, bool)`

GetLastSyncAtOk returns a tuple with the LastSyncAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncAt

`func (o *Integration) SetLastSyncAt(v interface{})`

SetLastSyncAt sets LastSyncAt field to given value.

### HasLastSyncAt

`func (o *Integration) HasLastSyncAt() bool`

HasLastSyncAt returns a boolean if a field has been set.

### SetLastSyncAtNil

`func (o *Integration) SetLastSyncAtNil(b bool)`

 SetLastSyncAtNil sets the value for LastSyncAt to be an explicit nil

### UnsetLastSyncAt
`func (o *Integration) UnsetLastSyncAt()`

UnsetLastSyncAt ensures that no value is present for LastSyncAt, not even an explicit nil
### GetObject

`func (o *Integration) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Integration) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Integration) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Integration) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Integration) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Integration) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetProvider

`func (o *Integration) GetProvider() IntegrationProvider`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *Integration) GetProviderOk() (*IntegrationProvider, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *Integration) SetProvider(v IntegrationProvider)`

SetProvider sets Provider field to given value.


### GetStatus

`func (o *Integration) GetStatus() IntegrationStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Integration) GetStatusOk() (*IntegrationStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Integration) SetStatus(v IntegrationStatus)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *Integration) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Integration) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Integration) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Integration) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Integration) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Integration) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


