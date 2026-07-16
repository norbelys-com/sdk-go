# PeopleBulkCreateResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **int32** | Number of people actually inserted. | 
**Enrolled** | **int32** | Total enrollments created across all &#x60;campaignIds&#x60; (0 when none requested). | 
**FieldsDropped** | **int32** | Individual field VALUES dropped as invalid (an unparseable phone, a malformed &#x60;email&#x60;/&#x60;phone&#x60; custom-field value). The person was still imported — only the bad value was left out. | 
**Grouped** | **int32** | Total group memberships created across all &#x60;groupIds&#x60; (0 when none requested). | 
**Ids** | **[]string** | Ids of EVERY matched person (new + pre-existing), for enrolling the whole set. | 
**ImportId** | **string** | The import id — poll its verification stats at GET /v1/people/bulk/{importId}. | 
**Rejected** | **int32** | People dropped because the email was malformed — never inserted, and never fatal to the rest of the batch. | 
**Skipped** | **int32** | People skipped as duplicate emails (already exist). | 
**Updated** | **int32** | Existing people updated in place. 0 when &#x60;onConflict&#x60; is &#x60;skip&#x60;. | 

## Methods

### NewPeopleBulkCreateResult

`func NewPeopleBulkCreateResult(created int32, enrolled int32, fieldsDropped int32, grouped int32, ids []string, importId string, rejected int32, skipped int32, updated int32, ) *PeopleBulkCreateResult`

NewPeopleBulkCreateResult instantiates a new PeopleBulkCreateResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeopleBulkCreateResultWithDefaults

`func NewPeopleBulkCreateResultWithDefaults() *PeopleBulkCreateResult`

NewPeopleBulkCreateResultWithDefaults instantiates a new PeopleBulkCreateResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *PeopleBulkCreateResult) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PeopleBulkCreateResult) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PeopleBulkCreateResult) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetEnrolled

`func (o *PeopleBulkCreateResult) GetEnrolled() int32`

GetEnrolled returns the Enrolled field if non-nil, zero value otherwise.

### GetEnrolledOk

`func (o *PeopleBulkCreateResult) GetEnrolledOk() (*int32, bool)`

GetEnrolledOk returns a tuple with the Enrolled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrolled

`func (o *PeopleBulkCreateResult) SetEnrolled(v int32)`

SetEnrolled sets Enrolled field to given value.


### GetFieldsDropped

`func (o *PeopleBulkCreateResult) GetFieldsDropped() int32`

GetFieldsDropped returns the FieldsDropped field if non-nil, zero value otherwise.

### GetFieldsDroppedOk

`func (o *PeopleBulkCreateResult) GetFieldsDroppedOk() (*int32, bool)`

GetFieldsDroppedOk returns a tuple with the FieldsDropped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldsDropped

`func (o *PeopleBulkCreateResult) SetFieldsDropped(v int32)`

SetFieldsDropped sets FieldsDropped field to given value.


### GetGrouped

`func (o *PeopleBulkCreateResult) GetGrouped() int32`

GetGrouped returns the Grouped field if non-nil, zero value otherwise.

### GetGroupedOk

`func (o *PeopleBulkCreateResult) GetGroupedOk() (*int32, bool)`

GetGroupedOk returns a tuple with the Grouped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrouped

`func (o *PeopleBulkCreateResult) SetGrouped(v int32)`

SetGrouped sets Grouped field to given value.


### GetIds

`func (o *PeopleBulkCreateResult) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *PeopleBulkCreateResult) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *PeopleBulkCreateResult) SetIds(v []string)`

SetIds sets Ids field to given value.


### GetImportId

`func (o *PeopleBulkCreateResult) GetImportId() string`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *PeopleBulkCreateResult) GetImportIdOk() (*string, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *PeopleBulkCreateResult) SetImportId(v string)`

SetImportId sets ImportId field to given value.


### GetRejected

`func (o *PeopleBulkCreateResult) GetRejected() int32`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *PeopleBulkCreateResult) GetRejectedOk() (*int32, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *PeopleBulkCreateResult) SetRejected(v int32)`

SetRejected sets Rejected field to given value.


### GetSkipped

`func (o *PeopleBulkCreateResult) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *PeopleBulkCreateResult) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *PeopleBulkCreateResult) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.


### GetUpdated

`func (o *PeopleBulkCreateResult) GetUpdated() int32`

GetUpdated returns the Updated field if non-nil, zero value otherwise.

### GetUpdatedOk

`func (o *PeopleBulkCreateResult) GetUpdatedOk() (*int32, bool)`

GetUpdatedOk returns a tuple with the Updated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdated

`func (o *PeopleBulkCreateResult) SetUpdated(v int32)`

SetUpdated sets Updated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


