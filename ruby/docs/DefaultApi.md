# SwaggerClient::DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/javifc/tesla-demo/0.0.1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**vehicle_get**](DefaultApi.md#vehicle_get) | **GET** /vehicle | Vechile details


# **vehicle_get**
> InlineResponse200 vehicle_get

Vechile details

Returns details about a vehicle

### Example
```ruby
# load the gem
require 'swagger_client'

api_instance = SwaggerClient::DefaultApi.new

begin
  #Vechile details
  result = api_instance.vehicle_get
  p result
rescue SwaggerClient::ApiError => e
  puts "Exception when calling DefaultApi->vehicle_get: #{e}"
end
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined



