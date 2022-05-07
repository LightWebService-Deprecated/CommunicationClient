# RegisterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserEmail** | Pointer to **string** | Email Address | [optional] 
**UserNickName** | Pointer to **string** | User Nickname | [optional] 
**UserPassword** | Pointer to **string** | User Password | [optional] 

## Methods

### NewRegisterRequest

`func NewRegisterRequest() *RegisterRequest`

NewRegisterRequest instantiates a new RegisterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegisterRequestWithDefaults

`func NewRegisterRequestWithDefaults() *RegisterRequest`

NewRegisterRequestWithDefaults instantiates a new RegisterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserEmail

`func (o *RegisterRequest) GetUserEmail() string`

GetUserEmail returns the UserEmail field if non-nil, zero value otherwise.

### GetUserEmailOk

`func (o *RegisterRequest) GetUserEmailOk() (*string, bool)`

GetUserEmailOk returns a tuple with the UserEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserEmail

`func (o *RegisterRequest) SetUserEmail(v string)`

SetUserEmail sets UserEmail field to given value.

### HasUserEmail

`func (o *RegisterRequest) HasUserEmail() bool`

HasUserEmail returns a boolean if a field has been set.

### GetUserNickName

`func (o *RegisterRequest) GetUserNickName() string`

GetUserNickName returns the UserNickName field if non-nil, zero value otherwise.

### GetUserNickNameOk

`func (o *RegisterRequest) GetUserNickNameOk() (*string, bool)`

GetUserNickNameOk returns a tuple with the UserNickName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserNickName

`func (o *RegisterRequest) SetUserNickName(v string)`

SetUserNickName sets UserNickName field to given value.

### HasUserNickName

`func (o *RegisterRequest) HasUserNickName() bool`

HasUserNickName returns a boolean if a field has been set.

### GetUserPassword

`func (o *RegisterRequest) GetUserPassword() string`

GetUserPassword returns the UserPassword field if non-nil, zero value otherwise.

### GetUserPasswordOk

`func (o *RegisterRequest) GetUserPasswordOk() (*string, bool)`

GetUserPasswordOk returns a tuple with the UserPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserPassword

`func (o *RegisterRequest) SetUserPassword(v string)`

SetUserPassword sets UserPassword field to given value.

### HasUserPassword

`func (o *RegisterRequest) HasUserPassword() bool`

HasUserPassword returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


