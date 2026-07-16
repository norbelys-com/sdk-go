# InboundMessage

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
**AssigneeId** | **NullableString** |  | 
**BodyHtml** | **NullableString** |  | 
**BodyText** | **NullableString** |  | 
**Classification** | **string** | Triage class: interested, out_of_office, not_interested, auto_reply, bounce, complaint, unsubscribe, or uncategorized. | 
**Direction** | **interface{}** |  | 
**FromEmail** | **NullableString** |  | 
**IsRead** | **bool** | Whether the reply has been read. | 

## Methods

### NewInboundMessage

`func NewInboundMessage(contactEmail NullableString, contactName NullableString, id string, personId NullableString, senderId NullableString, subject NullableString, threadId NullableString, assigneeId NullableString, bodyHtml NullableString, bodyText NullableString, classification string, direction interface{}, fromEmail NullableString, isRead bool, ) *InboundMessage`

NewInboundMessage instantiates a new InboundMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundMessageWithDefaults

`func NewInboundMessageWithDefaults() *InboundMessage`

NewInboundMessageWithDefaults instantiates a new InboundMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactEmail

`func (o *InboundMessage) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *InboundMessage) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *InboundMessage) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.


### SetContactEmailNil

`func (o *InboundMessage) SetContactEmailNil(b bool)`

 SetContactEmailNil sets the value for ContactEmail to be an explicit nil

### UnsetContactEmail
`func (o *InboundMessage) UnsetContactEmail()`

UnsetContactEmail ensures that no value is present for ContactEmail, not even an explicit nil
### GetContactName

`func (o *InboundMessage) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *InboundMessage) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *InboundMessage) SetContactName(v string)`

SetContactName sets ContactName field to given value.


### SetContactNameNil

`func (o *InboundMessage) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *InboundMessage) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetId

`func (o *InboundMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InboundMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InboundMessage) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *InboundMessage) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *InboundMessage) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *InboundMessage) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *InboundMessage) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *InboundMessage) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *InboundMessage) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetOccurredAt

`func (o *InboundMessage) GetOccurredAt() interface{}`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *InboundMessage) GetOccurredAtOk() (*interface{}, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *InboundMessage) SetOccurredAt(v interface{})`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *InboundMessage) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *InboundMessage) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *InboundMessage) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil
### GetPersonId

`func (o *InboundMessage) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *InboundMessage) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *InboundMessage) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### SetPersonIdNil

`func (o *InboundMessage) SetPersonIdNil(b bool)`

 SetPersonIdNil sets the value for PersonId to be an explicit nil

### UnsetPersonId
`func (o *InboundMessage) UnsetPersonId()`

UnsetPersonId ensures that no value is present for PersonId, not even an explicit nil
### GetSenderId

`func (o *InboundMessage) GetSenderId() string`

GetSenderId returns the SenderId field if non-nil, zero value otherwise.

### GetSenderIdOk

`func (o *InboundMessage) GetSenderIdOk() (*string, bool)`

GetSenderIdOk returns a tuple with the SenderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderId

`func (o *InboundMessage) SetSenderId(v string)`

SetSenderId sets SenderId field to given value.


### SetSenderIdNil

`func (o *InboundMessage) SetSenderIdNil(b bool)`

 SetSenderIdNil sets the value for SenderId to be an explicit nil

### UnsetSenderId
`func (o *InboundMessage) UnsetSenderId()`

UnsetSenderId ensures that no value is present for SenderId, not even an explicit nil
### GetSubject

`func (o *InboundMessage) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *InboundMessage) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *InboundMessage) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *InboundMessage) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *InboundMessage) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetThreadId

