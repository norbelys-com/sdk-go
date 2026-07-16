# IntegrationSyncResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Queued** | [**[]SyncModel**](SyncModel.md) | The record types queued to sync: &#x60;Lead&#x60;, &#x60;Deal&#x60;, &#x60;Meeting&#x60;. | 

## Methods

### NewIntegrationSyncResult

`func NewIntegrationSyncResult(queued []SyncModel, ) *IntegrationSyncResult`

NewIntegrationSyncResult instantiates a new IntegrationSyncResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrationSyncResultWithDefaults

`func NewIntegrationSyncResultWithDefaults() *IntegrationSyncResult`

NewIntegrationSyncResultWithDefaults instantiates a new IntegrationSyncResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQueued

`func (o *IntegrationSyncResult) GetQueued() []SyncModel`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *IntegrationSyncResult) GetQueuedOk() (*[]SyncModel, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *IntegrationSyncResult) SetQueued(v []SyncModel)`

SetQueued sets Queued field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


