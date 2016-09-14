# RunnerChange

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tv** | **double** | The total amount matched. This value is truncated at 2dp. | [optional] 
**batb** | [**double[][]**](array.md) | Best Available To Back - LevelPriceVol triple delta of price changes, keyed by level (0 vol is remove) | [optional] 
**spb** | [**double[][]**](array.md) | Starting Price Back - PriceVol tuple delta of price changes (0 vol is remove) | [optional] 
**bdatl** | [**double[][]**](array.md) | Best Display Available To Lay (includes virtual prices)- LevelPriceVol triple delta of price changes, keyed by level (0 vol is remove) | [optional] 
**trd** | [**double[][]**](array.md) | Traded - PriceVol tuple delta of price changes (0 vol is remove) | [optional] 
**spf** | **double** | Starting Price Far - The far starting price (or null if un-changed) | [optional] 
**ltp** | **double** | Last Traded Price - The last traded price (or null if un-changed) | [optional] 
**atb** | [**double[][]**](array.md) | Available To Back - PriceVol tuple delta of price changes (0 vol is remove) | [optional] 
**spl** | [**double[][]**](array.md) | Starting Price Lay - PriceVol tuple delta of price changes (0 vol is remove) | [optional] 
**spn** | **double** | Starting Price Near - The far starting price (or null if un-changed) | [optional] 
**atl** | [**double[][]**](array.md) | Available To Lay - PriceVol tuple delta of price changes (0 vol is remove) | [optional] 
**batl** | [**double[][]**](array.md) | Best Available To Lay - LevelPriceVol triple delta of price changes, keyed by level (0 vol is remove) | [optional] 
**id** | **int** | Selection Id - the id of the runner (selection) | [optional] 
**hc** | **double** | Handicap - the handicap of the runner (selection) (null if not applicable) | [optional] 
**bdatb** | [**double[][]**](array.md) | Best Display Available To Back (includes virtual prices)- LevelPriceVol triple delta of price changes, keyed by level (0 vol is remove) | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


