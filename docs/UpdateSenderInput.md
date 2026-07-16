# UpdateSenderInput

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
**State** | Pointer to **string** | Operator-set state to pause or resume the mailbox: &#x60;healthy&#x60;, &#x60;throttled&#x60;, or &#x60;paused&#x60;. | [optional] 
**Warmup** | Pointer to [**NullableWarmupSettings**](WarmupSettings.md) |  | [optional] 
**ArchivedAt** | Pointer to **NullableInt32** |  | [optional] 
**FromEmail** | Pointer to **string** | The sending address (re-verifies the mailbox when changed). | [optional] 
**FromName** | Pointer to **string** | Display name. | [optional] 
**Imap** | Pointer to [**UpdateSenderInputImap**](UpdateSenderInputImap.md) |  | [optional] 
**Smtp** | Pointer to [**UpdateSenderInputSmtp**](UpdateSenderInputSmtp.md) |  | [optional] 
**TransportMode** | Pointer to **string** | How messages are carried: &#x60;smtp&#x60;, &#x60;provider_api&#x60;, &#x60;self_hosted&#x60;, or &#x60;voice&#x60;. | [optional] 
**TransportProvider** | Pointer to **string** | Managed provider; omit for a plain cold/SMTP mailbox. | [optional] 

## Methods

### NewUpdateSenderInput

`func NewUpdateSenderInput() *UpdateSenderInput`

NewUpdateSenderInput instantiates a new UpdateSenderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateSenderInputWithDefaults

`func NewUpdateSenderInputWithDefaults() *UpdateSenderInput`

NewUpdateSenderInputWithDefaults instantiates a new UpdateSenderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBccCrmEmail

`func (o *UpdateSenderInput) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *UpdateSenderInput) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *UpdateSenderInput) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.

### HasBccCrmEmail

`func (o *UpdateSenderInput) HasBccCrmEmail() bool`

HasBccCrmEmail returns a boolean if a field has been set.

### GetClientLabel

`func (o *UpdateSenderInput) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *UpdateSenderInput) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *UpdateSenderInput) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.

### HasClientLabel

`func (o *UpdateSenderInput) HasClientLabel() bool`

HasClientLabel returns a boolean if a field has been set.

### GetDailyLimit

`func (o *UpdateSenderInput) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *UpdateSenderInput) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *UpdateSenderInput) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.

### HasDailyLimit

`func (o *UpdateSenderInput) HasDailyLimit() bool`

HasDailyLimit returns a boolean if a field has been set.

### GetMinGapMinutes

`func (o *UpdateSenderInput) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *UpdateSenderInput) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *UpdateSenderInput) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.

### HasMinGapMinutes

`func (o *UpdateSenderInput) HasMinGapMinutes() bool`

HasMinGapMinutes returns a boolean if a field has been set.

### GetReplyTo

`func (o *UpdateSenderInput) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *UpdateSenderInput) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *UpdateSenderInput) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *UpdateSenderInput) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetSendingDomainId

`func (o *UpdateSenderInput) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *UpdateSenderInput) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *UpdateSenderInput) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.

### HasSendingDomainId

`func (o *UpdateSenderInput) HasSendingDomainId() bool`

HasSendingDomainId returns a boolean if a field has been set.

### GetSignatureHtml

