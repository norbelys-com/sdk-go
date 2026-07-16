# PersonUpdateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomFields** | Pointer to **map[string]interface{}** |  | [optional] 
**FamilyName** | Pointer to **NullableString** |  | [optional] 
**GivenName** | Pointer to **NullableString** |  | [optional] 
**PrivateNotes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **string** | Set the lifecycle status: &#x60;active&#x60;, &#x60;replied&#x60;, &#x60;bounced&#x60;, &#x60;unsubscribed&#x60;, &#x60;finished&#x60;. | [optional] 
**Telephone** | Pointer to **NullableString** |  | [optional] 
**Telephones** | Pointer to **[]string** |  | [optional] 

## Methods

### NewPersonUpdateParams

`func NewPersonUpdateParams() *PersonUpdateParams`

NewPersonUpdateParams instantiates a new PersonUpdateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonUpdateParamsWithDefaults

`func NewPersonUpdateParamsWithDefaults() *PersonUpdateParams`

NewPersonUpdateParamsWithDefaults instantiates a new PersonUpdateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomFields

`func (o *PersonUpdateParams) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *PersonUpdateParams) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *PersonUpdateParams) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *PersonUpdateParams) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### SetCustomFieldsNil

`func (o *PersonUpdateParams) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *PersonUpdateParams) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetFamilyName

`func (o *PersonUpdateParams) GetFamilyName() string`

GetFamilyName returns the FamilyName field if non-nil, zero value otherwise.

### GetFamilyNameOk

`func (o *PersonUpdateParams) GetFamilyNameOk() (*string, bool)`

GetFamilyNameOk returns a tuple with the FamilyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamilyName

`func (o *PersonUpdateParams) SetFamilyName(v string)`

SetFamilyName sets FamilyName field to given value.

### HasFamilyName

`func (o *PersonUpdateParams) HasFamilyName() bool`

HasFamilyName returns a boolean if a field has been set.

### SetFamilyNameNil

`func (o *PersonUpdateParams) SetFamilyNameNil(b bool)`

 SetFamilyNameNil sets the value for FamilyName to be an explicit nil

### UnsetFamilyName
`func (o *PersonUpdateParams) UnsetFamilyName()`

UnsetFamilyName ensures that no value is present for FamilyName, not even an explicit nil
### GetGivenName

`func (o *PersonUpdateParams) GetGivenName() string`

GetGivenName returns the GivenName field if non-nil, zero value otherwise.

### GetGivenNameOk

`func (o *PersonUpdateParams) GetGivenNameOk() (*string, bool)`

GetGivenNameOk returns a tuple with the GivenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGivenName

`func (o *PersonUpdateParams) SetGivenName(v string)`

SetGivenName sets GivenName field to given value.

### HasGivenName

`func (o *PersonUpdateParams) HasGivenName() bool`

HasGivenName returns a boolean if a field has been set.

### SetGivenNameNil

`func (o *PersonUpdateParams) SetGivenNameNil(b bool)`

 SetGivenNameNil sets the value for GivenName to be an explicit nil

### UnsetGivenName
`func (o *PersonUpdateParams) UnsetGivenName()`

UnsetGivenName ensures that no value is present for GivenName, not even an explicit nil
### GetPrivateNotes

`func (o *PersonUpdateParams) GetPrivateNotes() string`

GetPrivateNotes returns the PrivateNotes field if non-nil, zero value otherwise.

### GetPrivateNotesOk

`func (o *PersonUpdateParams) GetPrivateNotesOk() (*string, bool)`

GetPrivateNotesOk returns a tuple with the PrivateNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateNotes

`func (o *PersonUpdateParams) SetPrivateNotes(v string)`

SetPrivateNotes sets PrivateNotes field to given value.

### HasPrivateNotes

`func (o *PersonUpdateParams) HasPrivateNotes() bool`

HasPrivateNotes returns a boolean if a field has been set.

### SetPrivateNotesNil

`func (o *PersonUpdateParams) SetPrivateNotesNil(b bool)`

 SetPrivateNotesNil sets the value for PrivateNotes to be an explicit nil

### UnsetPrivateNotes
`func (o *PersonUpdateParams) UnsetPrivateNotes()`

UnsetPrivateNotes ensures that no value is present for PrivateNotes, not even an explicit nil
### GetStatus

`func (o *PersonUpdateParams) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PersonUpdateParams) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PersonUpdateParams) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PersonUpdateParams) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTelephone

`func (o *PersonUpdateParams) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *PersonUpdateParams) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *PersonUpdateParams) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.

### HasTelephone

`func (o *PersonUpdateParams) HasTelephone() bool`

HasTelephone returns a boolean if a field has been set.

### SetTelephoneNil

`func (o *PersonUpdateParams) SetTelephoneNil(b bool)`

 SetTelephoneNil sets the value for Telephone to be an explicit nil

### UnsetTelephone
`func (o *PersonUpdateParams) UnsetTelephone()`

UnsetTelephone ensures that no value is present for Telephone, not even an explicit nil
### GetTelephones

`func (o *PersonUpdateParams) GetTelephones() []string`

GetTelephones returns the Telephones field if non-nil, zero value otherwise.

### GetTelephonesOk

`func (o *PersonUpdateParams) GetTelephonesOk() (*[]string, bool)`

GetTelephonesOk returns a tuple with the Telephones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephones

`func (o *PersonUpdateParams) SetTelephones(v []string)`

SetTelephones sets Telephones field to given value.

### HasTelephones

`func (o *PersonUpdateParams) HasTelephones() bool`

HasTelephones returns a boolean if a field has been set.

### SetTelephonesNil

`func (o *PersonUpdateParams) SetTelephonesNil(b bool)`

 SetTelephonesNil sets the value for Telephones to be an explicit nil

### UnsetTelephones
`func (o *PersonUpdateParams) UnsetTelephones()`

UnsetTelephones ensures that no value is present for Telephones, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


