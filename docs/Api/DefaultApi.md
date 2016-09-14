# Swagger\Client\DefaultApi

All URIs are relative to *http://stream-api.betfair.com:443/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**requestPost**](DefaultApi.md#requestPost) | **POST** /request | 


# **requestPost**
> \Swagger\Client\Model\AllResponseTypesExample requestPost($request_message)



This is a socket protocol delimited by CRLF (not http)

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\DefaultApi();
$request_message = new \Swagger\Client\Model\AllRequestTypesExample(); // \Swagger\Client\Model\AllRequestTypesExample | Requests are sent to socket

try {
    $result = $api_instance->requestPost($request_message);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->requestPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_message** | [**\Swagger\Client\Model\AllRequestTypesExample**](../Model/\Swagger\Client\Model\AllRequestTypesExample.md)| Requests are sent to socket |

### Return type

[**\Swagger\Client\Model\AllResponseTypesExample**](../Model/AllResponseTypesExample.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

