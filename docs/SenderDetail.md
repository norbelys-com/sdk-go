# SenderDetail

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
**Usage** | Pointer to [**SenderDetailUsage**](SenderDetailUsage.md) |  | [optional] 
**Warmup** | Pointer to [**SenderDetailWarmup**](SenderDetailWarmup.md) |  | [optional] 

## Methods

### NewSenderDetail

`func NewSenderDetail(bccCrmEmail NullableString, clientLabel NullableString, dailyLimit int32, fromEmail string, fromName string, id string, imapHost NullableString, imapPort NullableInt32, imapSecurity NullableString, minGapMinutes int32, replyTo NullableString, reputation string, sendingDomainId string, signatureHtml NullableString, smtpHost NullableString, smtpPort NullableInt32, smtpSecurity NullableString, state string, transportMode string, transportProvider NullableString, ) *SenderDetail`

NewSenderDetail instantiates a new SenderDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderDetailWithDefaults

`func NewSenderDetailWithDefaults() *SenderDetail`

NewSenderDetailWithDefaults instantiates a new SenderDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *SenderDetail) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *SenderDetail) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *SenderDetail) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *SenderDetail) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *SenderDetail) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *SenderDetail) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetBccCrmEmail

`func (o *SenderDetail) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *SenderDetail) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *SenderDetail) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.


### SetBccCrmEmailNil

`func (o *SenderDetail) SetBccCrmEmailNil(b bool)`

 SetBccCrmEmailNil sets the value for BccCrmEmail to be an explicit nil

### UnsetBccCrmEmail
`func (o *SenderDetail) UnsetBccCrmEmail()`

UnsetBccCrmEmail ensures that no value is present for BccCrmEmail, not even an explicit nil
### GetClientLabel

`func (o *SenderDetail) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *SenderDetail) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *SenderDetail) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.


### SetClientLabelNil

`func (o *SenderDetail) SetClientLabelNil(b bool)`

 SetClientLabelNil sets the value for ClientLabel to be an explicit nil

### UnsetClientLabel
`func (o *SenderDetail) UnsetClientLabel()`

UnsetClientLabel ensures that no value is present for ClientLabel, not even an explicit nil
### GetCreatedAt

`func (o *SenderDetail) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SenderDetail) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SenderDetail) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SenderDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *SenderDetail) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *SenderDetail) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetDailyLimit

`func (o *SenderDetail) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *SenderDetail) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *SenderDetail) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.


### GetFromEmail

