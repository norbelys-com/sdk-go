# EnrollProgramResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | **bool** | Whether the program is live after this enroll (true &#x3D; the new leads start sending). | 
**AlreadyEnrolled** | **int32** | How many of the resolved audience were already in this program and were skipped. | 
**Enrolled** | **int32** | Number of people newly enrolled. | 
**ProgramId** | **string** | The program id. | 
**SenderIds** | **[]string** | The program&#39;s attached mailboxes. | 
**Suppressed** | **int32** | How many of the resolved audience were excluded by the suppression list (unsubscribed, hard-bounced, or verified-undeliverable addresses never enter a campaign). | 

## Methods

### NewEnrollProgramResult

`func NewEnrollProgramResult(active bool, alreadyEnrolled int32, enrolled int32, programId string, senderIds []string, suppressed int32, ) *EnrollProgramResult`

NewEnrollProgramResult instantiates a new EnrollProgramResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrollProgramResultWithDefaults

`func NewEnrollProgramResultWithDefaults() *EnrollProgramResult`

NewEnrollProgramResultWithDefaults instantiates a new EnrollProgramResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *EnrollProgramResult) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *EnrollProgramResult) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *EnrollProgramResult) SetActive(v bool)`

SetActive sets Active field to given value.


### GetAlreadyEnrolled

`func (o *EnrollProgramResult) GetAlreadyEnrolled() int32`

GetAlreadyEnrolled returns the AlreadyEnrolled field if non-nil, zero value otherwise.

### GetAlreadyEnrolledOk

`func (o *EnrollProgramResult) GetAlreadyEnrolledOk() (*int32, bool)`

GetAlreadyEnrolledOk returns a tuple with the AlreadyEnrolled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlreadyEnrolled

`func (o *EnrollProgramResult) SetAlreadyEnrolled(v int32)`

SetAlreadyEnrolled sets AlreadyEnrolled field to given value.


### GetEnrolled

`func (o *EnrollProgramResult) GetEnrolled() int32`

GetEnrolled returns the Enrolled field if non-nil, zero value otherwise.

### GetEnrolledOk

`func (o *EnrollProgramResult) GetEnrolledOk() (*int32, bool)`

GetEnrolledOk returns a tuple with the Enrolled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrolled

`func (o *EnrollProgramResult) SetEnrolled(v int32)`

SetEnrolled sets Enrolled field to given value.


### GetProgramId

`func (o *EnrollProgramResult) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *EnrollProgramResult) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *EnrollProgramResult) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetSenderIds

`func (o *EnrollProgramResult) GetSenderIds() []string`

GetSenderIds returns the SenderIds field if non-nil, zero value otherwise.

### GetSenderIdsOk

`func (o *EnrollProgramResult) GetSenderIdsOk() (*[]string, bool)`

GetSenderIdsOk returns a tuple with the SenderIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderIds

`func (o *EnrollProgramResult) SetSenderIds(v []string)`

SetSenderIds sets SenderIds field to given value.


### GetSuppressed

`func (o *EnrollProgramResult) GetSuppressed() int32`

GetSuppressed returns the Suppressed field if non-nil, zero value otherwise.

### GetSuppressedOk

`func (o *EnrollProgramResult) GetSuppressedOk() (*int32, bool)`

GetSuppressedOk returns a tuple with the Suppressed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressed

`func (o *EnrollProgramResult) SetSuppressed(v int32)`

SetSuppressed sets Suppressed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


