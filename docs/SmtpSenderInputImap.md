# SmtpSenderInputImap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | The server hostname. | 
**Port** | **int32** | The server port. | 
**Security** | Pointer to **string** | TLS mode: &#x60;ssl&#x60; (implicit TLS), &#x60;tls&#x60; (STARTTLS), or &#x60;none&#x60;. Defaults to STARTTLS when unset. | [optional] 

## Methods

### NewSmtpSenderInputImap

`func NewSmtpSenderInputImap(host string, port int32, ) *SmtpSenderInputImap`

NewSmtpSenderInputImap instantiates a new SmtpSenderInputImap object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmtpSenderInputImapWithDefaults

`func NewSmtpSenderInputImapWithDefaults() *SmtpSenderInputImap`

NewSmtpSenderInputImapWithDefaults instantiates a new SmtpSenderInputImap object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *SmtpSenderInputImap) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *SmtpSenderInputImap) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *SmtpSenderInputImap) SetHost(v string)`

SetHost sets Host field to given value.


### GetPort

`func (o *SmtpSenderInputImap) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *SmtpSenderInputImap) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *SmtpSenderInputImap) SetPort(v int32)`

SetPort sets Port field to given value.


### GetSecurity

`func (o *SmtpSenderInputImap) GetSecurity() string`

GetSecurity returns the Security field if non-nil, zero value otherwise.

### GetSecurityOk

`func (o *SmtpSenderInputImap) GetSecurityOk() (*string, bool)`

GetSecurityOk returns a tuple with the Security field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurity

`func (o *SmtpSenderInputImap) SetSecurity(v string)`

SetSecurity sets Security field to given value.

### HasSecurity

`func (o *SmtpSenderInputImap) HasSecurity() bool`

HasSecurity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


