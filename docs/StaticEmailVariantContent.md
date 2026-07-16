# StaticEmailVariantContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CtaOverrideReason** | Pointer to **string** | Documented operator reason for keeping multiple commercial asks; advisory, never a launch blocker. | [optional] 
**Html** | Pointer to **string** | HTML body; supports template variables. | [optional] 
**Preheader** | Pointer to **string** | Optional inbox preview snippet; separate from the MIME plain-text body. | [optional] 
**Subject** | Pointer to **string** | Subject line; supports template variables like {{ firstname }} (always give bare tags a &#x60;| default:&#x60; fallback). | [optional] 
**Text** | Pointer to **string** | Optional plain-text body; when omitted it is derived from the rendered HTML. | [optional] 
**Ai** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewStaticEmailVariantContent

`func NewStaticEmailVariantContent() *StaticEmailVariantContent`

NewStaticEmailVariantContent instantiates a new StaticEmailVariantContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStaticEmailVariantContentWithDefaults

`func NewStaticEmailVariantContentWithDefaults() *StaticEmailVariantContent`

NewStaticEmailVariantContentWithDefaults instantiates a new StaticEmailVariantContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCtaOverrideReason

`func (o *StaticEmailVariantContent) GetCtaOverrideReason() string`

GetCtaOverrideReason returns the CtaOverrideReason field if non-nil, zero value otherwise.

### GetCtaOverrideReasonOk

`func (o *StaticEmailVariantContent) GetCtaOverrideReasonOk() (*string, bool)`

GetCtaOverrideReasonOk returns a tuple with the CtaOverrideReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtaOverrideReason

`func (o *StaticEmailVariantContent) SetCtaOverrideReason(v string)`

SetCtaOverrideReason sets CtaOverrideReason field to given value.

### HasCtaOverrideReason

`func (o *StaticEmailVariantContent) HasCtaOverrideReason() bool`

HasCtaOverrideReason returns a boolean if a field has been set.

### GetHtml

`func (o *StaticEmailVariantContent) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *StaticEmailVariantContent) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *StaticEmailVariantContent) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *StaticEmailVariantContent) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetPreheader

`func (o *StaticEmailVariantContent) GetPreheader() string`

GetPreheader returns the Preheader field if non-nil, zero value otherwise.

### GetPreheaderOk

`func (o *StaticEmailVariantContent) GetPreheaderOk() (*string, bool)`

GetPreheaderOk returns a tuple with the Preheader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreheader

`func (o *StaticEmailVariantContent) SetPreheader(v string)`

SetPreheader sets Preheader field to given value.

### HasPreheader

`func (o *StaticEmailVariantContent) HasPreheader() bool`

HasPreheader returns a boolean if a field has been set.

### GetSubject

`func (o *StaticEmailVariantContent) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *StaticEmailVariantContent) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *StaticEmailVariantContent) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *StaticEmailVariantContent) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *StaticEmailVariantContent) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *StaticEmailVariantContent) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *StaticEmailVariantContent) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *StaticEmailVariantContent) HasText() bool`

HasText returns a boolean if a field has been set.

### GetAi

`func (o *StaticEmailVariantContent) GetAi() interface{}`

GetAi returns the Ai field if non-nil, zero value otherwise.

### GetAiOk

`func (o *StaticEmailVariantContent) GetAiOk() (*interface{}, bool)`

GetAiOk returns a tuple with the Ai field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAi

`func (o *StaticEmailVariantContent) SetAi(v interface{})`

SetAi sets Ai field to given value.

### HasAi

`func (o *StaticEmailVariantContent) HasAi() bool`

HasAi returns a boolean if a field has been set.

### SetAiNil

`func (o *StaticEmailVariantContent) SetAiNil(b bool)`

 SetAiNil sets the value for Ai to be an explicit nil

### UnsetAi
`func (o *StaticEmailVariantContent) UnsetAi()`

UnsetAi ensures that no value is present for Ai, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


