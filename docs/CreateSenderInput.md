# CreateSenderInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BccCrmEmail** | Pointer to **string** | BCC every send to this address (CRM capture). | [optional] 
**ClientLabel** | Pointer to **string** | Free-text label for this mailbox (e.g. to tag by client). | [optional] 
**DailyLimit** | Pointer to **int32** | Maximum sends per day for this mailbox. | [optional] 
**MinGapMinutes** | Pointer to **int32** | Minimum gap between sends from this mailbox (floor 3; server default 5). | [optional] 
**ReplyTo** | Pointer to **string** | Reply-To override. | [optional] 
**SendingDomainId** | Pointer to **string** | The sending domain id. Omit to get-or-create it from the fromEmail host. | [optional] 
**SignatureHtml** | Pointer to **string** | HTML signature appended to every send. | [optional] 
**FromEmail** | **string** | The sending address. | 
**FromName** | **string** | Display name. | 
**Imap** | Pointer to [**ConnectionSettings**](ConnectionSettings.md) |  | [optional] 
**Smtp** | [**SmtpConnectionSettings**](SmtpConnectionSettings.md) |  | 
**TransportMode** | **interface{}** |  | 
**TransportProvider** | **string** | The voice provider key. | 

## Methods

### NewCreateSenderInput

`func NewCreateSenderInput(fromEmail string, fromName string, smtp SmtpConnectionSettings, transportMode interface{}, transportProvider string, ) *CreateSenderInput`

NewCreateSenderInput instantiates a new CreateSenderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSenderInputWithDefaults

`func NewCreateSenderInputWithDefaults() *CreateSenderInput`

NewCreateSenderInputWithDefaults instantiates a new CreateSenderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBccCrmEmail

`func (o *CreateSenderInput) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *CreateSenderInput) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *CreateSenderInput) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.

### HasBccCrmEmail

`func (o *CreateSenderInput) HasBccCrmEmail() bool`

HasBccCrmEmail returns a boolean if a field has been set.

### GetClientLabel

`func (o *CreateSenderInput) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *CreateSenderInput) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *CreateSenderInput) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.

### HasClientLabel

`func (o *CreateSenderInput) HasClientLabel() bool`

HasClientLabel returns a boolean if a field has been set.

### GetDailyLimit

`func (o *CreateSenderInput) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *CreateSenderInput) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *CreateSenderInput) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.

### HasDailyLimit

`func (o *CreateSenderInput) HasDailyLimit() bool`

HasDailyLimit returns a boolean if a field has been set.

### GetMinGapMinutes

`func (o *CreateSenderInput) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *CreateSenderInput) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *CreateSenderInput) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.

### HasMinGapMinutes

`func (o *CreateSenderInput) HasMinGapMinutes() bool`

HasMinGapMinutes returns a boolean if a field has been set.

### GetReplyTo

`func (o *CreateSenderInput) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *CreateSenderInput) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *CreateSenderInput) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *CreateSenderInput) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetSendingDomainId

`func (o *CreateSenderInput) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *CreateSenderInput) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *CreateSenderInput) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.

### HasSendingDomainId

`func (o *CreateSenderInput) HasSendingDomainId() bool`

HasSendingDomainId returns a boolean if a field has been set.

### GetSignatureHtml

`func (o *CreateSenderInput) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *CreateSenderInput) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *CreateSenderInput) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.

### HasSignatureHtml

`func (o *CreateSenderInput) HasSignatureHtml() bool`

HasSignatureHtml returns a boolean if a field has been set.

### GetFromEmail

`func (o *CreateSenderInput) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *CreateSenderInput) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *CreateSenderInput) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetFromName

`func (o *CreateSenderInput) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *CreateSenderInput) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *CreateSenderInput) SetFromName(v string)`

SetFromName sets FromName field to given value.


### GetImap

`func (o *CreateSenderInput) GetImap() ConnectionSettings`

GetImap returns the Imap field if non-nil, zero value otherwise.

### GetImapOk

`func (o *CreateSenderInput) GetImapOk() (*ConnectionSettings, bool)`

GetImapOk returns a tuple with the Imap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImap

`func (o *CreateSenderInput) SetImap(v ConnectionSettings)`

SetImap sets Imap field to given value.

### HasImap

`func (o *CreateSenderInput) HasImap() bool`

HasImap returns a boolean if a field has been set.

### GetSmtp

`func (o *CreateSenderInput) GetSmtp() SmtpConnectionSettings`

GetSmtp returns the Smtp field if non-nil, zero value otherwise.

### GetSmtpOk

`func (o *CreateSenderInput) GetSmtpOk() (*SmtpConnectionSettings, bool)`

GetSmtpOk returns a tuple with the Smtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtp

`func (o *CreateSenderInput) SetSmtp(v SmtpConnectionSettings)`

SetSmtp sets Smtp field to given value.


### GetTransportMode

`func (o *CreateSenderInput) GetTransportMode() interface{}`

GetTransportMode returns the TransportMode field if non-nil, zero value otherwise.

### GetTransportModeOk

`func (o *CreateSenderInput) GetTransportModeOk() (*interface{}, bool)`

GetTransportModeOk returns a tuple with the TransportMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportMode

`func (o *CreateSenderInput) SetTransportMode(v interface{})`

SetTransportMode sets TransportMode field to given value.


### SetTransportModeNil

`func (o *CreateSenderInput) SetTransportModeNil(b bool)`

 SetTransportModeNil sets the value for TransportMode to be an explicit nil

### UnsetTransportMode
`func (o *CreateSenderInput) UnsetTransportMode()`

UnsetTransportMode ensures that no value is present for TransportMode, not even an explicit nil
### GetTransportProvider

`func (o *CreateSenderInput) GetTransportProvider() string`

GetTransportProvider returns the TransportProvider field if non-nil, zero value otherwise.

### GetTransportProviderOk

`func (o *CreateSenderInput) GetTransportProviderOk() (*string, bool)`

GetTransportProviderOk returns a tuple with the TransportProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportProvider

`func (o *CreateSenderInput) SetTransportProvider(v string)`

SetTransportProvider sets TransportProvider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


