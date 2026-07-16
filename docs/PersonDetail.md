# PersonDetail

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
**Enrollments** | Pointer to [**[]Enrollment**](Enrollment.md) | Expansion: the person&#39;s enrollments across all campaigns. | [optional] 
**Groups** | Pointer to [**[]PersonGroupRef**](PersonGroupRef.md) | Expansion: the static groups this person belongs to. | [optional] 
**Segments** | Pointer to [**[]PersonSegmentRef**](PersonSegmentRef.md) | Expansion: the dynamic segments this person currently matches. | [optional] 
**Timeline** | Pointer to [**[]Message**](Message.md) | Expansion: the person&#39;s merged sent + received messages, newest first. | [optional] 

## Methods

### NewPersonDetail

`func NewPersonDetail(customFields map[string]interface{}, email NullableString, emailDomain NullableString, familyName NullableString, givenName NullableString, id string, importId NullableString, privateNotes NullableString, score NullableInt32, source string, status string, telephone NullableString, telephones []string, ) *PersonDetail`

NewPersonDetail instantiates a new PersonDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonDetailWithDefaults

`func NewPersonDetailWithDefaults() *PersonDetail`

NewPersonDetailWithDefaults instantiates a new PersonDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *PersonDetail) GetArchivedAt() interface{}`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *PersonDetail) GetArchivedAtOk() (*interface{}, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *PersonDetail) SetArchivedAt(v interface{})`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *PersonDetail) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *PersonDetail) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *PersonDetail) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCreatedAt

`func (o *PersonDetail) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PersonDetail) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PersonDetail) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PersonDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *PersonDetail) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *PersonDetail) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetCustomFields

`func (o *PersonDetail) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *PersonDetail) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *PersonDetail) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.


### SetCustomFieldsNil

`func (o *PersonDetail) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *PersonDetail) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetEmail

`func (o *PersonDetail) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PersonDetail) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PersonDetail) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *PersonDetail) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *PersonDetail) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetEmailDomain

`func (o *PersonDetail) GetEmailDomain() string`

GetEmailDomain returns the EmailDomain field if non-nil, zero value otherwise.

### GetEmailDomainOk

`func (o *PersonDetail) GetEmailDomainOk() (*string, bool)`

GetEmailDomainOk returns a tuple with the EmailDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailDomain

`func (o *PersonDetail) SetEmailDomain(v string)`

SetEmailDomain sets EmailDomain field to given value.


### SetEmailDomainNil

`func (o *PersonDetail) SetEmailDomainNil(b bool)`

 SetEmailDomainNil sets the value for EmailDomain to be an explicit nil

### UnsetEmailDomain
`func (o *PersonDetail) UnsetEmailDomain()`

UnsetEmailDomain ensures that no value is present for EmailDomain, not even an explicit nil
### GetFamilyName

`func (o *PersonDetail) GetFamilyName() string`

GetFamilyName returns the FamilyName field if non-nil, zero value otherwise.

### GetFamilyNameOk

`func (o *PersonDetail) GetFamilyNameOk() (*string, bool)`

GetFamilyNameOk returns a tuple with the FamilyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamilyName

`func (o *PersonDetail) SetFamilyName(v string)`

SetFamilyName sets FamilyName field to given value.


### SetFamilyNameNil

`func (o *PersonDetail) SetFamilyNameNil(b bool)`

 SetFamilyNameNil sets the value for FamilyName to be an explicit nil

### UnsetFamilyName
`func (o *PersonDetail) UnsetFamilyName()`

UnsetFamilyName ensures that no value is present for FamilyName, not even an explicit nil
### GetGivenName

`func (o *PersonDetail) GetGivenName() string`

GetGivenName returns the GivenName field if non-nil, zero value otherwise.

### GetGivenNameOk

`func (o *PersonDetail) GetGivenNameOk() (*string, bool)`

GetGivenNameOk returns a tuple with the GivenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGivenName

`func (o *PersonDetail) SetGivenName(v string)`

SetGivenName sets GivenName field to given value.


### SetGivenNameNil

`func (o *PersonDetail) SetGivenNameNil(b bool)`

 SetGivenNameNil sets the value for GivenName to be an explicit nil

### UnsetGivenName
`func (o *PersonDetail) UnsetGivenName()`

UnsetGivenName ensures that no value is present for GivenName, not even an explicit nil
### GetId

`func (o *PersonDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonDetail) SetId(v string)`

SetId sets Id field to given value.


### GetImportId

`func (o *PersonDetail) GetImportId() string`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *PersonDetail) GetImportIdOk() (*string, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *PersonDetail) SetImportId(v string)`

SetImportId sets ImportId field to given value.


### SetImportIdNil

`func (o *PersonDetail) SetImportIdNil(b bool)`

 SetImportIdNil sets the value for ImportId to be an explicit nil

### UnsetImportId
`func (o *PersonDetail) UnsetImportId()`

UnsetImportId ensures that no value is present for ImportId, not even an explicit nil
### GetLastActivityAt

`func (o *PersonDetail) GetLastActivityAt() interface{}`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *PersonDetail) GetLastActivityAtOk() (*interface{}, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *PersonDetail) SetLastActivityAt(v interface{})`

