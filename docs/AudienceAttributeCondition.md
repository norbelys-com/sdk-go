# AudienceAttributeCondition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | **string** | The field to test: a reserved field key (&#x60;email&#x60;, &#x60;firstname&#x60;, &#x60;lastname&#x60;, &#x60;telephone&#x60;, &#x60;email_domain&#x60;, &#x60;status&#x60;, &#x60;source&#x60;, &#x60;score&#x60;, &#x60;last_activity_at&#x60;, &#x60;created_at&#x60;, &#x60;group&#x60;, &#x60;program&#x60;, &#x60;suppressed&#x60;) or a custom field&#39;s code. | 
**Op** | [**AudienceConditionOp**](AudienceConditionOp.md) |  | 
**Value** | Pointer to [**NullableAudienceConditionValue**](AudienceConditionValue.md) |  | [optional] 

## Methods

### NewAudienceAttributeCondition

`func NewAudienceAttributeCondition(field string, op AudienceConditionOp, ) *AudienceAttributeCondition`

NewAudienceAttributeCondition instantiates a new AudienceAttributeCondition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceAttributeConditionWithDefaults

`func NewAudienceAttributeConditionWithDefaults() *AudienceAttributeCondition`

NewAudienceAttributeConditionWithDefaults instantiates a new AudienceAttributeCondition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *AudienceAttributeCondition) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *AudienceAttributeCondition) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *AudienceAttributeCondition) SetField(v string)`

SetField sets Field field to given value.


### GetOp

`func (o *AudienceAttributeCondition) GetOp() AudienceConditionOp`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *AudienceAttributeCondition) GetOpOk() (*AudienceConditionOp, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *AudienceAttributeCondition) SetOp(v AudienceConditionOp)`

SetOp sets Op field to given value.


### GetValue

`func (o *AudienceAttributeCondition) GetValue() AudienceConditionValue`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AudienceAttributeCondition) GetValueOk() (*AudienceConditionValue, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AudienceAttributeCondition) SetValue(v AudienceConditionValue)`

SetValue sets Value field to given value.

### HasValue

`func (o *AudienceAttributeCondition) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *AudienceAttributeCondition) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *AudienceAttributeCondition) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


