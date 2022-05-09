# AccountResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Account Unique ID | [optional] 
**Email** | Pointer to **string** | Email Address | [optional] 
**NickName** | Pointer to **string** | User Nickname | [optional] 
**AccountState** | Pointer to **string** | Account State - Created, Ready, Revoked, DroppedOut, Error | [optional] 
**Roles** | Pointer to **[]string** | Account roles - like admin, and normal user | [optional] 

## Methods

### NewAccountResponse

`func NewAccountResponse() *AccountResponse`

NewAccountResponse instantiates a new AccountResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountResponseWithDefaults

`func NewAccountResponseWithDefaults() *AccountResponse`

NewAccountResponseWithDefaults instantiates a new AccountResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetEmail

`func (o *AccountResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *AccountResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *AccountResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *AccountResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetNickName

`func (o *AccountResponse) GetNickName() string`

GetNickName returns the NickName field if non-nil, zero value otherwise.

### GetNickNameOk

`func (o *AccountResponse) GetNickNameOk() (*string, bool)`

GetNickNameOk returns a tuple with the NickName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNickName

`func (o *AccountResponse) SetNickName(v string)`

SetNickName sets NickName field to given value.

### HasNickName

`func (o *AccountResponse) HasNickName() bool`

HasNickName returns a boolean if a field has been set.

### GetAccountState

`func (o *AccountResponse) GetAccountState() string`

GetAccountState returns the AccountState field if non-nil, zero value otherwise.

### GetAccountStateOk

`func (o *AccountResponse) GetAccountStateOk() (*string, bool)`

GetAccountStateOk returns a tuple with the AccountState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountState

`func (o *AccountResponse) SetAccountState(v string)`

SetAccountState sets AccountState field to given value.

### HasAccountState

`func (o *AccountResponse) HasAccountState() bool`

HasAccountState returns a boolean if a field has been set.

### GetRoles

`func (o *AccountResponse) GetRoles() []string`

GetRoles returns the Roles field if non-nil, zero value otherwise.

### GetRolesOk

`func (o *AccountResponse) GetRolesOk() (*[]string, bool)`

GetRolesOk returns a tuple with the Roles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoles

`func (o *AccountResponse) SetRoles(v []string)`

SetRoles sets Roles field to given value.

### HasRoles

`func (o *AccountResponse) HasRoles() bool`

HasRoles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