`func (o *UpdateSenderInput) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *UpdateSenderInput) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *UpdateSenderInput) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.

### HasSignatureHtml

`func (o *UpdateSenderInput) HasSignatureHtml() bool`

HasSignatureHtml returns a boolean if a field has been set.

### GetState

`func (o *UpdateSenderInput) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *UpdateSenderInput) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *UpdateSenderInput) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *UpdateSenderInput) HasState() bool`

HasState returns a boolean if a field has been set.

### GetWarmup

`func (o *UpdateSenderInput) GetWarmup() WarmupSettings`

GetWarmup returns the Warmup field if non-nil, zero value otherwise.

### GetWarmupOk

`func (o *UpdateSenderInput) GetWarmupOk() (*WarmupSettings, bool)`

GetWarmupOk returns a tuple with the Warmup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmup

`func (o *UpdateSenderInput) SetWarmup(v WarmupSettings)`

SetWarmup sets Warmup field to given value.

### HasWarmup

`func (o *UpdateSenderInput) HasWarmup() bool`

HasWarmup returns a boolean if a field has been set.

### SetWarmupNil

`func (o *UpdateSenderInput) SetWarmupNil(b bool)`

 SetWarmupNil sets the value for Warmup to be an explicit nil

### UnsetWarmup
`func (o *UpdateSenderInput) UnsetWarmup()`

UnsetWarmup ensures that no value is present for Warmup, not even an explicit nil
### GetArchivedAt

`func (o *UpdateSenderInput) GetArchivedAt() int32`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *UpdateSenderInput) GetArchivedAtOk() (*int32, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *UpdateSenderInput) SetArchivedAt(v int32)`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *UpdateSenderInput) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *UpdateSenderInput) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *UpdateSenderInput) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetFromEmail

`func (o *UpdateSenderInput) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *UpdateSenderInput) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *UpdateSenderInput) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.

### HasFromEmail

`func (o *UpdateSenderInput) HasFromEmail() bool`

HasFromEmail returns a boolean if a field has been set.

### GetFromName

`func (o *UpdateSenderInput) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *UpdateSenderInput) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *UpdateSenderInput) SetFromName(v string)`

SetFromName sets FromName field to given value.

### HasFromName

`func (o *UpdateSenderInput) HasFromName() bool`

HasFromName returns a boolean if a field has been set.

### GetImap

`func (o *UpdateSenderInput) GetImap() UpdateSenderInputImap`

GetImap returns the Imap field if non-nil, zero value otherwise.

### GetImapOk

`func (o *UpdateSenderInput) GetImapOk() (*UpdateSenderInputImap, bool)`

GetImapOk returns a tuple with the Imap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImap

`func (o *UpdateSenderInput) SetImap(v UpdateSenderInputImap)`

SetImap sets Imap field to given value.

### HasImap

`func (o *UpdateSenderInput) HasImap() bool`

HasImap returns a boolean if a field has been set.

### GetSmtp

`func (o *UpdateSenderInput) GetSmtp() UpdateSenderInputSmtp`

GetSmtp returns the Smtp field if non-nil, zero value otherwise.

### GetSmtpOk

`func (o *UpdateSenderInput) GetSmtpOk() (*UpdateSenderInputSmtp, bool)`

GetSmtpOk returns a tuple with the Smtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtp

`func (o *UpdateSenderInput) SetSmtp(v UpdateSenderInputSmtp)`

SetSmtp sets Smtp field to given value.

### HasSmtp

`func (o *UpdateSenderInput) HasSmtp() bool`

HasSmtp returns a boolean if a field has been set.

### GetTransportMode

`func (o *UpdateSenderInput) GetTransportMode() string`

GetTransportMode returns the TransportMode field if non-nil, zero value otherwise.

### GetTransportModeOk

`func (o *UpdateSenderInput) GetTransportModeOk() (*string, bool)`

GetTransportModeOk returns a tuple with the TransportMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportMode

`func (o *UpdateSenderInput) SetTransportMode(v string)`

SetTransportMode sets TransportMode field to given value.

### HasTransportMode

`func (o *UpdateSenderInput) HasTransportMode() bool`

HasTransportMode returns a boolean if a field has been set.

### GetTransportProvider

`func (o *UpdateSenderInput) GetTransportProvider() string`

GetTransportProvider returns the TransportProvider field if non-nil, zero value otherwise.

### GetTransportProviderOk

`func (o *UpdateSenderInput) GetTransportProviderOk() (*string, bool)`

GetTransportProviderOk returns a tuple with the TransportProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportProvider

`func (o *UpdateSenderInput) SetTransportProvider(v string)`

SetTransportProvider sets TransportProvider field to given value.

### HasTransportProvider

`func (o *UpdateSenderInput) HasTransportProvider() bool`

HasTransportProvider returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


