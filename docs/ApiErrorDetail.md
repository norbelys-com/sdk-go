# ApiErrorDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Stable machine code — branch on this, never on the human &#x60;message&#x60;. | 
**DocUrl** | Pointer to **string** | Optional link to the relevant documentation. | [optional] 
**Hint** | Pointer to **string** | Optional one-sentence remediation. | [optional] 
**Message** | **string** | Human-readable explanation. Never a contract. | 
**Type** | **string** | Broad, machine-routable category derived from the HTTP status. | 

## Methods

### NewApiErrorDetail

`func NewApiErrorDetail(code string, message string, type_ string, ) *ApiErrorDetail`

NewApiErrorDetail instantiates a new ApiErrorDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiErrorDetailWithDefaults

`func NewApiErrorDetailWithDefaults() *ApiErrorDetail`

NewApiErrorDetailWithDefaults instantiates a new ApiErrorDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ApiErrorDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ApiErrorDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ApiErrorDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetDocUrl

`func (o *ApiErrorDetail) GetDocUrl() string`

GetDocUrl returns the DocUrl field if non-nil, zero value otherwise.

### GetDocUrlOk

`func (o *ApiErrorDetail) GetDocUrlOk() (*string, bool)`

GetDocUrlOk returns a tuple with the DocUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocUrl

`func (o *ApiErrorDetail) SetDocUrl(v string)`

SetDocUrl sets DocUrl field to given value.

### HasDocUrl

`func (o *ApiErrorDetail) HasDocUrl() bool`

HasDocUrl returns a boolean if a field has been set.

### GetHint

`func (o *ApiErrorDetail) GetHint() string`

GetHint returns the Hint field if non-nil, zero value otherwise.

### GetHintOk

`func (o *ApiErrorDetail) GetHintOk() (*string, bool)`

GetHintOk returns a tuple with the Hint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHint

`func (o *ApiErrorDetail) SetHint(v string)`

SetHint sets Hint field to given value.

### HasHint

`func (o *ApiErrorDetail) HasHint() bool`

HasHint returns a boolean if a field has been set.

### GetMessage

`func (o *ApiErrorDetail) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiErrorDetail) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiErrorDetail) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetType

`func (o *ApiErrorDetail) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ApiErrorDetail) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ApiErrorDetail) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


