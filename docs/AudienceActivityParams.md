# AudienceActivityParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**AudienceActivityAction**](AudienceActivityAction.md) |  | 
**After** | Pointer to **float32** | Only count activity at/after this instant (epoch milliseconds). | [optional] 
**Before** | Pointer to **float32** | Only count activity before this instant (epoch milliseconds). | [optional] 
**CampaignIds** | Pointer to **[]string** | Scope to these campaigns (matches ANY of them). Omit for activity in any campaign. | [optional] 
**Link** | Pointer to [**AudienceActivityLinkFilter**](AudienceActivityLinkFilter.md) |  | [optional] 
**StepIds** | Pointer to **[]string** | Scope to these cadence steps (matches ANY of them). | [optional] 
**VariantIds** | Pointer to **[]string** | Scope to these A/B variants (matches ANY of them). | [optional] 
**WithinDays** | Pointer to **int32** | Only count activity in the last N days. | [optional] 

## Methods

### NewAudienceActivityParams

`func NewAudienceActivityParams(action AudienceActivityAction, ) *AudienceActivityParams`

NewAudienceActivityParams instantiates a new AudienceActivityParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceActivityParamsWithDefaults

`func NewAudienceActivityParamsWithDefaults() *AudienceActivityParams`

NewAudienceActivityParamsWithDefaults instantiates a new AudienceActivityParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AudienceActivityParams) GetAction() AudienceActivityAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AudienceActivityParams) GetActionOk() (*AudienceActivityAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AudienceActivityParams) SetAction(v AudienceActivityAction)`

SetAction sets Action field to given value.


### GetAfter

`func (o *AudienceActivityParams) GetAfter() float32`

GetAfter returns the After field if non-nil, zero value otherwise.

### GetAfterOk

`func (o *AudienceActivityParams) GetAfterOk() (*float32, bool)`

GetAfterOk returns a tuple with the After field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAfter

`func (o *AudienceActivityParams) SetAfter(v float32)`

SetAfter sets After field to given value.

### HasAfter

`func (o *AudienceActivityParams) HasAfter() bool`

HasAfter returns a boolean if a field has been set.

### GetBefore

`func (o *AudienceActivityParams) GetBefore() float32`

GetBefore returns the Before field if non-nil, zero value otherwise.

### GetBeforeOk

`func (o *AudienceActivityParams) GetBeforeOk() (*float32, bool)`

GetBeforeOk returns a tuple with the Before field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBefore

`func (o *AudienceActivityParams) SetBefore(v float32)`

SetBefore sets Before field to given value.

### HasBefore

`func (o *AudienceActivityParams) HasBefore() bool`

HasBefore returns a boolean if a field has been set.

### GetCampaignIds

`func (o *AudienceActivityParams) GetCampaignIds() []string`

GetCampaignIds returns the CampaignIds field if non-nil, zero value otherwise.

### GetCampaignIdsOk

`func (o *AudienceActivityParams) GetCampaignIdsOk() (*[]string, bool)`

GetCampaignIdsOk returns a tuple with the CampaignIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignIds

`func (o *AudienceActivityParams) SetCampaignIds(v []string)`

SetCampaignIds sets CampaignIds field to given value.

### HasCampaignIds

`func (o *AudienceActivityParams) HasCampaignIds() bool`

HasCampaignIds returns a boolean if a field has been set.

### GetLink

`func (o *AudienceActivityParams) GetLink() AudienceActivityLinkFilter`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *AudienceActivityParams) GetLinkOk() (*AudienceActivityLinkFilter, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *AudienceActivityParams) SetLink(v AudienceActivityLinkFilter)`

SetLink sets Link field to given value.

### HasLink

`func (o *AudienceActivityParams) HasLink() bool`

HasLink returns a boolean if a field has been set.

### GetStepIds

`func (o *AudienceActivityParams) GetStepIds() []string`

GetStepIds returns the StepIds field if non-nil, zero value otherwise.

### GetStepIdsOk

`func (o *AudienceActivityParams) GetStepIdsOk() (*[]string, bool)`

GetStepIdsOk returns a tuple with the StepIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepIds

`func (o *AudienceActivityParams) SetStepIds(v []string)`

SetStepIds sets StepIds field to given value.

### HasStepIds

`func (o *AudienceActivityParams) HasStepIds() bool`

HasStepIds returns a boolean if a field has been set.

### GetVariantIds

`func (o *AudienceActivityParams) GetVariantIds() []string`

GetVariantIds returns the VariantIds field if non-nil, zero value otherwise.

### GetVariantIdsOk

`func (o *AudienceActivityParams) GetVariantIdsOk() (*[]string, bool)`

GetVariantIdsOk returns a tuple with the VariantIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantIds

`func (o *AudienceActivityParams) SetVariantIds(v []string)`

SetVariantIds sets VariantIds field to given value.

### HasVariantIds

`func (o *AudienceActivityParams) HasVariantIds() bool`

HasVariantIds returns a boolean if a field has been set.

### GetWithinDays

`func (o *AudienceActivityParams) GetWithinDays() int32`

GetWithinDays returns the WithinDays field if non-nil, zero value otherwise.

### GetWithinDaysOk

`func (o *AudienceActivityParams) GetWithinDaysOk() (*int32, bool)`

GetWithinDaysOk returns a tuple with the WithinDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithinDays

`func (o *AudienceActivityParams) SetWithinDays(v int32)`

SetWithinDays sets WithinDays field to given value.

### HasWithinDays

`func (o *AudienceActivityParams) HasWithinDays() bool`

HasWithinDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


