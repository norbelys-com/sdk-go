# ProgramSenderRef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromEmail** | **string** | The sender&#39;s from address. | 
**FromName** | **string** | The sender&#39;s display name. | 
**Id** | **string** | The sender id. | 
**NextSendAt** | Pointer to **interface{}** |  | [optional] 
**Queued** | Pointer to **int32** | Active leads whose thread this mailbox owns and that still have a send scheduled in this program. Only present in list responses. | [optional] 

## Methods

### NewProgramSenderRef

`func NewProgramSenderRef(fromEmail string, fromName string, id string, ) *ProgramSenderRef`

NewProgramSenderRef instantiates a new ProgramSenderRef object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProgramSenderRefWithDefaults

`func NewProgramSenderRefWithDefaults() *ProgramSenderRef`

NewProgramSenderRefWithDefaults instantiates a new ProgramSenderRef object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromEmail

`func (o *ProgramSenderRef) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *ProgramSenderRef) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *ProgramSenderRef) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetFromName

`func (o *ProgramSenderRef) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *ProgramSenderRef) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *ProgramSenderRef) SetFromName(v string)`

SetFromName sets FromName field to given value.


### GetId

`func (o *ProgramSenderRef) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProgramSenderRef) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProgramSenderRef) SetId(v string)`

SetId sets Id field to given value.


### GetNextSendAt

`func (o *ProgramSenderRef) GetNextSendAt() interface{}`

GetNextSendAt returns the NextSendAt field if non-nil, zero value otherwise.

### GetNextSendAtOk

`func (o *ProgramSenderRef) GetNextSendAtOk() (*interface{}, bool)`

GetNextSendAtOk returns a tuple with the NextSendAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextSendAt

`func (o *ProgramSenderRef) SetNextSendAt(v interface{})`

SetNextSendAt sets NextSendAt field to given value.

### HasNextSendAt

`func (o *ProgramSenderRef) HasNextSendAt() bool`

HasNextSendAt returns a boolean if a field has been set.

### SetNextSendAtNil

`func (o *ProgramSenderRef) SetNextSendAtNil(b bool)`

 SetNextSendAtNil sets the value for NextSendAt to be an explicit nil

### UnsetNextSendAt
`func (o *ProgramSenderRef) UnsetNextSendAt()`

UnsetNextSendAt ensures that no value is present for NextSendAt, not even an explicit nil
### GetQueued

`func (o *ProgramSenderRef) GetQueued() int32`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *ProgramSenderRef) GetQueuedOk() (*int32, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *ProgramSenderRef) SetQueued(v int32)`

SetQueued sets Queued field to given value.

### HasQueued

`func (o *ProgramSenderRef) HasQueued() bool`

HasQueued returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


