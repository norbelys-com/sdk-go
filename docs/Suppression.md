# Suppression

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**EmailOrDomain** | **string** | The suppressed email address or bare domain. | 
**Id** | **string** | The suppression id. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**ProgramId** | **NullableString** |  | 
**Reason** | **NullableString** |  | 
**Scope** | [**SuppressionScope**](SuppressionScope.md) |  | 

## Methods

### NewSuppression

`func NewSuppression(emailOrDomain string, id string, programId NullableString, reason NullableString, scope SuppressionScope, ) *Suppression`

NewSuppression instantiates a new Suppression object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppressionWithDefaults

`func NewSuppressionWithDefaults() *Suppression`

NewSuppressionWithDefaults instantiates a new Suppression object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *Suppression) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Suppression) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Suppression) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Suppression) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Suppression) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Suppression) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCreatedAt

`func (o *Suppression) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Suppression) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Suppression) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Suppression) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Suppression) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Suppression) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetEmailOrDomain

`func (o *Suppression) GetEmailOrDomain() string`

GetEmailOrDomain returns the EmailOrDomain field if non-nil, zero value otherwise.

### GetEmailOrDomainOk

`func (o *Suppression) GetEmailOrDomainOk() (*string, bool)`

GetEmailOrDomainOk returns a tuple with the EmailOrDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailOrDomain

`func (o *Suppression) SetEmailOrDomain(v string)`

SetEmailOrDomain sets EmailOrDomain field to given value.


### GetId

`func (o *Suppression) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Suppression) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Suppression) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *Suppression) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Suppression) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Suppression) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Suppression) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Suppression) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Suppression) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetProgramId

`func (o *Suppression) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *Suppression) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *Suppression) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### SetProgramIdNil

`func (o *Suppression) SetProgramIdNil(b bool)`

 SetProgramIdNil sets the value for ProgramId to be an explicit nil

### UnsetProgramId
`func (o *Suppression) UnsetProgramId()`

UnsetProgramId ensures that no value is present for ProgramId, not even an explicit nil
### GetReason

`func (o *Suppression) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *Suppression) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *Suppression) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *Suppression) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *Suppression) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetScope

`func (o *Suppression) GetScope() SuppressionScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *Suppression) GetScopeOk() (*SuppressionScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *Suppression) SetScope(v SuppressionScope)`

SetScope sets Scope field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


