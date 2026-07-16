# OrganizationOnboarding

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Completed** | **bool** | Whether onboarding has been completed. | 
**CompletedAt** | **NullableFloat32** |  | 

## Methods

### NewOrganizationOnboarding

`func NewOrganizationOnboarding(completed bool, completedAt NullableFloat32, ) *OrganizationOnboarding`

NewOrganizationOnboarding instantiates a new OrganizationOnboarding object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationOnboardingWithDefaults

`func NewOrganizationOnboardingWithDefaults() *OrganizationOnboarding`

NewOrganizationOnboardingWithDefaults instantiates a new OrganizationOnboarding object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompleted

`func (o *OrganizationOnboarding) GetCompleted() bool`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *OrganizationOnboarding) GetCompletedOk() (*bool, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *OrganizationOnboarding) SetCompleted(v bool)`

SetCompleted sets Completed field to given value.


### GetCompletedAt

`func (o *OrganizationOnboarding) GetCompletedAt() float32`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *OrganizationOnboarding) GetCompletedAtOk() (*float32, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *OrganizationOnboarding) SetCompletedAt(v float32)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *OrganizationOnboarding) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *OrganizationOnboarding) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