`func (o *SenderDetail) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *SenderDetail) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *SenderDetail) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetFromName

`func (o *SenderDetail) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *SenderDetail) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *SenderDetail) SetFromName(v string)`

SetFromName sets FromName field to given value.


### GetHealthUpdatedAt

`func (o *SenderDetail) GetHealthUpdatedAt() interface{}`

GetHealthUpdatedAt returns the HealthUpdatedAt field if non-nil, zero value otherwise.

### GetHealthUpdatedAtOk

`func (o *SenderDetail) GetHealthUpdatedAtOk() (*interface{}, bool)`

GetHealthUpdatedAtOk returns a tuple with the HealthUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthUpdatedAt

`func (o *SenderDetail) SetHealthUpdatedAt(v interface{})`

SetHealthUpdatedAt sets HealthUpdatedAt field to given value.

### HasHealthUpdatedAt

`func (o *SenderDetail) HasHealthUpdatedAt() bool`

HasHealthUpdatedAt returns a boolean if a field has been set.

### SetHealthUpdatedAtNil

`func (o *SenderDetail) SetHealthUpdatedAtNil(b bool)`

 SetHealthUpdatedAtNil sets the value for HealthUpdatedAt to be an explicit nil

### UnsetHealthUpdatedAt
`func (o *SenderDetail) UnsetHealthUpdatedAt()`

UnsetHealthUpdatedAt ensures that no value is present for HealthUpdatedAt, not even an explicit nil
### GetId

`func (o *SenderDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderDetail) SetId(v string)`

SetId sets Id field to given value.


### GetImapHost

`func (o *SenderDetail) GetImapHost() string`

GetImapHost returns the ImapHost field if non-nil, zero value otherwise.

### GetImapHostOk

`func (o *SenderDetail) GetImapHostOk() (*string, bool)`

GetImapHostOk returns a tuple with the ImapHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapHost

`func (o *SenderDetail) SetImapHost(v string)`

SetImapHost sets ImapHost field to given value.


### SetImapHostNil

`func (o *SenderDetail) SetImapHostNil(b bool)`

 SetImapHostNil sets the value for ImapHost to be an explicit nil

### UnsetImapHost
`func (o *SenderDetail) UnsetImapHost()`

UnsetImapHost ensures that no value is present for ImapHost, not even an explicit nil
### GetImapPort

`func (o *SenderDetail) GetImapPort() int32`

GetImapPort returns the ImapPort field if non-nil, zero value otherwise.

### GetImapPortOk

`func (o *SenderDetail) GetImapPortOk() (*int32, bool)`

GetImapPortOk returns a tuple with the ImapPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapPort

`func (o *SenderDetail) SetImapPort(v int32)`

SetImapPort sets ImapPort field to given value.


### SetImapPortNil

`func (o *SenderDetail) SetImapPortNil(b bool)`

 SetImapPortNil sets the value for ImapPort to be an explicit nil

### UnsetImapPort
`func (o *SenderDetail) UnsetImapPort()`

UnsetImapPort ensures that no value is present for ImapPort, not even an explicit nil
### GetImapSecurity

`func (o *SenderDetail) GetImapSecurity() string`

GetImapSecurity returns the ImapSecurity field if non-nil, zero value otherwise.

### GetImapSecurityOk

`func (o *SenderDetail) GetImapSecurityOk() (*string, bool)`

GetImapSecurityOk returns a tuple with the ImapSecurity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImapSecurity

`func (o *SenderDetail) SetImapSecurity(v string)`

SetImapSecurity sets ImapSecurity field to given value.


### SetImapSecurityNil

`func (o *SenderDetail) SetImapSecurityNil(b bool)`

 SetImapSecurityNil sets the value for ImapSecurity to be an explicit nil

### UnsetImapSecurity
`func (o *SenderDetail) UnsetImapSecurity()`

UnsetImapSecurity ensures that no value is present for ImapSecurity, not even an explicit nil
### GetMinGapMinutes

`func (o *SenderDetail) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *SenderDetail) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *SenderDetail) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.


### GetObject

`func (o *SenderDetail) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *SenderDetail) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *SenderDetail) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *SenderDetail) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *SenderDetail) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *SenderDetail) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetReplyTo

`func (o *SenderDetail) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *SenderDetail) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *SenderDetail) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.


### SetReplyToNil

`func (o *SenderDetail) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *SenderDetail) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetReputation

`func (o *SenderDetail) GetReputation() string`

GetReputation returns the Reputation field if non-nil, zero value otherwise.

### GetReputationOk

`func (o *SenderDetail) GetReputationOk() (*string, bool)`

GetReputationOk returns a tuple with the Reputation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReputation

`func (o *SenderDetail) SetReputation(v string)`

SetReputation sets Reputation field to given value.


### GetSendingDomainId

`func (o *SenderDetail) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *SenderDetail) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *SenderDetail) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.


### GetSignatureHtml

