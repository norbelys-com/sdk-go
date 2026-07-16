# EnrollmentList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Enrollment**](Enrollment.md) | The page of results, newest first. | 
**HasMore** | **bool** | Whether another page exists beyond this one. | 
**NextCursor** | **NullableString** |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Total** | Pointer to **int32** | Total number of rows matching the filters. Not included on every list. | [optional] 
**Counts** | [**EnrollmentCounts**](EnrollmentCounts.md) |  | 

## Methods

### NewEnrollmentList

`func NewEnrollmentList(data []Enrollment, hasMore bool, nextCursor NullableString, counts EnrollmentCounts, ) *EnrollmentList`

NewEnrollmentList instantiates a new EnrollmentList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrollmentListWithDefaults

`func NewEnrollmentListWithDefaults() *EnrollmentList`

NewEnrollmentListWithDefaults instantiates a new EnrollmentList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *EnrollmentList) GetData() []Enrollment`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *EnrollmentList) GetDataOk() (*[]Enrollment, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *EnrollmentList) SetData(v []Enrollment)`

SetData sets Data field to given value.


### GetHasMore

`func (o *EnrollmentList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *EnrollmentList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *EnrollmentList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetNextCursor

`func (o *EnrollmentList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *EnrollmentList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *EnrollmentList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *EnrollmentList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *EnrollmentList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetObject

`func (o *EnrollmentList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *EnrollmentList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *EnrollmentList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *EnrollmentList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *EnrollmentList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *EnrollmentList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetTotal

`func (o *EnrollmentList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *EnrollmentList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *EnrollmentList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *EnrollmentList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetCounts

`func (o *EnrollmentList) GetCounts() EnrollmentCounts`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *EnrollmentList) GetCountsOk() (*EnrollmentCounts, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *EnrollmentList) SetCounts(v EnrollmentCounts)`

SetCounts sets Counts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


