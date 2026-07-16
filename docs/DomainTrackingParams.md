# DomainTrackingParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedSendingDomainIds** | Pointer to **[]string** | Sending domains to route through this tracking hostname. Defaults to an empty list. | [optional] [default to []]
**IsOrganizationDefault** | Pointer to **bool** | Make this the organization&#39;s default tracking domain. Defaults to false. | [optional] [default to false]
**Label** | Pointer to **string** | Optional operator-facing label for this tracking domain. | [optional] 

## Methods

### NewDomainTrackingParams

`func NewDomainTrackingParams() *DomainTrackingParams`

NewDomainTrackingParams instantiates a new DomainTrackingParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainTrackingParamsWithDefaults

`func NewDomainTrackingParamsWithDefaults() *DomainTrackingParams`

NewDomainTrackingParamsWithDefaults instantiates a new DomainTrackingParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedSendingDomainIds

`func (o *DomainTrackingParams) GetAssignedSendingDomainIds() []string`

GetAssignedSendingDomainIds returns the AssignedSendingDomainIds field if non-nil, zero value otherwise.

### GetAssignedSendingDomainIdsOk

`func (o *DomainTrackingParams) GetAssignedSendingDomainIdsOk() (*[]string, bool)`

GetAssignedSendingDomainIdsOk returns a tuple with the AssignedSendingDomainIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedSendingDomainIds

`func (o *DomainTrackingParams) SetAssignedSendingDomainIds(v []string)`

SetAssignedSendingDomainIds sets AssignedSendingDomainIds field to given value.

### HasAssignedSendingDomainIds

`func (o *DomainTrackingParams) HasAssignedSendingDomainIds() bool`

HasAssignedSendingDomainIds returns a boolean if a field has been set.

### GetIsOrganizationDefault

`func (o *DomainTrackingParams) GetIsOrganizationDefault() bool`

GetIsOrganizationDefault returns the IsOrganizationDefault field if non-nil, zero value otherwise.

### GetIsOrganizationDefaultOk

`func (o *DomainTrackingParams) GetIsOrganizationDefaultOk() (*bool, bool)`

GetIsOrganizationDefaultOk returns a tuple with the IsOrganizationDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOrganizationDefault

`func (o *DomainTrackingParams) SetIsOrganizationDefault(v bool)`

SetIsOrganizationDefault sets IsOrganizationDefault field to given value.

### HasIsOrganizationDefault

`func (o *DomainTrackingParams) HasIsOrganizationDefault() bool`

HasIsOrganizationDefault returns a boolean if a field has been set.

### GetLabel

`func (o *DomainTrackingParams) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainTrackingParams) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainTrackingParams) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *DomainTrackingParams) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


