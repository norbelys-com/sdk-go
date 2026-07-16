# MessageReplyParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **map[string]interface{}** | Template variables merged over the person&#39;s fields at render time. | [optional] 
**From** | **string** | Who the message is sent from — a sender id, or any email address on a sending domain you&#39;ve set up (a sender identity is created automatically on first use). | 
**To** | **string** | Recipient email address. | 
**ToName** | Pointer to **string** | Recipient display name. | [optional] 
**Attachments** | Pointer to [**[]MessageAttachmentInput**](MessageAttachmentInput.md) | Files to attach (Base64-encoded). Up to 5 files, 7 MB decoded total. | [optional] 
**Html** | Pointer to **string** | Inline HTML body. | [optional] 
**Subject** | Pointer to **string** | Subject line for an inline send. | [optional] 
**Text** | Pointer to **string** | Inline plain-text body. | [optional] 
**TrackClicks** | Pointer to **bool** | Rewrite links to track clicks. | [optional] 
**TrackOpens** | Pointer to **bool** | Track opens for this message. | [optional] 
**VariantId** | Pointer to **string** | Id of a stored step variant to render as the template instead of inline content. | [optional] 
**InReplyTo** | **string** | Id of an inbound message to reply to; threads this send to that conversation. | 

## Methods

### NewMessageReplyParams

`func NewMessageReplyParams(from string, to string, inReplyTo string, ) *MessageReplyParams`

NewMessageReplyParams instantiates a new MessageReplyParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageReplyParamsWithDefaults

`func NewMessageReplyParamsWithDefaults() *MessageReplyParams`

NewMessageReplyParamsWithDefaults instantiates a new MessageReplyParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MessageReplyParams) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessageReplyParams) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessageReplyParams) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MessageReplyParams) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFrom

`func (o *MessageReplyParams) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *MessageReplyParams) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *MessageReplyParams) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *MessageReplyParams) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *MessageReplyParams) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *MessageReplyParams) SetTo(v string)`

SetTo sets To field to given value.


### GetToName

`func (o *MessageReplyParams) GetToName() string`

GetToName returns the ToName field if non-nil, zero value otherwise.

### GetToNameOk

`func (o *MessageReplyParams) GetToNameOk() (*string, bool)`

GetToNameOk returns a tuple with the ToName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToName

`func (o *MessageReplyParams) SetToName(v string)`

SetToName sets ToName field to given value.

### HasToName

`func (o *MessageReplyParams) HasToName() bool`

HasToName returns a boolean if a field has been set.

### GetAttachments

`func (o *MessageReplyParams) GetAttachments() []MessageAttachmentInput`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *MessageReplyParams) GetAttachmentsOk() (*[]MessageAttachmentInput, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *MessageReplyParams) SetAttachments(v []MessageAttachmentInput)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *MessageReplyParams) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetHtml

`func (o *MessageReplyParams) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *MessageReplyParams) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *MessageReplyParams) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *MessageReplyParams) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetSubject

`func (o *MessageReplyParams) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *MessageReplyParams) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *MessageReplyParams) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *MessageReplyParams) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *MessageReplyParams) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *MessageReplyParams) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *MessageReplyParams) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *MessageReplyParams) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTrackClicks

`func (o *MessageReplyParams) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *MessageReplyParams) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *MessageReplyParams) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.

### HasTrackClicks

`func (o *MessageReplyParams) HasTrackClicks() bool`

HasTrackClicks returns a boolean if a field has been set.

### GetTrackOpens

`func (o *MessageReplyParams) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *MessageReplyParams) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *MessageReplyParams) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.

### HasTrackOpens

`func (o *MessageReplyParams) HasTrackOpens() bool`

HasTrackOpens returns a boolean if a field has been set.

### GetVariantId

`func (o *MessageReplyParams) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *MessageReplyParams) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *MessageReplyParams) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *MessageReplyParams) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### GetInReplyTo

`func (o *MessageReplyParams) GetInReplyTo() string`

GetInReplyTo returns the InReplyTo field if non-nil, zero value otherwise.

### GetInReplyToOk

`func (o *MessageReplyParams) GetInReplyToOk() (*string, bool)`

GetInReplyToOk returns a tuple with the InReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInReplyTo

`func (o *MessageReplyParams) SetInReplyTo(v string)`

SetInReplyTo sets InReplyTo field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


