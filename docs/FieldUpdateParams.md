# FieldUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsFilterable** | Pointer to **bool** | Whether this field is offered as a segment/list filter. | [optional] 
**Label** | Pointer to **string** | New display name for the field. | [optional] 
**Options** | Pointer to **[]string** |  | [optional] 
**Type** | Pointer to **string** | Change the data type: &#x60;text&#x60;, &#x60;email&#x60;, &#x60;phone&#x60;, &#x60;date&#x60;, &#x60;datetime&#x60;, &#x60;number&#x60;, or &#x60;dropdown&#x60;. | [optional] 

## Methods

### NewFieldUpdateParams

`func NewFieldUpdateParams() *FieldUpdateParams`

NewFieldUpdateParams instantiates a new FieldUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldUpdateParamsWithDefaults

`func NewFieldUpdateParamsWithDefaults() *FieldUpdateParams`

NewFieldUpdateParamsWithDefaults instantiates a new FieldUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsFilterable

`func (o *FieldUpdateParams) GetIsFilterable() bool`

GetIsFilterable returns the IsFilterable field if non-nil, zero value otherwise.

### GetIsFilterableOk

`func (o *FieldUpdateParams) GetIsFilterableOk() (*bool, bool)`

GetIsFilterableOk returns a tuple with the IsFilterable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFilterable

`func (o *FieldUpdateParams) SetIsFilterable(v bool)`

SetIsFilterable sets IsFilterable field to given value.

### HasIsFilterable

`func (o *FieldUpdateParams) HasIsFilterable() bool`

HasIsFilterable returns a boolean if a field has been set.

### GetLabel

`func (o *FieldUpdateParams) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FieldUpdateParams) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FieldUpdateParams) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *FieldUpdateParams) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetOptions

`func (o *FieldUpdateParams) GetOptions() []string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *FieldUpdateParams) GetOptionsOk() (*[]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *FieldUpdateParams) SetOptions(v []string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *FieldUpdateParams) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### SetOptionsNil

`func (o *FieldUpdateParams) SetOptionsNil(b bool)`

 SetOptionsNil sets the value for Options to be an explicit nil

### UnsetOptions
`func (o *FieldUpdateParams) UnsetOptions()`

UnsetOptions ensures that no value is present for Options, not even an explicit nil
### GetType

`func (o *FieldUpdateParams) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FieldUpdateParams) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FieldUpdateParams) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *FieldUpdateParams) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


