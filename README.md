# Go API client for swagger

This is an internal payments API gateway for Chamaconekt Kenya 

## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 0.1
- Package version: 1.0.0
- Build package: io.swagger.codegen.languages.GoClientCodegen
For more information, please visit [https://github.com/wondenge](https://github.com/wondenge)

## Installation
Put the package under your project folder and add the following in import:
```
    "./swagger"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost:8081*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AccountApi* | [**AccountCreate**](docs/AccountApi.md#accountcreate) | **Post** /v1/accounts | create account
*AccountApi* | [**AccountDelete**](docs/AccountApi.md#accountdelete) | **Delete** /v1/accounts/{accountID} | delete account
*AccountApi* | [**AccountList**](docs/AccountApi.md#accountlist) | **Get** /v1/accounts | list account
*AccountApi* | [**AccountShow**](docs/AccountApi.md#accountshow) | **Get** /v1/accounts/{accountID} | show account
*AccountApi* | [**AccountUpdate**](docs/AccountApi.md#accountupdate) | **Put** /v1/accounts/{accountID} | update account
*B2cApi* | [**B2cCreate**](docs/B2cApi.md#b2ccreate) | **Post** /v1/b2c/ | create b2c
*DefaultApi* | [**JsJsFilepath**](docs/DefaultApi.md#jsjsfilepath) | **Get** /js/{filepath} | Download public/js
*DefaultApi* | [**PublicUi**](docs/DefaultApi.md#publicui) | **Get** /ui | Download public/html/index.html
*DefaultApi* | [**SwaggerSwaggerJson**](docs/DefaultApi.md#swaggerswaggerjson) | **Get** /swagger.json | Download public/swagger/swagger.json


## Documentation For Models

 - [Account](docs/Account.md)
 - [AccountCollection](docs/AccountCollection.md)
 - [B2CPayload](docs/B2CPayload.md)
 - [B2CPayload1](docs/B2CPayload1.md)
 - [CreateAccountPayload](docs/CreateAccountPayload.md)
 - [CreateAccountPayload1](docs/CreateAccountPayload1.md)
 - [MediatypeIdentifierApplicationvndAccountjsonViewdefault](docs/MediatypeIdentifierApplicationvndAccountjsonViewdefault.md)
 - [MediatypeIdentifierApplicationvndGoaErrorViewdefault](docs/MediatypeIdentifierApplicationvndGoaErrorViewdefault.md)
 - [ModelError](docs/ModelError.md)
 - [UpdateAccountPayload](docs/UpdateAccountPayload.md)
 - [UpdateAccountPayload1](docs/UpdateAccountPayload1.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author

ondengew@gmail.com

