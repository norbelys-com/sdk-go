# MessageAttachmentDownload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentId** | Pointer to **NullableString** |  | [optional] 
**ContentType** | **string** | MIME type. | 
**Filename** | **string** | File name. | 
**Disposition** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** | The attachment id within the message. | 
**Size** | **int32** | Decoded file size in bytes. | 
**Content** | **string** | Base64-encoded file content — decode to get the file. | 
**Object** | **interface{}** |  | 

## Methods

### NewMessageAttachmentDownload

`func NewMessageAttachmentDownload(contentType string, filename string, id string, size int32, content string, object interface{}, ) *MessageAttachmentDownload`

NewMessageAttachmentDownload instantiates a new MessageAttachmentDownload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageAttachmentDownloadWithDefaults

`func NewMessageAttachmentDownloadWithDefaults() *MessageAttachmentDownload`

NewMessageAttachmentDownloadWithDefaults instantiates a new MessageAttachmentDownload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContentId

`func (o *MessageAttachmentDownload) GetContentId() string`

GetContentId returns the ContentId field if non-nil, zero value otherwise.

### GetContentIdOk

`func (o *MessageAttachmentDownload) GetContentIdOk() (*string, bool)`

GetContentIdOk returns a tuple with the ContentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentId

`func (o *MessageAttachmentDownload) SetContentId(v string)`

SetContentId sets ContentId field to given value.

### HasContentId

`func (o *MessageAttachmentDownload) HasContentId() bool`

HasContentId returns a boolean if a field has been set.

### SetContentIdNil

`func (o *MessageAttachmentDownload) SetContentIdNil(b bool)`

 SetContentIdNil sets the value for ContentId to be an explicit nil

### UnsetContentId
`func (o *MessageAttachmentDownload) UnsetContentId()`

UnsetContentId ensures that no value is present for ContentId, not even an explicit nil
### GetContentType

`func (o *MessageAttachmentDownload) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *MessageAttachmentDownload) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *MessageAttachmentDownload) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetFilename

`func (o *MessageAttachmentDownload) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *MessageAttachmentDownload) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *MessageAttachmentDownload) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetDisposition

`func (o *MessageAttachmentDownload) GetDisposition() string`

GetDisposition returns the Disposition field if non-nil, zero value otherwise.

### GetDispositionOk

`func (o *MessageAttachmentDownload) GetDispositionOk() (*string, bool)`

GetDispositionOk returns a tuple with the Disposition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisposition

`func (o *MessageAttachmentDownload) SetDisposition(v string)`

SetDisposition sets Disposition field to given value.

### HasDisposition

`func (o *MessageAttachmentDownload) HasDisposition() bool`

HasDisposition returns a boolean if a field has been set.

### SetDispositionNil

`func (o *MessageAttachmentDownload) SetDispositionNil(b bool)`

 SetDispositionNil sets the value for Disposition to be an explicit nil

### UnsetDisposition
`func (o *MessageAttachmentDownload) UnsetDisposition()`

UnsetDisposition ensures that no value is present for Disposition, not even an explicit nil
### GetId

`func (o *MessageAttachmentDownload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageAttachmentDownload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageAttachmentDownload) SetId(v string)`

SetId sets Id field to given value.


### GetSize

`func (o *MessageAttachmentDownload) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *MessageAttachmentDownload) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *MessageAttachmentDownload) SetSize(v int32)`

SetSize sets Size field to given value.


### GetContent

`func (o *MessageAttachmentDownload) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *MessageAttachmentDownload) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *MessageAttachmentDownload) SetContent(v string)`

SetContent sets Content field to given value.


### GetObject

`func (o *MessageAttachmentDownload) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *MessageAttachmentDownload) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *MessageAttachmentDownload) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *MessageAttachmentDownload) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *MessageAttachmentDownload) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


