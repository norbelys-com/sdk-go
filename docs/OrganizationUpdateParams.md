# OrganizationUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Alerts** | Pointer to [**OrganizationAlertsParams**](OrganizationAlertsParams.md) |  | [optional] 
**BouncePolicy** | Pointer to [**OrganizationBouncePolicyParams**](OrganizationBouncePolicyParams.md) |  | [optional] 
**Complete** | Pointer to **bool** | Mark onboarding complete (only applied once the organization is provisioned). | [optional] 
**Profile** | Pointer to [**OrganizationProfileParams**](OrganizationProfileParams.md) |  | [optional] 

## Methods

### NewOrganizationUpdateParams

`func NewOrganizationUpdateParams() *OrganizationUpdateParams`

NewOrganizationUpdateParams instantiates a new OrganizationUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationUpdateParamsWithDefaults

`func NewOrganizationUpdateParamsWithDefaults() *OrganizationUpdateParams`

NewOrganizationUpdateParamsWithDefaults instantiates a new OrganizationUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlerts

`func (o *OrganizationUpdateParams) GetAlerts() OrganizationAlertsParams`

GetAlerts returns the Alerts field if non-nil, zero value otherwise.

### GetAlertsOk

`func (o *OrganizationUpdateParams) GetAlertsOk() (*OrganizationAlertsParams, bool)`

GetAlertsOk returns a tuple with the Alerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlerts

`func (o *OrganizationUpdateParams) SetAlerts(v OrganizationAlertsParams)`

SetAlerts sets Alerts field to given value.

### HasAlerts

`func (o *OrganizationUpdateParams) HasAlerts() bool`

HasAlerts returns a boolean if a field has been set.

### GetBouncePolicy

`func (o *OrganizationUpdateParams) GetBouncePolicy() OrganizationBouncePolicyParams`

GetBouncePolicy returns the BouncePolicy field if non-nil, zero value otherwise.

### GetBouncePolicyOk

`func (o *OrganizationUpdateParams) GetBouncePolicyOk() (*OrganizationBouncePolicyParams, bool)`

GetBouncePolicyOk returns a tuple with the BouncePolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePolicy

`func (o *OrganizationUpdateParams) SetBouncePolicy(v OrganizationBouncePolicyParams)`

SetBouncePolicy sets BouncePolicy field to given value.

### HasBouncePolicy

`func (o *OrganizationUpdateParams) HasBouncePolicy() bool`

HasBouncePolicy returns a boolean if a field has been set.

### GetComplete

`func (o *OrganizationUpdateParams) GetComplete() bool`

GetComplete returns the Complete field if non-nil, zero value otherwise.

### GetCompleteOk

`func (o *OrganizationUpdateParams) GetCompleteOk() (*bool, bool)`

GetCompleteOk returns a tuple with the Complete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplete

`func (o *OrganizationUpdateParams) SetComplete(v bool)`

SetComplete sets Complete field to given value.

### HasComplete

`func (o *OrganizationUpdateParams) HasComplete() bool`

HasComplete returns a boolean if a field has been set.

### GetProfile

`func (o *OrganizationUpdateParams) GetProfile() OrganizationProfileParams`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *OrganizationUpdateParams) GetProfileOk() (*OrganizationProfileParams, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *OrganizationUpdateParams) SetProfile(v OrganizationProfileParams)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *OrganizationUpdateParams) HasProfile() bool`

HasProfile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


