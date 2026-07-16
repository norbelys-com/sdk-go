# AudienceActivityLinkFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Op** | [**AudienceActivityLinkMatchOp**](AudienceActivityLinkMatchOp.md) |  | 
**Value** | **string** | The URL (or fragment) the click must match. | 

## Methods

### NewAudienceActivityLinkFilter

`func NewAudienceActivityLinkFilter(op AudienceActivityLinkMatchOp, value string, ) *AudienceActivityLinkFilter`

NewAudienceActivityLinkFilter instantiates a new AudienceActivityLinkFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceActivityLinkFilterWithDefaults

`func NewAudienceActivityLinkFilterWithDefaults() *AudienceActivityLinkFilter`

NewAudienceActivityLinkFilterWithDefaults instantiates a new AudienceActivityLinkFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOp

`func (o *AudienceActivityLinkFilter) GetOp() AudienceActivityLinkMatchOp`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *AudienceActivityLinkFilter) GetOpOk() (*AudienceActivityLinkMatchOp, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *AudienceActivityLinkFilter) SetOp(v AudienceActivityLinkMatchOp)`

SetOp sets Op field to given value.


### GetValue

`func (o *AudienceActivityLinkFilter) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AudienceActivityLinkFilter) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AudienceActivityLinkFilter) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


