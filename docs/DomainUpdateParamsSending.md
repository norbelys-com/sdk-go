# DomainUpdateParamsSending

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DefaultTrackingDomainId** | Pointer to **NullableString** |  | [optional] 
**Policy** | Pointer to [**DomainUpdateParamsSendingPolicy**](DomainUpdateParamsSendingPolicy.md) |  | [optional] 

## Methods

### NewDomainUpdateParamsSending

`func NewDomainUpdateParamsSending() *DomainUpdateParamsSending`

NewDomainUpdateParamsSending instantiates a new DomainUpdateParamsSending object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainUpdateParamsSendingWithDefaults

`func NewDomainUpdateParamsSendingWithDefaults() *DomainUpdateParamsSending`

NewDomainUpdateParamsSendingWithDefaults instantiates a new DomainUpdateParamsSending object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefaultTrackingDomainId

`func (o *DomainUpdateParamsSending) GetDefaultTrackingDomainId() string`

GetDefaultTrackingDomainId returns the DefaultTrackingDomainId field if non-nil, zero value otherwise.

### GetDefaultTrackingDomainIdOk

`func (o *DomainUpdateParamsSending) GetDefaultTrackingDomainIdOk() (*string, bool)`

GetDefaultTrackingDomainIdOk returns a tuple with the DefaultTrackingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTrackingDomainId

`func (o *DomainUpdateParamsSending) SetDefaultTrackingDomainId(v string)`

SetDefaultTrackingDomainId sets DefaultTrackingDomainId field to given value.

### HasDefaultTrackingDomainId

`func (o *DomainUpdateParamsSending) HasDefaultTrackingDomainId() bool`

HasDefaultTrackingDomainId returns a boolean if a field has been set.

### SetDefaultTrackingDomainIdNil

`func (o *DomainUpdateParamsSending) SetDefaultTrackingDomainIdNil(b bool)`

 SetDefaultTrackingDomainIdNil sets the value for DefaultTrackingDomainId to be an explicit nil

### UnsetDefaultTrackingDomainId
`func (o *DomainUpdateParamsSending) UnsetDefaultTrackingDomainId()`

UnsetDefaultTrackingDomainId ensures that no value is present for DefaultTrackingDomainId, not even an explicit nil
### GetPolicy

`func (o *DomainUpdateParamsSending) GetPolicy() DomainUpdateParamsSendingPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *DomainUpdateParamsSending) GetPolicyOk() (*DomainUpdateParamsSendingPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *DomainUpdateParamsSending) SetPolicy(v DomainUpdateParamsSendingPolicy)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *DomainUpdateParamsSending) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


