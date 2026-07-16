# PersonListItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**CustomFields** | **map[string]interface{}** |  | 
**Email** | **NullableString** |  | 
**EmailDomain** | **NullableString** |  | 
**FamilyName** | **NullableString** |  | 
**GivenName** | **NullableString** |  | 
**Id** | **string** | The person id. | 
**ImportId** | **NullableString** |  | 
**LastActivityAt** | Pointer to **interface{}** |  | [optional] 
**Object** | Pointer to **interface{}** |  | [optional] 
**Score** | **NullableInt32** |  | 
**Source** | **string** | Where the person came from: &#x60;csv_import&#x60;, &#x60;manual&#x60;, &#x60;api&#x60;, &#x60;form&#x60;, &#x60;inbound&#x60;, &#x60;integration&#x60;. | 
**Status** | **string** | Lifecycle status: &#x60;active&#x60;, &#x60;replied&#x60;, &#x60;bounced&#x60;, &#x60;unsubscribed&#x60;, &#x60;finished&#x60;. | 
**Telephone** | **NullableString** |  | 
**Telephones** | **[]string** |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewPersonListItem

`func NewPersonListItem(customFields map[string]interface{}, email NullableString, emailDomain NullableString, familyName NullableString, givenName NullableString, id string, importId NullableString, score NullableInt32, source string, status string, telephone NullableString, telephones []string, ) *PersonListItem`

NewPersonListItem instantiates a new PersonListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonListItemWithDefaults

`func NewPersonListItemWithDefaults() *PersonListItem`

NewPersonListItemWithDefaults instantiates a new PersonListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *PersonListItem) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *PersonListItem) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *PersonListItem) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *PersonListItem) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *PersonListItem) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *PersonListItem) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCreatedAt

`func (o *PersonListItem) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PersonListItem) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PersonListItem) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PersonListItem) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *PersonListItem) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *PersonListItem) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetCustomFields

`func (o *PersonListItem) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *PersonListItem) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *PersonListItem) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.


### SetCustomFieldsNil

`func (o *PersonListItem) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *PersonListItem) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetEmail

`func (o *PersonListItem) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PersonListItem) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PersonListItem) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *PersonListItem) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *PersonListItem) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetEmailDomain

`func (o *PersonListItem) GetEmailDomain() string`

GetEmailDomain returns the EmailDomain field if non-nil, zero value otherwise.

### GetEmailDomainOk

`func (o *PersonListItem) GetEmailDomainOk() (*string, bool)`

GetEmailDomainOk returns a tuple with the EmailDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailDomain

`func (o *PersonListItem) SetEmailDomain(v string)`

SetEmailDomain sets EmailDomain field to given value.


### SetEmailDomainNil

`func (o *PersonListItem) SetEmailDomainNil(b bool)`

 SetEmailDomainNil sets the value for EmailDomain to be an explicit nil

### UnsetEmailDomain
`func (o *PersonListItem) UnsetEmailDomain()`

UnsetEmailDomain ensures that no value is present for EmailDomain, not even an explicit nil
### GetFamilyName

`func (o *PersonListItem) GetFamilyName() string`

GetFamilyName returns the FamilyName field if non-nil, zero value otherwise.

### GetFamilyNameOk

`func (o *PersonListItem) GetFamilyNameOk() (*string, bool)`

GetFamilyNameOk returns a tuple with the FamilyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamilyName

`func (o *PersonListItem) SetFamilyName(v string)`

SetFamilyName sets FamilyName field to given value.


### SetFamilyNameNil

`func (o *PersonListItem) SetFamilyNameNil(b bool)`

 SetFamilyNameNil sets the value for FamilyName to be an explicit nil

### UnsetFamilyName
`func (o *PersonListItem) UnsetFamilyName()`

UnsetFamilyName ensures that no value is present for FamilyName, not even an explicit nil
### GetGivenName

`func (o *PersonListItem) GetGivenName() string`

GetGivenName returns the GivenName field if non-nil, zero value otherwise.

### GetGivenNameOk

`func (o *PersonListItem) GetGivenNameOk() (*string, bool)`

GetGivenNameOk returns a tuple with the GivenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGivenName

`func (o *PersonListItem) SetGivenName(v string)`

SetGivenName sets GivenName field to given value.


### SetGivenNameNil

`func (o *PersonListItem) SetGivenNameNil(b bool)`

 SetGivenNameNil sets the value for GivenName to be an explicit nil

### UnsetGivenName
`func (o *PersonListItem) UnsetGivenName()`

UnsetGivenName ensures that no value is present for GivenName, not even an explicit nil
### GetId

`func (o *PersonListItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonListItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonListItem) SetId(v string)`

SetId sets Id field to given value.


### GetImportId

`func (o *PersonListItem) GetImportId() string`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *PersonListItem) GetImportIdOk() (*string, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *PersonListItem) SetImportId(v string)`

SetImportId sets ImportId field to given value.


### SetImportIdNil

`func (o *PersonListItem) SetImportIdNil(b bool)`

 SetImportIdNil sets the value for ImportId to be an explicit nil

### UnsetImportId
`func (o *PersonListItem) UnsetImportId()`

UnsetImportId ensures that no value is present for ImportId, not even an explicit nil
### GetLastActivityAt

`func (o *PersonListItem) GetLastActivityAt() interface{}`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *PersonListItem) GetLastActivityAtOk() (*interface{}, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *PersonListItem) SetLastActivityAt(v interface{})`

SetLastActivityAt sets LastActivityAt field to given value.

### HasLastActivityAt

`func (o *PersonListItem) HasLastActivityAt() bool`

HasLastActivityAt returns a boolean if a field has been set.

### SetLastActivityAtNil

`func (o *PersonListItem) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *PersonListItem) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetObject

`func (o *PersonListItem) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *PersonListItem) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *PersonListItem) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *PersonListItem) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *PersonListItem) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *PersonListItem) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetScore

`func (o *PersonListItem) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *PersonListItem) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *PersonListItem) SetScore(v int32)`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *PersonListItem) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *PersonListItem) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetSource

`func (o *PersonListItem) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PersonListItem) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PersonListItem) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *PersonListItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PersonListItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PersonListItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTelephone

`func (o *PersonListItem) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *PersonListItem) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *PersonListItem) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.


### SetTelephoneNil

`func (o *PersonListItem) SetTelephoneNil(b bool)`

 SetTelephoneNil sets the value for Telephone to be an explicit nil

### UnsetTelephone
`func (o *PersonListItem) UnsetTelephone()`

UnsetTelephone ensures that no value is present for Telephone, not even an explicit nil
### GetTelephones

`func (o *PersonListItem) GetTelephones() []string`

GetTelephones returns the Telephones field if non-nil, zero value otherwise.

### GetTelephonesOk

`func (o *PersonListItem) GetTelephonesOk() (*[]string, bool)`

GetTelephonesOk returns a tuple with the Telephones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephones

`func (o *PersonListItem) SetTelephones(v []string)`

SetTelephones sets Telephones field to given value.


### SetTelephonesNil

`func (o *PersonListItem) SetTelephonesNil(b bool)`

 SetTelephonesNil sets the value for Telephones to be an explicit nil

### UnsetTelephones
`func (o *PersonListItem) UnsetTelephones()`

UnsetTelephones ensures that no value is present for Telephones, not even an explicit nil
### GetUpdatedAt

`func (o *PersonListItem) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PersonListItem) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PersonListItem) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PersonListItem) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PersonListItem) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PersonListItem) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


