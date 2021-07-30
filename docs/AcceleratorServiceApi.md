# \AcceleratorServiceApi

All URIs are relative to *https://api.subspace.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accelerator_service_create**](AcceleratorServiceApi.md#accelerator_service_create) | **POST** /v1/accelerators | CreateAccelerator
[**accelerator_service_delete**](AcceleratorServiceApi.md#accelerator_service_delete) | **DELETE** /v1/accelerators/{id} | DeleteAccelerator
[**accelerator_service_get**](AcceleratorServiceApi.md#accelerator_service_get) | **GET** /v1/accelerators/{id} | GetAccelerator
[**accelerator_service_list**](AcceleratorServiceApi.md#accelerator_service_list) | **GET** /v1/accelerators | ListAccelerators
[**accelerator_service_update**](AcceleratorServiceApi.md#accelerator_service_update) | **PUT** /v1/accelerators/{id} | UpdateAccelerator



## accelerator_service_create

> crate::models::V1Accelerator accelerator_service_create(body, idempotency_key)
CreateAccelerator

CreateAccelerator generates a new PacketAccelerator

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**body** | [**Body**](Body.md) | Required parameters to create a new PacketAccelerator.  NOTE- only subspace_port is optional | [required] |
**idempotency_key** | Option<**String**> | Value is the returned etag of a get request.  If a retry sends an Idempotency-Key that has been seen before, the existing accelerator is returned with the status code of 200 |  |

### Return type

[**crate::models::V1Accelerator**](v1Accelerator.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accelerator_service_delete

> serde_json::Value accelerator_service_delete(id)
DeleteAccelerator

DeleteAccelerator deletes the given PacketAccelerator, specified by its id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accelerator_service_get

> crate::models::V1Accelerator accelerator_service_get(id)
GetAccelerator

GetAccelerator returns the details of a given PacketAccelerator, specified by its id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**crate::models::V1Accelerator**](v1Accelerator.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accelerator_service_list

> crate::models::V1ListAcceleratorsResponse accelerator_service_list(before, limit, q)
ListAccelerators

ListAccelerators returns a list of all existing PacketAccelerators.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**before** | Option<**String**> |  |  |
**limit** | Option<**i64**> |  |  |
**q** | Option<**String**> | q Provides a query string which filters accelerators in the response. |  |

### Return type

[**crate::models::V1ListAcceleratorsResponse**](v1ListAcceleratorsResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accelerator_service_update

> crate::models::V1Accelerator accelerator_service_update(id, body1, if_match)
UpdateAccelerator

UpdateAccelerator updates an existing accelerator, specified by its id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**body1** | [**Body1**](Body1.md) | Parameters to update an existing PacketAccelerator, minimum requirement of one of them defined to update | [required] |
**if_match** | Option<**i32**> |  |  |

### Return type

[**crate::models::V1Accelerator**](v1Accelerator.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

