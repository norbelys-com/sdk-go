# AudienceRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | **string** | The field to test: a reserved field key (&#x60;email&#x60;, &#x60;firstname&#x60;, &#x60;lastname&#x60;, &#x60;telephone&#x60;, &#x60;email_domain&#x60;, &#x60;status&#x60;, &#x60;source&#x60;, &#x60;score&#x60;, &#x60;last_activity_at&#x60;, &#x60;created_at&#x60;, &#x60;group&#x60;, &#x60;program&#x60;, &#x60;suppressed&#x60;) or a custom field&#39;s code. | 
**Op** | [**AudienceConditionOp**](AudienceConditionOp.md) |  | 
**Value** | Pointer to [**NullableAudienceAttributeConditionValue**](AudienceAttributeConditionValue.md) |  | [optional] 
**Activity** | [**AudienceActivityParams**](AudienceActivityParams.md) |  | 
**Did** | Pointer to **bool** | &#x60;true&#x60; &#x3D; the person DID this at least once; &#x60;false&#x60; &#x3D; the person did NOT (zero times). | [optional] [default to true]

## Methods

### NewAudienceRule

`func NewAudienceRule(field string, op AudienceConditionOp, activity AudienceActivityParams, ) *AudienceRule`

NewAudienceRule instantiates a new AudienceRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceRuleWithDefaults

`func NewAudienceRuleWithDefaults() *AudienceRule`

NewAudienceRuleWithDefaults instantiates a new AudienceRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *AudienceRule) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *AudienceRule) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *AudienceRule) SetField(v string)`

SetField sets Field field to given value.


### GetOp

`func (o *AudienceRule) GetOp() AudienceConditionOp`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *AudienceRule) GetOpOk() (*AudienceConditionOp, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *AudienceRule) SetOp(v AudienceConditionOp)`

SetOp sets Op field to given value.


### GetValue

`func (o *AudienceRule) GetValue() AudienceAttributeConditionValue`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AudienceRule) GetValueOk() (*AudienceAttributeConditionValue, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AudienceRule) SetValue(v AudienceAttributeConditionValue)`

SetValue sets Value field to given value.

### HasValue

`func (o *AudienceRule) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *AudienceRule) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *AudienceRule) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetActivity

`func (o *AudienceRule) GetActivity() AudienceActivityParams`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *AudienceRule) GetActivityOk() (*AudienceActivityParams, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *AudienceRule) SetActivity(v AudienceActivityParams)`

SetActivity sets Activity field to given value.


### GetDid

`func (o *AudienceRule) GetDid() bool`

GetDid returns the Did field if non-nil, zero value otherwise.

### GetDidOk

`func (o *AudienceRule) GetDidOk() (*bool, bool)`

GetDidOk returns a tuple with the Did field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDid

`func (o *AudienceRule) SetDid(v bool)`

SetDid sets Did field to given value.

### HasDid

`func (o *AudienceRule) HasDid() bool`

HasDid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


