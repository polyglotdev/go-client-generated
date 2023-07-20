# {{classname}}

All URIs are relative to *https://pokeapi.co/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PokemonHabitatList**](PokemonHabitatApi.md#PokemonHabitatList) | **Get** /api/v2/pokemon-habitat/ | 
[**PokemonHabitatRead**](PokemonHabitatApi.md#PokemonHabitatRead) | **Get** /api/v2/pokemon-habitat/{id}/ | 

# **PokemonHabitatList**
> string PokemonHabitatList(ctx, optional)


### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PokemonHabitatApiPokemonHabitatListOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PokemonHabitatApiPokemonHabitatListOpts struct
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

# **PokemonHabitatRead**
> string PokemonHabitatRead(ctx, id)


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

