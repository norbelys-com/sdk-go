# Field

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**Code** | **string** | The merge tag and storage key, templated as &#x60;{{ code }}&#x60;. | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The field id. | 
**IsFilterable** | **bool** | Whether this field is offered as a segment/list filter. | 
**Label** | **string** | The human-readable display name for the field. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Options** | **[]string** |  | 
**Order** | **int32** | Display order among custom fields (lower &#x3D; first). | 
**Type** | [**FieldType**](FieldType.md) |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewField

`func NewField(code string, id string, isFilterable bool, label string, options []string, order int32, type_ FieldType, ) *Field`

NewField instantiates a new Field object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldWithDefaults

`func NewFieldWithDefaults() *Field`

NewFieldWithDefaults instantiates a new Field object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *Field) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Field) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Field) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Field) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Field) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Field) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCode

`func (o *Field) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Field) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Field) SetCode(v string)`

SetCode sets Code field to given value.


### GetCreatedAt

`func (o *Field) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Field) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Field) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Field) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Field) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Field) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *Field) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Field) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Field) SetId(v string)`

SetId sets Id field to given value.


### GetIsFilterable

`func (o *Field) GetIsFilterable() bool`

GetIsFilterable returns the IsFilterable field if non-nil, zero value otherwise.

### GetIsFilterableOk

`func (o *Field) GetIsFilterableOk() (*bool, bool)`

GetIsFilterableOk returns a tuple with the IsFilterable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFilterable

`func (o *Field) SetIsFilterable(v bool)`

SetIsFilterable sets IsFilterable field to given value.


### GetLabel

`func (o *Field) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *Field) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *Field) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetObject

`func (o *Field) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Field) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Field) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Field) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Field) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Field) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetOptions

`func (o *Field) GetOptions() []string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *Field) GetOptionsOk() (*[]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *Field) SetOptions(v []string)`

SetOptions sets Options field to given value.


### SetOptionsNil

`func (o *Field) SetOptionsNil(b bool)`

 SetOptionsNil sets the value for Options to be an explicit nil

### UnsetOptions
`func (o *Field) UnsetOptions()`

UnsetOptions ensures that no value is present for Options, not even an explicit nil
### GetOrder

`func (o *Field) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Field) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Field) SetOrder(v int32)`

SetOrder sets Order field to given value.


### GetType

`func (o *Field) GetType() FieldType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Field) GetTypeOk() (*FieldType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Field) SetType(v FieldType)`

SetType sets Type field to given value.


### GetUpdatedAt

`func (o *Field) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Field) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Field) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Field) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Field) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Field) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


