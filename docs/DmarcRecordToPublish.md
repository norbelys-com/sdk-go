# DmarcRecordToPublish

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | The DNS host to create. | 
**Type** | **interface{}** |  | 
**Value** | **string** | The exact TXT value to publish, verbatim. Points DMARC &#x60;rua&#x60; at your collection address; if a &#x60;_dmarc&#x60; record already exists, this value keeps yours and adds the &#x60;rua&#x60;. | 

## Methods

### NewDmarcRecordToPublish

`func NewDmarcRecordToPublish(host string, type_ interface{}, value string, ) *DmarcRecordToPublish`

NewDmarcRecordToPublish instantiates a new DmarcRecordToPublish object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDmarcRecordToPublishWithDefaults

`func NewDmarcRecordToPublishWithDefaults() *DmarcRecordToPublish`

NewDmarcRecordToPublishWithDefaults instantiates a new DmarcRecordToPublish object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *DmarcRecordToPublish) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *DmarcRecordToPublish) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *DmarcRecordToPublish) SetHost(v string)`

SetHost sets Host field to given value.


### GetType

`func (o *DmarcRecordToPublish) GetType() interface{}`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DmarcRecordToPublish) GetTypeOk() (*interface{}, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DmarcRecordToPublish) SetType(v interface{})`

SetType sets Type field to given value.


### SetTypeNil

`func (o *DmarcRecordToPublish) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *DmarcRecordToPublish) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetValue

`func (o *DmarcRecordToPublish) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *DmarcRecordToPublish) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *DmarcRecordToPublish) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


