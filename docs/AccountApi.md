# \AccountApi

All URIs are relative to *http://localhost:8081*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountCreate**](AccountApi.md#AccountCreate) | **Post** /v1/accounts | create account
[**AccountDelete**](AccountApi.md#AccountDelete) | **Delete** /v1/accounts/{accountID} | delete account
[**AccountList**](AccountApi.md#AccountList) | **Get** /v1/accounts | list account
[**AccountShow**](AccountApi.md#AccountShow) | **Get** /v1/accounts/{accountID} | show account
[**AccountUpdate**](AccountApi.md#AccountUpdate) | **Put** /v1/accounts/{accountID} | update account


# **AccountCreate**
> AccountCreate($payload)

create account

Create new account


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **payload** | [**CreateAccountPayload1**](CreateAccountPayload1.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/vnd.goa.error

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AccountDelete**
> AccountDelete($accountID)

delete account


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountID** | **int32**| Account ID | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/vnd.goa.error

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AccountList**
> []MediatypeIdentifierApplicationvndAccountjsonViewdefault AccountList()

list account

Retrieve all accounts.


### Parameters
This endpoint does not need any parameter.

### Return type

[**[]MediatypeIdentifierApplicationvndAccountjsonViewdefault**](Mediatype identifier applicationvnd.accountjson viewdefault.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/vnd.account+json; type=collection

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AccountShow**
> MediatypeIdentifierApplicationvndAccountjsonViewdefault AccountShow($accountID)

show account

Retrieve account with given id. IDs 1 and 2 pre-exist in the system.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountID** | **int32**| Account ID | 

### Return type

[**MediatypeIdentifierApplicationvndAccountjsonViewdefault**](Mediatype identifier applicationvnd.accountjson viewdefault.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/vnd.goa.error, application/vnd.account+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AccountUpdate**
> AccountUpdate($accountID, $payload)

update account

Change account name


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountID** | **int32**| Account ID | 
 **payload** | [**UpdateAccountPayload1**](UpdateAccountPayload1.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/vnd.goa.error

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

