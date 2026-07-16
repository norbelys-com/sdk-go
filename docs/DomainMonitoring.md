# DomainMonitoring

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CollectionStatus** | **string** | Where report collection stands: \&quot;waiting\&quot; &#x3D; the &#x60;_dmarc&#x60; rua record isn&#39;t pointing to us yet; \&quot;live\&quot; &#x3D; published to us, awaiting the first report; \&quot;collecting\&quot; &#x3D; reports are arriving. | 
**DmarcPolicy** | **NullableString** |  | 
**Kind** | **string** | \&quot;sending\&quot; &#x3D; one of our own sending domains; \&quot;external\&quot; &#x3D; monitor-only. | 
**LastReportAt** | Pointer to **interface{}** |  | [optional] 
**PassRate7d** | **NullableFloat32** |  | 
**RecordToPublish** | [**NullableDmarcRecordToPublish**](DmarcRecordToPublish.md) |  | 
**SendingDomainId** | **NullableString** |  | 

## Methods

### NewDomainMonitoring

`func NewDomainMonitoring(collectionStatus string, dmarcPolicy NullableString, kind string, passRate7d NullableFloat32, recordToPublish NullableDmarcRecordToPublish, sendingDomainId NullableString, ) *DomainMonitoring`

NewDomainMonitoring instantiates a new DomainMonitoring object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainMonitoringWithDefaults

`func NewDomainMonitoringWithDefaults() *DomainMonitoring`

NewDomainMonitoringWithDefaults instantiates a new DomainMonitoring object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollectionStatus

`func (o *DomainMonitoring) GetCollectionStatus() string`

GetCollectionStatus returns the CollectionStatus field if non-nil, zero value otherwise.

### GetCollectionStatusOk

`func (o *DomainMonitoring) GetCollectionStatusOk() (*string, bool)`

GetCollectionStatusOk returns a tuple with the CollectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionStatus

`func (o *DomainMonitoring) SetCollectionStatus(v string)`

SetCollectionStatus sets CollectionStatus field to given value.


### GetDmarcPolicy

`func (o *DomainMonitoring) GetDmarcPolicy() string`

GetDmarcPolicy returns the DmarcPolicy field if non-nil, zero value otherwise.

### GetDmarcPolicyOk

`func (o *DomainMonitoring) GetDmarcPolicyOk() (*string, bool)`

GetDmarcPolicyOk returns a tuple with the DmarcPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDmarcPolicy

`func (o *DomainMonitoring) SetDmarcPolicy(v string)`

SetDmarcPolicy sets DmarcPolicy field to given value.


### SetDmarcPolicyNil

`func (o *DomainMonitoring) SetDmarcPolicyNil(b bool)`

 SetDmarcPolicyNil sets the value for DmarcPolicy to be an explicit nil

### UnsetDmarcPolicy
`func (o *DomainMonitoring) UnsetDmarcPolicy()`

UnsetDmarcPolicy ensures that no value is present for DmarcPolicy, not even an explicit nil
### GetKind

`func (o *DomainMonitoring) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *DomainMonitoring) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *DomainMonitoring) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLastReportAt

`func (o *DomainMonitoring) GetLastReportAt() interface{}`

GetLastReportAt returns the LastReportAt field if non-nil, zero value otherwise.

### GetLastReportAtOk

`func (o *DomainMonitoring) GetLastReportAtOk() (*interface{}, bool)`

GetLastReportAtOk returns a tuple with the LastReportAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReportAt

`func (o *DomainMonitoring) SetLastReportAt(v interface{})`

SetLastReportAt sets LastReportAt field to given value.

### HasLastReportAt

`func (o *DomainMonitoring) HasLastReportAt() bool`

HasLastReportAt returns a boolean if a field has been set.

### SetLastReportAtNil

`func (o *DomainMonitoring) SetLastReportAtNil(b bool)`

 SetLastReportAtNil sets the value for LastReportAt to be an explicit nil

### UnsetLastReportAt
`func (o *DomainMonitoring) UnsetLastReportAt()`

UnsetLastReportAt ensures that no value is present for LastReportAt, not even an explicit nil
### GetPassRate7d

`func (o *DomainMonitoring) GetPassRate7d() float32`

GetPassRate7d returns the PassRate7d field if non-nil, zero value otherwise.

### GetPassRate7dOk

`func (o *DomainMonitoring) GetPassRate7dOk() (*float32, bool)`

GetPassRate7dOk returns a tuple with the PassRate7d field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassRate7d

`func (o *DomainMonitoring) SetPassRate7d(v float32)`

SetPassRate7d sets PassRate7d field to given value.


### SetPassRate7dNil

`func (o *DomainMonitoring) SetPassRate7dNil(b bool)`

 SetPassRate7dNil sets the value for PassRate7d to be an explicit nil

### UnsetPassRate7d
`func (o *DomainMonitoring) UnsetPassRate7d()`

UnsetPassRate7d ensures that no value is present for PassRate7d, not even an explicit nil
### GetRecordToPublish

`func (o *DomainMonitoring) GetRecordToPublish() DmarcRecordToPublish`

GetRecordToPublish returns the RecordToPublish field if non-nil, zero value otherwise.

### GetRecordToPublishOk

`func (o *DomainMonitoring) GetRecordToPublishOk() (*DmarcRecordToPublish, bool)`

GetRecordToPublishOk returns a tuple with the RecordToPublish field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordToPublish

`func (o *DomainMonitoring) SetRecordToPublish(v DmarcRecordToPublish)`

SetRecordToPublish sets RecordToPublish field to given value.


### SetRecordToPublishNil

`func (o *DomainMonitoring) SetRecordToPublishNil(b bool)`

 SetRecordToPublishNil sets the value for RecordToPublish to be an explicit nil

### UnsetRecordToPublish
`func (o *DomainMonitoring) UnsetRecordToPublish()`

UnsetRecordToPublish ensures that no value is present for RecordToPublish, not even an explicit nil
### GetSendingDomainId

`func (o *DomainMonitoring) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *DomainMonitoring) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *DomainMonitoring) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.


### SetSendingDomainIdNil

`func (o *DomainMonitoring) SetSendingDomainIdNil(b bool)`

 SetSendingDomainIdNil sets the value for SendingDomainId to be an explicit nil

### UnsetSendingDomainId
`func (o *DomainMonitoring) UnsetSendingDomainId()`

UnsetSendingDomainId ensures that no value is present for SendingDomainId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


