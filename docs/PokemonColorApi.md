# {{classname}}

All URIs are relative to *https://pokeapi.co/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PokemonColorList**](PokemonColorApi.md#PokemonColorList) | **Get** /api/v2/pokemon-color/ | 
[**PokemonColorRead**](PokemonColorApi.md#PokemonColorRead) | **Get** /api/v2/pokemon-color/{id}/ | 

# **PokemonColorList**
> string PokemonColorList(ctx, optional)


### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PokemonColorApiPokemonColorListOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PokemonColorApiPokemonColorListOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **optional.Int32**|  | 
 **offset** | **optional.Int32**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PokemonColorRead**
> string PokemonColorRead(ctx, id)


### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | **int32**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

