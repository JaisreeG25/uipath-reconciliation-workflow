# Matching Logic

## Overview
This document describes the detailed matching rules for GPay, NEFT, and Sales Sheet transactions.

### GPay Transaction Matching Rules
1. **Transaction ID:** Match based on the unique transaction ID provided by GPay.
2. **Amount:** Ensure that the transaction amount matches the amount in the reconciliation sheet.
3. **Timestamp:** Compare the transaction timestamp within a tolerance of +/- 5 minutes.
4. **Merchant Information:** Check that the merchant name or ID corresponds with records in the system.

### NEFT Transaction Matching Rules
1. **UTR Number:** Validate the Unique Transaction Reference number.
2. **Amount:** Ensure the payment amount is identical.
3. **Date of Transaction:** The NEFT transaction date should match the corresponding entry in the records.
4. **Beneficiary Account:** Confirm that the beneficiary account number is registered in the matching records.

### Sales Sheet Transaction Matching Rules
1. **Invoice Number:** Match based on the unique invoice number present in the sales sheet.
2. **Amount:** Check that the transaction amount coincides with the sales record.
3. **Date of Sale:** Verify that the date of sale matches the date on the reconciliation sheet.
4. **Customer Information:** Ensure that the customer name or account number matches the records.

## Conclusion
Following these rules will ensure accurate and efficient reconciliation of transactions across GPay, NEFT, and Sales Sheet records. 
