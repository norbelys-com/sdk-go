# PersonImportReason

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | People in this (outcome, reason) bucket. | 
**Outcome** | **string** | Which outcome bucket this reason belongs to: &#x60;sendable&#x60;, &#x60;suppressed_new&#x60;, or &#x60;suppressed_existing&#x60;. | 
**ReasonCode** | **string** | Machine-readable reason for the verdict (typo_suspected · invalid_tld · disposable · no_mail_server · previously_bounced · spam_listed · role_account · …). | 

## Methods

### NewPersonImportReason

`func NewPersonImportReason(count int32, outcome string, reasonCode string, ) *PersonImportReason`

NewPersonImportReason instantiates a new PersonImportReason object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonImportReasonWithDefaults

`func NewPersonImportReasonWithDefaults() *PersonImportReason`

NewPersonImportReasonWithDefaults instantiates a new PersonImportReason object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *PersonImportReason) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PersonImportReason) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PersonImportReason) SetCount(v int32)`

SetCount sets Count field to given value.


### GetOutcome

`func (o *PersonImportReason) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *PersonImportReason) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *PersonImportReason) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetReasonCode

`func (o *PersonImportReason) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *PersonImportReason) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *PersonImportReason) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


