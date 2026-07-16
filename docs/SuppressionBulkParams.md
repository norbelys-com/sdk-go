# SuppressionBulkParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Emails** | **[]string** | Up to 10,000 email addresses or bare domains to suppress. | 
**Reason** | Pointer to **string** | Free-text note applied to every added entry. | [optional] 

## Methods

### NewSuppressionBulkParams

`func NewSuppressionBulkParams(emails []string, ) *SuppressionBulkParams`

NewSuppressionBulkParams instantiates a new SuppressionBulkParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppressionBulkParamsWithDefaults

`func NewSuppressionBulkParamsWithDefaults() *SuppressionBulkParams`

NewSuppressionBulkParamsWithDefaults instantiates a new SuppressionBulkParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmails

`func (o *SuppressionBulkParams) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *SuppressionBulkParams) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *SuppressionBulkParams) SetEmails(v []string)`

SetEmails sets Emails field to given value.


### GetReason

`func (o *SuppressionBulkParams) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *SuppressionBulkParams) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *SuppressionBulkParams) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *SuppressionBulkParams) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


