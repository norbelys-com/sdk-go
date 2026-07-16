# OrganizationProfileParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Industry** | Pointer to **string** | Free-text industry label. | [optional] 
**TeamSize** | Pointer to **string** | Coarse team-size bucket: &#x60;1&#x60;, &#x60;2-10&#x60;, &#x60;11-50&#x60;, &#x60;51-200&#x60;, or &#x60;201+&#x60;. | [optional] 
**Website** | Pointer to **string** | The company website URL. | [optional] 

## Methods

### NewOrganizationProfileParams

`func NewOrganizationProfileParams() *OrganizationProfileParams`

NewOrganizationProfileParams instantiates a new OrganizationProfileParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationProfileParamsWithDefaults

`func NewOrganizationProfileParamsWithDefaults() *OrganizationProfileParams`

NewOrganizationProfileParamsWithDefaults instantiates a new OrganizationProfileParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndustry

`func (o *OrganizationProfileParams) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *OrganizationProfileParams) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *OrganizationProfileParams) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *OrganizationProfileParams) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetTeamSize

`func (o *OrganizationProfileParams) GetTeamSize() string`

GetTeamSize returns the TeamSize field if non-nil, zero value otherwise.

### GetTeamSizeOk

`func (o *OrganizationProfileParams) GetTeamSizeOk() (*string, bool)`

GetTeamSizeOk returns a tuple with the TeamSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamSize

`func (o *OrganizationProfileParams) SetTeamSize(v string)`

SetTeamSize sets TeamSize field to given value.

### HasTeamSize

`func (o *OrganizationProfileParams) HasTeamSize() bool`

HasTeamSize returns a boolean if a field has been set.

### GetWebsite

`func (o *OrganizationProfileParams) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *OrganizationProfileParams) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *OrganizationProfileParams) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *OrganizationProfileParams) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


