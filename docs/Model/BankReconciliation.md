# BankReconciliation

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**version** | **int** |  | [optional] 
**changes** | [**\Tripletex\Model\Change[]**](Change.md) |  | [optional] 
**url** | **string** |  | [optional] 
**account** | [**\Tripletex\Model\Account**](Account.md) |  | 
**accounting_period** | [**\Tripletex\Model\AccountingPeriod**](AccountingPeriod.md) |  | 
**voucher** | [**\Tripletex\Model\Voucher**](Voucher.md) |  | [optional] 
**transactions** | [**\Tripletex\Model\BankTransaction[]**](BankTransaction.md) | Bank transactions tied to the bank reconciliation | [optional] 
**is_closed** | **bool** |  | [optional] [default to false]
**type** | **string** | Type of Bank Reconciliation. | 
**bank_account_closing_balance_currency** | **float** |  | [optional] 
**closed_date** | **string** |  | [optional] 
**closed_by_contact** | [**\Tripletex\Model\Contact**](Contact.md) |  | [optional] 
**closed_by_employee** | [**\Tripletex\Model\Employee**](Employee.md) |  | [optional] 
**approvable** | **bool** |  | [optional] [default to false]

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

