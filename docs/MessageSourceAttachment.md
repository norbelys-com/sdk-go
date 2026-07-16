# MessageSourceAttachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentId** | Pointer to **string** | Inline-image Content-ID (for &#x60;cid:&#x60; references), if any. | [optional] 
**ContentType** | Pointer to **string** | MIME type. | [optional] 
**Filename** | **string** | File name. | 

## Methods

### NewMessageSourceAttachment

`func NewMessageSourceAttachment(filename string, ) *MessageSourceAttachment`

NewMessageSourceAttachment instantiates a new MessageSourceAttachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageSourceAttachmentWithDefaults

`func NewMessageSourceAttachmentWithDefaults() *MessageSourceAttachment`

NewMessageSourceAttachmentWithDefaults instantiates a new MessageSourceAttachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContentId

`func (o *MessageSourceAttachment) GetContentId() string`

GetContentId returns the ContentId field if non-nil, zero value otherwise.

### GetContentIdOk

`func (o *MessageSourceAttachment) GetContentIdOk() (*string, bool)`

GetContentIdOk returns a tuple with the ContentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentId

`func (o *MessageSourceAttachment) SetContentId(v string)`

SetContentId sets ContentId field to given value.

### HasContentId

`func (o *MessageSourceAttachment) HasContentId() bool`

HasContentId returns a boolean if a field has been set.

### GetContentType

`func (o *MessageSourceAttachment) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *MessageSourceAttachment) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *MessageSourceAttachment) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *MessageSourceAttachment) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetFilename

`func (o *MessageSourceAttachment) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *MessageSourceAttachment) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *MessageSourceAttachment) SetFilename(v string)`

SetFilename sets Filename field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


