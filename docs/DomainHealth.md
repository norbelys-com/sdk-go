# DomainHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reasons** | **[]string** | Human-readable reasons behind the current health state. | 
**RecommendedAction** | **NullableString** |  | 
**State** | **string** | Overall sending health: &#x60;unknown&#x60;, &#x60;healthy&#x60;, &#x60;degraded&#x60;, or &#x60;critical&#x60;. | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewDomainHealth

`func NewDomainHealth(reasons []string, recommendedAction NullableString, state string, ) *DomainHealth`

NewDomainHealth instantiates a new DomainHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainHealthWithDefaults

`func NewDomainHealthWithDefaults() *DomainHealth`

NewDomainHealthWithDefaults instantiates a new DomainHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReasons

`func (o *DomainHealth) GetReasons() []string`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *DomainHealth) GetReasonsOk() (*[]string, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *DomainHealth) SetReasons(v []string)`

SetReasons sets Reasons field to given value.


### GetRecommendedAction

`func (o *DomainHealth) GetRecommendedAction() string`

GetRecommendedAction returns the RecommendedAction field if non-nil, zero value otherwise.

### GetRecommendedActionOk

`func (o *DomainHealth) GetRecommendedActionOk() (*string, bool)`

GetRecommendedActionOk returns a tuple with the RecommendedAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedAction

`func (o *DomainHealth) SetRecommendedAction(v string)`

SetRecommendedAction sets RecommendedAction field to given value.


### SetRecommendedActionNil

`func (o *DomainHealth) SetRecommendedActionNil(b bool)`

 SetRecommendedActionNil sets the value for RecommendedAction to be an explicit nil

### UnsetRecommendedAction
`func (o *DomainHealth) UnsetRecommendedAction()`

UnsetRecommendedAction ensures that no value is present for RecommendedAction, not even an explicit nil
### GetState

`func (o *DomainHealth) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DomainHealth) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DomainHealth) SetState(v string)`

SetState sets State field to given value.


### GetUpdatedAt

`func (o *DomainHealth) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainHealth) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainHealth) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DomainHealth) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *DomainHealth) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *DomainHealth) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


