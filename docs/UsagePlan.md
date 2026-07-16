# UsagePlan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AiBudgetUsdMonthly** | **float32** | Monthly AI budget included with the plan, in USD. Example: 50. | 
**Name** | **string** | Plan display name. Example: \&quot;Growth\&quot;. | 
**Slug** | **string** | Plan slug: &#x60;starter&#x60;, &#x60;growth&#x60;, &#x60;scale&#x60;, or &#x60;none&#x60; (no paid plan). Example: &#x60;growth&#x60;. | 

## Methods

### NewUsagePlan

`func NewUsagePlan(aiBudgetUsdMonthly float32, name string, slug string, ) *UsagePlan`

NewUsagePlan instantiates a new UsagePlan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsagePlanWithDefaults

`func NewUsagePlanWithDefaults() *UsagePlan`

NewUsagePlanWithDefaults instantiates a new UsagePlan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAiBudgetUsdMonthly

`func (o *UsagePlan) GetAiBudgetUsdMonthly() float32`

GetAiBudgetUsdMonthly returns the AiBudgetUsdMonthly field if non-nil, zero value otherwise.

### GetAiBudgetUsdMonthlyOk

`func (o *UsagePlan) GetAiBudgetUsdMonthlyOk() (*float32, bool)`

GetAiBudgetUsdMonthlyOk returns a tuple with the AiBudgetUsdMonthly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiBudgetUsdMonthly

`func (o *UsagePlan) SetAiBudgetUsdMonthly(v float32)`

SetAiBudgetUsdMonthly sets AiBudgetUsdMonthly field to given value.


### GetName

`func (o *UsagePlan) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UsagePlan) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UsagePlan) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *UsagePlan) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *UsagePlan) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *UsagePlan) SetSlug(v string)`

SetSlug sets Slug field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


