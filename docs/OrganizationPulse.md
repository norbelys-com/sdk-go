# OrganizationPulse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deliverability** | [**PulseDeliverability**](PulseDeliverability.md) |  | 
**Object** | **interface{}** |  | 
**Programs** | [**[]PulseProgram**](PulseProgram.md) | Every non-archived campaign with its state and window metrics — active first, then by lead count. | 
**Senders** | [**PulseSenderFleet**](PulseSenderFleet.md) |  | 
**Value** | [**PulseValue**](PulseValue.md) |  | 
**WindowDays** | **float32** | The window (days) the metrics were computed over. Example: 7 | 

## Methods

### NewOrganizationPulse

`func NewOrganizationPulse(deliverability PulseDeliverability, object interface{}, programs []PulseProgram, senders PulseSenderFleet, value PulseValue, windowDays float32, ) *OrganizationPulse`

NewOrganizationPulse instantiates a new OrganizationPulse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationPulseWithDefaults

`func NewOrganizationPulseWithDefaults() *OrganizationPulse`

NewOrganizationPulseWithDefaults instantiates a new OrganizationPulse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliverability

`func (o *OrganizationPulse) GetDeliverability() PulseDeliverability`

GetDeliverability returns the Deliverability field if non-nil, zero value otherwise.

### GetDeliverabilityOk

`func (o *OrganizationPulse) GetDeliverabilityOk() (*PulseDeliverability, bool)`

GetDeliverabilityOk returns a tuple with the Deliverability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverability

`func (o *OrganizationPulse) SetDeliverability(v PulseDeliverability)`

SetDeliverability sets Deliverability field to given value.


### GetObject

`func (o *OrganizationPulse) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *OrganizationPulse) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *OrganizationPulse) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *OrganizationPulse) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *OrganizationPulse) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPrograms

`func (o *OrganizationPulse) GetPrograms() []PulseProgram`

GetPrograms returns the Programs field if non-nil, zero value otherwise.

### GetProgramsOk

`func (o *OrganizationPulse) GetProgramsOk() (*[]PulseProgram, bool)`

GetProgramsOk returns a tuple with the Programs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrograms

`func (o *OrganizationPulse) SetPrograms(v []PulseProgram)`

SetPrograms sets Programs field to given value.


### GetSenders

`func (o *OrganizationPulse) GetSenders() PulseSenderFleet`

GetSenders returns the Senders field if non-nil, zero value otherwise.

### GetSendersOk

`func (o *OrganizationPulse) GetSendersOk() (*PulseSenderFleet, bool)`

GetSendersOk returns a tuple with the Senders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenders

`func (o *OrganizationPulse) SetSenders(v PulseSenderFleet)`

SetSenders sets Senders field to given value.


### GetValue

`func (o *OrganizationPulse) GetValue() PulseValue`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *OrganizationPulse) GetValueOk() (*PulseValue, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *OrganizationPulse) SetValue(v PulseValue)`

SetValue sets Value field to given value.


### GetWindowDays

`func (o *OrganizationPulse) GetWindowDays() float32`

GetWindowDays returns the WindowDays field if non-nil, zero value otherwise.

### GetWindowDaysOk

`func (o *OrganizationPulse) GetWindowDaysOk() (*float32, bool)`

GetWindowDaysOk returns a tuple with the WindowDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowDays

`func (o *OrganizationPulse) SetWindowDays(v float32)`

SetWindowDays sets WindowDays field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


