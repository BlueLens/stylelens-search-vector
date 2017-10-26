# stylelens_search_vector.SearchApi

All URIs are relative to *http://vector.stylelens.io*

Method | HTTP request | Description
------------- | ------------- | -------------
[**search_vector**](SearchApi.md#search_vector) | **POST** /vectors | Query to search vector


# **search_vector**
> VectorSearchResponse search_vector(body)

Query to search vector



### Example 
```python
from __future__ import print_function
import time
import stylelens_search_vector
from stylelens_search_vector.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = stylelens_search_vector.SearchApi()
body = stylelens_search_vector.VectorSearchRequest() # VectorSearchRequest | 

try: 
    # Query to search vector
    api_response = api_instance.search_vector(body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling SearchApi->search_vector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**VectorSearchRequest**](VectorSearchRequest.md)|  | 

### Return type

[**VectorSearchResponse**](VectorSearchResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

