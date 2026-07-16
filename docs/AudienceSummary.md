# AudienceSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AverageScore** | **NullableFloat32** |  | 
**Engaged30d** | **int32** | People whose last recorded activity was in the last 30 days. | 
**Status** | [**[]AudienceStatusBreakdown**](AudienceStatusBreakdown.md) | Exact lifecycle-status distribution for the current audience. | 
**Total** | **int32** | Current people in the selected audience or whole workspace. | 
**WeeklyCreated** | [**[]AudienceWeekPoint**](AudienceWeekPoint.md) | Current audience members grouped by the week they first entered the workspace, limited to the last 12 weeks. | 

## Methods

### NewAudienceSummary

`func NewAudienceSummary(averageScore NullableFloat32, engaged30d int32, status []AudienceStatusBreakdown, total int32, weeklyCreated []AudienceWeekPoint, ) *AudienceSummary`

NewAudienceSummary instantiates a new AudienceSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudienceSummaryWithDefaults

`func NewAudienceSummaryWithDefaults() *AudienceSummary`

NewAudienceSummaryWithDefaults instantiates a new AudienceSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAverageScore

`func (o *AudienceSummary) GetAverageScore() float32`

GetAverageScore returns the AverageScore field if non-nil, zero value otherwise.

### GetAverageScoreOk

`func (o *AudienceSummary) GetAverageScoreOk() (*float32, bool)`

GetAverageScoreOk returns a tuple with the AverageScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageScore

`func (o *AudienceSummary) SetAverageScore(v float32)`

SetAverageScore sets AverageScore field to given value.


### SetAverageScoreNil

`func (o *AudienceSummary) SetAverageScoreNil(b bool)`

 SetAverageScoreNil sets the value for AverageScore to be an explicit nil

### UnsetAverageScore
`func (o *AudienceSummary) UnsetAverageScore()`

UnsetAverageScore ensures that no value is present for AverageScore, not even an explicit nil
### GetEngaged30d

`func (o *AudienceSummary) GetEngaged30d() int32`

GetEngaged30d returns the Engaged30d field if non-nil, zero value otherwise.

### GetEngaged30dOk

`func (o *AudienceSummary) GetEngaged30dOk() (*int32, bool)`

GetEngaged30dOk returns a tuple with the Engaged30d field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngaged30d

`func (o *AudienceSummary) SetEngaged30d(v int32)`

SetEngaged30d sets Engaged30d field to given value.


### GetStatus

`func (o *AudienceSummary) GetStatus() []AudienceStatusBreakdown`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AudienceSummary) GetStatusOk() (*[]AudienceStatusBreakdown, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AudienceSummary) SetStatus(v []AudienceStatusBreakdown)`

SetStatus sets Status field to given value.


### GetTotal

`func (o *AudienceSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AudienceSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AudienceSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetWeeklyCreated

`func (o *AudienceSummary) GetWeeklyCreated() []AudienceWeekPoint`

GetWeeklyCreated returns the WeeklyCreated field if non-nil, zero value otherwise.

### GetWeeklyCreatedOk

`func (o *AudienceSummary) GetWeeklyCreatedOk() (*[]AudienceWeekPoint, bool)`

GetWeeklyCreatedOk returns a tuple with the WeeklyCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyCreated

`func (o *AudienceSummary) SetWeeklyCreated(v []AudienceWeekPoint)`

SetWeeklyCreated sets WeeklyCreated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


