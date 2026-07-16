# OrganizationAlerts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deliverability** | **bool** | Email the org admin when a domain starts failing DMARC, DNS verification breaks, or a mailbox&#39;s reputation goes bad. Default: true. | 

## Methods

### NewOrganizationAlerts

`func NewOrganizationAlerts(deliverability bool, ) *OrganizationAlerts`

NewOrganizationAlerts instantiates a new OrganizationAlerts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationAlertsWithDefaults

`func NewOrganizationAlertsWithDefaults() *OrganizationAlerts`

NewOrganizationAlertsWithDefaults instantiates a new OrganizationAlerts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliverability

`func (o *OrganizationAlerts) GetDeliverability() bool`

GetDeliverability returns the Deliverability field if non-nil, zero value otherwise.

### GetDeliverabilityOk

`func (o *OrganizationAlerts) GetDeliverabilityOk() (*bool, bool)`

GetDeliverabilityOk returns a tuple with the Deliverability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverability

`func (o *OrganizationAlerts) SetDeliverability(v bool)`

SetDeliverability sets Deliverability field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


