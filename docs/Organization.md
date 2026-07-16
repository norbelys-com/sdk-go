# Organization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Alerts** | [**OrganizationAlerts**](OrganizationAlerts.md) |  | 
**BouncePolicy** | [**OrganizationBouncePolicy**](OrganizationBouncePolicy.md) |  | 
**Name** | **string** | The organization display name. | 
**Onboarding** | [**OrganizationOnboarding**](OrganizationOnboarding.md) |  | 
**OrgId** | **string** | The organization id. | 
**Profile** | [**OrganizationProfile**](OrganizationProfile.md) |  | 
**TenantReady** | **bool** | Whether the organization is fully provisioned and active. | 

## Methods

### NewOrganization

`func NewOrganization(alerts OrganizationAlerts, bouncePolicy OrganizationBouncePolicy, name string, onboarding OrganizationOnboarding, orgId string, profile OrganizationProfile, tenantReady bool, ) *Organization`

NewOrganization instantiates a new Organization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationWithDefaults

`func NewOrganizationWithDefaults() *Organization`

NewOrganizationWithDefaults instantiates a new Organization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlerts

`func (o *Organization) GetAlerts() OrganizationAlerts`

GetAlerts returns the Alerts field if non-nil, zero value otherwise.

### GetAlertsOk

`func (o *Organization) GetAlertsOk() (*OrganizationAlerts, bool)`

GetAlertsOk returns a tuple with the Alerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlerts

`func (o *Organization) SetAlerts(v OrganizationAlerts)`

SetAlerts sets Alerts field to given value.


### GetBouncePolicy

`func (o *Organization) GetBouncePolicy() OrganizationBouncePolicy`

GetBouncePolicy returns the BouncePolicy field if non-nil, zero value otherwise.

### GetBouncePolicyOk

`func (o *Organization) GetBouncePolicyOk() (*OrganizationBouncePolicy, bool)`

GetBouncePolicyOk returns a tuple with the BouncePolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBouncePolicy

`func (o *Organization) SetBouncePolicy(v OrganizationBouncePolicy)`

SetBouncePolicy sets BouncePolicy field to given value.


### GetName

`func (o *Organization) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Organization) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Organization) SetName(v string)`

SetName sets Name field to given value.


### GetOnboarding

`func (o *Organization) GetOnboarding() OrganizationOnboarding`

GetOnboarding returns the Onboarding field if non-nil, zero value otherwise.

### GetOnboardingOk

`func (o *Organization) GetOnboardingOk() (*OrganizationOnboarding, bool)`

GetOnboardingOk returns a tuple with the Onboarding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnboarding

`func (o *Organization) SetOnboarding(v OrganizationOnboarding)`

SetOnboarding sets Onboarding field to given value.


### GetOrgId

`func (o *Organization) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *Organization) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *Organization) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetProfile

`func (o *Organization) GetProfile() OrganizationProfile`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *Organization) GetProfileOk() (*OrganizationProfile, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *Organization) SetProfile(v OrganizationProfile)`

SetProfile sets Profile field to given value.


### GetTenantReady

`func (o *Organization) GetTenantReady() bool`

GetTenantReady returns the TenantReady field if non-nil, zero value otherwise.

### GetTenantReadyOk

`func (o *Organization) GetTenantReadyOk() (*bool, bool)`

GetTenantReadyOk returns a tuple with the TenantReady field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantReady

`func (o *Organization) SetTenantReady(v bool)`

SetTenantReady sets TenantReady field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


