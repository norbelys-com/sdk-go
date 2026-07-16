# AudienceSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** | The source type: a saved segment, a static group, a CSV import, or explicit ids. | 
**Label** | **string** | The source&#39;s name as it was at enroll time. | 
**People** | **int32** | People enrolled from this source (accumulated across enrolls). | 
**RefId** | **string** | The source id (segment/group/import id); \&quot;\&quot; for manually added people. | 
**Synced** | **bool** | True for a segment kept in CONTINUOUS sync — new matches are auto-enrolled (a dynamic audience). | 

## Methods

### NewAudienceSource

`func NewAudienceSource(kind string, label string, people int32, refId string, synced bool, ) *AudienceSource`

NewAudienceSource instantiates a new AudienceSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceSourceWithDefaults

`func NewAudienceSourceWithDefaults() *AudienceSource`

NewAudienceSourceWithDefaults instantiates a new AudienceSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *AudienceSource) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AudienceSource) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AudienceSource) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *AudienceSource) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AudienceSource) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AudienceSource) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetPeople

`func (o *AudienceSource) GetPeople() int32`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *AudienceSource) GetPeopleOk() (*int32, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *AudienceSource) SetPeople(v int32)`

SetPeople sets People field to given value.


### GetRefId

`func (o *AudienceSource) GetRefId() string`

GetRefId returns the RefId field if non-nil, zero value otherwise.

### GetRefIdOk

`func (o *AudienceSource) GetRefIdOk() (*string, bool)`

GetRefIdOk returns a tuple with the RefId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefId

`func (o *AudienceSource) SetRefId(v string)`

SetRefId sets RefId field to given value.


### GetSynced

`func (o *AudienceSource) GetSynced() bool`

GetSynced returns the Synced field if non-nil, zero value otherwise.

### GetSyncedOk

`func (o *AudienceSource) GetSyncedOk() (*bool, bool)`

GetSyncedOk returns a tuple with the Synced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynced

`func (o *AudienceSource) SetSynced(v bool)`

SetSynced sets Synced field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


