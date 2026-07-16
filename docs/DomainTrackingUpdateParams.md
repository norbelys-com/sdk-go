# DomainTrackingUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedSendingDomainIds** | Pointer to **[]string** | Replace the set of sending domains routed through this tracking hostname. | [optional] 
**DesiredState** | Pointer to **string** | Set the target state: &#x60;active&#x60; or &#x60;disabled&#x60;. | [optional] 
**IsOrganizationDefault** | Pointer to **bool** | Make this the organization&#39;s default tracking domain. | [optional] 
**Label** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDomainTrackingUpdateParams

`func NewDomainTrackingUpdateParams() *DomainTrackingUpdateParams`

NewDomainTrackingUpdateParams instantiates a new DomainTrackingUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainTrackingUpdateParamsWithDefaults

`func NewDomainTrackingUpdateParamsWithDefaults() *DomainTrackingUpdateParams`

NewDomainTrackingUpdateParamsWithDefaults instantiates a new DomainTrackingUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedSendingDomainIds

`func (o *DomainTrackingUpdateParams) GetAssignedSendingDomainIds() []string`

GetAssignedSendingDomainIds returns the AssignedSendingDomainIds field if non-nil, zero value otherwise.

### GetAssignedSendingDomainIdsOk

`func (o *DomainTrackingUpdateParams) GetAssignedSendingDomainIdsOk() (*[]string, bool)`

GetAssignedSendingDomainIdsOk returns a tuple with the AssignedSendingDomainIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedSendingDomainIds

`func (o *DomainTrackingUpdateParams) SetAssignedSendingDomainIds(v []string)`

SetAssignedSendingDomainIds sets AssignedSendingDomainIds field to given value.

### HasAssignedSendingDomainIds

`func (o *DomainTrackingUpdateParams) HasAssignedSendingDomainIds() bool`

HasAssignedSendingDomainIds returns a boolean if a field has been set.

### GetDesiredState

`func (o *DomainTrackingUpdateParams) GetDesiredState() string`

GetDesiredState returns the DesiredState field if non-nil, zero value otherwise.

### GetDesiredStateOk

`func (o *DomainTrackingUpdateParams) GetDesiredStateOk() (*string, bool)`

GetDesiredStateOk returns a tuple with the DesiredState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredState

`func (o *DomainTrackingUpdateParams) SetDesiredState(v string)`

SetDesiredState sets DesiredState field to given value.

### HasDesiredState

`func (o *DomainTrackingUpdateParams) HasDesiredState() bool`

HasDesiredState returns a boolean if a field has been set.

### GetIsOrganizationDefault

`func (o *DomainTrackingUpdateParams) GetIsOrganizationDefault() bool`

GetIsOrganizationDefault returns the IsOrganizationDefault field if non-nil, zero value otherwise.

### GetIsOrganizationDefaultOk

`func (o *DomainTrackingUpdateParams) GetIsOrganizationDefaultOk() (*bool, bool)`

GetIsOrganizationDefaultOk returns a tuple with the IsOrganizationDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOrganizationDefault

`func (o *DomainTrackingUpdateParams) SetIsOrganizationDefault(v bool)`

SetIsOrganizationDefault sets IsOrganizationDefault field to given value.

### HasIsOrganizationDefault

`func (o *DomainTrackingUpdateParams) HasIsOrganizationDefault() bool`

HasIsOrganizationDefault returns a boolean if a field has been set.

### GetLabel

`func (o *DomainTrackingUpdateParams) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainTrackingUpdateParams) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainTrackingUpdateParams) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *DomainTrackingUpdateParams) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *DomainTrackingUpdateParams) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *DomainTrackingUpdateParams) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