`func (o *SenderDetail) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *SenderDetail) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *SenderDetail) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.


### SetSignatureHtmlNil

`func (o *SenderDetail) SetSignatureHtmlNil(b bool)`

 SetSignatureHtmlNil sets the value for SignatureHtml to be an explicit nil

### UnsetSignatureHtml
`func (o *SenderDetail) UnsetSignatureHtml()`

UnsetSignatureHtml ensures that no value is present for SignatureHtml, not even an explicit nil
### GetSmtpHost

`func (o *SenderDetail) GetSmtpHost() string`

GetSmtpHost returns the SmtpHost field if non-nil, zero value otherwise.

### GetSmtpHostOk

`func (o *SenderDetail) GetSmtpHostOk() (*string, bool)`

GetSmtpHostOk returns a tuple with the SmtpHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpHost

`func (o *SenderDetail) SetSmtpHost(v string)`

SetSmtpHost sets SmtpHost field to given value.


### SetSmtpHostNil

`func (o *SenderDetail) SetSmtpHostNil(b bool)`

 SetSmtpHostNil sets the value for SmtpHost to be an explicit nil

### UnsetSmtpHost
`func (o *SenderDetail) UnsetSmtpHost()`

UnsetSmtpHost ensures that no value is present for SmtpHost, not even an explicit nil
### GetSmtpPort

`func (o *SenderDetail) GetSmtpPort() int32`

GetSmtpPort returns the SmtpPort field if non-nil, zero value otherwise.

### GetSmtpPortOk

`func (o *SenderDetail) GetSmtpPortOk() (*int32, bool)`

GetSmtpPortOk returns a tuple with the SmtpPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpPort

`func (o *SenderDetail) SetSmtpPort(v int32)`

SetSmtpPort sets SmtpPort field to given value.


### SetSmtpPortNil

`func (o *SenderDetail) SetSmtpPortNil(b bool)`

 SetSmtpPortNil sets the value for SmtpPort to be an explicit nil

### UnsetSmtpPort
`func (o *SenderDetail) UnsetSmtpPort()`

UnsetSmtpPort ensures that no value is present for SmtpPort, not even an explicit nil
### GetSmtpSecurity

`func (o *SenderDetail) GetSmtpSecurity() string`

GetSmtpSecurity returns the SmtpSecurity field if non-nil, zero value otherwise.

### GetSmtpSecurityOk

`func (o *SenderDetail) GetSmtpSecurityOk() (*string, bool)`

GetSmtpSecurityOk returns a tuple with the SmtpSecurity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpSecurity

`func (o *SenderDetail) SetSmtpSecurity(v string)`

SetSmtpSecurity sets SmtpSecurity field to given value.


### SetSmtpSecurityNil

`func (o *SenderDetail) SetSmtpSecurityNil(b bool)`

 SetSmtpSecurityNil sets the value for SmtpSecurity to be an explicit nil

### UnsetSmtpSecurity
`func (o *SenderDetail) UnsetSmtpSecurity()`

UnsetSmtpSecurity ensures that no value is present for SmtpSecurity, not even an explicit nil
### GetState

`func (o *SenderDetail) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SenderDetail) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SenderDetail) SetState(v string)`

SetState sets State field to given value.


### GetTransportMode

`func (o *SenderDetail) GetTransportMode() string`

GetTransportMode returns the TransportMode field if non-nil, zero value otherwise.

### GetTransportModeOk

`func (o *SenderDetail) GetTransportModeOk() (*string, bool)`

GetTransportModeOk returns a tuple with the TransportMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportMode

`func (o *SenderDetail) SetTransportMode(v string)`

SetTransportMode sets TransportMode field to given value.


### GetTransportProvider

`func (o *SenderDetail) GetTransportProvider() string`

GetTransportProvider returns the TransportProvider field if non-nil, zero value otherwise.

### GetTransportProviderOk

`func (o *SenderDetail) GetTransportProviderOk() (*string, bool)`

GetTransportProviderOk returns a tuple with the TransportProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportProvider

`func (o *SenderDetail) SetTransportProvider(v string)`

SetTransportProvider sets TransportProvider field to given value.


### SetTransportProviderNil

`func (o *SenderDetail) SetTransportProviderNil(b bool)`

 SetTransportProviderNil sets the value for TransportProvider to be an explicit nil

### UnsetTransportProvider
`func (o *SenderDetail) UnsetTransportProvider()`

UnsetTransportProvider ensures that no value is present for TransportProvider, not even an explicit nil
### GetUpdatedAt

`func (o *SenderDetail) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SenderDetail) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SenderDetail) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SenderDetail) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *SenderDetail) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *SenderDetail) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUsage

`func (o *SenderDetail) GetUsage() SenderDetailUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *SenderDetail) GetUsageOk() (*SenderDetailUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *SenderDetail) SetUsage(v SenderDetailUsage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *SenderDetail) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetWarmup

`func (o *SenderDetail) GetWarmup() SenderDetailWarmup`

GetWarmup returns the Warmup field if non-nil, zero value otherwise.

### GetWarmupOk

`func (o *SenderDetail) GetWarmupOk() (*SenderDetailWarmup, bool)`

GetWarmupOk returns a tuple with the Warmup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmup

`func (o *SenderDetail) SetWarmup(v SenderDetailWarmup)`

SetWarmup sets Warmup field to given value.

### HasWarmup

`func (o *SenderDetail) HasWarmup() bool`

HasWarmup returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


