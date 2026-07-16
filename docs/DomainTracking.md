# DomainTracking

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedSendingDomainIds** | **[]string** | Sending domains whose links route through this tracking hostname. | 
**CloudflareHostnameId** | **NullableString** |  | 
**DesiredState** | **string** | Operator target state: &#x60;active&#x60; or &#x60;disabled&#x60;. | 
**DnsStatus** | **string** | Whether the CNAME resolves correctly: &#x60;pending&#x60;, &#x60;valid&#x60;, or &#x60;invalid&#x60;. | 
**DomainConnectSupported** | **bool** | Whether the DNS provider supports one-click Domain Connect setup. | 
**DomainConnectUrl** | **NullableString** |  | 
**HttpStatus** | **string** | Whether the tracking host serves over HTTP correctly: &#x60;pending&#x60;, &#x60;valid&#x60;, or &#x60;invalid&#x60;. | 
**IsOrganizationDefault** | **bool** | Whether this is the organization&#39;s default tracking domain. | 
**Label** | **NullableString** |  | 
**LastCheckedAt** | Pointer to **interface{}** |  | [optional] 
**Provider** | **string** | Detected DNS provider: &#x60;cloudflare&#x60;, &#x60;vercel&#x60;, &#x60;other&#x60;, or &#x60;unknown&#x60;. | 
**ProviderDisplayName** | **NullableString** |  | 
**ProviderUrl** | **NullableString** |  | 
**Record** | [**TrackingDnsRecord**](TrackingDnsRecord.md) |  | 
**SetupMode** | **string** | How the record is being set up: &#x60;domain_connect&#x60; or &#x60;manual&#x60;. | 
**Status** | **string** | Lifecycle status: &#x60;pending_dns&#x60;, &#x60;pending_tls&#x60;, &#x60;checking&#x60;, &#x60;active&#x60;, &#x60;degraded&#x60;, or &#x60;archived&#x60;. | 
**TlsStatus** | **string** | Whether the edge TLS certificate is issued: &#x60;pending&#x60;, &#x60;valid&#x60;, or &#x60;invalid&#x60;. | 

## Methods

### NewDomainTracking

`func NewDomainTracking(assignedSendingDomainIds []string, cloudflareHostnameId NullableString, desiredState string, dnsStatus string, domainConnectSupported bool, domainConnectUrl NullableString, httpStatus string, isOrganizationDefault bool, label NullableString, provider string, providerDisplayName NullableString, providerUrl NullableString, record TrackingDnsRecord, setupMode string, status string, tlsStatus string, ) *DomainTracking`

NewDomainTracking instantiates a new DomainTracking object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainTrackingWithDefaults

`func NewDomainTrackingWithDefaults() *DomainTracking`

NewDomainTrackingWithDefaults instantiates a new DomainTracking object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedSendingDomainIds

`func (o *DomainTracking) GetAssignedSendingDomainIds() []string`

GetAssignedSendingDomainIds returns the AssignedSendingDomainIds field if non-nil, zero value otherwise.

### GetAssignedSendingDomainIdsOk

`func (o *DomainTracking) GetAssignedSendingDomainIdsOk() (*[]string, bool)`

GetAssignedSendingDomainIdsOk returns a tuple with the AssignedSendingDomainIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedSendingDomainIds

`func (o *DomainTracking) SetAssignedSendingDomainIds(v []string)`

SetAssignedSendingDomainIds sets AssignedSendingDomainIds field to given value.


### GetCloudflareHostnameId

`func (o *DomainTracking) GetCloudflareHostnameId() string`

GetCloudflareHostnameId returns the CloudflareHostnameId field if non-nil, zero value otherwise.

### GetCloudflareHostnameIdOk

`func (o *DomainTracking) GetCloudflareHostnameIdOk() (*string, bool)`

GetCloudflareHostnameIdOk returns a tuple with the CloudflareHostnameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudflareHostnameId

`func (o *DomainTracking) SetCloudflareHostnameId(v string)`

SetCloudflareHostnameId sets CloudflareHostnameId field to given value.


### SetCloudflareHostnameIdNil

`func (o *DomainTracking) SetCloudflareHostnameIdNil(b bool)`

 SetCloudflareHostnameIdNil sets the value for CloudflareHostnameId to be an explicit nil

