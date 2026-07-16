# MessageAttachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentId** | Pointer to **NullableString** |  | [optional] 
**ContentType** | **string** | MIME type. | 
**Filename** | **string** | File name. | 
**Disposition** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** | The attachment id within the message. | 
**Size** | **int32** | Decoded file size in bytes. | 

## Methods

### NewMessageAttachment

`func NewMessageAttachment(contentType string, filename string, id string, size int32, ) *MessageAttachment`

NewMessageAttachment instantiates a new MessageAttachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageAttachmentWithDefaults

`func NewMessageAttachmentWithDefaults() *MessageAttachment`

NewMessageAttachmentWithDefaults instantiates a new MessageAttachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContentId

`func (o *MessageAttachment) GetContentId() string`

GetContentId returns the ContentId field if non-nil, zero value otherwise.

### GetContentIdOk

`func (o *MessageAttachment) GetContentIdOk() (*string, bool)`

GetContentIdOk returns a tuple with the ContentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentId

`func (o *MessageAttachment) SetContentId(v string)`

SetContentId sets ContentId field to given value.

### HasContentId

`func (o *MessageAttachment) HasContentId() bool`

HasContentId returns a boolean if a field has been set.

### SetContentIdNil

`func (o *MessageAttachment) SetContentIdNil(b bool)`

 SetContentIdNil sets the value for ContentId to be an explicit nil

### UnsetContentId
`func (o *MessageAttachment) UnsetContentId()`

UnsetContentId ensures that no value is present for ContentId, not even an explicit nil
### GetContentType

`func (o *MessageAttachment) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *MessageAttachment) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *MessageAttachment) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetFilename

`func (o *MessageAttachment) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *MessageAttachment) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *MessageAttachment) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetDisposition

`func (o *MessageAttachment) GetDisposition() string`

GetDisposition returns the Disposition field if non-nil, zero value otherwise.

### GetDispositionOk

`func (o *MessageAttachment) GetDispositionOk() (*string, bool)`

GetDispositionOk returns a tuple with the Disposition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisposition

`func (o *MessageAttachment) SetDisposition(v string)`

SetDisposition sets Disposition field to given value.

### HasDisposition

`func (o *MessageAttachment) HasDisposition() bool`

HasDisposition returns a boolean if a field has been set.

### SetDispositionNil

`func (o *MessageAttachment) SetDispositionNil(b bool)`

 SetDispositionNil sets the value for Disposition to be an explicit nil

### UnsetDisposition
`func (o *MessageAttachment) UnsetDisposition()`

UnsetDisposition ensures that no value is present for Disposition, not even an explicit nil
### GetId

`func (o *MessageAttachment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageAttachment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageAttachment) SetId(v string)`

SetId sets Id field to given value.


### GetSize

`func (o *MessageAttachment) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *MessageAttachment) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *MessageAttachment) SetSize(v int32)`

SetSize sets Size field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


