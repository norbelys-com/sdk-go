# MessageUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssigneeId** | Pointer to **NullableString** |  | [optional] 
**Classification** | Pointer to **string** | Re-classify the reply&#39;s intent: interested, out_of_office, not_interested, auto_reply, bounce, complaint, unsubscribe, uncategorized. | [optional] 
**IsRead** | Pointer to **bool** | Mark read or unread. | [optional] 

## Methods

### NewMessageUpdateParams

`func NewMessageUpdateParams() *MessageUpdateParams`

NewMessageUpdateParams instantiates a new MessageUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageUpdateParamsWithDefaults

`func NewMessageUpdateParamsWithDefaults() *MessageUpdateParams`

NewMessageUpdateParamsWithDefaults instantiates a new MessageUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssigneeId

`func (o *MessageUpdateParams) GetAssigneeId() string`

GetAssigneeId returns the AssigneeId field if non-nil, zero value otherwise.

### GetAssigneeIdOk

`func (o *MessageUpdateParams) GetAssigneeIdOk() (*string, bool)`

GetAssigneeIdOk returns a tuple with the AssigneeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssigneeId

`func (o *MessageUpdateParams) SetAssigneeId(v string)`

SetAssigneeId sets AssigneeId field to given value.

### HasAssigneeId

`func (o *MessageUpdateParams) HasAssigneeId() bool`

HasAssigneeId returns a boolean if a field has been set.

### SetAssigneeIdNil

`func (o *MessageUpdateParams) SetAssigneeIdNil(b bool)`

 SetAssigneeIdNil sets the value for AssigneeId to be an explicit nil

### UnsetAssigneeId
`func (o *MessageUpdateParams) UnsetAssigneeId()`

UnsetAssigneeId ensures that no value is present for AssigneeId, not even an explicit nil
### GetClassification

`func (o *MessageUpdateParams) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *MessageUpdateParams) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *MessageUpdateParams) SetClassification(v string)`

SetClassification sets Classification field to given value.

### HasClassification

`func (o *MessageUpdateParams) HasClassification() bool`

HasClassification returns a boolean if a field has been set.

### GetIsRead

`func (o *MessageUpdateParams) GetIsRead() bool`

GetIsRead returns the IsRead field if non-nil, zero value otherwise.

### GetIsReadOk

`func (o *MessageUpdateParams) GetIsReadOk() (*bool, bool)`

GetIsReadOk returns a tuple with the IsRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRead

`func (o *MessageUpdateParams) SetIsRead(v bool)`

SetIsRead sets IsRead field to given value.

### HasIsRead

`func (o *MessageUpdateParams) HasIsRead() bool`

HasIsRead returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


