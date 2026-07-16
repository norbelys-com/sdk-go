# PersonCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomFields** | Pointer to **map[string]interface{}** | Custom field values keyed by code (see the Fields page). | [optional] 
**Email** | **string** | The person&#39;s email address. | 
**FamilyName** | Pointer to **string** | The person&#39;s last name. | [optional] 
**GivenName** | Pointer to **string** | The person&#39;s first name. | [optional] 
**Source** | Pointer to **string** | Where this person came from: &#x60;csv_import&#x60;, &#x60;manual&#x60;, &#x60;api&#x60;, &#x60;form&#x60;, &#x60;inbound&#x60;, &#x60;integration&#x60;. Defaults to &#x60;manual&#x60;. | [optional] 
**Telephone** | Pointer to **string** | The primary telephone number. Normalized to E.164 on write; an invalid number is dropped (the person still saves), never fatal. | [optional] 
**Telephones** | Pointer to **[]string** | Additional telephone numbers. Merged with &#x60;telephone&#x60;, normalized to E.164, deduped; invalid entries are dropped. | [optional] 

## Methods

### NewPersonCreateParams

`func NewPersonCreateParams(email string, ) *PersonCreateParams`

NewPersonCreateParams instantiates a new PersonCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonCreateParamsWithDefaults

`func NewPersonCreateParamsWithDefaults() *PersonCreateParams`

NewPersonCreateParamsWithDefaults instantiates a new PersonCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomFields

`func (o *PersonCreateParams) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *PersonCreateParams) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *PersonCreateParams) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *PersonCreateParams) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### GetEmail

`func (o *PersonCreateParams) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PersonCreateParams) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PersonCreateParams) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetFamilyName

`func (o *PersonCreateParams) GetFamilyName() string`

GetFamilyName returns the FamilyName field if non-nil, zero value otherwise.

### GetFamilyNameOk

`func (o *PersonCreateParams) GetFamilyNameOk() (*string, bool)`

GetFamilyNameOk returns a tuple with the FamilyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamilyName

`func (o *PersonCreateParams) SetFamilyName(v string)`

SetFamilyName sets FamilyName field to given value.

### HasFamilyName

`func (o *PersonCreateParams) HasFamilyName() bool`

HasFamilyName returns a boolean if a field has been set.

### GetGivenName

`func (o *PersonCreateParams) GetGivenName() string`

GetGivenName returns the GivenName field if non-nil, zero value otherwise.

### GetGivenNameOk

`func (o *PersonCreateParams) GetGivenNameOk() (*string, bool)`

GetGivenNameOk returns a tuple with the GivenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGivenName

`func (o *PersonCreateParams) SetGivenName(v string)`

SetGivenName sets GivenName field to given value.

### HasGivenName

`func (o *PersonCreateParams) HasGivenName() bool`

HasGivenName returns a boolean if a field has been set.

### GetSource

`func (o *PersonCreateParams) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PersonCreateParams) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PersonCreateParams) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PersonCreateParams) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTelephone

`func (o *PersonCreateParams) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *PersonCreateParams) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *PersonCreateParams) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.

### HasTelephone

`func (o *PersonCreateParams) HasTelephone() bool`

HasTelephone returns a boolean if a field has been set.

### GetTelephones

`func (o *PersonCreateParams) GetTelephones() []string`

GetTelephones returns the Telephones field if non-nil, zero value otherwise.

### GetTelephonesOk

`func (o *PersonCreateParams) GetTelephonesOk() (*[]string, bool)`

GetTelephonesOk returns a tuple with the Telephones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephones

`func (o *PersonCreateParams) SetTelephones(v []string)`

SetTelephones sets Telephones field to given value.

### HasTelephones

`func (o *PersonCreateParams) HasTelephones() bool`

HasTelephones returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


