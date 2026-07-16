# BulkUpdateSenderPatch

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

## Methods

### NewBulkUpdateSenderPatch

`func NewBulkUpdateSenderPatch() *BulkUpdateSenderPatch`

NewBulkUpdateSenderPatch instantiates a new BulkUpdateSenderPatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkUpdateSenderPatchWithDefaults

`func NewBulkUpdateSenderPatchWithDefaults() *BulkUpdateSenderPatch`

NewBulkUpdateSenderPatchWithDefaults instantiates a new BulkUpdateSenderPatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBccCrmEmail

`func (o *BulkUpdateSenderPatch) GetBccCrmEmail() string`

GetBccCrmEmail returns the BccCrmEmail field if non-nil, zero value otherwise.

### GetBccCrmEmailOk

`func (o *BulkUpdateSenderPatch) GetBccCrmEmailOk() (*string, bool)`

GetBccCrmEmailOk returns a tuple with the BccCrmEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBccCrmEmail

`func (o *BulkUpdateSenderPatch) SetBccCrmEmail(v string)`

SetBccCrmEmail sets BccCrmEmail field to given value.

### HasBccCrmEmail

`func (o *BulkUpdateSenderPatch) HasBccCrmEmail() bool`

HasBccCrmEmail returns a boolean if a field has been set.

### GetClientLabel

`func (o *BulkUpdateSenderPatch) GetClientLabel() string`

GetClientLabel returns the ClientLabel field if non-nil, zero value otherwise.

### GetClientLabelOk

`func (o *BulkUpdateSenderPatch) GetClientLabelOk() (*string, bool)`

GetClientLabelOk returns a tuple with the ClientLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientLabel

`func (o *BulkUpdateSenderPatch) SetClientLabel(v string)`

SetClientLabel sets ClientLabel field to given value.

### HasClientLabel

`func (o *BulkUpdateSenderPatch) HasClientLabel() bool`

HasClientLabel returns a boolean if a field has been set.

### GetDailyLimit

`func (o *BulkUpdateSenderPatch) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *BulkUpdateSenderPatch) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *BulkUpdateSenderPatch) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.

### HasDailyLimit

`func (o *BulkUpdateSenderPatch) HasDailyLimit() bool`

HasDailyLimit returns a boolean if a field has been set.

### GetMinGapMinutes

`func (o *BulkUpdateSenderPatch) GetMinGapMinutes() int32`

GetMinGapMinutes returns the MinGapMinutes field if non-nil, zero value otherwise.

### GetMinGapMinutesOk

`func (o *BulkUpdateSenderPatch) GetMinGapMinutesOk() (*int32, bool)`

GetMinGapMinutesOk returns a tuple with the MinGapMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinGapMinutes

`func (o *BulkUpdateSenderPatch) SetMinGapMinutes(v int32)`

SetMinGapMinutes sets MinGapMinutes field to given value.

### HasMinGapMinutes

`func (o *BulkUpdateSenderPatch) HasMinGapMinutes() bool`

HasMinGapMinutes returns a boolean if a field has been set.

### GetReplyTo

`func (o *BulkUpdateSenderPatch) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *BulkUpdateSenderPatch) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *BulkUpdateSenderPatch) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *BulkUpdateSenderPatch) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetSendingDomainId

`func (o *BulkUpdateSenderPatch) GetSendingDomainId() string`

GetSendingDomainId returns the SendingDomainId field if non-nil, zero value otherwise.

### GetSendingDomainIdOk

`func (o *BulkUpdateSenderPatch) GetSendingDomainIdOk() (*string, bool)`

GetSendingDomainIdOk returns a tuple with the SendingDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingDomainId

`func (o *BulkUpdateSenderPatch) SetSendingDomainId(v string)`

SetSendingDomainId sets SendingDomainId field to given value.

### HasSendingDomainId

`func (o *BulkUpdateSenderPatch) HasSendingDomainId() bool`

HasSendingDomainId returns a boolean if a field has been set.

### GetSignatureHtml

`func (o *BulkUpdateSenderPatch) GetSignatureHtml() string`

GetSignatureHtml returns the SignatureHtml field if non-nil, zero value otherwise.

### GetSignatureHtmlOk

`func (o *BulkUpdateSenderPatch) GetSignatureHtmlOk() (*string, bool)`

GetSignatureHtmlOk returns a tuple with the SignatureHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureHtml

`func (o *BulkUpdateSenderPatch) SetSignatureHtml(v string)`

SetSignatureHtml sets SignatureHtml field to given value.

### HasSignatureHtml

`func (o *BulkUpdateSenderPatch) HasSignatureHtml() bool`

HasSignatureHtml returns a boolean if a field has been set.

### GetState

`func (o *BulkUpdateSenderPatch) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *BulkUpdateSenderPatch) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *BulkUpdateSenderPatch) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *BulkUpdateSenderPatch) HasState() bool`

HasState returns a boolean if a field has been set.

### GetWarmup

`func (o *BulkUpdateSenderPatch) GetWarmup() WarmupSettings`

GetWarmup returns the Warmup field if non-nil, zero value otherwise.

### GetWarmupOk

`func (o *BulkUpdateSenderPatch) GetWarmupOk() (*WarmupSettings, bool)`

GetWarmupOk returns a tuple with the Warmup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmup

`func (o *BulkUpdateSenderPatch) SetWarmup(v WarmupSettings)`

SetWarmup sets Warmup field to given value.

### HasWarmup

`func (o *BulkUpdateSenderPatch) HasWarmup() bool`

HasWarmup returns a boolean if a field has been set.

### SetWarmupNil

`func (o *BulkUpdateSenderPatch) SetWarmupNil(b bool)`

 SetWarmupNil sets the value for Warmup to be an explicit nil

### UnsetWarmup
`func (o *BulkUpdateSenderPatch) UnsetWarmup()`

UnsetWarmup ensures that no value is present for Warmup, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


