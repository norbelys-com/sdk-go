# DomainMonitoringParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | Pointer to **string** | What the monitored domain is: &#x60;sending&#x60; (one of our own) or &#x60;external&#x60; (monitor-only). Defaults to &#x60;external&#x60;. | [optional] [default to "external"]
**SendingDomainId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDomainMonitoringParams

`func NewDomainMonitoringParams() *DomainMonitoringParams`

NewDomainMonitoringParams instantiates a new DomainMonitoringParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainMonitoringParamsWithDefaults

`func NewDomainMonitoringParamsWithDefaults() *DomainMonitoringParams`

NewDomainMonitoringParamsWithDefaults instantiates a new DomainMonitoringParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *DomainMonitoringParams) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *DomainMonitoringParams) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *DomainMonitoringParams) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *DomainMonitoringParams) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetSendingDomainId

`func (o *DomainMonitoringParams) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *DomainMonitoringParams) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *DomainMonitoringParams) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.

### HasSendingDomainId

`func (o *DomainMonitoringParams) HasSendingDomainId() bool`

HasSendingDomainId returns a boolean if a field has been set.

### SetSendingDomainIdNil

`func (o *DomainMonitoringParams) SetSendingDomainIdNil(b bool)`

 SetSendingDomainIdNil sets the value for SendingDomainId to be an explicit nil

### UnsetSendingDomainId
`func (o *DomainMonitoringParams) UnsetSendingDomainId()`

UnsetSendingDomainId ensures that no value is present for SendingDomainId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


