# \SipTeleportServiceApi

All URIs are relative to *https://api.subspace.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sip_teleport_service_create**](SipTeleportServiceApi.md#sip_teleport_service_create) | **POST** /v1/sip-teleports | CreateSipTeleport
[**sip_teleport_service_delete**](SipTeleportServiceApi.md#sip_teleport_service_delete) | **DELETE** /v1/sip-teleports/{id} | DeleteSipTeleport
[**sip_teleport_service_get**](SipTeleportServiceApi.md#sip_teleport_service_get) | **GET** /v1/sip-teleports/{id} | GetSipTeleport
[**sip_teleport_service_list**](SipTeleportServiceApi.md#sip_teleport_service_list) | **GET** /v1/sip-teleports | ListSipTeleports
[**sip_teleport_service_update**](SipTeleportServiceApi.md#sip_teleport_service_update) | **PUT** /v1/sip-teleports/{id} | UpdateSipTeleport



## sip_teleport_service_create

> crate::models::V1SipTeleportResponse sip_teleport_service_create()
CreateSipTeleport

CreateSipTeleport creates a new SIP Teleport

### Parameters

This endpoint does not need any parameter.

### Return type

[**crate::models::V1SipTeleportResponse**](v1SipTeleportResponse.md)

### Authorization

[accessCode](../README.md#accessCode)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sip_teleport_service_delete

> crate::models::V1SipTeleportResponse sip_teleport_service_delete(id)
DeleteSipTeleport

DeleteSipTeleport deletes an existing SIP Teleport, specified by its id

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
GetSipTeleport

GetSipTeleport fetches the details of a specific SIP Teleport, specified by its id

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
ListSipTeleports

ListSipTeleports lists all SIP Teleports

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

> crate::models::V1SipTeleportResponse sip_teleport_service_update(id)
UpdateSipTeleport

UpdateSipTeleport updates an existing SIP Teleport, specified by its id

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

