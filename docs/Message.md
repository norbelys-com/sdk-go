# Message

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactEmail** | **string** |  | 
**ContactName** | **string** |  | 
**Id** | **string** | The message id. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**OccurredAt** | Pointer to **interface{}** |  | [optional] 
**PersonId** | **string** |  | 
**SenderId** | **string** |  | 
**Subject** | **string** |  | 
**ThreadId** | **string** |  | 
**Channel** | **string** | Outbound channel: email, call, sms, or linkedin. | 
**Direction** | **interface{}** |  | 
**IsTest** | **bool** | A test/probe send — surfaced in the log but excluded from campaign rates. | 
**ProgramId** | **string** |  | 
**Status** | **string** | Delivery status: queued, sent, delivered, failed, bounced, or cancelled. | 
**StepId** | **string** |  | 
**AssigneeId** | **string** |  | 
**BodyHtml** | **string** |  | 
**BodyText** | **string** |  | 
**Classification** | **string** | Triage class: interested, out_of_office, not_interested, auto_reply, bounce, complaint, unsubscribe, or uncategorized. | 
**FromEmail** | **string** |  | 
**IsRead** | **bool** | Whether the reply has been read. | 

## Methods

### NewMessage

`func NewMessage(contactEmail string, contactName string, id string, personId string, senderId string, subject string, threadId string, channel string, direction interface{}, isTest bool, programId string, status string, stepId string, assigneeId string, bodyHtml string, bodyText string, classification string, fromEmail string, isRead bool, ) *Message`

NewMessage instantiates a new Message object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageWithDefaults

`func NewMessageWithDefaults() *Message`

NewMessageWithDefaults instantiates a new Message object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactEmail

`func (o *Message) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *Message) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *Message) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.


### GetContactName

`func (o *Message) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *Message) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *Message) SetContactName(v string)`

SetContactName sets ContactName field to given value.


### GetId

`func (o *Message) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Message) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Message) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *Message) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Message) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Message) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Message) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Message) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Message) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetOccurredAt

`func (o *Message) GetOccurredAt() interface{}`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *Message) GetOccurredAtOk() (*interface{}, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *Message) SetOccurredAt(v interface{})`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *Message) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *Message) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *Message) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil
### GetPersonId

`func (o *Message) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *Message) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *Message) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### GetSenderId

`func (o *Message) GetSenderId() string`

GetSenderId returns the SenderId field if non-nil, zero value otherwise.

### GetSenderIdOk

`func (o *Message) GetSenderIdOk() (*string, bool)`

GetSenderIdOk returns a tuple with the SenderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderId

`func (o *Message) SetSenderId(v string)`

SetSenderId sets SenderId field to given value.


### GetSubject

`func (o *Message) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *Message) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *Message) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetThreadId

`func (o *Message) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *Message) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *Message) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetChannel

`func (o *Message) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *Message) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *Message) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetDirection

`func (o *Message) GetDirection() interface{}`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *Message) GetDirectionOk() (*interface{}, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *Message) SetDirection(v interface{})`

SetDirection sets Direction field to given value.


### SetDirectionNil

`func (o *Message) SetDirectionNil(b bool)`

 SetDirectionNil sets the value for Direction to be an explicit nil

### UnsetDirection
`func (o *Message) UnsetDirection()`

UnsetDirection ensures that no value is present for Direction, not even an explicit nil
### GetIsTest

`func (o *Message) GetIsTest() bool`

GetIsTest returns the IsTest field if non-nil, zero value otherwise.

### GetIsTestOk

`func (o *Message) GetIsTestOk() (*bool, bool)`

GetIsTestOk returns a tuple with the IsTest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTest

`func (o *Message) SetIsTest(v bool)`

SetIsTest sets IsTest field to given value.


### GetProgramId

`func (o *Message) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *Message) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *Message) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetStatus

`func (o *Message) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Message) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Message) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStepId

`func (o *Message) GetStepId() string`

GetStepId returns the StepId field if non-nil, zero value otherwise.

### GetStepIdOk

`func (o *Message) GetStepIdOk() (*string, bool)`

GetStepIdOk returns a tuple with the StepId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepId

`func (o *Message) SetStepId(v string)`

SetStepId sets StepId field to given value.


### GetAssigneeId

`func (o *Message) GetAssigneeId() string`

GetAssigneeId returns the AssigneeId field if non-nil, zero value otherwise.

### GetAssigneeIdOk

`func (o *Message) GetAssigneeIdOk() (*string, bool)`

GetAssigneeIdOk returns a tuple with the AssigneeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssigneeId

`func (o *Message) SetAssigneeId(v string)`

SetAssigneeId sets AssigneeId field to given value.


### GetBodyHtml

`func (o *Message) GetBodyHtml() string`

GetBodyHtml returns the BodyHtml field if non-nil, zero value otherwise.

### GetBodyHtmlOk

`func (o *Message) GetBodyHtmlOk() (*string, bool)`

GetBodyHtmlOk returns a tuple with the BodyHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBodyHtml

`func (o *Message) SetBodyHtml(v string)`

SetBodyHtml sets BodyHtml field to given value.


### GetBodyText

`func (o *Message) GetBodyText() string`

GetBodyText returns the BodyText field if non-nil, zero value otherwise.

### GetBodyTextOk

`func (o *Message) GetBodyTextOk() (*string, bool)`

GetBodyTextOk returns a tuple with the BodyText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBodyText

`func (o *Message) SetBodyText(v string)`

SetBodyText sets BodyText field to given value.


### GetClassification

`func (o *Message) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *Message) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *Message) SetClassification(v string)`

SetClassification sets Classification field to given value.


### GetFromEmail

`func (o *Message) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *Message) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *Message) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### GetIsRead

`func (o *Message) GetIsRead() bool`

GetIsRead returns the IsRead field if non-nil, zero value otherwise.

### GetIsReadOk

`func (o *Message) GetIsReadOk() (*bool, bool)`

GetIsReadOk returns a tuple with the IsRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRead

`func (o *Message) SetIsRead(v bool)`

SetIsRead sets IsRead field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


