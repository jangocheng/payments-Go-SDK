# \DefaultApi

All URIs are relative to *http://localhost:8081*

Method | HTTP request | Description
------------- | ------------- | -------------
[**JsJsFilepath**](DefaultApi.md#JsJsFilepath) | **Get** /js/{filepath} | Download public/js
[**PublicUi**](DefaultApi.md#PublicUi) | **Get** /ui | Download public/html/index.html
[**SwaggerSwaggerJson**](DefaultApi.md#SwaggerSwaggerJson) | **Get** /swagger.json | Download public/swagger/swagger.json


# **JsJsFilepath**
> *os.File JsJsFilepath($filepath)

Download public/js


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filepath** | **string**| Relative file path | 

### Return type

[***os.File**](*os.File.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PublicUi**
> *os.File PublicUi()

Download public/html/index.html


### Parameters
This endpoint does not need any parameter.

### Return type

[***os.File**](*os.File.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SwaggerSwaggerJson**
> *os.File SwaggerSwaggerJson()

Download public/swagger/swagger.json


### Parameters
This endpoint does not need any parameter.

### Return type

[***os.File**](*os.File.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

