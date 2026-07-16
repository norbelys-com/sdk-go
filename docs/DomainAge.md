# DomainAge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgeDays** | **NullableInt32** |  | 
**CheckedAt** | Pointer to **interface{}** |  | [optional] 
**FirstHealthyAt** | Pointer to **interface{}** |  | [optional] 
**FirstSeenSendingAt** | Pointer to **interface{}** |  | [optional] 
**RegisteredAt** | Pointer to **interface{}** |  | [optional] 
**SendingAgeDays** | **NullableInt32** |  | 
**Source** | **string** | Where the age came from: &#x60;rdap&#x60;, &#x60;sending_history&#x60;, or &#x60;unknown&#x60;. | 

## Methods

### NewDomainAge

`func NewDomainAge(ageDays NullableInt32, sendingAgeDays NullableInt32, source string, ) *DomainAge`

NewDomainAge instantiates a new DomainAge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainAgeWithDefaults

`func NewDomainAgeWithDefaults() *DomainAge`

NewDomainAgeWithDefaults instantiates a new DomainAge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgeDays

`func (o *DomainAge) GetAgeDays() int32`

GetAgeDays returns the AgeDays field if non-nil, zero value otherwise.

### GetAgeDaysOk

`func (o *DomainAge) GetAgeDaysOk() (*int32, bool)`

GetAgeDaysOk returns a tuple with the AgeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeDays

`func (o *DomainAge) SetAgeDays(v int32)`

SetAgeDays sets AgeDays field to given value.


### SetAgeDaysNil

`func (o *DomainAge) SetAgeDaysNil(b bool)`

 SetAgeDaysNil sets the value for AgeDays to be an explicit nil

### UnsetAgeDays
`func (o *DomainAge) UnsetAgeDays()`

UnsetAgeDays ensures that no value is present for AgeDays, not even an explicit nil
### GetCheckedAt

`func (o *DomainAge) GetCheckedAt() interface{}`

GetCheckedAt returns the CheckedAt field if non-nil, zero value otherwise.

### GetCheckedAtOk

`func (o *DomainAge) GetCheckedAtOk() (*interface{}, bool)`

GetCheckedAtOk returns a tuple with the CheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedAt

`func (o *DomainAge) SetCheckedAt(v interface{})`

SetCheckedAt sets CheckedAt field to given value.

### HasCheckedAt

`func (o *DomainAge) HasCheckedAt() bool`

HasCheckedAt returns a boolean if a field has been set.

### SetCheckedAtNil

`func (o *DomainAge) SetCheckedAtNil(b bool)`

 SetCheckedAtNil sets the value for CheckedAt to be an explicit nil

### UnsetCheckedAt
`func (o *DomainAge) UnsetCheckedAt()`

UnsetCheckedAt ensures that no value is present for CheckedAt, not even an explicit nil
### GetFirstHealthyAt

`func (o *DomainAge) GetFirstHealthyAt() interface{}`

GetFirstHealthyAt returns the FirstHealthyAt field if non-nil, zero value otherwise.

### GetFirstHealthyAtOk

`func (o *DomainAge) GetFirstHealthyAtOk() (*interface{}, bool)`

GetFirstHealthyAtOk returns a tuple with the FirstHealthyAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstHealthyAt

`func (o *DomainAge) SetFirstHealthyAt(v interface{})`

SetFirstHealthyAt sets FirstHealthyAt field to given value.

### HasFirstHealthyAt

`func (o *DomainAge) HasFirstHealthyAt() bool`

HasFirstHealthyAt returns a boolean if a field has been set.

### SetFirstHealthyAtNil

`func (o *DomainAge) SetFirstHealthyAtNil(b bool)`

 SetFirstHealthyAtNil sets the value for FirstHealthyAt to be an explicit nil

### UnsetFirstHealthyAt
`func (o *DomainAge) UnsetFirstHealthyAt()`

UnsetFirstHealthyAt ensures that no value is present for FirstHealthyAt, not even an explicit nil
### GetFirstSeenSendingAt

`func (o *DomainAge) GetFirstSeenSendingAt() interface{}`

GetFirstSeenSendingAt returns the FirstSeenSendingAt field if non-nil, zero value otherwise.

### GetFirstSeenSendingAtOk

`func (o *DomainAge) GetFirstSeenSendingAtOk() (*interface{}, bool)`

GetFirstSeenSendingAtOk returns a tuple with the FirstSeenSendingAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenSendingAt

`func (o *DomainAge) SetFirstSeenSendingAt(v interface{})`

SetFirstSeenSendingAt sets FirstSeenSendingAt field to given value.

### HasFirstSeenSendingAt

`func (o *DomainAge) HasFirstSeenSendingAt() bool`

HasFirstSeenSendingAt returns a boolean if a field has been set.

### SetFirstSeenSendingAtNil

`func (o *DomainAge) SetFirstSeenSendingAtNil(b bool)`

 SetFirstSeenSendingAtNil sets the value for FirstSeenSendingAt to be an explicit nil

### UnsetFirstSeenSendingAt
`func (o *DomainAge) UnsetFirstSeenSendingAt()`

UnsetFirstSeenSendingAt ensures that no value is present for FirstSeenSendingAt, not even an explicit nil
### GetRegisteredAt

`func (o *DomainAge) GetRegisteredAt() interface{}`

GetRegisteredAt returns the RegisteredAt field if non-nil, zero value otherwise.

### GetRegisteredAtOk

`func (o *DomainAge) GetRegisteredAtOk() (*interface{}, bool)`

GetRegisteredAtOk returns a tuple with the RegisteredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredAt

`func (o *DomainAge) SetRegisteredAt(v interface{})`

SetRegisteredAt sets RegisteredAt field to given value.

### HasRegisteredAt

`func (o *DomainAge) HasRegisteredAt() bool`

HasRegisteredAt returns a boolean if a field has been set.

### SetRegisteredAtNil

`func (o *DomainAge) SetRegisteredAtNil(b bool)`

 SetRegisteredAtNil sets the value for RegisteredAt to be an explicit nil

### UnsetRegisteredAt
`func (o *DomainAge) UnsetRegisteredAt()`

UnsetRegisteredAt ensures that no value is present for RegisteredAt, not even an explicit nil
### GetSendingAgeDays

`func (o *DomainAge) GetSendingAgeDays() int32`

GetSendingAgeDays returns the SendingAgeDays field if non-nil, zero value otherwise.

### GetSendingAgeDaysOk

`func (o *DomainAge) GetSendingAgeDaysOk() (*int32, bool)`

GetSendingAgeDaysOk returns a tuple with the SendingAgeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingAgeDays

`func (o *DomainAge) SetSendingAgeDays(v int32)`

SetSendingAgeDays sets SendingAgeDays field to given value.


### SetSendingAgeDaysNil

`func (o *DomainAge) SetSendingAgeDaysNil(b bool)`

 SetSendingAgeDaysNil sets the value for SendingAgeDays to be an explicit nil

### UnsetSendingAgeDays
`func (o *DomainAge) UnsetSendingAgeDays()`

UnsetSendingAgeDays ensures that no value is present for SendingAgeDays, not even an explicit nil
### GetSource

`func (o *DomainAge) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *DomainAge) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *DomainAge) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


