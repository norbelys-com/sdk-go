# MessageAttachmentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | Pointer to **string** | MIME type; defaults to application/octet-stream. | [optional] 
**Filename** | **string** | File name shown to the recipient. | 
**Content** | **string** | Base64-encoded file content. | 

## Methods

### NewMessageAttachmentInput

`func NewMessageAttachmentInput(filename string, content string, ) *MessageAttachmentInput`

NewMessageAttachmentInput instantiates a new MessageAttachmentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageAttachmentInputWithDefaults

`func NewMessageAttachmentInputWithDefaults() *MessageAttachmentInput`

NewMessageAttachmentInputWithDefaults instantiates a new MessageAttachmentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContentType

`func (o *MessageAttachmentInput) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *MessageAttachmentInput) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *MessageAttachmentInput) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *MessageAttachmentInput) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetFilename

`func (o *MessageAttachmentInput) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *MessageAttachmentInput) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *MessageAttachmentInput) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetContent

`func (o *MessageAttachmentInput) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *MessageAttachmentInput) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *MessageAttachmentInput) SetContent(v string)`

SetContent sets Content field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


