# AnalyticsQuery

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Params** | Pointer to [**AnalyticsQueryParams**](AnalyticsQueryParams.md) |  | [optional] 
**Query** | [**AnalyticsQueryName**](AnalyticsQueryName.md) |  | 

## Methods

### NewAnalyticsQuery

`func NewAnalyticsQuery(query AnalyticsQueryName, ) *AnalyticsQuery`

NewAnalyticsQuery instantiates a new AnalyticsQuery object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsQueryWithDefaults

`func NewAnalyticsQueryWithDefaults() *AnalyticsQuery`

NewAnalyticsQueryWithDefaults instantiates a new AnalyticsQuery object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetParams

`func (o *AnalyticsQuery) GetParams() AnalyticsQueryParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *AnalyticsQuery) GetParamsOk() (*AnalyticsQueryParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *AnalyticsQuery) SetParams(v AnalyticsQueryParams)`

SetParams sets Params field to given value.

### HasParams

`func (o *AnalyticsQuery) HasParams() bool`

HasParams returns a boolean if a field has been set.

### GetQuery

`func (o *AnalyticsQuery) GetQuery() AnalyticsQueryName`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *AnalyticsQuery) GetQueryOk() (*AnalyticsQueryName, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *AnalyticsQuery) SetQuery(v AnalyticsQueryName)`

SetQuery sets Query field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


