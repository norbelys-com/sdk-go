# VerifySignals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsDisposable** | **bool** | Domain is a known disposable / temporary-mail provider. | 
**IsFreeEmail** | **bool** | Domain is a consumer webmail provider (gmail, outlook, …). | 
**IsGibberish** | **bool** | The local part looks like random characters — likely not a real person&#39;s mailbox. | 
**IsReputable** | **bool** | Domain is among the reputable top domains — a positive trust signal. | 
**IsRoleAccount** | **bool** | Local part is a role account (e.g. \&quot;info\&quot;, \&quot;support\&quot;). | 
**IsSpamDomain** | **bool** | Domain is on a spam/abuse blocklist — a reputation hazard to send to. | 

## Methods

### NewVerifySignals

`func NewVerifySignals(isDisposable bool, isFreeEmail bool, isGibberish bool, isReputable bool, isRoleAccount bool, isSpamDomain bool, ) *VerifySignals`

NewVerifySignals instantiates a new VerifySignals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifySignalsWithDefaults

`func NewVerifySignalsWithDefaults() *VerifySignals`

NewVerifySignalsWithDefaults instantiates a new VerifySignals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsDisposable

`func (o *VerifySignals) GetIsDisposable() bool`

GetIsDisposable returns the IsDisposable field if non-nil, zero value otherwise.

### GetIsDisposableOk

`func (o *VerifySignals) GetIsDisposableOk() (*bool, bool)`

GetIsDisposableOk returns a tuple with the IsDisposable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDisposable

`func (o *VerifySignals) SetIsDisposable(v bool)`

SetIsDisposable sets IsDisposable field to given value.


### GetIsFreeEmail

`func (o *VerifySignals) GetIsFreeEmail() bool`

GetIsFreeEmail returns the IsFreeEmail field if non-nil, zero value otherwise.

### GetIsFreeEmailOk

`func (o *VerifySignals) GetIsFreeEmailOk() (*bool, bool)`

GetIsFreeEmailOk returns a tuple with the IsFreeEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFreeEmail

`func (o *VerifySignals) SetIsFreeEmail(v bool)`

SetIsFreeEmail sets IsFreeEmail field to given value.


### GetIsGibberish

`func (o *VerifySignals) GetIsGibberish() bool`

GetIsGibberish returns the IsGibberish field if non-nil, zero value otherwise.

### GetIsGibberishOk

`func (o *VerifySignals) GetIsGibberishOk() (*bool, bool)`

GetIsGibberishOk returns a tuple with the IsGibberish field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGibberish

`func (o *VerifySignals) SetIsGibberish(v bool)`

SetIsGibberish sets IsGibberish field to given value.


### GetIsReputable

`func (o *VerifySignals) GetIsReputable() bool`

GetIsReputable returns the IsReputable field if non-nil, zero value otherwise.

### GetIsReputableOk

`func (o *VerifySignals) GetIsReputableOk() (*bool, bool)`

GetIsReputableOk returns a tuple with the IsReputable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReputable

`func (o *VerifySignals) SetIsReputable(v bool)`

SetIsReputable sets IsReputable field to given value.


### GetIsRoleAccount

`func (o *VerifySignals) GetIsRoleAccount() bool`

GetIsRoleAccount returns the IsRoleAccount field if non-nil, zero value otherwise.

### GetIsRoleAccountOk

`func (o *VerifySignals) GetIsRoleAccountOk() (*bool, bool)`

GetIsRoleAccountOk returns a tuple with the IsRoleAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRoleAccount

`func (o *VerifySignals) SetIsRoleAccount(v bool)`

SetIsRoleAccount sets IsRoleAccount field to given value.


### GetIsSpamDomain

`func (o *VerifySignals) GetIsSpamDomain() bool`

GetIsSpamDomain returns the IsSpamDomain field if non-nil, zero value otherwise.

### GetIsSpamDomainOk

`func (o *VerifySignals) GetIsSpamDomainOk() (*bool, bool)`

GetIsSpamDomainOk returns a tuple with the IsSpamDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSpamDomain

`func (o *VerifySignals) SetIsSpamDomain(v bool)`

SetIsSpamDomain sets IsSpamDomain field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


