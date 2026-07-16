# DomainUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sending** | Pointer to [**DomainSendingUpdateParams**](DomainSendingUpdateParams.md) |  | [optional] 
**Tracking** | Pointer to [**DomainTrackingUpdateParams**](DomainTrackingUpdateParams.md) |  | [optional] 
**Version** | **int32** | Optimistic concurrency version; must match the current row. | 

## Methods

### NewDomainUpdateParams

`func NewDomainUpdateParams(version int32, ) *DomainUpdateParams`

NewDomainUpdateParams instantiates a new DomainUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainUpdateParamsWithDefaults

`func NewDomainUpdateParamsWithDefaults() *DomainUpdateParams`

NewDomainUpdateParamsWithDefaults instantiates a new DomainUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSending

`func (o *DomainUpdateParams) GetSending() DomainSendingUpdateParams`

GetSending returns the Sending field if non-nil, zero value otherwise.

### GetSendingOk

`func (o *DomainUpdateParams) GetSendingOk() (*DomainSendingUpdateParams, bool)`

GetSendingOk returns a tuple with the Sending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSending

`func (o *DomainUpdateParams) SetSending(v DomainSendingUpdateParams)`

SetSending sets Sending field to given value.

### HasSending

`func (o *DomainUpdateParams) HasSending() bool`

HasSending returns a boolean if a field has been set.

### GetTracking

`func (o *DomainUpdateParams) GetTracking() DomainTrackingUpdateParams`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *DomainUpdateParams) GetTrackingOk() (*DomainTrackingUpdateParams, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *DomainUpdateParams) SetTracking(v DomainTrackingUpdateParams)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *DomainUpdateParams) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### GetVersion

`func (o *DomainUpdateParams) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DomainUpdateParams) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DomainUpdateParams) SetVersion(v int32)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


