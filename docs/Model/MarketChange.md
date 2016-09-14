# MarketChange

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rc** | [**\Swagger\Client\Model\RunnerChange[]**](RunnerChange.md) | Runner Changes - a list of changes to runners (or null if un-changed) | [optional] 
**img** | **bool** | Image - replace existing prices / data with the data supplied: it is not a delta (or null if delta) | [optional] 
**tv** | **double** | The total amount matched across the market. This value is truncated at 2dp (or null if un-changed) | [optional] 
**con** | **bool** | Conflated - have more than a single change been combined (or null if not conflated) | [optional] 
**market_definition** | [**\Swagger\Client\Model\MarketDefinition**](MarketDefinition.md) | Market Definition - the definition of the market (or null if un-changed) | [optional] 
**id** | **string** | Market Id - the id of the market | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


