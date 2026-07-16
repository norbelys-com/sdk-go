# VerifyResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckedAt** | **time.Time** | When this verdict was computed (RFC 3339). Verdicts are cached for 24h, so this can be up to a day old. | 
**Email** | **string** | The normalized (trimmed, lowercased) address that was checked. | 
**Mx** | [**VerifyMx**](VerifyMx.md) |  | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Reachability** | [**VerifyReachability**](VerifyReachability.md) |  | 
**Reason** | **string** | A short, human-readable explanation of the verdict. | 
**ReasonCode** | [**VerifyReasonCode**](VerifyReasonCode.md) |  | 
**Score** | **int32** | Quality and confidence score from 0 to 100; higher means more likely a real, deliverable address. | 
**Signals** | [**VerifySignals**](VerifySignals.md) |  | 
**SuggestedCorrection** | **NullableString** |  | 
**Syntax** | [**VerifySyntax**](VerifySyntax.md) |  | 

## Methods

### NewVerifyResult

`func NewVerifyResult(checkedAt time.Time, email string, mx VerifyMx, reachability VerifyReachability, reason string, reasonCode VerifyReasonCode, score int32, signals VerifySignals, suggestedCorrection NullableString, syntax VerifySyntax, ) *VerifyResult`

NewVerifyResult instantiates a new VerifyResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyResultWithDefaults

`func NewVerifyResultWithDefaults() *VerifyResult`

NewVerifyResultWithDefaults instantiates a new VerifyResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckedAt

`func (o *VerifyResult) GetCheckedAt() time.Time`

GetCheckedAt returns the CheckedAt field if non-nil, zero value otherwise.

### GetCheckedAtOk

`func (o *VerifyResult) GetCheckedAtOk() (*time.Time, bool)`

GetCheckedAtOk returns a tuple with the CheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedAt

`func (o *VerifyResult) SetCheckedAt(v time.Time)`

SetCheckedAt sets CheckedAt field to given value.


### GetEmail

`func (o *VerifyResult) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *VerifyResult) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *VerifyResult) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetMx

`func (o *VerifyResult) GetMx() VerifyMx`

GetMx returns the Mx field if non-nil, zero value otherwise.

### GetMxOk

`func (o *VerifyResult) GetMxOk() (*VerifyMx, bool)`

GetMxOk returns a tuple with the Mx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMx

`func (o *VerifyResult) SetMx(v VerifyMx)`

SetMx sets Mx field to given value.


### GetObject

`func (o *VerifyResult) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *VerifyResult) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *VerifyResult) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *VerifyResult) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *VerifyResult) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *VerifyResult) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetReachability

`func (o *VerifyResult) GetReachability() VerifyReachability`

GetReachability returns the Reachability field if non-nil, zero value otherwise.

### GetReachabilityOk

`func (o *VerifyResult) GetReachabilityOk() (*VerifyReachability, bool)`

GetReachabilityOk returns a tuple with the Reachability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReachability

`func (o *VerifyResult) SetReachability(v VerifyReachability)`

SetReachability sets Reachability field to given value.


### GetReason

`func (o *VerifyResult) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *VerifyResult) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *VerifyResult) SetReason(v string)`

SetReason sets Reason field to given value.


### GetReasonCode

`func (o *VerifyResult) GetReasonCode() VerifyReasonCode`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *VerifyResult) GetReasonCodeOk() (*VerifyReasonCode, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *VerifyResult) SetReasonCode(v VerifyReasonCode)`

SetReasonCode sets ReasonCode field to given value.


### GetScore

`func (o *VerifyResult) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *VerifyResult) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *VerifyResult) SetScore(v int32)`

SetScore sets Score field to given value.


### GetSignals

`func (o *VerifyResult) GetSignals() VerifySignals`

GetSignals returns the Signals field if non-nil, zero value otherwise.

### GetSignalsOk

`func (o *VerifyResult) GetSignalsOk() (*VerifySignals, bool)`

GetSignalsOk returns a tuple with the Signals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignals

`func (o *VerifyResult) SetSignals(v VerifySignals)`

SetSignals sets Signals field to given value.


### GetSuggestedCorrection

`func (o *VerifyResult) GetSuggestedCorrection() string`

GetSuggestedCorrection returns the SuggestedCorrection field if non-nil, zero value otherwise.

### GetSuggestedCorrectionOk

`func (o *VerifyResult) GetSuggestedCorrectionOk() (*string, bool)`

GetSuggestedCorrectionOk returns a tuple with the SuggestedCorrection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedCorrection

`func (o *VerifyResult) SetSuggestedCorrection(v string)`

SetSuggestedCorrection sets SuggestedCorrection field to given value.


### SetSuggestedCorrectionNil

`func (o *VerifyResult) SetSuggestedCorrectionNil(b bool)`

 SetSuggestedCorrectionNil sets the value for SuggestedCorrection to be an explicit nil

### UnsetSuggestedCorrection
`func (o *VerifyResult) UnsetSuggestedCorrection()`

UnsetSuggestedCorrection ensures that no value is present for SuggestedCorrection, not even an explicit nil
### GetSyntax

`func (o *VerifyResult) GetSyntax() VerifySyntax`

GetSyntax returns the Syntax field if non-nil, zero value otherwise.

### GetSyntaxOk

`func (o *VerifyResult) GetSyntaxOk() (*VerifySyntax, bool)`

GetSyntaxOk returns a tuple with the Syntax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyntax

`func (o *VerifyResult) SetSyntax(v VerifySyntax)`

SetSyntax sets Syntax field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


