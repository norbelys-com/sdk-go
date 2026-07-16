# FieldList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Field**](Field.md) | The org&#39;s custom fields, in display order. | 
**Object** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewFieldList

`func NewFieldList(data []Field, ) *FieldList`

NewFieldList instantiates a new FieldList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldListWithDefaults

`func NewFieldListWithDefaults() *FieldList`

NewFieldListWithDefaults instantiates a new FieldList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *FieldList) GetData() []Field`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FieldList) GetDataOk() (*[]Field, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FieldList) SetData(v []Field)`

SetData sets Data field to given value.


### GetObject

`func (o *FieldList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *FieldList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *FieldList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *FieldList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *FieldList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *FieldList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


