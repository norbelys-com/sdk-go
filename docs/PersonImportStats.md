# PersonImportStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **int32** | New people this import inserted. | 
**Id** | **string** | The import id. | 
**Object** | Pointer to **interface{}** |  | [optional] 
**Pending** | **int32** | Created people still awaiting a verdict (&#x60;created − processed&#x60;). | 
**Processed** | **int32** | How many of the created people have been verified so far. | 
**Reasons** | [**[]PersonImportReason**](PersonImportReason.md) | The cleaning report: WHAT the verification found, per reason — which addresses were removed as dead domains, likely typos, disposables, previously bounced, and so on. Ordered by count, descending. | 
**Sendable** | **int32** | Verified and safe to email. | 
**Status** | **string** | &#x60;processing&#x60; while addresses are still being verified, &#x60;completed&#x60; once every created person has a verdict. | 
**SuppressedExisting** | **int32** | Already on the suppression list before the import, so verification was skipped. | 
**SuppressedNew** | **int32** | Newly suppressed by an undeliverable verdict. | 

## Methods

### NewPersonImportStats

`func NewPersonImportStats(created int32, id string, pending int32, processed int32, reasons []PersonImportReason, sendable int32, status string, suppressedExisting int32, suppressedNew int32, ) *PersonImportStats`

NewPersonImportStats instantiates a new PersonImportStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonImportStatsWithDefaults

`func NewPersonImportStatsWithDefaults() *PersonImportStats`

NewPersonImportStatsWithDefaults instantiates a new PersonImportStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *PersonImportStats) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PersonImportStats) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PersonImportStats) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetId

`func (o *PersonImportStats) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonImportStats) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonImportStats) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *PersonImportStats) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *PersonImportStats) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *PersonImportStats) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *PersonImportStats) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *PersonImportStats) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *PersonImportStats) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetPending

`func (o *PersonImportStats) GetPending() int32`

GetPending returns the Pending field if non-nil, zero value otherwise.

### GetPendingOk

`func (o *PersonImportStats) GetPendingOk() (*int32, bool)`

GetPendingOk returns a tuple with the Pending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPending

`func (o *PersonImportStats) SetPending(v int32)`

SetPending sets Pending field to given value.


### GetProcessed

`func (o *PersonImportStats) GetProcessed() int32`

GetProcessed returns the Processed field if non-nil, zero value otherwise.

### GetProcessedOk

`func (o *PersonImportStats) GetProcessedOk() (*int32, bool)`

GetProcessedOk returns a tuple with the Processed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessed

`func (o *PersonImportStats) SetProcessed(v int32)`

SetProcessed sets Processed field to given value.


### GetReasons

`func (o *PersonImportStats) GetReasons() []PersonImportReason`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *PersonImportStats) GetReasonsOk() (*[]PersonImportReason, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *PersonImportStats) SetReasons(v []PersonImportReason)`

SetReasons sets Reasons field to given value.


### GetSendable

`func (o *PersonImportStats) GetSendable() int32`

GetSendable returns the Sendable field if non-nil, zero value otherwise.

### GetSendableOk

`func (o *PersonImportStats) GetSendableOk() (*int32, bool)`

GetSendableOk returns a tuple with the Sendable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendable

`func (o *PersonImportStats) SetSendable(v int32)`

SetSendable sets Sendable field to given value.


### GetStatus

`func (o *PersonImportStats) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PersonImportStats) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PersonImportStats) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSuppressedExisting

`func (o *PersonImportStats) GetSuppressedExisting() int32`

GetSuppressedExisting returns the SuppressedExisting field if non-nil, zero value otherwise.

### GetSuppressedExistingOk

`func (o *PersonImportStats) GetSuppressedExistingOk() (*int32, bool)`

GetSuppressedExistingOk returns a tuple with the SuppressedExisting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressedExisting

`func (o *PersonImportStats) SetSuppressedExisting(v int32)`

SetSuppressedExisting sets SuppressedExisting field to given value.


### GetSuppressedNew

`func (o *PersonImportStats) GetSuppressedNew() int32`

GetSuppressedNew returns the SuppressedNew field if non-nil, zero value otherwise.

### GetSuppressedNewOk

`func (o *PersonImportStats) GetSuppressedNewOk() (*int32, bool)`

GetSuppressedNewOk returns a tuple with the SuppressedNew field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressedNew

`func (o *PersonImportStats) SetSuppressedNew(v int32)`

SetSuppressedNew sets SuppressedNew field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


