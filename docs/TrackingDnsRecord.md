# TrackingDnsRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | The CNAME host to create. | 
**Type** | **interface{}** |  | 
**Value** | **string** | The CNAME target to point at. | 

## Methods

### NewTrackingDnsRecord

`func NewTrackingDnsRecord(host string, type_ interface{}, value string, ) *TrackingDnsRecord`

NewTrackingDnsRecord instantiates a new TrackingDnsRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingDnsRecordWithDefaults

`func NewTrackingDnsRecordWithDefaults() *TrackingDnsRecord`

NewTrackingDnsRecordWithDefaults instantiates a new TrackingDnsRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *TrackingDnsRecord) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *TrackingDnsRecord) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *TrackingDnsRecord) SetHost(v string)`

SetHost sets Host field to given value.


### GetType

`func (o *TrackingDnsRecord) GetType() interface{}`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrackingDnsRecord) GetTypeOk() (*interface{}, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrackingDnsRecord) SetType(v interface{})`

SetType sets Type field to given value.


### SetTypeNil

`func (o *TrackingDnsRecord) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *TrackingDnsRecord) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetValue

`func (o *TrackingDnsRecord) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *TrackingDnsRecord) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *TrackingDnsRecord) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


