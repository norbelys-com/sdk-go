# AudienceActivityCondition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | [**AudienceActivityParams**](AudienceActivityParams.md) |  | 
**Did** | Pointer to **bool** | &#x60;true&#x60; &#x3D; the person DID this at least once; &#x60;false&#x60; &#x3D; the person did NOT (zero times). | [optional] [default to true]

## Methods

### NewAudienceActivityCondition

`func NewAudienceActivityCondition(activity AudienceActivityParams, ) *AudienceActivityCondition`

NewAudienceActivityCondition instantiates a new AudienceActivityCondition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceActivityConditionWithDefaults

`func NewAudienceActivityConditionWithDefaults() *AudienceActivityCondition`

NewAudienceActivityConditionWithDefaults instantiates a new AudienceActivityCondition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivity

`func (o *AudienceActivityCondition) GetActivity() AudienceActivityParams`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *AudienceActivityCondition) GetActivityOk() (*AudienceActivityParams, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *AudienceActivityCondition) SetActivity(v AudienceActivityParams)`

SetActivity sets Activity field to given value.


### GetDid

`func (o *AudienceActivityCondition) GetDid() bool`

GetDid returns the Did field if non-nil, zero value otherwise.

### GetDidOk

`func (o *AudienceActivityCondition) GetDidOk() (*bool, bool)`

GetDidOk returns a tuple with the Did field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDid

`func (o *AudienceActivityCondition) SetDid(v bool)`

SetDid sets Did field to given value.

### HasDid

`func (o *AudienceActivityCondition) HasDid() bool`

HasDid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


