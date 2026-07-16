# ProgramsSendersList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ProgramSenderRef**](ProgramSenderRef.md) | The page of results, newest first. | 
**HasMore** | **bool** | Whether another page exists beyond this one. | 
**NextCursor** | **NullableString** |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Total** | Pointer to **int32** | Total number of rows matching the filters. Not included on every list. | [optional] 

## Methods

### NewProgramsSendersList

`func NewProgramsSendersList(data []ProgramSenderRef, hasMore bool, nextCursor NullableString, ) *ProgramsSendersList`

NewProgramsSendersList instantiates a new ProgramsSendersList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramsSendersListWithDefaults

`func NewProgramsSendersListWithDefaults() *ProgramsSendersList`

NewProgramsSendersListWithDefaults instantiates a new ProgramsSendersList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ProgramsSendersList) GetData() []ProgramSenderRef`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ProgramsSendersList) GetDataOk() (*[]ProgramSenderRef, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ProgramsSendersList) SetData(v []ProgramSenderRef)`

SetData sets Data field to given value.


### GetHasMore

`func (o *ProgramsSendersList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *ProgramsSendersList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *ProgramsSendersList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetNextCursor

`func (o *ProgramsSendersList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ProgramsSendersList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ProgramsSendersList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ProgramsSendersList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ProgramsSendersList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetObject

`func (o *ProgramsSendersList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ProgramsSendersList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ProgramsSendersList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *ProgramsSendersList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *ProgramsSendersList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *ProgramsSendersList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetTotal

`func (o *ProgramsSendersList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ProgramsSendersList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ProgramsSendersList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ProgramsSendersList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


