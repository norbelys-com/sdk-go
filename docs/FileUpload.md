# FileUpload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** | Base64-encoded file content (max 8 MB decoded). Example: iVBORw0KGgoAAAANSUhEUgAA… | 
**ContentType** | **string** | MIME type — an &#x60;image/_*&#x60; type or &#x60;application/pdf&#x60;. Example: image/png | 
**Filename** | **string** | Original file name — kept (sanitized) as the URL&#39;s last segment. Example: logo.png | 

## Methods

### NewFileUpload

`func NewFileUpload(content string, contentType string, filename string, ) *FileUpload`

NewFileUpload instantiates a new FileUpload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileUploadWithDefaults

`func NewFileUploadWithDefaults() *FileUpload`

NewFileUploadWithDefaults instantiates a new FileUpload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *FileUpload) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *FileUpload) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *FileUpload) SetContent(v string)`

SetContent sets Content field to given value.


### GetContentType

`func (o *FileUpload) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *FileUpload) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *FileUpload) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetFilename

`func (o *FileUpload) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FileUpload) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FileUpload) SetFilename(v string)`

SetFilename sets Filename field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


