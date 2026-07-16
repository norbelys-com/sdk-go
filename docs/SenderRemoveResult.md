# SenderRemoveResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Outcome** | **string** | \&quot;deleted\&quot; (no history) or \&quot;archived\&quot; (history kept). | 
**Sender** | [**NullableSender**](Sender.md) |  | 

## Methods

### NewSenderRemoveResult

`func NewSenderRemoveResult(outcome string, sender NullableSender, ) *SenderRemoveResult`

NewSenderRemoveResult instantiates a new SenderRemoveResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRemoveResultWithDefaults

`func NewSenderRemoveResultWithDefaults() *SenderRemoveResult`

NewSenderRemoveResultWithDefaults instantiates a new SenderRemoveResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutcome

`func (o *SenderRemoveResult) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *SenderRemoveResult) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *SenderRemoveResult) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetSender

`func (o *SenderRemoveResult) GetSender() Sender`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRemoveResult) GetSenderOk() (*Sender, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRemoveResult) SetSender(v Sender)`

SetSender sets Sender field to given value.


### SetSenderNil

`func (o *SenderRemoveResult) SetSenderNil(b bool)`

 SetSenderNil sets the value for Sender to be an explicit nil

### UnsetSender
`func (o *SenderRemoveResult) UnsetSender()`

UnsetSender ensures that no value is present for Sender, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


