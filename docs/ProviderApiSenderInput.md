# ProviderApiSenderInput

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
**TransportMode** | **interface{}** |  | 
**TransportProvider** | **string** | The managed provider key. | 

## Methods

### NewProviderApiSenderInput

`func NewProviderApiSenderInput(fromEmail string, fromName string, transportMode interface{}, transportProvider string, ) *ProviderApiSenderInput`

NewProviderApiSenderInput instantiates a new ProviderApiSenderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProviderApiSenderInputWithDefaults

`func NewProviderApiSenderInputWithDefaults() *ProviderApiSenderInput`

NewProviderApiSenderInputWithDefaults instantiates a new ProviderApiSenderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBccCrmEmail

`func (o *ProviderApiSenderInput) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *ProviderApiSenderInput) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *ProviderApiSenderInput) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.

### HasBccCrmEmail

`func (o *ProviderApiSenderInput) HasBccCrmEmail() bool`

HasBccCrmEmail returns a boolean if a field has been set.

### GetClientLabel

`func (o *ProviderApiSenderInput) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *ProviderApiSenderInput) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *ProviderApiSenderInput) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.

### HasClientLabel

`func (o *ProviderApiSenderInput) HasClientLabel() bool`

HasClientLabel returns a boolean if a field has been set.

### GetDailyLimit

`func (o *ProviderApiSenderInput) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *ProviderApiSenderInput) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *ProviderApiSenderInput) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.

### HasDailyLimit

`func (o *ProviderApiSenderInput) HasDailyLimit() bool`

HasDailyLimit returns a boolean if a field has been set.

### GetMinGapMinutes

`func (o *ProviderApiSenderInput) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *ProviderApiSenderInput) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *ProviderApiSenderInput) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.

### HasMinGapMinutes

`func (o *ProviderApiSenderInput) HasMinGapMinutes() bool`

HasMinGapMinutes returns a boolean if a field has been set.

### GetReplyTo

`func (o *ProviderApiSenderInput) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *ProviderApiSenderInput) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *ProviderApiSenderInput) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *ProviderApiSenderInput) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetSendingDomainId

`func (o *ProviderApiSenderInput) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *ProviderApiSenderInput) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *ProviderApiSenderInput) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.

### HasSendingDomainId

`func (o *ProviderApiSenderInput) HasSendingDomainId() bool`

HasSendingDomainId returns a boolean if a field has been set.

### GetSignatureHtml

`func (o *ProviderApiSenderInput) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *ProviderApiSenderInput) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *ProviderApiSenderInput) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.

### HasSignatureHtml

`func (o *ProviderApiSenderInput) HasSignatureHtml() bool`

HasSignatureHtml returns a boolean if a field has been set.

### GetFromEmail

`func (o *ProviderApiSenderInput) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *ProviderApiSenderInput) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *ProviderApiSenderInput) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetFromName

`func (o *ProviderApiSenderInput) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *ProviderApiSenderInput) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *ProviderApiSenderInput) SetFromName(v string)`

SetFromName sets FromName field to given value.


### GetTransportMode

`func (o *ProviderApiSenderInput) GetTransportMode() interface{}`

GetTransportMode returns the TransportMode field if non-nil, zero value otherwise.

### GetTransportModeOk

`func (o *ProviderApiSenderInput) GetTransportModeOk() (*interface{}, bool)`

GetTransportModeOk returns a tuple with the TransportMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportMode

`func (o *ProviderApiSenderInput) SetTransportMode(v interface{})`

SetTransportMode sets TransportMode field to given value.


### SetTransportModeNil

`func (o *ProviderApiSenderInput) SetTransportModeNil(b bool)`

 SetTransportModeNil sets the value for TransportMode to be an explicit nil

### UnsetTransportMode
`func (o *ProviderApiSenderInput) UnsetTransportMode()`

UnsetTransportMode ensures that no value is present for TransportMode, not even an explicit nil
### GetTransportProvider

`func (o *ProviderApiSenderInput) GetTransportProvider() string`

GetTransportProvider returns the TransportProvider field if non-nil, zero value otherwise.

### GetTransportProviderOk

`func (o *ProviderApiSenderInput) GetTransportProviderOk() (*string, bool)`

GetTransportProviderOk returns a tuple with the TransportProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportProvider

`func (o *ProviderApiSenderInput) SetTransportProvider(v string)`

SetTransportProvider sets TransportProvider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


