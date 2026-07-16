# OrganizationUpdateParamsBouncePolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StopOnSoftFailure** | Pointer to **bool** | Stop sequences on a soft delivery failure (full / over-quota mailbox). | [optional] 
**SuppressOnSoftStop** | Pointer to **bool** | Also suppress the address when a soft failure stops it. | [optional] 

## Methods

### NewOrganizationUpdateParamsBouncePolicy

`func NewOrganizationUpdateParamsBouncePolicy() *OrganizationUpdateParamsBouncePolicy`

NewOrganizationUpdateParamsBouncePolicy instantiates a new OrganizationUpdateParamsBouncePolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationUpdateParamsBouncePolicyWithDefaults

`func NewOrganizationUpdateParamsBouncePolicyWithDefaults() *OrganizationUpdateParamsBouncePolicy`

NewOrganizationUpdateParamsBouncePolicyWithDefaults instantiates a new OrganizationUpdateParamsBouncePolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStopOnSoftFailure

`func (o *OrganizationUpdateParamsBouncePolicy) GetStopOnSoftFailure() bool`

GetStopOnSoftFailure returns the StopOnSoftFailure field if non-nil, zero value otherwise.

### GetStopOnSoftFailureOk

`func (o *OrganizationUpdateParamsBouncePolicy) GetStopOnSoftFailureOk() (*bool, bool)`

GetStopOnSoftFailureOk returns a tuple with the StopOnSoftFailure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnSoftFailure

`func (o *OrganizationUpdateParamsBouncePolicy) SetStopOnSoftFailure(v bool)`

SetStopOnSoftFailure sets StopOnSoftFailure field to given value.

### HasStopOnSoftFailure

`func (o *OrganizationUpdateParamsBouncePolicy) HasStopOnSoftFailure() bool`

HasStopOnSoftFailure returns a boolean if a field has been set.

### GetSuppressOnSoftStop

`func (o *OrganizationUpdateParamsBouncePolicy) GetSuppressOnSoftStop() bool`

GetSuppressOnSoftStop returns the SuppressOnSoftStop field if non-nil, zero value otherwise.

### GetSuppressOnSoftStopOk

`func (o *OrganizationUpdateParamsBouncePolicy) GetSuppressOnSoftStopOk() (*bool, bool)`

GetSuppressOnSoftStopOk returns a tuple with the SuppressOnSoftStop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressOnSoftStop

`func (o *OrganizationUpdateParamsBouncePolicy) SetSuppressOnSoftStop(v bool)`

SetSuppressOnSoftStop sets SuppressOnSoftStop field to given value.

### HasSuppressOnSoftStop

`func (o *OrganizationUpdateParamsBouncePolicy) HasSuppressOnSoftStop() bool`

HasSuppressOnSoftStop returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


