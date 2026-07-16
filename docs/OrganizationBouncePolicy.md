# OrganizationBouncePolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StopOnSoftFailure** | **bool** | Stop a person&#39;s sequences when a delivery fails softly (mailbox full / over quota). Off &#x3D; only permanently-dead bounces stop the cadence. Default: true. | 
**SuppressOnSoftStop** | **bool** | When a soft failure stops the cadence, also add the address to the suppression list (block re-import/re-send). Default: false — the mailbox may clear, so the lead stays re-importable. | 

## Methods

### NewOrganizationBouncePolicy

`func NewOrganizationBouncePolicy(stopOnSoftFailure bool, suppressOnSoftStop bool, ) *OrganizationBouncePolicy`

NewOrganizationBouncePolicy instantiates a new OrganizationBouncePolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationBouncePolicyWithDefaults

`func NewOrganizationBouncePolicyWithDefaults() *OrganizationBouncePolicy`

NewOrganizationBouncePolicyWithDefaults instantiates a new OrganizationBouncePolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStopOnSoftFailure

`func (o *OrganizationBouncePolicy) GetStopOnSoftFailure() bool`

GetStopOnSoftFailure returns the StopOnSoftFailure field if non-nil, zero value otherwise.

### GetStopOnSoftFailureOk

`func (o *OrganizationBouncePolicy) GetStopOnSoftFailureOk() (*bool, bool)`

GetStopOnSoftFailureOk returns a tuple with the StopOnSoftFailure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnSoftFailure

`func (o *OrganizationBouncePolicy) SetStopOnSoftFailure(v bool)`

SetStopOnSoftFailure sets StopOnSoftFailure field to given value.


### GetSuppressOnSoftStop

`func (o *OrganizationBouncePolicy) GetSuppressOnSoftStop() bool`

GetSuppressOnSoftStop returns the SuppressOnSoftStop field if non-nil, zero value otherwise.

### GetSuppressOnSoftStopOk

`func (o *OrganizationBouncePolicy) GetSuppressOnSoftStopOk() (*bool, bool)`

GetSuppressOnSoftStopOk returns a tuple with the SuppressOnSoftStop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressOnSoftStop

`func (o *OrganizationBouncePolicy) SetSuppressOnSoftStop(v bool)`

SetSuppressOnSoftStop sets SuppressOnSoftStop field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


