# Features

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SenderGoogleOAuth** | **bool** | Whether this organization can connect email senders via Google OAuth. Access is granted per organization. Example: true | 

## Methods

### NewFeatures

`func NewFeatures(senderGoogleOAuth bool, ) *Features`

NewFeatures instantiates a new Features object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFeaturesWithDefaults

`func NewFeaturesWithDefaults() *Features`

NewFeaturesWithDefaults instantiates a new Features object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSenderGoogleOAuth

`func (o *Features) GetSenderGoogleOAuth() bool`

GetSenderGoogleOAuth returns the SenderGoogleOAuth field if non-nil, zero value otherwise.

### GetSenderGoogleOAuthOk

`func (o *Features) GetSenderGoogleOAuthOk() (*bool, bool)`

GetSenderGoogleOAuthOk returns a tuple with the SenderGoogleOAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderGoogleOAuth

`func (o *Features) SetSenderGoogleOAuth(v bool)`

SetSenderGoogleOAuth sets SenderGoogleOAuth field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


