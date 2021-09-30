# \SipTeleportServiceApi

All URIs are relative to *https://api.subspace.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sip_teleport_service_create**](SipTeleportServiceApi.md#sip_teleport_service_create) | **POST** /v1/sipteleport | 
[**sip_teleport_service_delete**](SipTeleportServiceApi.md#sip_teleport_service_delete) | **DELETE** /v1/sipteleport/{id} | 
[**sip_teleport_service_get**](SipTeleportServiceApi.md#sip_teleport_service_get) | **GET** /v1/sipteleport/{id} | 
[**sip_teleport_service_list**](SipTeleportServiceApi.md#sip_teleport_service_list) | **GET** /v1/sipteleport | 
[**sip_teleport_service_update**](SipTeleportServiceApi.md#sip_teleport_service_update) | **PUT** /v1/sipteleport/{id} | 



## sip_teleport_service_create

> crate::models::V1SipTeleportResponse sip_teleport_service_create(v1_create_sip_teleport, idempotency_key)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v1_create_sip_teleport** | [**V1CreateSipTeleport**](V1CreateSipTeleport.md) | Required parameters to create a new SIPTeleport | [required] |
**idempotency_key** | Option<**String**> | Value is the returned etag of a get request.  If a retry sends an Idempotency-Key that has been seen before, the existing teleport is returned with the status code of 200 |  |

### Return type

[**crate::models::V1SipTeleportResponse**](v1SipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sip_teleport_service_delete

> crate::models::V1SipTeleportResponse sip_teleport_service_delete(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**crate::models::V1SipTeleportResponse**](v1SipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sip_teleport_service_get

> crate::models::V1SipTeleportResponse sip_teleport_service_get(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**crate::models::V1SipTeleportResponse**](v1SipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sip_teleport_service_list

> crate::models::V1ListSipTeleportResponse sip_teleport_service_list(before, limit)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**before** | Option<**String**> |  |  |
**limit** | Option<**i64**> |  |  |

### Return type

[**crate::models::V1ListSipTeleportResponse**](v1ListSipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sip_teleport_service_update

> crate::models::V1SipTeleportResponse sip_teleport_service_update(id, v1_update_sip_teleport)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**v1_update_sip_teleport** | [**V1UpdateSipTeleport**](V1UpdateSipTeleport.md) | Parameters to update an existing SIPTeleport, minimum requirement of one of them defined to update | [required] |

### Return type

[**crate::models::V1SipTeleportResponse**](v1SipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