`func (o *InboundMessage) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *InboundMessage) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *InboundMessage) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### SetThreadIdNil

`func (o *InboundMessage) SetThreadIdNil(b bool)`

 SetThreadIdNil sets the value for ThreadId to be an explicit nil

### UnsetThreadId
`func (o *InboundMessage) UnsetThreadId()`

UnsetThreadId ensures that no value is present for ThreadId, not even an explicit nil
### GetAssigneeId

`func (o *InboundMessage) GetAssigneeId() string`

GetAssigneeId returns the AssigneeId field if non-nil, zero value otherwise.

### GetAssigneeIdOk

`func (o *InboundMessage) GetAssigneeIdOk() (*string, bool)`

GetAssigneeIdOk returns a tuple with the AssigneeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssigneeId

`func (o *InboundMessage) SetAssigneeId(v string)`

SetAssigneeId sets AssigneeId field to given value.


### SetAssigneeIdNil

`func (o *InboundMessage) SetAssigneeIdNil(b bool)`

 SetAssigneeIdNil sets the value for AssigneeId to be an explicit nil

### UnsetAssigneeId
`func (o *InboundMessage) UnsetAssigneeId()`

UnsetAssigneeId ensures that no value is present for AssigneeId, not even an explicit nil
### GetBodyHtml

`func (o *InboundMessage) GetBodyHtml() string`

GetBodyHtml returns the BodyHtml field if non-nil, zero value otherwise.

### GetBodyHtmlOk

`func (o *InboundMessage) GetBodyHtmlOk() (*string, bool)`

GetBodyHtmlOk returns a tuple with the BodyHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBodyHtml

`func (o *InboundMessage) SetBodyHtml(v string)`

SetBodyHtml sets BodyHtml field to given value.


### SetBodyHtmlNil

`func (o *InboundMessage) SetBodyHtmlNil(b bool)`

 SetBodyHtmlNil sets the value for BodyHtml to be an explicit nil

### UnsetBodyHtml
`func (o *InboundMessage) UnsetBodyHtml()`

UnsetBodyHtml ensures that no value is present for BodyHtml, not even an explicit nil
### GetBodyText

`func (o *InboundMessage) GetBodyText() string`

GetBodyText returns the BodyText field if non-nil, zero value otherwise.

### GetBodyTextOk

`func (o *InboundMessage) GetBodyTextOk() (*string, bool)`

GetBodyTextOk returns a tuple with the BodyText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBodyText

`func (o *InboundMessage) SetBodyText(v string)`

SetBodyText sets BodyText field to given value.


### SetBodyTextNil

`func (o *InboundMessage) SetBodyTextNil(b bool)`

 SetBodyTextNil sets the value for BodyText to be an explicit nil

### UnsetBodyText
`func (o *InboundMessage) UnsetBodyText()`

UnsetBodyText ensures that no value is present for BodyText, not even an explicit nil
### GetClassification

`func (o *InboundMessage) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *InboundMessage) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *InboundMessage) SetClassification(v string)`

SetClassification sets Classification field to given value.


### GetDirection

`func (o *InboundMessage) GetDirection() interface{}`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *InboundMessage) GetDirectionOk() (*interface{}, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *InboundMessage) SetDirection(v interface{})`

SetDirection sets Direction field to given value.


### SetDirectionNil

`func (o *InboundMessage) SetDirectionNil(b bool)`

 SetDirectionNil sets the value for Direction to be an explicit nil

### UnsetDirection
`func (o *InboundMessage) UnsetDirection()`

UnsetDirection ensures that no value is present for Direction, not even an explicit nil
### GetFromEmail

`func (o *InboundMessage) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *InboundMessage) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *InboundMessage) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### SetFromEmailNil

`func (o *InboundMessage) SetFromEmailNil(b bool)`

 SetFromEmailNil sets the value for FromEmail to be an explicit nil

### UnsetFromEmail
`func (o *InboundMessage) UnsetFromEmail()`

UnsetFromEmail ensures that no value is present for FromEmail, not even an explicit nil
### GetIsRead

`func (o *InboundMessage) GetIsRead() bool`

GetIsRead returns the IsRead field if non-nil, zero value otherwise.

### GetIsReadOk

`func (o *InboundMessage) GetIsReadOk() (*bool, bool)`

GetIsReadOk returns a tuple with the IsRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRead

`func (o *InboundMessage) SetIsRead(v bool)`

SetIsRead sets IsRead field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


