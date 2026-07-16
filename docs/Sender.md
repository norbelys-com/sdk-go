# Sender

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**BccCrmEmail** | **NullableString** |  | 
**ClientLabel** | **NullableString** |  | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**DailyLimit** | **int32** | Max sends per day for this mailbox. | 
**FromEmail** | **string** | The sending address. | 
**FromName** | **string** | Display name. | 
**HealthUpdatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The sender id. | 
**ImapHost** | **NullableString** |  | 
**ImapPort** | **NullableInt32** |  | 
**ImapSecurity** | **NullableString** |  | 
**MinGapMinutes** | **int32** | Minimum gap between sends from this mailbox. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**ReplyTo** | **NullableString** |  | 
**Reputation** | **string** | System-computed reputation tier: &#x60;good&#x60;, &#x60;warning&#x60;, or &#x60;bad&#x60;. | 
**SendingDomainId** | **string** | The sending domain this mailbox lives under. | 
**SignatureHtml** | **NullableString** |  | 
**SmtpHost** | **NullableString** |  | 
**SmtpPort** | **NullableInt32** |  | 
**SmtpSecurity** | **NullableString** |  | 
**State** | **string** | Operational state: &#x60;healthy&#x60;, &#x60;throttled&#x60;, or &#x60;paused&#x60;. | 
**TransportMode** | **string** | How messages are carried: &#x60;smtp&#x60;, &#x60;provider_api&#x60;, &#x60;self_hosted&#x60;, or &#x60;voice&#x60;. | 
**TransportProvider** | **NullableString** |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewSender

`func NewSender(bccCrmEmail NullableString, clientLabel NullableString, dailyLimit int32, fromEmail string, fromName string, id string, imapHost NullableString, imapPort NullableInt32, imapSecurity NullableString, minGapMinutes int32, replyTo NullableString, reputation string, sendingDomainId string, signatureHtml NullableString, smtpHost NullableString, smtpPort NullableInt32, smtpSecurity NullableString, state string, transportMode string, transportProvider NullableString, ) *Sender`

NewSender instantiates a new Sender object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderWithDefaults

`func NewSenderWithDefaults() *Sender`

NewSenderWithDefaults instantiates a new Sender object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *Sender) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Sender) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Sender) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Sender) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Sender) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Sender) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetBccCrmEmail

`func (o *Sender) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *Sender) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *Sender) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.


### SetBccCrmEmailNil

`func (o *Sender) SetBccCrmEmailNil(b bool)`

 SetBccCrmEmailNil sets the value for BccCrmEmail to be an explicit nil

### UnsetBccCrmEmail
`func (o *Sender) UnsetBccCrmEmail()`

UnsetBccCrmEmail ensures that no value is present for BccCrmEmail, not even an explicit nil
### GetClientLabel

`func (o *Sender) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *Sender) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *Sender) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.


### SetClientLabelNil

`func (o *Sender) SetClientLabelNil(b bool)`

 SetClientLabelNil sets the value for ClientLabel to be an explicit nil

### UnsetClientLabel
`func (o *Sender) UnsetClientLabel()`

UnsetClientLabel ensures that no value is present for ClientLabel, not even an explicit nil
### GetCreatedAt

`func (o *Sender) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Sender) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Sender) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Sender) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Sender) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Sender) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetDailyLimit

`func (o *Sender) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *Sender) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *Sender) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.


### GetFromEmail

