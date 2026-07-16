# EmailVariantContent

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

### NewEmailVariantContent

`func NewEmailVariantContent(ai VariantAi, ) *EmailVariantContent`

NewEmailVariantContent instantiates a new EmailVariantContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailVariantContentWithDefaults

`func NewEmailVariantContentWithDefaults() *EmailVariantContent`

NewEmailVariantContentWithDefaults instantiates a new EmailVariantContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCtaOverrideReason

`func (o *EmailVariantContent) GetCtaOverrideReason() string`

GetCtaOverrideReason returns the CtaOverrideReason field if non-nil, zero value otherwise.

### GetCtaOverrideReasonOk

`func (o *EmailVariantContent) GetCtaOverrideReasonOk() (*string, bool)`

GetCtaOverrideReasonOk returns a tuple with the CtaOverrideReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtaOverrideReason

`func (o *EmailVariantContent) SetCtaOverrideReason(v string)`

SetCtaOverrideReason sets CtaOverrideReason field to given value.

### HasCtaOverrideReason

`func (o *EmailVariantContent) HasCtaOverrideReason() bool`

HasCtaOverrideReason returns a boolean if a field has been set.

### GetHtml

`func (o *EmailVariantContent) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *EmailVariantContent) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *EmailVariantContent) SetHtml(v string)`

SetHtml sets Html field to given value.

### HasHtml

`func (o *EmailVariantContent) HasHtml() bool`

HasHtml returns a boolean if a field has been set.

### GetPreheader

`func (o *EmailVariantContent) GetPreheader() string`

GetPreheader returns the Preheader field if non-nil, zero value otherwise.

### GetPreheaderOk

`func (o *EmailVariantContent) GetPreheaderOk() (*string, bool)`

GetPreheaderOk returns a tuple with the Preheader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreheader

`func (o *EmailVariantContent) SetPreheader(v string)`

SetPreheader sets Preheader field to given value.

### HasPreheader

`func (o *EmailVariantContent) HasPreheader() bool`

HasPreheader returns a boolean if a field has been set.

### GetSubject

`func (o *EmailVariantContent) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *EmailVariantContent) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *EmailVariantContent) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *EmailVariantContent) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetText

`func (o *EmailVariantContent) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *EmailVariantContent) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *EmailVariantContent) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *EmailVariantContent) HasText() bool`

HasText returns a boolean if a field has been set.

### GetAi

`func (o *EmailVariantContent) GetAi() VariantAi`

GetAi returns the Ai field if non-nil, zero value otherwise.

### GetAiOk

`func (o *EmailVariantContent) GetAiOk() (*VariantAi, bool)`

GetAiOk returns a tuple with the Ai field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAi

`func (o *EmailVariantContent) SetAi(v VariantAi)`

SetAi sets Ai field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


