# MessageEnrollParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **map[string]interface{}** | Template variables merged over the person&#39;s fields at render time. | [optional] 
**From** | **string** | Who the message is sent from — a sender id, or any email address on a sending domain you&#39;ve set up (a sender identity is created automatically on first use). | 
**To** | **string** | Recipient email address. | 
**ToName** | Pointer to **string** | Recipient display name. | [optional] 
**Sequence** | **string** | Id of a program to enroll the person into instead of sending now; the program then controls send timing. Required for a cold-email sender (those send on a paced schedule, not immediately). | 

## Methods

### NewMessageEnrollParams

`func NewMessageEnrollParams(from string, to string, sequence string, ) *MessageEnrollParams`

NewMessageEnrollParams instantiates a new MessageEnrollParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageEnrollParamsWithDefaults

`func NewMessageEnrollParamsWithDefaults() *MessageEnrollParams`

NewMessageEnrollParamsWithDefaults instantiates a new MessageEnrollParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MessageEnrollParams) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessageEnrollParams) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessageEnrollParams) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MessageEnrollParams) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFrom

`func (o *MessageEnrollParams) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *MessageEnrollParams) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *MessageEnrollParams) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *MessageEnrollParams) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *MessageEnrollParams) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *MessageEnrollParams) SetTo(v string)`

SetTo sets To field to given value.


### GetToName

`func (o *MessageEnrollParams) GetToName() string`

GetToName returns the ToName field if non-nil, zero value otherwise.

### GetToNameOk

`func (o *MessageEnrollParams) GetToNameOk() (*string, bool)`

GetToNameOk returns a tuple with the ToName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToName

`func (o *MessageEnrollParams) SetToName(v string)`

SetToName sets ToName field to given value.

### HasToName

`func (o *MessageEnrollParams) HasToName() bool`

HasToName returns a boolean if a field has been set.

### GetSequence

`func (o *MessageEnrollParams) GetSequence() string`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *MessageEnrollParams) GetSequenceOk() (*string, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *MessageEnrollParams) SetSequence(v string)`

SetSequence sets Sequence field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


