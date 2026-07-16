# MessageTestParams

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
**Test** | **interface{}** |  | 

## Methods

### NewMessageTestParams

`func NewMessageTestParams(from string, to string, test interface{}, ) *MessageTestParams`

NewMessageTestParams instantiates a new MessageTestParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageTestParamsWithDefaults

`func NewMessageTestParamsWithDefaults() *MessageTestParams`

NewMessageTestParamsWithDefaults instantiates a new MessageTestParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MessageTestParams) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessageTestParams) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessageTestParams) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MessageTestParams) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFrom

`func (o *MessageTestParams) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *MessageTestParams) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *MessageTestParams) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *MessageTestParams) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *MessageTestParams) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *MessageTestParams) SetTo(v string)`

SetTo sets To field to given value.


### GetToName

`func (o *MessageTestParams) GetToName() string`

GetToName returns the ToName field if non-nil, zero value otherwise.

### GetToNameOk

`func (o *MessageTestParams) GetToNameOk() (*string, bool)`

GetToNameOk returns a tuple with the ToName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToName

`func (o *MessageTestParams) SetToName(v string)`

SetToName sets ToName field to given value.

### HasToName

`func (o *MessageTestParams) HasToName() bool`

HasToName returns a boolean if a field has been set.

### GetAttachments

`func (o *MessageTestParams) GetAttachments() []MessageAttachmentInput`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *MessageTestParams) GetAttachmentsOk() (*[]MessageAttachmentInput, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *MessageTestParams) SetAttachments(v []MessageAttachmentInput)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *MessageTestParams) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetHtml

`func (o *MessageTestParams) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *MessageTestParams) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *MessageTestParams) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *MessageTestParams) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetSubject

`func (o *MessageTestParams) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *MessageTestParams) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *MessageTestParams) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *MessageTestParams) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *MessageTestParams) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *MessageTestParams) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *MessageTestParams) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *MessageTestParams) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTrackClicks

`func (o *MessageTestParams) GetTrackClicks() bool`

GetTrackClicks returns the TrackClicks field if non-nil, zero value otherwise.

### GetTrackClicksOk

`func (o *MessageTestParams) GetTrackClicksOk() (*bool, bool)`

GetTrackClicksOk returns a tuple with the TrackClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackClicks

`func (o *MessageTestParams) SetTrackClicks(v bool)`

SetTrackClicks sets TrackClicks field to given value.

### HasTrackClicks

`func (o *MessageTestParams) HasTrackClicks() bool`

HasTrackClicks returns a boolean if a field has been set.

### GetTrackOpens

`func (o *MessageTestParams) GetTrackOpens() bool`

GetTrackOpens returns the TrackOpens field if non-nil, zero value otherwise.

### GetTrackOpensOk

`func (o *MessageTestParams) GetTrackOpensOk() (*bool, bool)`

GetTrackOpensOk returns a tuple with the TrackOpens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackOpens

`func (o *MessageTestParams) SetTrackOpens(v bool)`

SetTrackOpens sets TrackOpens field to given value.

### HasTrackOpens

`func (o *MessageTestParams) HasTrackOpens() bool`

HasTrackOpens returns a boolean if a field has been set.

### GetVariantId

`func (o *MessageTestParams) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *MessageTestParams) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *MessageTestParams) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *MessageTestParams) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### GetTest

`func (o *MessageTestParams) GetTest() interface{}`

GetTest returns the Test field if non-nil, zero value otherwise.

### GetTestOk

`func (o *MessageTestParams) GetTestOk() (*interface{}, bool)`

GetTestOk returns a tuple with the Test field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTest

`func (o *MessageTestParams) SetTest(v interface{})`

SetTest sets Test field to given value.


### SetTestNil

`func (o *MessageTestParams) SetTestNil(b bool)`

 SetTestNil sets the value for Test to be an explicit nil

### UnsetTest
`func (o *MessageTestParams) UnsetTest()`

UnsetTest ensures that no value is present for Test, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


