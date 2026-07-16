# MessageAttachmentList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]MessageAttachment**](MessageAttachment.md) | The attachment metadata. | 
**HasMore** | **bool** | Always false — attachments are returned in full. | 
**Object** | **interface{}** |  | 

## Methods

### NewMessageAttachmentList

`func NewMessageAttachmentList(data []MessageAttachment, hasMore bool, object interface{}, ) *MessageAttachmentList`

NewMessageAttachmentList instantiates a new MessageAttachmentList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageAttachmentListWithDefaults

`func NewMessageAttachmentListWithDefaults() *MessageAttachmentList`

NewMessageAttachmentListWithDefaults instantiates a new MessageAttachmentList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MessageAttachmentList) GetData() []MessageAttachment`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessageAttachmentList) GetDataOk() (*[]MessageAttachment, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessageAttachmentList) SetData(v []MessageAttachment)`

SetData sets Data field to given value.


### GetHasMore

`func (o *MessageAttachmentList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *MessageAttachmentList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *MessageAttachmentList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetObject

`func (o *MessageAttachmentList) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *MessageAttachmentList) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *MessageAttachmentList) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *MessageAttachmentList) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *MessageAttachmentList) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


