# ProgramVariantInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | Pointer to [**EmailVariantContent**](EmailVariantContent.md) | The arm&#39;s email content (subject/html/text, optional AI directive). | [optional] 
**Label** | Pointer to **string** | Short arm label, e.g. A / B. | [optional] 
**Weight** | Pointer to **int32** | Relative distribution weight among the step&#39;s live arms. | [optional] 
**Archived** | Pointer to **bool** | Set true (with id) to archive this arm. | [optional] 
**Id** | Pointer to **string** | Existing variant id to edit; omit to create a new arm. | [optional] 

## Methods

### NewProgramVariantInput

`func NewProgramVariantInput() *ProgramVariantInput`

NewProgramVariantInput instantiates a new ProgramVariantInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramVariantInputWithDefaults

`func NewProgramVariantInputWithDefaults() *ProgramVariantInput`

NewProgramVariantInputWithDefaults instantiates a new ProgramVariantInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *ProgramVariantInput) GetContent() EmailVariantContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ProgramVariantInput) GetContentOk() (*EmailVariantContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ProgramVariantInput) SetContent(v EmailVariantContent)`

SetContent sets Content field to given value.

### HasContent

`func (o *ProgramVariantInput) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetLabel

`func (o *ProgramVariantInput) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ProgramVariantInput) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ProgramVariantInput) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ProgramVariantInput) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetWeight

`func (o *ProgramVariantInput) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *ProgramVariantInput) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *ProgramVariantInput) SetWeight(v int32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *ProgramVariantInput) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetArchived

`func (o *ProgramVariantInput) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *ProgramVariantInput) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *ProgramVariantInput) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *ProgramVariantInput) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetId

`func (o *ProgramVariantInput) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProgramVariantInput) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProgramVariantInput) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ProgramVariantInput) HasId() bool`

HasId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