### UnsetCloudflareHostnameId
`func (o *DomainTracking) UnsetCloudflareHostnameId()`

UnsetCloudflareHostnameId ensures that no value is present for CloudflareHostnameId, not even an explicit nil
### GetDesiredState

`func (o *DomainTracking) GetDesiredState() string`

GetDesiredState returns the DesiredState field if non-nil, zero value otherwise.

### GetDesiredStateOk

`func (o *DomainTracking) GetDesiredStateOk() (*string, bool)`

GetDesiredStateOk returns a tuple with the DesiredState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredState

`func (o *DomainTracking) SetDesiredState(v string)`

SetDesiredState sets DesiredState field to given value.


### GetDnsStatus

`func (o *DomainTracking) GetDnsStatus() string`

GetDnsStatus returns the DnsStatus field if non-nil, zero value otherwise.

### GetDnsStatusOk

`func (o *DomainTracking) GetDnsStatusOk() (*string, bool)`

GetDnsStatusOk returns a tuple with the DnsStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsStatus

`func (o *DomainTracking) SetDnsStatus(v string)`

SetDnsStatus sets DnsStatus field to given value.


### GetDomainConnectSupported

`func (o *DomainTracking) GetDomainConnectSupported() bool`

GetDomainConnectSupported returns the DomainConnectSupported field if non-nil, zero value otherwise.

### GetDomainConnectSupportedOk

`func (o *DomainTracking) GetDomainConnectSupportedOk() (*bool, bool)`

GetDomainConnectSupportedOk returns a tuple with the DomainConnectSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainConnectSupported

`func (o *DomainTracking) SetDomainConnectSupported(v bool)`

SetDomainConnectSupported sets DomainConnectSupported field to given value.


### GetDomainConnectUrl

`func (o *DomainTracking) GetDomainConnectUrl() string`

GetDomainConnectUrl returns the DomainConnectUrl field if non-nil, zero value otherwise.

### GetDomainConnectUrlOk

`func (o *DomainTracking) GetDomainConnectUrlOk() (*string, bool)`

GetDomainConnectUrlOk returns a tuple with the DomainConnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainConnectUrl

`func (o *DomainTracking) SetDomainConnectUrl(v string)`

SetDomainConnectUrl sets DomainConnectUrl field to given value.


### SetDomainConnectUrlNil

`func (o *DomainTracking) SetDomainConnectUrlNil(b bool)`

 SetDomainConnectUrlNil sets the value for DomainConnectUrl to be an explicit nil

### UnsetDomainConnectUrl
`func (o *DomainTracking) UnsetDomainConnectUrl()`

UnsetDomainConnectUrl ensures that no value is present for DomainConnectUrl, not even an explicit nil
### GetHttpStatus

`func (o *DomainTracking) GetHttpStatus() string`

GetHttpStatus returns the HttpStatus field if non-nil, zero value otherwise.

### GetHttpStatusOk

`func (o *DomainTracking) GetHttpStatusOk() (*string, bool)`

GetHttpStatusOk returns a tuple with the HttpStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttpStatus

`func (o *DomainTracking) SetHttpStatus(v string)`

SetHttpStatus sets HttpStatus field to given value.


### GetIsOrganizationDefault

`func (o *DomainTracking) GetIsOrganizationDefault() bool`

GetIsOrganizationDefault returns the IsOrganizationDefault field if non-nil, zero value otherwise.

### GetIsOrganizationDefaultOk

`func (o *DomainTracking) GetIsOrganizationDefaultOk() (*bool, bool)`

GetIsOrganizationDefaultOk returns a tuple with the IsOrganizationDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOrganizationDefault

`func (o *DomainTracking) SetIsOrganizationDefault(v bool)`

SetIsOrganizationDefault sets IsOrganizationDefault field to given value.


### GetLabel

