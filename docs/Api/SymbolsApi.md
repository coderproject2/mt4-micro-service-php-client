# Swagger\Client\SymbolsApi

All URIs are relative to *https://apps.noorcm.com:6502/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**symbolsGet**](SymbolsApi.md#symbolsGet) | **GET** /symbols | Get list of market symbols


# **symbolsGet**
> symbolsGet($token, $accept)

Get list of market symbols

TODO: Add Description

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\SymbolsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$token = "token_example"; // string | 
$accept = "accept_example"; // string | 

try {
    $apiInstance->symbolsGet($token, $accept);
} catch (Exception $e) {
    echo 'Exception when calling SymbolsApi->symbolsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string**|  |
 **accept** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

