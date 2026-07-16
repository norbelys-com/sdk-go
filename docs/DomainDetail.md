# DomainDetail

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
**CollectionAddresses** | Pointer to [**[]CollectionAddress**](CollectionAddress.md) | The monitoring rua addresses DMARC reports are sent to — present when expand[]&#x3D;collectionAddresses (empty on a sending domain). | [optional] 
**TrackingDomains** | Pointer to [**[]Domain**](Domain.md) | Tracking-domain resources assigned to this sending domain, or an empty array for other capabilities. | [optional] 

## Methods

### NewDomainDetail

`func NewDomainDetail(age NullableDomainAge, capability string, domain string, id string, monitoring NullableDomainMonitoring, senderCount NullableInt32, sending NullableDomainSending, tracking NullableDomainTracking, version int32, ) *DomainDetail`

NewDomainDetail instantiates a new DomainDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainDetailWithDefaults

`func NewDomainDetailWithDefaults() *DomainDetail`

NewDomainDetailWithDefaults instantiates a new DomainDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAge

`func (o *DomainDetail) GetAge() DomainAge`

GetAge returns the Age field if non-nil, zero value otherwise.

### GetAgeOk

`func (o *DomainDetail) GetAgeOk() (*DomainAge, bool)`

GetAgeOk returns a tuple with the Age field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAge

`func (o *DomainDetail) SetAge(v DomainAge)`

SetAge sets Age field to given value.


### SetAgeNil

`func (o *DomainDetail) SetAgeNil(b bool)`

 SetAgeNil sets the value for Age to be an explicit nil

### UnsetAge
`func (o *DomainDetail) UnsetAge()`

UnsetAge ensures that no value is present for Age, not even an explicit nil
### GetCapability

`func (o *DomainDetail) GetCapability() string`

GetCapability returns the Capability field if non-nil, zero value otherwise.

### GetCapabilityOk

`func (o *DomainDetail) GetCapabilityOk() (*string, bool)`

GetCapabilityOk returns a tuple with the Capability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapability

`func (o *DomainDetail) SetCapability(v string)`

SetCapability sets Capability field to given value.


### GetCreatedAt

`func (o *DomainDetail) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainDetail) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainDetail) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DomainDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *DomainDetail) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *DomainDetail) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetDomain

`func (o *DomainDetail) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainDetail) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainDetail) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetId

`func (o *DomainDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DomainDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DomainDetail) SetId(v string)`

SetId sets Id field to given value.


### GetMonitoring

`func (o *DomainDetail) GetMonitoring() DomainMonitoring`

GetMonitoring returns the Monitoring field if non-nil, zero value otherwise.

### GetMonitoringOk

`func (o *DomainDetail) GetMonitoringOk() (*DomainMonitoring, bool)`

GetMonitoringOk returns a tuple with the Monitoring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoring

`func (o *DomainDetail) SetMonitoring(v DomainMonitoring)`

SetMonitoring sets Monitoring field to given value.


### SetMonitoringNil

`func (o *DomainDetail) SetMonitoringNil(b bool)`

 SetMonitoringNil sets the value for Monitoring to be an explicit nil

### UnsetMonitoring
`func (o *DomainDetail) UnsetMonitoring()`

UnsetMonitoring ensures that no value is present for Monitoring, not even an explicit nil
### GetObject

`func (o *DomainDetail) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *DomainDetail) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *DomainDetail) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *DomainDetail) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *DomainDetail) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *DomainDetail) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetSenderCount

`func (o *DomainDetail) GetSenderCount() int32`

GetSenderCount returns the SenderCount field if non-nil, zero value otherwise.

### GetSenderCountOk

`func (o *DomainDetail) GetSenderCountOk() (*int32, bool)`

GetSenderCountOk returns a tuple with the SenderCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCount

`func (o *DomainDetail) SetSenderCount(v int32)`

SetSenderCount sets SenderCount field to given value.


### SetSenderCountNil

`func (o *DomainDetail) SetSenderCountNil(b bool)`

 SetSenderCountNil sets the value for SenderCount to be an explicit nil

### UnsetSenderCount
`func (o *DomainDetail) UnsetSenderCount()`

UnsetSenderCount ensures that no value is present for SenderCount, not even an explicit nil
### GetSending

`func (o *DomainDetail) GetSending() DomainSending`

GetSending returns the Sending field if non-nil, zero value otherwise.

### GetSendingOk

`func (o *DomainDetail) GetSendingOk() (*DomainSending, bool)`

GetSendingOk returns a tuple with the Sending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSending

`func (o *DomainDetail) SetSending(v DomainSending)`

SetSending sets Sending field to given value.


### SetSendingNil

`func (o *DomainDetail) SetSendingNil(b bool)`

 SetSendingNil sets the value for Sending to be an explicit nil

### UnsetSending
`func (o *DomainDetail) UnsetSending()`

UnsetSending ensures that no value is present for Sending, not even an explicit nil
### GetTracking

`func (o *DomainDetail) GetTracking() DomainTracking`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *DomainDetail) GetTrackingOk() (*DomainTracking, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *DomainDetail) SetTracking(v DomainTracking)`

SetTracking sets Tracking field to given value.


### SetTrackingNil

`func (o *DomainDetail) SetTrackingNil(b bool)`

 SetTrackingNil sets the value for Tracking to be an explicit nil

### UnsetTracking
`func (o *DomainDetail) UnsetTracking()`

UnsetTracking ensures that no value is present for Tracking, not even an explicit nil
### GetVersion

`func (o *DomainDetail) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DomainDetail) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DomainDetail) SetVersion(v int32)`

SetVersion sets Version field to given value.


### GetCollectionAddresses

`func (o *DomainDetail) GetCollectionAddresses() []CollectionAddress`

GetCollectionAddresses returns the CollectionAddresses field if non-nil, zero value otherwise.

### GetCollectionAddressesOk

`func (o *DomainDetail) GetCollectionAddressesOk() (*[]CollectionAddress, bool)`

GetCollectionAddressesOk returns a tuple with the CollectionAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionAddresses

`func (o *DomainDetail) SetCollectionAddresses(v []CollectionAddress)`

SetCollectionAddresses sets CollectionAddresses field to given value.

### HasCollectionAddresses

`func (o *DomainDetail) HasCollectionAddresses() bool`

HasCollectionAddresses returns a boolean if a field has been set.

### GetTrackingDomains

`func (o *DomainDetail) GetTrackingDomains() []Domain`

GetTrackingDomains returns the TrackingDomains field if non-nil, zero value otherwise.

### GetTrackingDomainsOk

`func (o *DomainDetail) GetTrackingDomainsOk() (*[]Domain, bool)`

GetTrackingDomainsOk returns a tuple with the TrackingDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingDomains

`func (o *DomainDetail) SetTrackingDomains(v []Domain)`

SetTrackingDomains sets TrackingDomains field to given value.

### HasTrackingDomains

`func (o *DomainDetail) HasTrackingDomains() bool`

HasTrackingDomains returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


