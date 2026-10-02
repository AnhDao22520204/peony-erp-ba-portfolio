# Business Rules

| ID | Area | Rule |
|---|---|---|
| BRULE-001 | Sales | Quotation must identify a customer; the report marks Customer as mandatory. |
| BRULE-002 | Sales | Quotation invoice address and delivery address are auto-filled from the selected contact/customer in the documented data library. |
| BRULE-003 | Sales | A quotation is confirmed before it becomes a sales order. |
| BRULE-004 | Sales | A quotation may be cancelled when the customer does not agree to purchase. |
| BRULE-005 | Purchase | Supplier is mandatory in the RFQ/purchase-order data library. |
| BRULE-006 | Purchase | Order deadline and expected receipt date are mandatory in the RFQ/purchase-order data library. |
| BRULE-007 | Purchase | Delivery destination and currency are mandatory in the RFQ/purchase-order data library. |
| BRULE-008 | Inventory - Receipt | Received goods are checked for quantity and quality before receipt confirmation. |
| BRULE-009 | Inventory | Warehouse name is mandatory in the warehouse data library. |
| BRULE-010 | Inventory | Warehouse location is mandatory in the warehouse-location data library. |
| BRULE-011 | Inventory - Stock Count | Stock-count variance is investigated when physical quantity differs from system-recorded quantity. |
| BRULE-012 | Inventory - Stock Count | If stock-count variance is not approved, the warehouse performs the count again. |
| BRULE-013 | Inventory - Stock Count | After approved count results, the requesting department performs stock adjustment to match actual conditions. |
| BRULE-014 | Inventory - Transfer | If the source warehouse is out of stock, the internal transfer is cancelled. |
| BRULE-015 | Inventory - Transfer | If source stock is available, the source warehouse proceeds with the transfer and creates the stock-issue record. |
| BRULE-016 | Inventory - Transfer | Transferred goods that do not meet requirements are returned; acceptable goods are confirmed by the receiving warehouse. |
| BRULE-017 | CRM | CRM opportunity progresses to Consulting after customer information is available, and to Qualified when staff assess the customer as a potential buyer. |
| BRULE-018 | CRM/Sales | If a customer agrees to the quotation, the quotation is confirmed to create a sales order; if the customer does not agree, the quotation can be cancelled. |
| BRULE-019 | Accounting - Overdue AR | An overdue invoice receives a second email reminder when it is 15 days late. |
| BRULE-020 | Accounting - Overdue AR | An invoice unpaid for more than 30 days triggers a phone reminder. |
| BRULE-021 | Accounting - Customer Refund | A customer refund request is rejected if invalid; valid requests proceed to refund processing. |
| BRULE-022 | Accounting - Customer Refund | A customer refund Credit Note is linked to the original invoice. |
| BRULE-023 | Accounting - Customer Refund | Documented customer-refund reasons include faulty/nonconforming products, invoice value/tax/discount errors, transaction cancellation, and promotion/price adjustment. |
| BRULE-024 | Accounting - Supplier Refund | A supplier refund proceeds only when the refund case is valid; invalid cases are rejected. |
| BRULE-025 | Accounting - Supplier Refund | A supplier refund Credit Note is linked to the original vendor bill. |
