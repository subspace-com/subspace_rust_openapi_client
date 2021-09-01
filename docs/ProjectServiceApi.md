# \ProjectServiceApi

All URIs are relative to *https://api.subspace.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_service_create**](ProjectServiceApi.md#project_service_create) | **POST** /v1/projects | 
[**project_service_get**](ProjectServiceApi.md#project_service_get) | **GET** /v1/projects/{id} | 
[**project_service_list**](ProjectServiceApi.md#project_service_list) | **GET** /v1/projects | 
[**project_service_update**](ProjectServiceApi.md#project_service_update) | **PUT** /v1/projects/{id} | 



## project_service_create

> crate::models::V1Project project_service_create()


### Parameters

This endpoint does not need any parameter.

### Return type

[**crate::models::V1Project**](v1Project.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_service_get

> crate::models::V1Project project_service_get(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**crate::models::V1Project**](v1Project.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_service_list

> crate::models::V1ListProjectsResponse project_service_list(before, limit)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**before** | Option<**String**> |  |  |
**limit** | Option<**i64**> |  |  |

### Return type

[**crate::models::V1ListProjectsResponse**](v1ListProjectsResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_service_update

> crate::models::V1Project project_service_update(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** | id is the project identity | [required] |

### Return type

[**crate::models::V1Project**](v1Project.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

