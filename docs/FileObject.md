# FileObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **string** | MIME type. Example: image/png | 
**Filename** | **string** | The sanitized file name. Example: logo.png | 
**Id** | **string** | The file id. | 
**Object** | **interface{}** |  | 
**Size** | **int32** | Decoded size in bytes. Example: 24680 | 
**Url** | **string** | The permanent public URL. | 

## Methods

### NewFileObject

`func NewFileObject(contentType string, filename string, id string, object interface{}, size int32, url string, ) *FileObject`

NewFileObject instantiates a new FileObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileObjectWithDefaults

`func NewFileObjectWithDefaults() *FileObject`

NewFileObjectWithDefaults instantiates a new FileObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContentType

`func (o *FileObject) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *FileObject) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *FileObject) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetFilename

`func (o *FileObject) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FileObject) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FileObject) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetId

`func (o *FileObject) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FileObject) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FileObject) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *FileObject) GetObject() interface{}`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *FileObject) GetObjectOk() (*interface{}, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *FileObject) SetObject(v interface{})`

SetObject sets Object field to given value.


### SetObjectNil

`func (o *FileObject) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *FileObject) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetSize

`func (o *FileObject) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FileObject) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FileObject) SetSize(v int32)`

SetSize sets Size field to given value.


### GetUrl

`func (o *FileObject) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FileObject) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FileObject) SetUrl(v string)`

SetUrl sets Url field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


