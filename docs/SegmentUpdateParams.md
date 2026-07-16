# SegmentUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Definition** | Pointer to [**SegmentUpdateParamsDefinition**](SegmentUpdateParamsDefinition.md) |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **string** | New display name for the segment. | [optional] 

## Methods

### NewSegmentUpdateParams

`func NewSegmentUpdateParams() *SegmentUpdateParams`

NewSegmentUpdateParams instantiates a new SegmentUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSegmentUpdateParamsWithDefaults

`func NewSegmentUpdateParamsWithDefaults() *SegmentUpdateParams`

NewSegmentUpdateParamsWithDefaults instantiates a new SegmentUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefinition

`func (o *SegmentUpdateParams) GetDefinition() SegmentUpdateParamsDefinition`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *SegmentUpdateParams) GetDefinitionOk() (*SegmentUpdateParamsDefinition, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *SegmentUpdateParams) SetDefinition(v SegmentUpdateParamsDefinition)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *SegmentUpdateParams) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetDescription

`func (o *SegmentUpdateParams) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SegmentUpdateParams) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SegmentUpdateParams) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SegmentUpdateParams) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *SegmentUpdateParams) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SegmentUpdateParams) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *SegmentUpdateParams) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SegmentUpdateParams) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SegmentUpdateParams) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SegmentUpdateParams) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


