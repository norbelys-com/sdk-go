# IntegrationUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | [**IntegrationConfig**](IntegrationConfig.md) | Config patch, shallow-merged over the stored config (top-level keys replace). | 

## Methods

### NewIntegrationUpdateParams

`func NewIntegrationUpdateParams(config IntegrationConfig, ) *IntegrationUpdateParams`

NewIntegrationUpdateParams instantiates a new IntegrationUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationUpdateParamsWithDefaults

`func NewIntegrationUpdateParamsWithDefaults() *IntegrationUpdateParams`

NewIntegrationUpdateParamsWithDefaults instantiates a new IntegrationUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *IntegrationUpdateParams) GetConfig() IntegrationConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *IntegrationUpdateParams) GetConfigOk() (*IntegrationConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *IntegrationUpdateParams) SetConfig(v IntegrationConfig)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


