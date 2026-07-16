# GroupAddMembersResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Added** | **int32** | Number of people newly added to the group. | 
**MemberCount** | **int32** | The group&#39;s total member count after the add. | 
**Skipped** | **int32** | Number of people skipped because they were already members. | 

## Methods

### NewGroupAddMembersResult

`func NewGroupAddMembersResult(added int32, memberCount int32, skipped int32, ) *GroupAddMembersResult`

NewGroupAddMembersResult instantiates a new GroupAddMembersResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupAddMembersResultWithDefaults

`func NewGroupAddMembersResultWithDefaults() *GroupAddMembersResult`

NewGroupAddMembersResultWithDefaults instantiates a new GroupAddMembersResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdded

`func (o *GroupAddMembersResult) GetAdded() int32`

GetAdded returns the Added field if non-nil, zero value otherwise.

### GetAddedOk

`func (o *GroupAddMembersResult) GetAddedOk() (*int32, bool)`

GetAddedOk returns a tuple with the Added field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdded

`func (o *GroupAddMembersResult) SetAdded(v int32)`

SetAdded sets Added field to given value.


### GetMemberCount

`func (o *GroupAddMembersResult) GetMemberCount() int32`

GetMemberCount returns the MemberCount field if non-nil, zero value otherwise.

### GetMemberCountOk

`func (o *GroupAddMembersResult) GetMemberCountOk() (*int32, bool)`

GetMemberCountOk returns a tuple with the MemberCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberCount

`func (o *GroupAddMembersResult) SetMemberCount(v int32)`

SetMemberCount sets MemberCount field to given value.


### GetSkipped

`func (o *GroupAddMembersResult) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *GroupAddMembersResult) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *GroupAddMembersResult) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


