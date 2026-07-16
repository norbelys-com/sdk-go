# AiEmailVariantContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CtaOverrideReason** | Pointer to **string** | Documented operator reason for keeping multiple commercial asks; advisory, never a launch blocker. | [optional] 
**Html** | Pointer to **string** | HTML body; supports template variables. | [optional] 
**Preheader** | Pointer to **string** | Optional inbox preview snippet; separate from the MIME plain-text body. | [optional] 
**Subject** | Pointer to **string** | Subject line; supports template variables like {{ firstname }} (always give bare tags a &#x60;| default:&#x60; fallback). | [optional] 
**Text** | Pointer to **string** | Optional plain-text body; when omitted it is derived from the rendered HTML. | [optional] 
**Ai** | [**VariantAi**](VariantAi.md) |  | 

## Methods

### NewAiEmailVariantContent

`func NewAiEmailVariantContent(ai VariantAi, ) *AiEmailVariantContent`

NewAiEmailVariantContent instantiates a new AiEmailVariantContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiEmailVariantContentWithDefaults

`func NewAiEmailVariantContentWithDefaults() *AiEmailVariantContent`

NewAiEmailVariantContentWithDefaults instantiates a new AiEmailVariantContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCtaOverrideReason

`func (o *AiEmailVariantContent) GetCtaOverrideReason() string`

GetCtaOverrideReason returns the CtaOverrideReason field if non-nil, zero value otherwise.

### GetCtaOverrideReasonOk

`func (o *AiEmailVariantContent) GetCtaOverrideReasonOk() (*string, bool)`

GetCtaOverrideReasonOk returns a tuple with the CtaOverrideReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtaOverrideReason

`func (o *AiEmailVariantContent) SetCtaOverrideReason(v string)`

SetCtaOverrideReason sets CtaOverrideReason field to given value.

### HasCtaOverrideReason

`func (o *AiEmailVariantContent) HasCtaOverrideReason() bool`

HasCtaOverrideReason returns a boolean if a field has been set.

### GetHtml

`func (o *AiEmailVariantContent) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *AiEmailVariantContent) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *AiEmailVariantContent) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *AiEmailVariantContent) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetPreheader

`func (o *AiEmailVariantContent) GetPreheader() string`

GetPreheader returns the Preheader field if non-nil, zero value otherwise.

### GetPreheaderOk

`func (o *AiEmailVariantContent) GetPreheaderOk() (*string, bool)`

GetPreheaderOk returns a tuple with the Preheader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreheader

`func (o *AiEmailVariantContent) SetPreheader(v string)`

SetPreheader sets Preheader field to given value.

### HasPreheader

`func (o *AiEmailVariantContent) HasPreheader() bool`

HasPreheader returns a boolean if a field has been set.

### GetSubject

`func (o *AiEmailVariantContent) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *AiEmailVariantContent) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *AiEmailVariantContent) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *AiEmailVariantContent) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *AiEmailVariantContent) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *AiEmailVariantContent) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *AiEmailVariantContent) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *AiEmailVariantContent) HasText() bool`

HasText returns a boolean if a field has been set.

### GetAi

`func (o *AiEmailVariantContent) GetAi() VariantAi`

GetAi returns the Ai field if non-nil, zero value otherwise.

### GetAiOk

`func (o *AiEmailVariantContent) GetAiOk() (*VariantAi, bool)`

GetAiOk returns a tuple with the Ai field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAi

`func (o *AiEmailVariantContent) SetAi(v VariantAi)`

SetAi sets Ai field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


