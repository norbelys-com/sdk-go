# BulkUpdateSendersResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | [**[]SenderBulkError**](SenderBulkError.md) | Per-mailbox failures — every other mailbox still updated. | 
**Object** | **interface{}** |  | 
**Senders** | [**[]Sender**](Sender.md) | The updated mailboxes. | 
**Updated** | **int32** | How many mailboxes were updated. | 

## Methods

### NewBulkUpdateSendersResult

`func NewBulkUpdateSendersResult(errors []SenderBulkError, object interface{}, senders []Sender, updated int32, ) *BulkUpdateSendersResult`

NewBulkUpdateSendersResult instantiates a new BulkUpdateSendersResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkUpdateSendersResultWithDefaults

`func NewBulkUpdateSendersResultWithDefaults() *BulkUpdateSendersResult`

NewBulkUpdateSendersResultWithDefaults instantiates a new BulkUpdateSendersResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *BulkUpdateSendersResult) GetErrors() []SenderBulkError`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *BulkUpdateSendersResult) GetErrorsOk() (*[]SenderBulkError, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *BulkUpdateSendersResult) SetErrors(v []SenderBulkError)`

SetErrors sets Errors field to given value.


### GetObject

`func (o *BulkUpdateSendersResult) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *BulkUpdateSendersResult) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *BulkUpdateSendersResult) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *BulkUpdateSendersResult) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *BulkUpdateSendersResult) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetSenders

`func (o *BulkUpdateSendersResult) GetSenders() []Sender`

GetSenders returns the Senders field if non-nil, zero value otherwise.

### GetSendersOk

`func (o *BulkUpdateSendersResult) GetSendersOk() (*[]Sender, bool)`

GetSendersOk returns a tuple with the Senders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenders

`func (o *BulkUpdateSendersResult) SetSenders(v []Sender)`

SetSenders sets Senders field to given value.


### GetUpdated

`func (o *BulkUpdateSendersResult) GetUpdated() int32`

GetUpdated returns the Updated field if non-nil, zero value otherwise.

### GetUpdatedOk

`func (o *BulkUpdateSendersResult) GetUpdatedOk() (*int32, bool)`

GetUpdatedOk returns a tuple with the Updated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdated

`func (o *BulkUpdateSendersResult) SetUpdated(v int32)`

SetUpdated sets Updated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


