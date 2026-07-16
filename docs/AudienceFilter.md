# AudienceFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Conditions** | Pointer to [**[]AudienceRule**](AudienceRule.md) | The rules, up to 50 — attribute conditions (field · op · value) and/or activity conditions (did/did-not + engagement scope); an empty list matches every (non-archived) person. | [optional] [default to []]
**Match** | Pointer to [**AudienceMatch**](AudienceMatch.md) |  | [optional] [default to AUDIENCEMATCH_ALL]

## Methods

### NewAudienceFilter

`func NewAudienceFilter() *AudienceFilter`

NewAudienceFilter instantiates a new AudienceFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceFilterWithDefaults

`func NewAudienceFilterWithDefaults() *AudienceFilter`

NewAudienceFilterWithDefaults instantiates a new AudienceFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConditions

`func (o *AudienceFilter) GetConditions() []AudienceRule`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *AudienceFilter) GetConditionsOk() (*[]AudienceRule, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *AudienceFilter) SetConditions(v []AudienceRule)`

SetConditions sets Conditions field to given value.

### HasConditions

`func (o *AudienceFilter) HasConditions() bool`

HasConditions returns a boolean if a field has been set.

### GetMatch

`func (o *AudienceFilter) GetMatch() AudienceMatch`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *AudienceFilter) GetMatchOk() (*AudienceMatch, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *AudienceFilter) SetMatch(v AudienceMatch)`

SetMatch sets Match field to given value.

### HasMatch

`func (o *AudienceFilter) HasMatch() bool`

HasMatch returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


