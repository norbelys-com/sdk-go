# SenderBulkError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The mailbox that failed. | 
**Message** | **string** | Why it failed. | 

## Methods

### NewSenderBulkError

`func NewSenderBulkError(id string, message string, ) *SenderBulkError`

NewSenderBulkError instantiates a new SenderBulkError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderBulkErrorWithDefaults

`func NewSenderBulkErrorWithDefaults() *SenderBulkError`

NewSenderBulkErrorWithDefaults instantiates a new SenderBulkError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SenderBulkError) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderBulkError) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderBulkError) SetId(v string)`

SetId sets Id field to given value.


### GetMessage

`func (o *SenderBulkError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SenderBulkError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SenderBulkError) SetMessage(v string)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


