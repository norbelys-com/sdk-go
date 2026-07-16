# DomainCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Capability** | Pointer to **string** | What the domain is for: &#x60;sending&#x60;, &#x60;monitoring&#x60;, or &#x60;tracking&#x60;. Defaults to &#x60;sending&#x60;. | [optional] [default to "sending"]
**Domain** | **string** | The bare DNS name. | 
**Monitoring** | Pointer to [**DomainCreateParamsMonitoring**](DomainCreateParamsMonitoring.md) |  | [optional] 
**Tracking** | Pointer to [**DomainCreateParamsTracking**](DomainCreateParamsTracking.md) |  | [optional] 

## Methods

### NewDomainCreateParams

`func NewDomainCreateParams(domain string, ) *DomainCreateParams`

NewDomainCreateParams instantiates a new DomainCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainCreateParamsWithDefaults

`func NewDomainCreateParamsWithDefaults() *DomainCreateParams`

NewDomainCreateParamsWithDefaults instantiates a new DomainCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCapability

`func (o *DomainCreateParams) GetCapability() string`

GetCapability returns the Capability field if non-nil, zero value otherwise.

### GetCapabilityOk

`func (o *DomainCreateParams) GetCapabilityOk() (*string, bool)`

GetCapabilityOk returns a tuple with the Capability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapability

`func (o *DomainCreateParams) SetCapability(v string)`

SetCapability sets Capability field to given value.

### HasCapability

`func (o *DomainCreateParams) HasCapability() bool`

HasCapability returns a boolean if a field has been set.

### GetDomain

`func (o *DomainCreateParams) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainCreateParams) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainCreateParams) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetMonitoring

`func (o *DomainCreateParams) GetMonitoring() DomainCreateParamsMonitoring`

GetMonitoring returns the Monitoring field if non-nil, zero value otherwise.

### GetMonitoringOk

`func (o *DomainCreateParams) GetMonitoringOk() (*DomainCreateParamsMonitoring, bool)`

GetMonitoringOk returns a tuple with the Monitoring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoring

`func (o *DomainCreateParams) SetMonitoring(v DomainCreateParamsMonitoring)`

SetMonitoring sets Monitoring field to given value.

### HasMonitoring

`func (o *DomainCreateParams) HasMonitoring() bool`

HasMonitoring returns a boolean if a field has been set.

### GetTracking

`func (o *DomainCreateParams) GetTracking() DomainCreateParamsTracking`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *DomainCreateParams) GetTrackingOk() (*DomainCreateParamsTracking, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *DomainCreateParams) SetTracking(v DomainCreateParamsTracking)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *DomainCreateParams) HasTracking() bool`

HasTracking returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


