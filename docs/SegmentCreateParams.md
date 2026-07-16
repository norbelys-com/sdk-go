# SegmentCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Definition** | [**AudienceFilter**](AudienceFilter.md) | The audience filter that defines membership; its conditions are evaluated live against your people. | 
**Description** | Pointer to **string** | Optional notes on the segment&#39;s intent. | [optional] 
**Name** | **string** | The segment&#39;s display name. | 

## Methods

### NewSegmentCreateParams

`func NewSegmentCreateParams(definition AudienceFilter, name string, ) *SegmentCreateParams`

NewSegmentCreateParams instantiates a new SegmentCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSegmentCreateParamsWithDefaults

`func NewSegmentCreateParamsWithDefaults() *SegmentCreateParams`

NewSegmentCreateParamsWithDefaults instantiates a new SegmentCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefinition

`func (o *SegmentCreateParams) GetDefinition() AudienceFilter`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *SegmentCreateParams) GetDefinitionOk() (*AudienceFilter, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *SegmentCreateParams) SetDefinition(v AudienceFilter)`

SetDefinition sets Definition field to given value.


### GetDescription

`func (o *SegmentCreateParams) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SegmentCreateParams) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SegmentCreateParams) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SegmentCreateParams) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *SegmentCreateParams) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SegmentCreateParams) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SegmentCreateParams) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


