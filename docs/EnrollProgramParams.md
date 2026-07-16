# EnrollProgramParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**All** | Pointer to **interface{}** | Enroll EVERY active person. Required explicitly — omitting all selectors is an error, never an implicit enroll-everyone. | [optional] 
**GroupIds** | Pointer to **[]string** | Enroll every LIVE person in these groups (static lists) — several at once, resolved as one union. | [optional] 
**ImportIds** | Pointer to **[]string** | When the &#x60;personIds&#x60; came from CSV imports, the import ids — each is recorded as an audience source so the campaign shows where its people came from. | [optional] 
**Mode** | Pointer to **string** | &#x60;snapshot&#x60; (default): enroll the CURRENT matches once and freeze. &#x60;reactive&#x60;: also keep the campaign in sync with EVERY given segment — new people are enrolled automatically as they come to match. Groups are static lists, so they always behave as snapshots. | [optional] 
**PersonIds** | Pointer to **[]string** | Explicit person ids (CSV/preview-resolved sets). | [optional] 
**SegmentIds** | Pointer to **[]string** | Enroll every person CURRENTLY matching these segments (saved filters) — several at once, resolved as one union. | [optional] 

## Methods

### NewEnrollProgramParams

`func NewEnrollProgramParams() *EnrollProgramParams`

NewEnrollProgramParams instantiates a new EnrollProgramParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrollProgramParamsWithDefaults

`func NewEnrollProgramParamsWithDefaults() *EnrollProgramParams`

NewEnrollProgramParamsWithDefaults instantiates a new EnrollProgramParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAll

`func (o *EnrollProgramParams) GetAll() interface{}`

GetAll returns the All field if non-nil, zero value otherwise.

### GetAllOk

`func (o *EnrollProgramParams) GetAllOk() (*interface{}, bool)`

GetAllOk returns a tuple with the All field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAll

`func (o *EnrollProgramParams) SetAll(v interface{})`

SetAll sets All field to given value.

### HasAll

`func (o *EnrollProgramParams) HasAll() bool`

HasAll returns a boolean if a field has been set.

### SetAllNil

`func (o *EnrollProgramParams) SetAllNil(b bool)`

 SetAllNil sets the value for All to be an explicit nil

### UnsetAll
`func (o *EnrollProgramParams) UnsetAll()`

UnsetAll ensures that no value is present for All, not even an explicit nil
### GetGroupIds

`func (o *EnrollProgramParams) GetGroupIds() []string`

GetGroupIds returns the GroupIds field if non-nil, zero value otherwise.

### GetGroupIdsOk

`func (o *EnrollProgramParams) GetGroupIdsOk() (*[]string, bool)`

GetGroupIdsOk returns a tuple with the GroupIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupIds

`func (o *EnrollProgramParams) SetGroupIds(v []string)`

SetGroupIds sets GroupIds field to given value.

### HasGroupIds

`func (o *EnrollProgramParams) HasGroupIds() bool`

HasGroupIds returns a boolean if a field has been set.

### GetImportIds

`func (o *EnrollProgramParams) GetImportIds() []string`

GetImportIds returns the ImportIds field if non-nil, zero value otherwise.

### GetImportIdsOk

`func (o *EnrollProgramParams) GetImportIdsOk() (*[]string, bool)`

GetImportIdsOk returns a tuple with the ImportIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportIds

`func (o *EnrollProgramParams) SetImportIds(v []string)`

SetImportIds sets ImportIds field to given value.

### HasImportIds

`func (o *EnrollProgramParams) HasImportIds() bool`

HasImportIds returns a boolean if a field has been set.

### GetMode

`func (o *EnrollProgramParams) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *EnrollProgramParams) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *EnrollProgramParams) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *EnrollProgramParams) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetPersonIds

`func (o *EnrollProgramParams) GetPersonIds() []string`

GetPersonIds returns the PersonIds field if non-nil, zero value otherwise.

### GetPersonIdsOk

`func (o *EnrollProgramParams) GetPersonIdsOk() (*[]string, bool)`

GetPersonIdsOk returns a tuple with the PersonIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonIds

`func (o *EnrollProgramParams) SetPersonIds(v []string)`

SetPersonIds sets PersonIds field to given value.

### HasPersonIds

`func (o *EnrollProgramParams) HasPersonIds() bool`

HasPersonIds returns a boolean if a field has been set.

### GetSegmentIds

`func (o *EnrollProgramParams) GetSegmentIds() []string`

GetSegmentIds returns the SegmentIds field if non-nil, zero value otherwise.

### GetSegmentIdsOk

`func (o *EnrollProgramParams) GetSegmentIdsOk() (*[]string, bool)`

GetSegmentIdsOk returns a tuple with the SegmentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentIds

`func (o *EnrollProgramParams) SetSegmentIds(v []string)`

SetSegmentIds sets SegmentIds field to given value.

### HasSegmentIds

`func (o *EnrollProgramParams) HasSegmentIds() bool`

HasSegmentIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


