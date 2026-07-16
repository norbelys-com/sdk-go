# LaunchProgramResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProgramId** | **string** | The program id. | 
**Status** | **string** | Always \&quot;active\&quot; on success. | 
**Warnings** | **[]string** | Non-fatal compliance advisories (e.g. cold campaign without one-click unsubscribe). The launch still succeeded. | 

## Methods

### NewLaunchProgramResult

`func NewLaunchProgramResult(programId string, status string, warnings []string, ) *LaunchProgramResult`

NewLaunchProgramResult instantiates a new LaunchProgramResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLaunchProgramResultWithDefaults

`func NewLaunchProgramResultWithDefaults() *LaunchProgramResult`

NewLaunchProgramResultWithDefaults instantiates a new LaunchProgramResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProgramId

`func (o *LaunchProgramResult) GetProgramId() string`

GetProgramId returns the ProgramId field if non-nil, zero value otherwise.

### GetProgramIdOk

`func (o *LaunchProgramResult) GetProgramIdOk() (*string, bool)`

GetProgramIdOk returns a tuple with the ProgramId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgramId

`func (o *LaunchProgramResult) SetProgramId(v string)`

SetProgramId sets ProgramId field to given value.


### GetStatus

`func (o *LaunchProgramResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LaunchProgramResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LaunchProgramResult) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetWarnings

`func (o *LaunchProgramResult) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *LaunchProgramResult) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *LaunchProgramResult) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


