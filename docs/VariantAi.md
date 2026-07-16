# VariantAi

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Language** | Pointer to **string** | Language for the generated email (e.g. &#39;es&#39;, &#39;en&#39;). Default: mirror the base template&#39;s language. | [optional] 
**Prompt** | **string** | The operator&#39;s personalization instruction — what to emphasize, tone, goal. The AI keeps the base template&#39;s intent and CTA; it never invents facts about the recipient. | 
**Signals** | Pointer to **[]string** | What research feeds the generation. &#x60;company&#x60; &#x3D; firmographics for the recipient&#39;s domain (industry, city, size — one cached lookup per domain); &#x60;person&#x60; &#x3D; the contact&#39;s own fields; &#x60;website&#x60; &#x3D; read the recipient company&#39;s own site (business domains only — public/free-mail addresses are skipped; fetched once per domain and cached). Default: company + person. | [optional] 

## Methods

### NewVariantAi

`func NewVariantAi(prompt string, ) *VariantAi`

NewVariantAi instantiates a new VariantAi object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVariantAiWithDefaults

`func NewVariantAiWithDefaults() *VariantAi`

NewVariantAiWithDefaults instantiates a new VariantAi object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *VariantAi) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *VariantAi) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *VariantAi) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *VariantAi) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetPrompt

`func (o *VariantAi) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *VariantAi) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *VariantAi) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetSignals

`func (o *VariantAi) GetSignals() []string`

GetSignals returns the Signals field if non-nil, zero value otherwise.

### GetSignalsOk

`func (o *VariantAi) GetSignalsOk() (*[]string, bool)`

GetSignalsOk returns a tuple with the Signals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignals

`func (o *VariantAi) SetSignals(v []string)`

SetSignals sets Signals field to given value.

### HasSignals

`func (o *VariantAi) HasSignals() bool`

HasSignals returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


