# UpdateSenderInputSmtp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | Pointer to **string** | The server hostname. | [optional] 
**Port** | Pointer to **int32** | The server port. | [optional] 
**Security** | Pointer to **string** | TLS mode: &#x60;ssl&#x60; (implicit TLS), &#x60;tls&#x60; (STARTTLS), or &#x60;none&#x60;. Defaults to STARTTLS when unset. | [optional] 
**Password** | Pointer to **string** | Auth password; encrypted at rest and never returned. | [optional] 
**Username** | Pointer to **string** | Auth username; defaults to the fromEmail when omitted. | [optional] 

## Methods

### NewUpdateSenderInputSmtp

`func NewUpdateSenderInputSmtp() *UpdateSenderInputSmtp`

NewUpdateSenderInputSmtp instantiates a new UpdateSenderInputSmtp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateSenderInputSmtpWithDefaults

`func NewUpdateSenderInputSmtpWithDefaults() *UpdateSenderInputSmtp`

NewUpdateSenderInputSmtpWithDefaults instantiates a new UpdateSenderInputSmtp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *UpdateSenderInputSmtp) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *UpdateSenderInputSmtp) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *UpdateSenderInputSmtp) SetHost(v string)`

SetHost sets Host field to given value.

### HasHost

`func (o *UpdateSenderInputSmtp) HasHost() bool`

HasHost returns a boolean if a field has been set.

### GetPort

`func (o *UpdateSenderInputSmtp) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *UpdateSenderInputSmtp) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *UpdateSenderInputSmtp) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *UpdateSenderInputSmtp) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetSecurity

`func (o *UpdateSenderInputSmtp) GetSecurity() string`

GetSecurity returns the Security field if non-nil, zero value otherwise.

### GetSecurityOk

`func (o *UpdateSenderInputSmtp) GetSecurityOk() (*string, bool)`

GetSecurityOk returns a tuple with the Security field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurity

`func (o *UpdateSenderInputSmtp) SetSecurity(v string)`

SetSecurity sets Security field to given value.

### HasSecurity

`func (o *UpdateSenderInputSmtp) HasSecurity() bool`

HasSecurity returns a boolean if a field has been set.

### GetPassword

`func (o *UpdateSenderInputSmtp) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UpdateSenderInputSmtp) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UpdateSenderInputSmtp) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UpdateSenderInputSmtp) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetUsername

`func (o *UpdateSenderInputSmtp) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *UpdateSenderInputSmtp) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *UpdateSenderInputSmtp) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *UpdateSenderInputSmtp) HasUsername() bool`

HasUsername returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


