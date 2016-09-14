# Order

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**side** | **string** | Side - the side of the order | [optional] 
**sv** | **double** | Size Voided - the amount of the order that has been voided | [optional] 
**pt** | **string** | Persistence Type - whether the order will persist at in play or not (L &#x3D; LAPSE, P &#x3D; PERSIST, MOC &#x3D; Market On Close) | [optional] 
**ot** | **string** | Order Type - the type of the order (L &#x3D; LIMIT, MOC &#x3D; MARKET_ON_CLOSE, LOC &#x3D; LIMIT_ON_CLOSE) | [optional] 
**p** | **double** | Price - the original placed price of the order | [optional] 
**sc** | **double** | Size Cancelled - the amount of the order that has been cancelled | [optional] 
**rc** | **string** | Regulator Code - the regulator of the order | [optional] 
**s** | **double** | Size - the original placed size of the order | [optional] 
**pd** | **int** | Placed Date - the date the order was placed | [optional] 
**rac** | **string** | Regulator Auth Code - the auth code returned by the regulator | [optional] 
**md** | **int** | Matched Date - the date the order was matched (null if the order is not matched) | [optional] 
**sl** | **double** | Size Lapsed - the amount of the order that has been lapsed | [optional] 
**avp** | **double** | Average Price Matched - the average price the order was matched at (null if the order is not matched | [optional] 
**sm** | **double** | Size Matched - the amount of the order that has been matched | [optional] 
**id** | **string** | Bet Id - the id of the order | [optional] 
**bsp** | **double** | BSP Liability - the BSP liability of the order (null if the order is not a BSP order) | [optional] 
**status** | **string** | Status - the status of the order (E &#x3D; EXECUTABLE, EC &#x3D; EXECUTION_COMPLETE) | [optional] 
**sr** | **double** | Size Remaining - the amount of the order that is remaining unmatched | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


