# Person

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
**PrivateNotes** | **NullableString** |  | 
**Score** | **NullableInt32** |  | 
**Source** | **string** | Where the person came from: &#x60;csv_import&#x60;, &#x60;manual&#x60;, &#x60;api&#x60;, &#x60;form&#x60;, &#x60;inbound&#x60;, &#x60;integration&#x60;. | 
**Status** | **string** | Lifecycle status: &#x60;active&#x60;, &#x60;replied&#x60;, &#x60;bounced&#x60;, &#x60;unsubscribed&#x60;, &#x60;finished&#x60;. | 
**Telephone** | **NullableString** |  | 
**Telephones** | **[]string** |  | 
**UpdatedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewPerson

`func NewPerson(customFields map[string]interface{}, email NullableString, emailDomain NullableString, familyName NullableString, givenName NullableString, id string, importId NullableString, privateNotes NullableString, score NullableInt32, source string, status string, telephone NullableString, telephones []string, ) *Person`

NewPerson instantiates a new Person object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonWithDefaults

`func NewPersonWithDefaults() *Person`

NewPersonWithDefaults instantiates a new Person object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *Person) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Person) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Person) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Person) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Person) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Person) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCreatedAt

`func (o *Person) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Person) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Person) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Person) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Person) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Person) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetCustomFields

`func (o *Person) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *Person) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *Person) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.


### SetCustomFieldsNil

`func (o *Person) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *Person) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetEmail

`func (o *Person) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Person) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Person) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *Person) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *Person) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetEmailDomain

`func (o *Person) GetEmailDomain() string`

GetEmailDomain returns the EmailDomain field if non-nil, zero value otherwise.

### GetEmailDomainOk

`func (o *Person) GetEmailDomainOk() (*string, bool)`

GetEmailDomainOk returns a tuple with the EmailDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailDomain

`func (o *Person) SetEmailDomain(v string)`

SetEmailDomain sets EmailDomain field to given value.


### SetEmailDomainNil

`func (o *Person) SetEmailDomainNil(b bool)`

 SetEmailDomainNil sets the value for EmailDomain to be an explicit nil

### UnsetEmailDomain
`func (o *Person) UnsetEmailDomain()`

UnsetEmailDomain ensures that no value is present for EmailDomain, not even an explicit nil
### GetFamilyName

`func (o *Person) GetFamilyName() string`

GetFamilyName returns the FamilyName field if non-nil, zero value otherwise.

### GetFamilyNameOk

`func (o *Person) GetFamilyNameOk() (*string, bool)`

GetFamilyNameOk returns a tuple with the FamilyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamilyName

`func (o *Person) SetFamilyName(v string)`

SetFamilyName sets FamilyName field to given value.


### SetFamilyNameNil

`func (o *Person) SetFamilyNameNil(b bool)`

 SetFamilyNameNil sets the value for FamilyName to be an explicit nil

### UnsetFamilyName
`func (o *Person) UnsetFamilyName()`

UnsetFamilyName ensures that no value is present for FamilyName, not even an explicit nil
### GetGivenName

`func (o *Person) GetGivenName() string`

GetGivenName returns the GivenName field if non-nil, zero value otherwise.

### GetGivenNameOk

`func (o *Person) GetGivenNameOk() (*string, bool)`

GetGivenNameOk returns a tuple with the GivenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGivenName

`func (o *Person) SetGivenName(v string)`

SetGivenName sets GivenName field to given value.


### SetGivenNameNil

`func (o *Person) SetGivenNameNil(b bool)`

 SetGivenNameNil sets the value for GivenName to be an explicit nil

### UnsetGivenName
`func (o *Person) UnsetGivenName()`

UnsetGivenName ensures that no value is present for GivenName, not even an explicit nil
### GetId

`func (o *Person) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Person) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Person) SetId(v string)`

SetId sets Id field to given value.


### GetImportId

`func (o *Person) GetImportId() string`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *Person) GetImportIdOk() (*string, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *Person) SetImportId(v string)`

SetImportId sets ImportId field to given value.


### SetImportIdNil

`func (o *Person) SetImportIdNil(b bool)`

 SetImportIdNil sets the value for ImportId to be an explicit nil

### UnsetImportId
`func (o *Person) UnsetImportId()`

UnsetImportId ensures that no value is present for ImportId, not even an explicit nil
### GetLastActivityAt

`func (o *Person) GetLastActivityAt() interface{}`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *Person) GetLastActivityAtOk() (*interface{}, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *Person) SetLastActivityAt(v interface{})`

SetLastActivityAt sets LastActivityAt field to given value.

### HasLastActivityAt

`func (o *Person) HasLastActivityAt() bool`

HasLastActivityAt returns a boolean if a field has been set.

### SetLastActivityAtNil

`func (o *Person) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *Person) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetObject

`func (o *Person) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *Person) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *Person) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *Person) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *Person) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *Person) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPrivateNotes

`func (o *Person) GetPrivateNotes() string`

GetPrivateNotes returns the PrivateNotes field if non-nil, zero value otherwise.

### GetPrivateNotesOk

`func (o *Person) GetPrivateNotesOk() (*string, bool)`

GetPrivateNotesOk returns a tuple with the PrivateNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateNotes

`func (o *Person) SetPrivateNotes(v string)`

SetPrivateNotes sets PrivateNotes field to given value.


### SetPrivateNotesNil

`func (o *Person) SetPrivateNotesNil(b bool)`

 SetPrivateNotesNil sets the value for PrivateNotes to be an explicit nil

### UnsetPrivateNotes
`func (o *Person) UnsetPrivateNotes()`

UnsetPrivateNotes ensures that no value is present for PrivateNotes, not even an explicit nil
### GetScore

`func (o *Person) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *Person) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *Person) SetScore(v int32)`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *Person) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *Person) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetSource

`func (o *Person) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Person) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Person) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *Person) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Person) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Person) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTelephone

`func (o *Person) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *Person) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *Person) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.


### SetTelephoneNil

`func (o *Person) SetTelephoneNil(b bool)`

 SetTelephoneNil sets the value for Telephone to be an explicit nil

### UnsetTelephone
`func (o *Person) UnsetTelephone()`

UnsetTelephone ensures that no value is present for Telephone, not even an explicit nil
### GetTelephones

`func (o *Person) GetTelephones() []string`

GetTelephones returns the Telephones field if non-nil, zero value otherwise.

### GetTelephonesOk

`func (o *Person) GetTelephonesOk() (*[]string, bool)`

GetTelephonesOk returns a tuple with the Telephones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephones

`func (o *Person) SetTelephones(v []string)`

SetTelephones sets Telephones field to given value.


### SetTelephonesNil

`func (o *Person) SetTelephonesNil(b bool)`

 SetTelephonesNil sets the value for Telephones to be an explicit nil

### UnsetTelephones
`func (o *Person) UnsetTelephones()`

UnsetTelephones ensures that no value is present for Telephones, not even an explicit nil
### GetUpdatedAt

`func (o *Person) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Person) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Person) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Person) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Person) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Person) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