SetLastActivityAt sets LastActivityAt field to given value.

### HasLastActivityAt

`func (o *PersonDetail) HasLastActivityAt() bool`

HasLastActivityAt returns a boolean if a field has been set.

### SetLastActivityAtNil

`func (o *PersonDetail) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *PersonDetail) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetObject

`func (o *PersonDetail) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *PersonDetail) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *PersonDetail) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *PersonDetail) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *PersonDetail) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *PersonDetail) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPrivateNotes

`func (o *PersonDetail) GetPrivateNotes() string`

GetPrivateNotes returns the PrivateNotes field if non-nil, zero value otherwise.

### GetPrivateNotesOk

`func (o *PersonDetail) GetPrivateNotesOk() (*string, bool)`

GetPrivateNotesOk returns a tuple with the PrivateNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateNotes

`func (o *PersonDetail) SetPrivateNotes(v string)`

SetPrivateNotes sets PrivateNotes field to given value.


### SetPrivateNotesNil

`func (o *PersonDetail) SetPrivateNotesNil(b bool)`

 SetPrivateNotesNil sets the value for PrivateNotes to be an explicit nil

### UnsetPrivateNotes
`func (o *PersonDetail) UnsetPrivateNotes()`

UnsetPrivateNotes ensures that no value is present for PrivateNotes, not even an explicit nil
### GetScore

`func (o *PersonDetail) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *PersonDetail) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *PersonDetail) SetScore(v int32)`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *PersonDetail) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *PersonDetail) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetSource

`func (o *PersonDetail) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PersonDetail) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PersonDetail) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *PersonDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PersonDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PersonDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTelephone

`func (o *PersonDetail) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *PersonDetail) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *PersonDetail) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.


### SetTelephoneNil

`func (o *PersonDetail) SetTelephoneNil(b bool)`

 SetTelephoneNil sets the value for Telephone to be an explicit nil

### UnsetTelephone
`func (o *PersonDetail) UnsetTelephone()`

UnsetTelephone ensures that no value is present for Telephone, not even an explicit nil
### GetTelephones

`func (o *PersonDetail) GetTelephones() []string`

GetTelephones returns the Telephones field if non-nil, zero value otherwise.

### GetTelephonesOk

`func (o *PersonDetail) GetTelephonesOk() (*[]string, bool)`

GetTelephonesOk returns a tuple with the Telephones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephones

`func (o *PersonDetail) SetTelephones(v []string)`

SetTelephones sets Telephones field to given value.


### SetTelephonesNil

`func (o *PersonDetail) SetTelephonesNil(b bool)`

 SetTelephonesNil sets the value for Telephones to be an explicit nil

### UnsetTelephones
`func (o *PersonDetail) UnsetTelephones()`

UnsetTelephones ensures that no value is present for Telephones, not even an explicit nil
### GetUpdatedAt

`func (o *PersonDetail) GetUpdatedAt() interface{}`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PersonDetail) GetUpdatedAtOk() (*interface{}, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PersonDetail) SetUpdatedAt(v interface{})`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PersonDetail) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PersonDetail) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PersonDetail) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetEnrollments

`func (o *PersonDetail) GetEnrollments() []Enrollment`

GetEnrollments returns the Enrollments field if non-nil, zero value otherwise.

### GetEnrollmentsOk

`func (o *PersonDetail) GetEnrollmentsOk() (*[]Enrollment, bool)`

GetEnrollmentsOk returns a tuple with the Enrollments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrollments

`func (o *PersonDetail) SetEnrollments(v []Enrollment)`

SetEnrollments sets Enrollments field to given value.

### HasEnrollments

`func (o *PersonDetail) HasEnrollments() bool`

HasEnrollments returns a boolean if a field has been set.

### GetGroups

`func (o *PersonDetail) GetGroups() []PersonGroupRef`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *PersonDetail) GetGroupsOk() (*[]PersonGroupRef, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *PersonDetail) SetGroups(v []PersonGroupRef)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *PersonDetail) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetSegments

`func (o *PersonDetail) GetSegments() []PersonSegmentRef`

GetSegments returns the Segments field if non-nil, zero value otherwise.

### GetSegmentsOk

`func (o *PersonDetail) GetSegmentsOk() (*[]PersonSegmentRef, bool)`

GetSegmentsOk returns a tuple with the Segments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegments

`func (o *PersonDetail) SetSegments(v []PersonSegmentRef)`

SetSegments sets Segments field to given value.

### HasSegments

`func (o *PersonDetail) HasSegments() bool`

HasSegments returns a boolean if a field has been set.

### GetTimeline

`func (o *PersonDetail) GetTimeline() []Message`

GetTimeline returns the Timeline field if non-nil, zero value otherwise.

### GetTimelineOk

`func (o *PersonDetail) GetTimelineOk() (*[]Message, bool)`

GetTimelineOk returns a tuple with the Timeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeline

`func (o *PersonDetail) SetTimeline(v []Message)`

SetTimeline sets Timeline field to given value.

### HasTimeline

`func (o *PersonDetail) HasTimeline() bool`

HasTimeline returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


