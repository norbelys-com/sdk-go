# OrganizationProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Industry** | **NullableString** |  | 
**TeamSize** | [**NullableTeamSize**](TeamSize.md) |  | 
**Website** | **NullableString** |  | 

## Methods

### NewOrganizationProfile

`func NewOrganizationProfile(industry NullableString, teamSize NullableTeamSize, website NullableString, ) *OrganizationProfile`

NewOrganizationProfile instantiates a new OrganizationProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationProfileWithDefaults

`func NewOrganizationProfileWithDefaults() *OrganizationProfile`

NewOrganizationProfileWithDefaults instantiates a new OrganizationProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndustry

`func (o *OrganizationProfile) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *OrganizationProfile) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *OrganizationProfile) SetIndustry(v string)`

SetIndustry sets Industry field to given value.


### SetIndustryNil

`func (o *OrganizationProfile) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *OrganizationProfile) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetTeamSize

`func (o *OrganizationProfile) GetTeamSize() TeamSize`

GetTeamSize returns the TeamSize field if non-nil, zero value otherwise.

### GetTeamSizeOk

`func (o *OrganizationProfile) GetTeamSizeOk() (*TeamSize, bool)`

GetTeamSizeOk returns a tuple with the TeamSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamSize

`func (o *OrganizationProfile) SetTeamSize(v TeamSize)`

SetTeamSize sets TeamSize field to given value.


### SetTeamSizeNil

`func (o *OrganizationProfile) SetTeamSizeNil(b bool)`

 SetTeamSizeNil sets the value for TeamSize to be an explicit nil

### UnsetTeamSize
`func (o *OrganizationProfile) UnsetTeamSize()`

UnsetTeamSize ensures that no value is present for TeamSize, not even an explicit nil
### GetWebsite

`func (o *OrganizationProfile) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *OrganizationProfile) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *OrganizationProfile) SetWebsite(v string)`

SetWebsite sets Website field to given value.


### SetWebsiteNil

`func (o *OrganizationProfile) SetWebsiteNil(b bool)`

 SetWebsiteNil sets the value for Website to be an explicit nil

### UnsetWebsite
`func (o *OrganizationProfile) UnsetWebsite()`

UnsetWebsite ensures that no value is present for Website, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


