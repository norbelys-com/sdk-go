# SuppressionBulkResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **int32** | How many addresses were newly suppressed (already-suppressed values are skipped). | 

## Methods

### NewSuppressionBulkResult

`func NewSuppressionBulkResult(created int32, ) *SuppressionBulkResult`

NewSuppressionBulkResult instantiates a new SuppressionBulkResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppressionBulkResultWithDefaults

`func NewSuppressionBulkResultWithDefaults() *SuppressionBulkResult`

NewSuppressionBulkResultWithDefaults instantiates a new SuppressionBulkResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *SuppressionBulkResult) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *SuppressionBulkResult) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *SuppressionBulkResult) SetCreated(v int32)`

SetCreated sets Created field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


