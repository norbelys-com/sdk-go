# SuppressionCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmailOrDomain** | **string** | The email address or bare domain to suppress. | 
**ProgramId** | Pointer to **string** | The campaign to scope to; required when scope is \&quot;program\&quot;. | [optional] 
**Reason** | Pointer to **string** | Free-text note recording why the address is being suppressed. | [optional] 
**Scope** | Pointer to **string** | Suppression scope: \&quot;org\&quot; (the default) suppresses everywhere; \&quot;program\&quot; suppresses within one campaign only. | [optional] 

## Methods

### NewSuppressionCreateParams

`func NewSuppressionCreateParams(emailOrDomain string, ) *SuppressionCreateParams`

NewSuppressionCreateParams instantiates a new SuppressionCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuppressionCreateParamsWithDefaults

`func NewSuppressionCreateParamsWithDefaults() *SuppressionCreateParams`

NewSuppressionCreateParamsWithDefaults instantiates a new SuppressionCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmailOrDomain

`func (o *SuppressionCreateParams) GetEmailOrDomain() string`

GetEmailOrDomain returns the EmailOrDomain field if non-nil, zero value otherwise.

### GetEmailOrDomainOk

`func (o *SuppressionCreateParams) GetEmailOrDomainOk() (*string, bool)`

GetEmailOrDomainOk returns a tuple with the EmailOrDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailOrDomain

`func (o *SuppressionCreateParams) SetEmailOrDomain(v string)`

SetEmailOrDomain sets EmailOrDomain field to given value.


### GetProgramId

`func (o *SuppressionCreateParams) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *SuppressionCreateParams) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *SuppressionCreateParams) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.

### HasProgramId

`func (o *SuppressionCreateParams) HasProgramId() bool`

HasProgramId returns a boolean if a field has been set.

### GetReason

`func (o *SuppressionCreateParams) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *SuppressionCreateParams) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *SuppressionCreateParams) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *SuppressionCreateParams) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetScope

`func (o *SuppressionCreateParams) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *SuppressionCreateParams) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *SuppressionCreateParams) SetScope(v string)`

SetScope sets Scope field to given value.

### HasScope

`func (o *SuppressionCreateParams) HasScope() bool`

HasScope returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


