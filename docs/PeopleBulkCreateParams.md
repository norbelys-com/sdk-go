# PeopleBulkCreateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignIds** | Pointer to **[]string** | Optional campaigns to enroll every imported person into — both newly created people and already-existing matches. Several allowed; a draft campaign holds them until launch. | [optional] 
**DefaultCountry** | Pointer to **string** | ISO 3166-1 alpha-2 country used to normalize NATIONAL phone numbers to E.164 — e.g. &#x60;CO&#x60; turns &#x60;3163586947&#x60; into &#x60;+573163586947&#x60;. A number that already carries its country code (&#x60;+57…&#x60;) ignores this. | [optional] 
**GroupIds** | Pointer to **[]string** | Optional static groups (lists) to add every imported person to — new AND already-existing matches. Several allowed. | [optional] 
**ImportId** | Pointer to **string** | Optional import id you supply to GROUP several chunked calls into ONE import (so the stats at &#x60;GET /v1/people/bulk/{importId}&#x60; cover the whole upload). Generated automatically when omitted. | [optional] 
**OnConflict** | Pointer to **string** | What to do when a person with this email already exists. &#x60;fill&#x60; (default): update the existing person, only filling fields that are currently empty — never overwrites existing values. &#x60;overwrite&#x60;: the uploaded values win for every field they provide. &#x60;skip&#x60;: leave the existing person untouched. | [optional] [default to "fill"]
**People** | [**[]PersonImportItem**](PersonImportItem.md) | Up to 10,000 people to insert (data + custom fields); duplicate emails are skipped and malformed emails are rejected (both non-fatal — see &#x60;skipped&#x60; / &#x60;rejected&#x60;). | 

## Methods

### NewPeopleBulkCreateParams

`func NewPeopleBulkCreateParams(people []PersonImportItem, ) *PeopleBulkCreateParams`

NewPeopleBulkCreateParams instantiates a new PeopleBulkCreateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeopleBulkCreateParamsWithDefaults

`func NewPeopleBulkCreateParamsWithDefaults() *PeopleBulkCreateParams`

NewPeopleBulkCreateParamsWithDefaults instantiates a new PeopleBulkCreateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaignIds

`func (o *PeopleBulkCreateParams) GetCampaignIds() []string`

GetCampaignIds returns the CampaignIds field if non-nil, zero value otherwise.

### GetCampaignIdsOk

`func (o *PeopleBulkCreateParams) GetCampaignIdsOk() (*[]string, bool)`

GetCampaignIdsOk returns a tuple with the CampaignIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignIds

`func (o *PeopleBulkCreateParams) SetCampaignIds(v []string)`

SetCampaignIds sets CampaignIds field to given value.

### HasCampaignIds

`func (o *PeopleBulkCreateParams) HasCampaignIds() bool`

HasCampaignIds returns a boolean if a field has been set.

### GetDefaultCountry

`func (o *PeopleBulkCreateParams) GetDefaultCountry() string`

GetDefaultCountry returns the DefaultCountry field if non-nil, zero value otherwise.

### GetDefaultCountryOk

`func (o *PeopleBulkCreateParams) GetDefaultCountryOk() (*string, bool)`

GetDefaultCountryOk returns a tuple with the DefaultCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCountry

`func (o *PeopleBulkCreateParams) SetDefaultCountry(v string)`

SetDefaultCountry sets DefaultCountry field to given value.

### HasDefaultCountry

`func (o *PeopleBulkCreateParams) HasDefaultCountry() bool`

HasDefaultCountry returns a boolean if a field has been set.

### GetGroupIds

`func (o *PeopleBulkCreateParams) GetGroupIds() []string`

GetGroupIds returns the GroupIds field if non-nil, zero value otherwise.

### GetGroupIdsOk

`func (o *PeopleBulkCreateParams) GetGroupIdsOk() (*[]string, bool)`

GetGroupIdsOk returns a tuple with the GroupIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupIds

`func (o *PeopleBulkCreateParams) SetGroupIds(v []string)`

SetGroupIds sets GroupIds field to given value.

### HasGroupIds

`func (o *PeopleBulkCreateParams) HasGroupIds() bool`

HasGroupIds returns a boolean if a field has been set.

### GetImportId

`func (o *PeopleBulkCreateParams) GetImportId() string`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *PeopleBulkCreateParams) GetImportIdOk() (*string, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *PeopleBulkCreateParams) SetImportId(v string)`

SetImportId sets ImportId field to given value.

### HasImportId

`func (o *PeopleBulkCreateParams) HasImportId() bool`

HasImportId returns a boolean if a field has been set.

### GetOnConflict

`func (o *PeopleBulkCreateParams) GetOnConflict() string`

GetOnConflict returns the OnConflict field if non-nil, zero value otherwise.

### GetOnConflictOk

`func (o *PeopleBulkCreateParams) GetOnConflictOk() (*string, bool)`

GetOnConflictOk returns a tuple with the OnConflict field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnConflict

`func (o *PeopleBulkCreateParams) SetOnConflict(v string)`

SetOnConflict sets OnConflict field to given value.

### HasOnConflict

`func (o *PeopleBulkCreateParams) HasOnConflict() bool`

HasOnConflict returns a boolean if a field has been set.

### GetPeople

`func (o *PeopleBulkCreateParams) GetPeople() []PersonImportItem`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *PeopleBulkCreateParams) GetPeopleOk() (*[]PersonImportItem, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *PeopleBulkCreateParams) SetPeople(v []PersonImportItem)`

SetPeople sets People field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


