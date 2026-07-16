# Domain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Age** | [**NullableDomainAge**](DomainAge.md) |  | 
**Capability** | **string** | What the domain is for: &#x60;sending&#x60;, &#x60;monitoring&#x60;, or &#x60;tracking&#x60;. | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Domain** | **string** | The bare DNS name. | 
**Id** | **string** | The domain id. | 
**Monitoring** | [**NullableDomainMonitoring**](DomainMonitoring.md) |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**SenderCount** | **NullableInt32** |  | 
**Sending** | [**NullableDomainSending**](DomainSending.md) |  | 
**Tracking** | [**NullableDomainTracking**](DomainTracking.md) |  | 
**Version** | **int32** | Optimistic concurrency version. | 

## Methods

### NewDomain

`func NewDomain(age NullableDomainAge, capability string, domain string, id string, monitoring NullableDomainMonitoring, senderCount NullableInt32, sending NullableDomainSending, tracking NullableDomainTracking, version int32, ) *Domain`

NewDomain instantiates a new Domain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainWithDefaults

`func NewDomainWithDefaults() *Domain`

NewDomainWithDefaults instantiates a new Domain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAge

`func (o *Domain) GetAge() DomainAge`

GetAge returns the Age field if non-nil, zero value otherwise.

### GetAgeOk

`func (o *Domain) GetAgeOk() (*DomainAge, bool)`

GetAgeOk returns a tuple with the Age field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAge

`func (o *Domain) SetAge(v DomainAge)`

SetAge sets Age field to given value.


### SetAgeNil

`func (o *Domain) SetAgeNil(b bool)`

 SetAgeNil sets the value for Age to be an explicit nil

### UnsetAge
`func (o *Domain) UnsetAge()`

UnsetAge ensures that no value is present for Age, not even an explicit nil
### GetCapability

`func (o *Domain) GetCapability() string`

GetCapability returns the Capability field if non-nil, zero value otherwise.

### GetCapabilityOk

`func (o *Domain) GetCapabilityOk() (*string, bool)`

GetCapabilityOk returns a tuple with the Capability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapability

`func (o *Domain) SetCapability(v string)`

SetCapability sets Capability field to given value.


### GetCreatedAt

`func (o *Domain) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Domain) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Domain) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Domain) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Domain) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Domain) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetDomain

`func (o *Domain) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *Domain) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *Domain) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetId

`func (o *Domain) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Domain) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Domain) SetId(v string)`

SetId sets Id field to given value.


### GetMonitoring

`func (o *Domain) GetMonitoring() DomainMonitoring`

GetMonitoring returns the Monitoring field if non-nil, zero value otherwise.

### GetMonitoringOk

`func (o *Domain) GetMonitoringOk() (*DomainMonitoring, bool)`

GetMonitoringOk returns a tuple with the Monitoring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoring

`func (o *Domain) SetMonitoring(v DomainMonitoring)`

SetMonitoring sets Monitoring field to given value.


### SetMonitoringNil

`func (o *Domain) SetMonitoringNil(b bool)`

 SetMonitoringNil sets the value for Monitoring to be an explicit nil

### UnsetMonitoring
`func (o *Domain) UnsetMonitoring()`

UnsetMonitoring ensures that no value is present for Monitoring, not even an explicit nil
### GetObject

`func (o *Domain) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Domain) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Domain) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Domain) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Domain) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Domain) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetSenderCount

`func (o *Domain) GetSenderCount() int32`

GetSenderCount returns the SenderCount field if non-nil, zero value otherwise.

### GetSenderCountOk

`func (o *Domain) GetSenderCountOk() (*int32, bool)`

GetSenderCountOk returns a tuple with the SenderCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCount

`func (o *Domain) SetSenderCount(v int32)`

SetSenderCount sets SenderCount field to given value.


### SetSenderCountNil

`func (o *Domain) SetSenderCountNil(b bool)`

 SetSenderCountNil sets the value for SenderCount to be an explicit nil

### UnsetSenderCount
`func (o *Domain) UnsetSenderCount()`

UnsetSenderCount ensures that no value is present for SenderCount, not even an explicit nil
### GetSending

`func (o *Domain) GetSending() DomainSending`

GetSending returns the Sending field if non-nil, zero value otherwise.

### GetSendingOk

`func (o *Domain) GetSendingOk() (*DomainSending, bool)`

GetSendingOk returns a tuple with the Sending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSending

`func (o *Domain) SetSending(v DomainSending)`

SetSending sets Sending field to given value.


### SetSendingNil

`func (o *Domain) SetSendingNil(b bool)`

 SetSendingNil sets the value for Sending to be an explicit nil

### UnsetSending
`func (o *Domain) UnsetSending()`

UnsetSending ensures that no value is present for Sending, not even an explicit nil
### GetTracking

`func (o *Domain) GetTracking() DomainTracking`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *Domain) GetTrackingOk() (*DomainTracking, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *Domain) SetTracking(v DomainTracking)`

SetTracking sets Tracking field to given value.


### SetTrackingNil

`func (o *Domain) SetTrackingNil(b bool)`

 SetTrackingNil sets the value for Tracking to be an explicit nil

### UnsetTracking
`func (o *Domain) UnsetTracking()`

UnsetTracking ensures that no value is present for Tracking, not even an explicit nil
### GetVersion

`func (o *Domain) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *Domain) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *Domain) SetVersion(v int32)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


