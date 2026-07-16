# FieldCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | The merge code; omit to auto-derive a slug from the label. | [optional] 
**IsFilterable** | Pointer to **bool** | Offer this field as a segment filter; defaults to true. | [optional] 
**Label** | **string** | The human-readable display name for the field. | 
**Options** | Pointer to **[]string** | Allowed values — required when &#x60;type&#x60; is &#x60;dropdown&#x60;. | [optional] 
**Type** | Pointer to **string** | The data type: &#x60;text&#x60;, &#x60;email&#x60;, &#x60;phone&#x60;, &#x60;date&#x60;, &#x60;datetime&#x60;, &#x60;number&#x60;, or &#x60;dropdown&#x60;; defaults to &#x60;text&#x60;. | [optional] [default to "text"]

## Methods

### NewFieldCreateParams

`func NewFieldCreateParams(label string, ) *FieldCreateParams`

NewFieldCreateParams instantiates a new FieldCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldCreateParamsWithDefaults

`func NewFieldCreateParamsWithDefaults() *FieldCreateParams`

NewFieldCreateParamsWithDefaults instantiates a new FieldCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *FieldCreateParams) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *FieldCreateParams) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *FieldCreateParams) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *FieldCreateParams) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetIsFilterable

`func (o *FieldCreateParams) GetIsFilterable() bool`

GetIsFilterable returns the IsFilterable field if non-nil, zero value otherwise.

### GetIsFilterableOk

`func (o *FieldCreateParams) GetIsFilterableOk() (*bool, bool)`

GetIsFilterableOk returns a tuple with the IsFilterable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFilterable

`func (o *FieldCreateParams) SetIsFilterable(v bool)`

SetIsFilterable sets IsFilterable field to given value.

### HasIsFilterable

`func (o *FieldCreateParams) HasIsFilterable() bool`

HasIsFilterable returns a boolean if a field has been set.

### GetLabel

`func (o *FieldCreateParams) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FieldCreateParams) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FieldCreateParams) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetOptions

`func (o *FieldCreateParams) GetOptions() []string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *FieldCreateParams) GetOptionsOk() (*[]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *FieldCreateParams) SetOptions(v []string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *FieldCreateParams) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetType

`func (o *FieldCreateParams) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FieldCreateParams) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FieldCreateParams) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *FieldCreateParams) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


