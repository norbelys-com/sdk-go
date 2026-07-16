# VerifyMx

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptsMail** | **bool** | Domain has MX records (or an implicit A-record MX, RFC 5321). | 
**Provider** | **NullableString** |  | 
**Records** | **[]string** | MX hostnames, lowercased, deduped. | 

## Methods

### NewVerifyMx

`func NewVerifyMx(acceptsMail bool, provider NullableString, records []string, ) *VerifyMx`

NewVerifyMx instantiates a new VerifyMx object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyMxWithDefaults

`func NewVerifyMxWithDefaults() *VerifyMx`

NewVerifyMxWithDefaults instantiates a new VerifyMx object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptsMail

`func (o *VerifyMx) GetAcceptsMail() bool`

GetAcceptsMail returns the AcceptsMail field if non-nil, zero value otherwise.

### GetAcceptsMailOk

`func (o *VerifyMx) GetAcceptsMailOk() (*bool, bool)`

GetAcceptsMailOk returns a tuple with the AcceptsMail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptsMail

`func (o *VerifyMx) SetAcceptsMail(v bool)`

SetAcceptsMail sets AcceptsMail field to given value.


### GetProvider

`func (o *VerifyMx) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *VerifyMx) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *VerifyMx) SetProvider(v string)`

SetProvider sets Provider field to given value.


### SetProviderNil

`func (o *VerifyMx) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *VerifyMx) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetRecords

`func (o *VerifyMx) GetRecords() []string`

GetRecords returns the Records field if non-nil, zero value otherwise.

### GetRecordsOk

`func (o *VerifyMx) GetRecordsOk() (*[]string, bool)`

GetRecordsOk returns a tuple with the Records field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecords

`func (o *VerifyMx) SetRecords(v []string)`

SetRecords sets Records field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


