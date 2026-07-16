# SegmentList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Segment**](Segment.md) | The page of results, newest first. | 
**HasMore** | **bool** | Whether another page exists beyond this one. | 
**NextCursor** | **NullableString** |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Total** | **int32** | Total number of segments matching the search. | 

## Methods

### NewSegmentList

`func NewSegmentList(data []Segment, hasMore bool, nextCursor NullableString, total int32, ) *SegmentList`

NewSegmentList instantiates a new SegmentList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSegmentListWithDefaults

`func NewSegmentListWithDefaults() *SegmentList`

NewSegmentListWithDefaults instantiates a new SegmentList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SegmentList) GetData() []Segment`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SegmentList) GetDataOk() (*[]Segment, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SegmentList) SetData(v []Segment)`

SetData sets Data field to given value.


### GetHasMore

`func (o *SegmentList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *SegmentList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *SegmentList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetNextCursor

`func (o *SegmentList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *SegmentList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *SegmentList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *SegmentList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *SegmentList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetObject

`func (o *SegmentList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *SegmentList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *SegmentList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *SegmentList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *SegmentList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *SegmentList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetTotal

`func (o *SegmentList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SegmentList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SegmentList) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


