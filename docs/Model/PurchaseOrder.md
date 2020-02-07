# PurchaseOrder

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**version** | **int** |  | [optional] 
**changes** | [**\Tripletex\Model\Change[]**](Change.md) |  | [optional] 
**url** | **string** |  | [optional] 
**number** | **string** | Purchase order number | [optional] 
**supplier** | [**\Tripletex\Model\Supplier**](Supplier.md) |  | 
**delivery_date** | **string** |  | 
**order_lines** | [**\Tripletex\Model\OrderLine[]**](OrderLine.md) | Order lines tied to the purchase order | [optional] 
**project** | [**\Tripletex\Model\Project**](Project.md) |  | [optional] 
**department** | [**\Tripletex\Model\Department**](Department.md) |  | [optional] 
**delivery_address** | [**\Tripletex\Model\Address**](Address.md) |  | [optional] 
**creation_date** | **string** |  | [optional] 
**is_closed** | **bool** |  | [optional] [default to false]
**contact** | [**\Tripletex\Model\Employee**](Employee.md) |  | 
**status** | **string** |  | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

