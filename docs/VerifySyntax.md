# VerifySyntax

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** | The domain part of the address. | 
**IsValidSyntax** | **bool** | RFC 5321/5322 syntactic validity. | 
**LocalPart** | **string** | The local part of the address (before the @). | 

## Methods

### NewVerifySyntax

`func NewVerifySyntax(domain string, isValidSyntax bool, localPart string, ) *VerifySyntax`

NewVerifySyntax instantiates a new VerifySyntax object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifySyntaxWithDefaults

`func NewVerifySyntaxWithDefaults() *VerifySyntax`

NewVerifySyntaxWithDefaults instantiates a new VerifySyntax object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *VerifySyntax) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *VerifySyntax) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *VerifySyntax) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetIsValidSyntax

`func (o *VerifySyntax) GetIsValidSyntax() bool`

GetIsValidSyntax returns the IsValidSyntax field if non-nil, zero value otherwise.

### GetIsValidSyntaxOk

`func (o *VerifySyntax) GetIsValidSyntaxOk() (*bool, bool)`

GetIsValidSyntaxOk returns a tuple with the IsValidSyntax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsValidSyntax

`func (o *VerifySyntax) SetIsValidSyntax(v bool)`

SetIsValidSyntax sets IsValidSyntax field to given value.


### GetLocalPart

`func (o *VerifySyntax) GetLocalPart() string`

GetLocalPart returns the LocalPart field if non-nil, zero value otherwise.

### GetLocalPartOk

`func (o *VerifySyntax) GetLocalPartOk() (*string, bool)`

GetLocalPartOk returns a tuple with the LocalPart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalPart

`func (o *VerifySyntax) SetLocalPart(v string)`

SetLocalPart sets LocalPart field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


