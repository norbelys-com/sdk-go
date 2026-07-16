# GroupAddMembersParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PersonIds** | Pointer to **[]string** | Explicit person ids to add. | [optional] 
**SegmentId** | Pointer to **string** | Add every person currently matching this segment as a one-time snapshot; they are copied in and not kept in sync with the segment afterward. | [optional] 

## Methods

### NewGroupAddMembersParams

`func NewGroupAddMembersParams() *GroupAddMembersParams`

NewGroupAddMembersParams instantiates a new GroupAddMembersParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupAddMembersParamsWithDefaults

`func NewGroupAddMembersParamsWithDefaults() *GroupAddMembersParams`

NewGroupAddMembersParamsWithDefaults instantiates a new GroupAddMembersParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPersonIds

`func (o *GroupAddMembersParams) GetPersonIds() []string`

GetPersonIds returns the PersonIds field if non-nil, zero value otherwise.

### GetPersonIdsOk

`func (o *GroupAddMembersParams) GetPersonIdsOk() (*[]string, bool)`

GetPersonIdsOk returns a tuple with the PersonIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonIds

`func (o *GroupAddMembersParams) SetPersonIds(v []string)`

SetPersonIds sets PersonIds field to given value.

### HasPersonIds

`func (o *GroupAddMembersParams) HasPersonIds() bool`

HasPersonIds returns a boolean if a field has been set.

### GetSegmentId

`func (o *GroupAddMembersParams) GetSegmentId() string`

GetSegmentId returns the SegmentId field if non-nil, zero value otherwise.

### GetSegmentIdOk

`func (o *GroupAddMembersParams) GetSegmentIdOk() (*string, bool)`

GetSegmentIdOk returns a tuple with the SegmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentId

`func (o *GroupAddMembersParams) SetSegmentId(v string)`

SetSegmentId sets SegmentId field to given value.

### HasSegmentId

`func (o *GroupAddMembersParams) HasSegmentId() bool`

HasSegmentId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


