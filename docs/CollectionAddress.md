# CollectionAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **string** | The full &#x60;rua&#x60; mailto address to put in your DMARC record. | 
**CreatedAt** | Pointer to **interface{}** |  | [optional] 
**Id** | **string** | The collection-address id. | 
**Kind** | **string** | What this collection address ingests: &#x60;dmarc_rua&#x60;, &#x60;dmarc_ruf&#x60;, &#x60;tls_rpt&#x60;, or &#x60;fbl&#x60; (only &#x60;dmarc_rua&#x60; is active today). | 
**Object** | Pointer to **interface{}** |  | [optional] 
**RevokedAt** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewCollectionAddress

`func NewCollectionAddress(address string, id string, kind string, ) *CollectionAddress`

NewCollectionAddress instantiates a new CollectionAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionAddressWithDefaults

`func NewCollectionAddressWithDefaults() *CollectionAddress`

NewCollectionAddressWithDefaults instantiates a new CollectionAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *CollectionAddress) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CollectionAddress) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CollectionAddress) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCreatedAt

`func (o *CollectionAddress) GetCreatedAt() interface{}`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CollectionAddress) GetCreatedAtOk() (*interface{}, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CollectionAddress) SetCreatedAt(v interface{})`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CollectionAddress) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *CollectionAddress) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *CollectionAddress) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetId

`func (o *CollectionAddress) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionAddress) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionAddress) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *CollectionAddress) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CollectionAddress) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CollectionAddress) SetKind(v string)`

SetKind sets Kind field to given value.


### GetObject

`func (o *CollectionAddress) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CollectionAddress) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CollectionAddress) SetObject(v interface{})`

SetObject sets Object field to given value.

### HasObject

`func (o *CollectionAddress) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *CollectionAddress) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *CollectionAddress) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetRevokedAt

`func (o *CollectionAddress) GetRevokedAt() interface{}`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *CollectionAddress) GetRevokedAtOk() (*interface{}, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *CollectionAddress) SetRevokedAt(v interface{})`

SetRevokedAt sets RevokedAt field to given value.

### HasRevokedAt

`func (o *CollectionAddress) HasRevokedAt() bool`

HasRevokedAt returns a boolean if a field has been set.

### SetRevokedAtNil

`func (o *CollectionAddress) SetRevokedAtNil(b bool)`

 SetRevokedAtNil sets the value for RevokedAt to be an explicit nil

### UnsetRevokedAt
`func (o *CollectionAddress) UnsetRevokedAt()`

UnsetRevokedAt ensures that no value is present for RevokedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


