# DomainList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Domain**](Domain.md) | The page of results, newest first. | 
**HasMore** | **bool** | Whether another page exists beyond this one. | 
**NextCursor** | **NullableString** |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Total** | Pointer to **int32** | Total number of rows matching the filters. Not included on every list. | [optional] 

## Methods

### NewDomainList

`func NewDomainList(data []Domain, hasMore bool, nextCursor NullableString, ) *DomainList`

NewDomainList instantiates a new DomainList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListWithDefaults

`func NewDomainListWithDefaults() *DomainList`

NewDomainListWithDefaults instantiates a new DomainList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DomainList) GetData() []Domain`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DomainList) GetDataOk() (*[]Domain, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DomainList) SetData(v []Domain)`

SetData sets Data field to given value.


### GetHasMore

`func (o *DomainList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *DomainList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *DomainList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetNextCursor

`func (o *DomainList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *DomainList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *DomainList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *DomainList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *DomainList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetObject

`func (o *DomainList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *DomainList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *DomainList) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *DomainList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *DomainList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *DomainList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetTotal

`func (o *DomainList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *DomainList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *DomainList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *DomainList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


