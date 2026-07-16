# OrganizationUpdateParamsProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Industry** | Pointer to **string** | Free-text industry label. | [optional] 
**TeamSize** | Pointer to **string** | Coarse team-size bucket: &#x60;1&#x60;, &#x60;2-10&#x60;, &#x60;11-50&#x60;, &#x60;51-200&#x60;, or &#x60;201+&#x60;. | [optional] 
**Website** | Pointer to **string** | The company website URL. | [optional] 

## Methods

### NewOrganizationUpdateParamsProfile

`func NewOrganizationUpdateParamsProfile() *OrganizationUpdateParamsProfile`

NewOrganizationUpdateParamsProfile instantiates a new OrganizationUpdateParamsProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationUpdateParamsProfileWithDefaults

`func NewOrganizationUpdateParamsProfileWithDefaults() *OrganizationUpdateParamsProfile`

NewOrganizationUpdateParamsProfileWithDefaults instantiates a new OrganizationUpdateParamsProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndustry

`func (o *OrganizationUpdateParamsProfile) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *OrganizationUpdateParamsProfile) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *OrganizationUpdateParamsProfile) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *OrganizationUpdateParamsProfile) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetTeamSize

`func (o *OrganizationUpdateParamsProfile) GetTeamSize() string`

GetTeamSize returns the TeamSize field if non-nil, zero value otherwise.

### GetTeamSizeOk

`func (o *OrganizationUpdateParamsProfile) GetTeamSizeOk() (*string, bool)`

GetTeamSizeOk returns a tuple with the TeamSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamSize

`func (o *OrganizationUpdateParamsProfile) SetTeamSize(v string)`

SetTeamSize sets TeamSize field to given value.

### HasTeamSize

`func (o *OrganizationUpdateParamsProfile) HasTeamSize() bool`

HasTeamSize returns a boolean if a field has been set.

### GetWebsite

`func (o *OrganizationUpdateParamsProfile) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *OrganizationUpdateParamsProfile) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *OrganizationUpdateParamsProfile) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *OrganizationUpdateParamsProfile) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


