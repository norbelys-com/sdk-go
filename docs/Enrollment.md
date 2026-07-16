# Enrollment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**AssignedSenderId** | **NullableString** |  | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**CurrentStepId** | **NullableString** |  | 
**Id** | **string** | The enrollment id. | 
**NextSendAt** | Pointer to **interface{}** |  | [optional] 
**Object** | Pointer to **interface{}** |  | [optional] 
**PersonId** | **string** | The enrolled person&#39;s id. | 
**ProgramId** | **string** | The owning program&#39;s id. | 
**Status** | **string** | Lifecycle status: &#x60;active&#x60;, &#x60;replied&#x60;, &#x60;bounced&#x60;, &#x60;unsubscribed&#x60;, &#x60;finished&#x60;, &#x60;skipped&#x60;, &#x60;stopped&#x60;, &#x60;cancelled&#x60;, &#x60;paused&#x60;. | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 
**Person** | [**NullableEnrollmentPersonRef**](EnrollmentPersonRef.md) |  | 
**Program** | [**NullableEnrollmentProgramRef**](EnrollmentProgramRef.md) |  | 

## Methods

### NewEnrollment

`func NewEnrollment(assignedSenderId NullableString, currentStepId NullableString, id string, personId string, programId string, status string, person NullableEnrollmentPersonRef, program NullableEnrollmentProgramRef, ) *Enrollment`

NewEnrollment instantiates a new Enrollment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrollmentWithDefaults

`func NewEnrollmentWithDefaults() *Enrollment`

NewEnrollmentWithDefaults instantiates a new Enrollment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *Enrollment) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Enrollment) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Enrollment) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Enrollment) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Enrollment) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Enrollment) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAssignedSenderId

`func (o *Enrollment) GetAssignedSenderId() string`

GetAssignedSenderId returns the AssignedSenderId field if non-nil, zero value otherwise.

### GetAssignedSenderIdOk

`func (o *Enrollment) GetAssignedSenderIdOk() (*string, bool)`

GetAssignedSenderIdOk returns a tuple with the AssignedSenderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedSenderId

`func (o *Enrollment) SetAssignedSenderId(v string)`

SetAssignedSenderId sets AssignedSenderId field to given value.


### SetAssignedSenderIdNil

`func (o *Enrollment) SetAssignedSenderIdNil(b bool)`

 SetAssignedSenderIdNil sets the value for AssignedSenderId to be an explicit nil

### UnsetAssignedSenderId
`func (o *Enrollment) UnsetAssignedSenderId()`

UnsetAssignedSenderId ensures that no value is present for AssignedSenderId, not even an explicit nil
### GetCreatedAt

`func (o *Enrollment) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Enrollment) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Enrollment) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Enrollment) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Enrollment) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Enrollment) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetCurrentStepId

`func (o *Enrollment) GetCurrentStepId() string`

GetCurrentStepId returns the CurrentStepId field if non-nil, zero value otherwise.

### GetCurrentStepIdOk

`func (o *Enrollment) GetCurrentStepIdOk() (*string, bool)`

GetCurrentStepIdOk returns a tuple with the CurrentStepId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStepId

`func (o *Enrollment) SetCurrentStepId(v string)`

SetCurrentStepId sets CurrentStepId field to given value.


### SetCurrentStepIdNil

`func (o *Enrollment) SetCurrentStepIdNil(b bool)`

 SetCurrentStepIdNil sets the value for CurrentStepId to be an explicit nil

### UnsetCurrentStepId
`func (o *Enrollment) UnsetCurrentStepId()`

UnsetCurrentStepId ensures that no value is present for CurrentStepId, not even an explicit nil
### GetId

`func (o *Enrollment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Enrollment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Enrollment) SetId(v string)`

SetId sets Id field to given value.


### GetNextSendAt

`func (o *Enrollment) GetNextSendAt() interface{}`

GetNextSendAt returns the NextSendAt field if non-nil, zero value otherwise.

### GetNextSendAtOk

`func (o *Enrollment) GetNextSendAtOk() (*interface{}, bool)`

GetNextSendAtOk returns a tuple with the NextSendAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextSendAt

`func (o *Enrollment) SetNextSendAt(v interface{})`

SetNextSendAt sets NextSendAt field to given value.

### HasNextSendAt

`func (o *Enrollment) HasNextSendAt() bool`

HasNextSendAt returns a boolean if a field has been set.

### SetNextSendAtNil

`func (o *Enrollment) SetNextSendAtNil(b bool)`

 SetNextSendAtNil sets the value for NextSendAt to be an explicit nil

### UnsetNextSendAt
`func (o *Enrollment) UnsetNextSendAt()`

UnsetNextSendAt ensures that no value is present for NextSendAt, not even an explicit nil
### GetObject

`func (o *Enrollment) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Enrollment) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Enrollment) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Enrollment) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Enrollment) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Enrollment) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPersonId

`func (o *Enrollment) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *Enrollment) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *Enrollment) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### GetProgramId

`func (o *Enrollment) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *Enrollment) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *Enrollment) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetStatus

`func (o *Enrollment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Enrollment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Enrollment) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *Enrollment) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Enrollment) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Enrollment) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Enrollment) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Enrollment) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Enrollment) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetPerson

`func (o *Enrollment) GetPerson() EnrollmentPersonRef`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *Enrollment) GetPersonOk() (*EnrollmentPersonRef, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *Enrollment) SetPerson(v EnrollmentPersonRef)`

SetPerson sets Person field to given value.


### SetPersonNil

`func (o *Enrollment) SetPersonNil(b bool)`

 SetPersonNil sets the value for Person to be an explicit nil

### UnsetPerson
`func (o *Enrollment) UnsetPerson()`

UnsetPerson ensures that no value is present for Person, not even an explicit nil
### GetProgram

`func (o *Enrollment) GetProgram() EnrollmentProgramRef`

GetProgram returns the Program field if non-nil, zero value otherwise.

### GetProgramOk

`func (o *Enrollment) GetProgramOk() (*EnrollmentProgramRef, bool)`

GetProgramOk returns a tuple with the Program field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgram

`func (o *Enrollment) SetProgram(v EnrollmentProgramRef)`

SetProgram sets Program field to given value.


### SetProgramNil

`func (o *Enrollment) SetProgramNil(b bool)`

 SetProgramNil sets the value for Program to be an explicit nil

### UnsetProgram
`func (o *Enrollment) UnsetProgram()`

UnsetProgram ensures that no value is present for Program, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


