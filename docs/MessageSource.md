# MessageSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attachments** | Pointer to [**[]MessageSourceAttachment**](MessageSourceAttachment.md) | Attached files (metadata only; raw content omitted). | [optional] 
**Bcc** | Pointer to [**[]MessageAddress**](MessageAddress.md) | Blind-carbon-copy recipients, as sent. | [optional] 
**Cc** | Pointer to [**[]MessageAddress**](MessageAddress.md) | Carbon-copy recipients, as sent. | [optional] 
**From** | [**MessageAddress**](MessageAddress.md) | The From identity as sent. | 
**Headers** | Pointer to **map[string]string** | Extra headers attached at send time. | [optional] 
**Html** | **string** | The final HTML body, tracking applied. | 
**ReplyTo** | Pointer to **string** | The Reply-To header, if set. | [optional] 
**Subject** | **string** | The final personalized subject. | 
**Text** | **string** | The final plain-text body. | 
**To** | [**MessageAddress**](MessageAddress.md) | The recipient as sent. | 

## Methods

### NewMessageSource

`func NewMessageSource(from MessageAddress, html string, subject string, text string, to MessageAddress, ) *MessageSource`

NewMessageSource instantiates a new MessageSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageSourceWithDefaults

`func NewMessageSourceWithDefaults() *MessageSource`

NewMessageSourceWithDefaults instantiates a new MessageSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachments

`func (o *MessageSource) GetAttachments() []MessageSourceAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *MessageSource) GetAttachmentsOk() (*[]MessageSourceAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *MessageSource) SetAttachments(v []MessageSourceAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *MessageSource) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetBcc

`func (o *MessageSource) GetBcc() []MessageAddress`

GetBcc returns the Bcc field if non-nil, zero value otherwise.

### GetBccOk

`func (o *MessageSource) GetBccOk() (*[]MessageAddress, bool)`

GetBccOk returns a tuple with the Bcc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBcc

`func (o *MessageSource) SetBcc(v []MessageAddress)`

SetBcc sets Bcc field to given value.

### HasBcc

`func (o *MessageSource) HasBcc() bool`

HasBcc returns a boolean if a field has been set.

### GetCc

`func (o *MessageSource) GetCc() []MessageAddress`

GetCc returns the Cc field if non-nil, zero value otherwise.

### GetCcOk

`func (o *MessageSource) GetCcOk() (*[]MessageAddress, bool)`

GetCcOk returns a tuple with the Cc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCc

`func (o *MessageSource) SetCc(v []MessageAddress)`

SetCc sets Cc field to given value.

### HasCc

`func (o *MessageSource) HasCc() bool`

HasCc returns a boolean if a field has been set.

### GetFrom

`func (o *MessageSource) GetFrom() MessageAddress`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *MessageSource) GetFromOk() (*MessageAddress, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *MessageSource) SetFrom(v MessageAddress)`

SetFrom sets From field to given value.


### GetHeaders

`func (o *MessageSource) GetHeaders() map[string]string`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *MessageSource) GetHeadersOk() (*map[string]string, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *MessageSource) SetHeaders(v map[string]string)`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *MessageSource) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### GetHtml

`func (o *MessageSource) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *MessageSource) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *MessageSource) SetHtml(v string)`

SetHtml sets Html field to given value.


### GetReplyTo

`func (o *MessageSource) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *MessageSource) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *MessageSource) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *MessageSource) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetSubject

`func (o *MessageSource) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *MessageSource) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *MessageSource) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetText

`func (o *MessageSource) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *MessageSource) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *MessageSource) SetText(v string)`

SetText sets Text field to given value.


### GetTo

`func (o *MessageSource) GetTo() MessageAddress`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *MessageSource) GetToOk() (*MessageAddress, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *MessageSource) SetTo(v MessageAddress)`

SetTo sets To field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


