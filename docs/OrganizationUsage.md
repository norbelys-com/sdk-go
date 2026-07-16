# OrganizationUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Campaigns** | [**UsageMeter**](UsageMeter.md) |  | 
**Contacts** | [**UsageMeter**](UsageMeter.md) | Active (non-archived) people. | 
**Emails** | [**MonthlyEmailUsageMeter**](MonthlyEmailUsageMeter.md) |  | 
**Object** | **interface{}** |  | 
**Plan** | [**UsagePlan**](UsagePlan.md) |  | 

## Methods

### NewOrganizationUsage

`func NewOrganizationUsage(campaigns UsageMeter, contacts UsageMeter, emails MonthlyEmailUsageMeter, object interface{}, plan UsagePlan, ) *OrganizationUsage`

NewOrganizationUsage instantiates a new OrganizationUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationUsageWithDefaults

`func NewOrganizationUsageWithDefaults() *OrganizationUsage`

NewOrganizationUsageWithDefaults instantiates a new OrganizationUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaigns

`func (o *OrganizationUsage) GetCampaigns() UsageMeter`

GetCampaigns returns the Campaigns field if non-nil, zero value otherwise.

### GetCampaignsOk

`func (o *OrganizationUsage) GetCampaignsOk() (*UsageMeter, bool)`

GetCampaignsOk returns a tuple with the Campaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaigns

`func (o *OrganizationUsage) SetCampaigns(v UsageMeter)`

SetCampaigns sets Campaigns field to given value.


### GetContacts

`func (o *OrganizationUsage) GetContacts() UsageMeter`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *OrganizationUsage) GetContactsOk() (*UsageMeter, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *OrganizationUsage) SetContacts(v UsageMeter)`

SetContacts sets Contacts field to given value.


### GetEmails

`func (o *OrganizationUsage) GetEmails() MonthlyEmailUsageMeter`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *OrganizationUsage) GetEmailsOk() (*MonthlyEmailUsageMeter, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *OrganizationUsage) SetEmails(v MonthlyEmailUsageMeter)`

SetEmails sets Emails field to given value.


### GetObject

`func (o *OrganizationUsage) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *OrganizationUsage) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *OrganizationUsage) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *OrganizationUsage) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *OrganizationUsage) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPlan

`func (o *OrganizationUsage) GetPlan() UsagePlan`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *OrganizationUsage) GetPlanOk() (*UsagePlan, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *OrganizationUsage) SetPlan(v UsagePlan)`

SetPlan sets Plan field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


