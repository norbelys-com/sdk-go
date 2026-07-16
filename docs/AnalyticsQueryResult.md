# AnalyticsQueryResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | **[]map[string]interface{}** | The result rows, one flat object per row. | 
**Rows** | **int32** | Number of rows returned. | 

## Methods

### NewAnalyticsQueryResult

`func NewAnalyticsQueryResult(data []map[string]interface{}, rows int32, ) *AnalyticsQueryResult`

NewAnalyticsQueryResult instantiates a new AnalyticsQueryResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsQueryResultWithDefaults

`func NewAnalyticsQueryResultWithDefaults() *AnalyticsQueryResult`

NewAnalyticsQueryResultWithDefaults instantiates a new AnalyticsQueryResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AnalyticsQueryResult) GetData() []map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsQueryResult) GetDataOk() (*[]map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsQueryResult) SetData(v []map[string]interface{})`

SetData sets Data field to given value.


### GetRows

`func (o *AnalyticsQueryResult) GetRows() int32`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *AnalyticsQueryResult) GetRowsOk() (*int32, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *AnalyticsQueryResult) SetRows(v int32)`

SetRows sets Rows field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