`func (o *Sender) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *Sender) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *Sender) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetFromName

`func (o *Sender) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *Sender) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *Sender) SetFromName(v string)`

SetFromName sets FromName field to given value.


### GetHealthUpdatedAt

`func (o *Sender) GetHealthUpdatedAt() interface{}`

GetHealthUpdatedAt returns the HealthUpdatedAt field if non-nil, zero value otherwise.

### GetHealthUpdatedAtOk

`func (o *Sender) GetHealthUpdatedAtOk() (*interface{}, bool)`

GetHealthUpdatedAtOk returns a tuple with the HealthUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthUpdatedAt

`func (o *Sender) SetHealthUpdatedAt(v interface{})`

SetHealthUpdatedAt sets HealthUpdatedAt field to given value.

### HasHealthUpdatedAt

`func (o *Sender) HasHealthUpdatedAt() bool`

HasHealthUpdatedAt returns a boolean if a field has been set.

### SetHealthUpdatedAtNil

`func (o *Sender) SetHealthUpdatedAtNil(b bool)`

 SetHealthUpdatedAtNil sets the value for HealthUpdatedAt to be an explicit nil

### UnsetHealthUpdatedAt
`func (o *Sender) UnsetHealthUpdatedAt()`

UnsetHealthUpdatedAt ensures that no value is present for HealthUpdatedAt, not even an explicit nil
### GetId

`func (o *Sender) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Sender) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Sender) SetId(v string)`

SetId sets Id field to given value.


### GetImapHost

`func (o *Sender) GetImapHost() string`

GetImapHost returns the ImapHost field if non-nil, zero value otherwise.

### GetImapHostOk

`func (o *Sender) GetImapHostOk() (*string, bool)`

GetImapHostOk returns a tuple with the ImapHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapHost

`func (o *Sender) SetImapHost(v string)`

SetImapHost sets ImapHost field to given value.


### SetImapHostNil

`func (o *Sender) SetImapHostNil(b bool)`

 SetImapHostNil sets the value for ImapHost to be an explicit nil

### UnsetImapHost
`func (o *Sender) UnsetImapHost()`

UnsetImapHost ensures that no value is present for ImapHost, not even an explicit nil
### GetImapPort

`func (o *Sender) GetImapPort() int32`

GetImapPort returns the ImapPort field if non-nil, zero value otherwise.

### GetImapPortOk

`func (o *Sender) GetImapPortOk() (*int32, bool)`

GetImapPortOk returns a tuple with the ImapPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapPort

`func (o *Sender) SetImapPort(v int32)`

SetImapPort sets ImapPort field to given value.


### SetImapPortNil

`func (o *Sender) SetImapPortNil(b bool)`

 SetImapPortNil sets the value for ImapPort to be an explicit nil

### UnsetImapPort
`func (o *Sender) UnsetImapPort()`

UnsetImapPort ensures that no value is present for ImapPort, not even an explicit nil
### GetImapSecurity

`func (o *Sender) GetImapSecurity() string`

GetImapSecurity returns the ImapSecurity field if non-nil, zero value otherwise.

### GetImapSecurityOk

`func (o *Sender) GetImapSecurityOk() (*string, bool)`

GetImapSecurityOk returns a tuple with the ImapSecurity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapSecurity

`func (o *Sender) SetImapSecurity(v string)`

SetImapSecurity sets ImapSecurity field to given value.


### SetImapSecurityNil

`func (o *Sender) SetImapSecurityNil(b bool)`

 SetImapSecurityNil sets the value for ImapSecurity to be an explicit nil

### UnsetImapSecurity
`func (o *Sender) UnsetImapSecurity()`

UnsetImapSecurity ensures that no value is present for ImapSecurity, not even an explicit nil
### GetMinGapMinutes

`func (o *Sender) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *Sender) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *Sender) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.


### GetObject

`func (o *Sender) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Sender) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Sender) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Sender) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Sender) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Sender) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetReplyTo

`func (o *Sender) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *Sender) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *Sender) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.


### SetReplyToNil

`func (o *Sender) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *Sender) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetReputation

`func (o *Sender) GetReputation() string`

GetReputation returns the Reputation field if non-nil, zero value otherwise.

### GetReputationOk

`func (o *Sender) GetReputationOk() (*string, bool)`

GetReputationOk returns a tuple with the Reputation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputation

`func (o *Sender) SetReputation(v string)`

SetReputation sets Reputation field to given value.


### GetSendingDomainId

`func (o *Sender) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *Sender) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *Sender) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.


### GetSignatureHtml

