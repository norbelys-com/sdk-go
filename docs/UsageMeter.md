# UsageMeter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Level** | **string** | &#x60;ok&#x60;, &#x60;near&#x60; (~80% of the cap used) or &#x60;reached&#x60; (at/over the cap). Example: &#x60;near&#x60;. | 
**Limit** | **NullableInt32** |  | 
**Used** | **int32** | Current usage against the cap. Example: 4. | 

## Methods

### NewUsageMeter

`func NewUsageMeter(level string, limit NullableInt32, used int32, ) *UsageMeter`

NewUsageMeter instantiates a new UsageMeter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsageMeterWithDefaults

`func NewUsageMeterWithDefaults() *UsageMeter`

NewUsageMeterWithDefaults instantiates a new UsageMeter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLevel

`func (o *UsageMeter) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *UsageMeter) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *UsageMeter) SetLevel(v string)`

SetLevel sets Level field to given value.


### GetLimit

`func (o *UsageMeter) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *UsageMeter) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *UsageMeter) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### SetLimitNil

`func (o *UsageMeter) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *UsageMeter) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUsed

`func (o *UsageMeter) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *UsageMeter) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *UsageMeter) SetUsed(v int32)`

SetUsed sets Used field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


