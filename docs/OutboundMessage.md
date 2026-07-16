# OutboundMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactEmail** | **NullableString** |  | 
**ContactName** | **NullableString** |  | 
**Id** | **string** | The message id. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**OccurredAt** | Pointer to **interface{}** |  | [optional] 
**PersonId** | **NullableString** |  | 
**SenderId** | **NullableString** |  | 
**Subject** | **NullableString** |  | 
**ThreadId** | **NullableString** |  | 
**Channel** | **string** | Outbound channel: email, call, sms, or linkedin. | 
**Direction** | **interface{}** |  | 
**IsTest** | **bool** | A test/probe send — surfaced in the log but excluded from campaign rates. | 
**ProgramId** | **NullableString** |  | 
**Status** | **string** | Delivery status: queued, sent, delivered, failed, bounced, or cancelled. | 
**StepId** | **NullableString** |  | 

## Methods

### NewOutboundMessage

`func NewOutboundMessage(contactEmail NullableString, contactName NullableString, id string, personId NullableString, senderId NullableString, subject NullableString, threadId NullableString, channel string, direction interface{}, isTest bool, programId NullableString, status string, stepId NullableString, ) *OutboundMessage`

NewOutboundMessage instantiates a new OutboundMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundMessageWithDefaults

`func NewOutboundMessageWithDefaults() *OutboundMessage`

NewOutboundMessageWithDefaults instantiates a new OutboundMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactEmail

`func (o *OutboundMessage) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *OutboundMessage) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *OutboundMessage) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.


### SetContactEmailNil

`func (o *OutboundMessage) SetContactEmailNil(b bool)`

 SetContactEmailNil sets the value for ContactEmail to be an explicit nil

### UnsetContactEmail
`func (o *OutboundMessage) UnsetContactEmail()`

UnsetContactEmail ensures that no value is present for ContactEmail, not even an explicit nil
### GetContactName

`func (o *OutboundMessage) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *OutboundMessage) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *OutboundMessage) SetContactName(v string)`

SetContactName sets ContactName field to given value.


### SetContactNameNil

`func (o *OutboundMessage) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *OutboundMessage) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetId

`func (o *OutboundMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OutboundMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OutboundMessage) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *OutboundMessage) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *OutboundMessage) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *OutboundMessage) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *OutboundMessage) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *OutboundMessage) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *OutboundMessage) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetOccurredAt

`func (o *OutboundMessage) GetOccurredAt() interface{}`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *OutboundMessage) GetOccurredAtOk() (*interface{}, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *OutboundMessage) SetOccurredAt(v interface{})`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *OutboundMessage) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *OutboundMessage) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *OutboundMessage) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil
### GetPersonId

`func (o *OutboundMessage) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *OutboundMessage) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *OutboundMessage) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### SetPersonIdNil

`func (o *OutboundMessage) SetPersonIdNil(b bool)`

 SetPersonIdNil sets the value for PersonId to be an explicit nil

### UnsetPersonId
`func (o *OutboundMessage) UnsetPersonId()`

UnsetPersonId ensures that no value is present for PersonId, not even an explicit nil
### GetSenderId

`func (o *OutboundMessage) GetSenderId() string`

GetSenderId returns the SenderId field if non-nil, zero value otherwise.

### GetSenderIdOk

`func (o *OutboundMessage) GetSenderIdOk() (*string, bool)`

GetSenderIdOk returns a tuple with the SenderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderId

`func (o *OutboundMessage) SetSenderId(v string)`

SetSenderId sets SenderId field to given value.


### SetSenderIdNil

`func (o *OutboundMessage) SetSenderIdNil(b bool)`

 SetSenderIdNil sets the value for SenderId to be an explicit nil

### UnsetSenderId
`func (o *OutboundMessage) UnsetSenderId()`

UnsetSenderId ensures that no value is present for SenderId, not even an explicit nil
### GetSubject

`func (o *OutboundMessage) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *OutboundMessage) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *OutboundMessage) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *OutboundMessage) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *OutboundMessage) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetThreadId

`func (o *OutboundMessage) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *OutboundMessage) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *OutboundMessage) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### SetThreadIdNil

`func (o *OutboundMessage) SetThreadIdNil(b bool)`

 SetThreadIdNil sets the value for ThreadId to be an explicit nil

### UnsetThreadId
`func (o *OutboundMessage) UnsetThreadId()`

UnsetThreadId ensures that no value is present for ThreadId, not even an explicit nil
### GetChannel

`func (o *OutboundMessage) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *OutboundMessage) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *OutboundMessage) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetDirection

`func (o *OutboundMessage) GetDirection() interface{}`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *OutboundMessage) GetDirectionOk() (*interface{}, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *OutboundMessage) SetDirection(v interface{})`

SetDirection sets Direction field to given value.


### SetDirectionNil

`func (o *OutboundMessage) SetDirectionNil(b bool)`

 SetDirectionNil sets the value for Direction to be an explicit nil

### UnsetDirection
`func (o *OutboundMessage) UnsetDirection()`

UnsetDirection ensures that no value is present for Direction, not even an explicit nil
### GetIsTest

`func (o *OutboundMessage) GetIsTest() bool`

GetIsTest returns the IsTest field if non-nil, zero value otherwise.

### GetIsTestOk

`func (o *OutboundMessage) GetIsTestOk() (*bool, bool)`

GetIsTestOk returns a tuple with the IsTest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTest

`func (o *OutboundMessage) SetIsTest(v bool)`

SetIsTest sets IsTest field to given value.


### GetProgramId

`func (o *OutboundMessage) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *OutboundMessage) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *OutboundMessage) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### SetProgramIdNil

`func (o *OutboundMessage) SetProgramIdNil(b bool)`

 SetProgramIdNil sets the value for ProgramId to be an explicit nil

### UnsetProgramId
`func (o *OutboundMessage) UnsetProgramId()`

UnsetProgramId ensures that no value is present for ProgramId, not even an explicit nil
### GetStatus

`func (o *OutboundMessage) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OutboundMessage) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OutboundMessage) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStepId

`func (o *OutboundMessage) GetStepId() string`

GetStepId returns the StepId field if non-nil, zero value otherwise.

### GetStepIdOk

`func (o *OutboundMessage) GetStepIdOk() (*string, bool)`

GetStepIdOk returns a tuple with the StepId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepId

`func (o *OutboundMessage) SetStepId(v string)`

SetStepId sets StepId field to given value.


### SetStepIdNil

`func (o *OutboundMessage) SetStepIdNil(b bool)`

 SetStepIdNil sets the value for StepId to be an explicit nil

### UnsetStepId
`func (o *OutboundMessage) UnsetStepId()`

UnsetStepId ensures that no value is present for StepId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