`func (o *Sender) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *Sender) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *Sender) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.


### SetSignatureHtmlNil

`func (o *Sender) SetSignatureHtmlNil(b bool)`

 SetSignatureHtmlNil sets the value for SignatureHtml to be an explicit nil

### UnsetSignatureHtml
`func (o *Sender) UnsetSignatureHtml()`

UnsetSignatureHtml ensures that no value is present for SignatureHtml, not even an explicit nil
### GetSmtpHost

`func (o *Sender) GetSmtpHost() string`

GetSmtpHost returns the SmtpHost field if non-nil, zero value otherwise.

### GetSmtpHostOk

`func (o *Sender) GetSmtpHostOk() (*string, bool)`

GetSmtpHostOk returns a tuple with the SmtpHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpHost

`func (o *Sender) SetSmtpHost(v string)`

SetSmtpHost sets SmtpHost field to given value.


### SetSmtpHostNil

`func (o *Sender) SetSmtpHostNil(b bool)`

 SetSmtpHostNil sets the value for SmtpHost to be an explicit nil

### UnsetSmtpHost
`func (o *Sender) UnsetSmtpHost()`

UnsetSmtpHost ensures that no value is present for SmtpHost, not even an explicit nil
### GetSmtpPort

`func (o *Sender) GetSmtpPort() int32`

GetSmtpPort returns the SmtpPort field if non-nil, zero value otherwise.

### GetSmtpPortOk

`func (o *Sender) GetSmtpPortOk() (*int32, bool)`

GetSmtpPortOk returns a tuple with the SmtpPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpPort

`func (o *Sender) SetSmtpPort(v int32)`

SetSmtpPort sets SmtpPort field to given value.


### SetSmtpPortNil

`func (o *Sender) SetSmtpPortNil(b bool)`

 SetSmtpPortNil sets the value for SmtpPort to be an explicit nil

### UnsetSmtpPort
`func (o *Sender) UnsetSmtpPort()`

UnsetSmtpPort ensures that no value is present for SmtpPort, not even an explicit nil
### GetSmtpSecurity

`func (o *Sender) GetSmtpSecurity() string`

GetSmtpSecurity returns the SmtpSecurity field if non-nil, zero value otherwise.

### GetSmtpSecurityOk

`func (o *Sender) GetSmtpSecurityOk() (*string, bool)`

GetSmtpSecurityOk returns a tuple with the SmtpSecurity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpSecurity

`func (o *Sender) SetSmtpSecurity(v string)`

SetSmtpSecurity sets SmtpSecurity field to given value.


### SetSmtpSecurityNil

`func (o *Sender) SetSmtpSecurityNil(b bool)`

 SetSmtpSecurityNil sets the value for SmtpSecurity to be an explicit nil

### UnsetSmtpSecurity
`func (o *Sender) UnsetSmtpSecurity()`

UnsetSmtpSecurity ensures that no value is present for SmtpSecurity, not even an explicit nil
### GetState

`func (o *Sender) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Sender) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Sender) SetState(v string)`

SetState sets State field to given value.


### GetTransportMode

`func (o *Sender) GetTransportMode() string`

GetTransportMode returns the TransportMode field if non-nil, zero value otherwise.

### GetTransportModeOk

`func (o *Sender) GetTransportModeOk() (*string, bool)`

GetTransportModeOk returns a tuple with the TransportMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportMode

`func (o *Sender) SetTransportMode(v string)`

SetTransportMode sets TransportMode field to given value.


### GetTransportProvider

`func (o *Sender) GetTransportProvider() string`

GetTransportProvider returns the TransportProvider field if non-nil, zero value otherwise.

### GetTransportProviderOk

`func (o *Sender) GetTransportProviderOk() (*string, bool)`

GetTransportProviderOk returns a tuple with the TransportProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportProvider

`func (o *Sender) SetTransportProvider(v string)`

SetTransportProvider sets TransportProvider field to given value.


### SetTransportProviderNil

`func (o *Sender) SetTransportProviderNil(b bool)`

 SetTransportProviderNil sets the value for TransportProvider to be an explicit nil

### UnsetTransportProvider
`func (o *Sender) UnsetTransportProvider()`

UnsetTransportProvider ensures that no value is present for TransportProvider, not even an explicit nil
### GetUpdatedAt

`func (o *Sender) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Sender) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Sender) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Sender) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Sender) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Sender) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


