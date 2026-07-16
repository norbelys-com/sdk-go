# MessageCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **map[string]interface{}** | Template variables merged over the person&#39;s fields at render time. | [optional] 
**From** | **string** | Who the message is sent from — a sender id, or any email address on a sending domain you&#39;ve set up (a sender identity is created automatically on first use). | 
**To** | **string** | Recipient email address. | 
**ToName** | Pointer to **string** | Recipient display name. | [optional] 
**Sequence** | **string** | Id of a program to enroll the person into instead of sending now; the program then controls send timing. Required for a cold-email sender (those send on a paced schedule, not immediately). | 
**Attachments** | Pointer to [**[]MessageAttachmentInput**](MessageAttachmentInput.md) | Files to attach (Base64-encoded). Up to 5 files, 7 MB decoded total. | [optional] 
**Html** | Pointer to **string** | Inline HTML body. | [optional] 
**Subject** | Pointer to **string** | Subject line for an inline send. | [optional] 
**Text** | Pointer to **string** | Inline plain-text body. | [optional] 
**TrackClicks** | Pointer to **bool** | Rewrite links to track clicks. | [optional] 
**TrackOpens** | Pointer to **bool** | Track opens for this message. | [optional] 
**VariantId** | Pointer to **string** | Id of a stored step variant to render as the template instead of inline content. | [optional] 
**InReplyTo** | **string** | Id of an inbound message to reply to; threads this send to that conversation. | 
**Test** | **interface{}** |  | 

## Methods

### NewMessageCreateParams

`func NewMessageCreateParams(from string, to string, sequence string, inReplyTo string, test interface{}, ) *MessageCreateParams`

NewMessageCreateParams instantiates a new MessageCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageCreateParamsWithDefaults

`func NewMessageCreateParamsWithDefaults() *MessageCreateParams`

NewMessageCreateParamsWithDefaults instantiates a new MessageCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MessageCreateParams) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessageCreateParams) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessageCreateParams) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MessageCreateParams) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFrom

`func (o *MessageCreateParams) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *MessageCreateParams) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *MessageCreateParams) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *MessageCreateParams) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *MessageCreateParams) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *MessageCreateParams) SetTo(v string)`

SetTo sets To field to given value.


### GetToName

`func (o *MessageCreateParams) GetToName() string`

GetToName returns the ToName field if non-nil, zero value otherwise.

### GetToNameOk

`func (o *MessageCreateParams) GetToNameOk() (*string, bool)`

GetToNameOk returns a tuple with the ToName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToName

`func (o *MessageCreateParams) SetToName(v string)`

SetToName sets ToName field to given value.

### HasToName

`func (o *MessageCreateParams) HasToName() bool`

HasToName returns a boolean if a field has been set.

### GetSequence

`func (o *MessageCreateParams) GetSequence() string`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *MessageCreateParams) GetSequenceOk() (*string, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *MessageCreateParams) SetSequence(v string)`

SetSequence sets Sequence field to given value.


### GetAttachments

`func (o *MessageCreateParams) GetAttachments() []MessageAttachmentInput`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *MessageCreateParams) GetAttachmentsOk() (*[]MessageAttachmentInput, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *MessageCreateParams) SetAttachments(v []MessageAttachmentInput)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *MessageCreateParams) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetHtml

`func (o *MessageCreateParams) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *MessageCreateParams) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *MessageCreateParams) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *MessageCreateParams) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetSubject

`func (o *MessageCreateParams) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *MessageCreateParams) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *MessageCreateParams) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *MessageCreateParams) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *MessageCreateParams) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *MessageCreateParams) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *MessageCreateParams) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *MessageCreateParams) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTrackClicks

`func (o *MessageCreateParams) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *MessageCreateParams) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *MessageCreateParams) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.

### HasTrackClicks

`func (o *MessageCreateParams) HasTrackClicks() bool`

HasTrackClicks returns a boolean if a field has been set.

### GetTrackOpens

`func (o *MessageCreateParams) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *MessageCreateParams) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *MessageCreateParams) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.

### HasTrackOpens

`func (o *MessageCreateParams) HasTrackOpens() bool`

HasTrackOpens returns a boolean if a field has been set.

### GetVariantId

`func (o *MessageCreateParams) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *MessageCreateParams) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *MessageCreateParams) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *MessageCreateParams) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### GetInReplyTo

`func (o *MessageCreateParams) GetInReplyTo() string`

GetInReplyTo returns the InReplyTo field if non-nil, zero value otherwise.

### GetInReplyToOk

`func (o *MessageCreateParams) GetInReplyToOk() (*string, bool)`

GetInReplyToOk returns a tuple with the InReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInReplyTo

`func (o *MessageCreateParams) SetInReplyTo(v string)`

SetInReplyTo sets InReplyTo field to given value.


### GetTest

`func (o *MessageCreateParams) GetTest() interface{}`

GetTest returns the Test field if non-nil, zero value otherwise.

### GetTestOk

`func (o *MessageCreateParams) GetTestOk() (*interface{}, bool)`

GetTestOk returns a tuple with the Test field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTest

`func (o *MessageCreateParams) SetTest(v interface{})`

SetTest sets Test field to given value.


### SetTestNil

`func (o *MessageCreateParams) SetTestNil(b bool)`

 SetTestNil sets the value for Test to be an explicit nil

### UnsetTest
`func (o *MessageCreateParams) UnsetTest()`

UnsetTest ensures that no value is present for Test, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


