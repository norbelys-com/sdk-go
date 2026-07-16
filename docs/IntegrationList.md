# IntegrationList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Integration**](Integration.md) | The page of results, newest first. | 
**HasMore** | **bool** | Whether another page exists beyond this one. | 
**NextCursor** | **NullableString** |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Total** | Pointer to **int32** | Total number of rows matching the filters. Not included on every list. | [optional] 

## Methods

### NewIntegrationList

`func NewIntegrationList(data []Integration, hasMore bool, nextCursor NullableString, ) *IntegrationList`

NewIntegrationList instantiates a new IntegrationList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationListWithDefaults

`func NewIntegrationListWithDefaults() *IntegrationList`

NewIntegrationListWithDefaults instantiates a new IntegrationList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *IntegrationList) GetData() []Integration`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *IntegrationList) GetDataOk() (*[]Integration, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *IntegrationList) SetData(v []Integration)`

SetData sets Data field to given value.


### GetHasMore

`func (o *IntegrationList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *IntegrationList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *IntegrationList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetNextCursor

`func (o *IntegrationList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *IntegrationList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *IntegrationList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *IntegrationList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *IntegrationList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetObject

`func (o *IntegrationList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *IntegrationList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *IntegrationList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *IntegrationList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *IntegrationList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *IntegrationList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetTotal

`func (o *IntegrationList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *IntegrationList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *IntegrationList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *IntegrationList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