`func (o *DomainTracking) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainTracking) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainTracking) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *DomainTracking) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *DomainTracking) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetLastCheckedAt

`func (o *DomainTracking) GetLastCheckedAt() interface{}`

GetLastCheckedAt returns the LastCheckedAt field if non-nil, zero value otherwise.

### GetLastCheckedAtOk

`func (o *DomainTracking) GetLastCheckedAtOk() (*interface{}, bool)`

GetLastCheckedAtOk returns a tuple with the LastCheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCheckedAt

`func (o *DomainTracking) SetLastCheckedAt(v interface{})`

SetLastCheckedAt sets LastCheckedAt field to given value.

### HasLastCheckedAt

`func (o *DomainTracking) HasLastCheckedAt() bool`

HasLastCheckedAt returns a boolean if a field has been set.

### SetLastCheckedAtNil

`func (o *DomainTracking) SetLastCheckedAtNil(b bool)`

 SetLastCheckedAtNil sets the value for LastCheckedAt to be an explicit nil

### UnsetLastCheckedAt
`func (o *DomainTracking) UnsetLastCheckedAt()`

UnsetLastCheckedAt ensures that no value is present for LastCheckedAt, not even an explicit nil
### GetProvider

`func (o *DomainTracking) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *DomainTracking) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *DomainTracking) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetProviderDisplayName

`func (o *DomainTracking) GetProviderDisplayName() string`

GetProviderDisplayName returns the ProviderDisplayName field if non-nil, zero value otherwise.

### GetProviderDisplayNameOk

`func (o *DomainTracking) GetProviderDisplayNameOk() (*string, bool)`

GetProviderDisplayNameOk returns a tuple with the ProviderDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderDisplayName

`func (o *DomainTracking) SetProviderDisplayName(v string)`

SetProviderDisplayName sets ProviderDisplayName field to given value.


### SetProviderDisplayNameNil

`func (o *DomainTracking) SetProviderDisplayNameNil(b bool)`

 SetProviderDisplayNameNil sets the value for ProviderDisplayName to be an explicit nil

### UnsetProviderDisplayName
`func (o *DomainTracking) UnsetProviderDisplayName()`

UnsetProviderDisplayName ensures that no value is present for ProviderDisplayName, not even an explicit nil
### GetProviderUrl

`func (o *DomainTracking) GetProviderUrl() string`

GetProviderUrl returns the ProviderUrl field if non-nil, zero value otherwise.

### GetProviderUrlOk

`func (o *DomainTracking) GetProviderUrlOk() (*string, bool)`

GetProviderUrlOk returns a tuple with the ProviderUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderUrl

`func (o *DomainTracking) SetProviderUrl(v string)`

SetProviderUrl sets ProviderUrl field to given value.


### SetProviderUrlNil

`func (o *DomainTracking) SetProviderUrlNil(b bool)`

 SetProviderUrlNil sets the value for ProviderUrl to be an explicit nil

### UnsetProviderUrl
`func (o *DomainTracking) UnsetProviderUrl()`

UnsetProviderUrl ensures that no value is present for ProviderUrl, not even an explicit nil
### GetRecord

`func (o *DomainTracking) GetRecord() TrackingDnsRecord`

GetRecord returns the Record field if non-nil, zero value otherwise.

### GetRecordOk

`func (o *DomainTracking) GetRecordOk() (*TrackingDnsRecord, bool)`

GetRecordOk returns a tuple with the Record field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecord

`func (o *DomainTracking) SetRecord(v TrackingDnsRecord)`

SetRecord sets Record field to given value.


### GetSetupMode

`func (o *DomainTracking) GetSetupMode() string`

GetSetupMode returns the SetupMode field if non-nil, zero value otherwise.

### GetSetupModeOk

`func (o *DomainTracking) GetSetupModeOk() (*string, bool)`

GetSetupModeOk returns a tuple with the SetupMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupMode

`func (o *DomainTracking) SetSetupMode(v string)`

SetSetupMode sets SetupMode field to given value.


### GetStatus

`func (o *DomainTracking) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DomainTracking) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DomainTracking) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTlsStatus

`func (o *DomainTracking) GetTlsStatus() string`

GetTlsStatus returns the TlsStatus field if non-nil, zero value otherwise.

### GetTlsStatusOk

`func (o *DomainTracking) GetTlsStatusOk() (*string, bool)`

GetTlsStatusOk returns a tuple with the TlsStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTlsStatus

`func (o *DomainTracking) SetTlsStatus(v string)`

SetTlsStatus sets TlsStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


