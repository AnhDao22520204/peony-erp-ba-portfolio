# Functional Requirements

| ID | Module | Function | Requirement | Related BR |
|---|---|---|---|---|
| FR-SAL-01 | Sales | Create quotation | The system shall allow Sales Staff to create a quotation in response to a customer quotation request. | BR-002 | §3.2.2, PDF p.35 |
| FR-SAL-02 | Sales | Maintain quotation details | The quotation shall support customer, products, quantity, price-related information, expiry/payment information as documented in the quotation data library. | BR-002, BR-014 | §3.2.2.2, PDF pp.36–37 |
| FR-SAL-03 | Sales | Send quotation | The system shall allow Sales Staff to send the quotation to the customer by email. | BR-002 | §3.2.3, PDF p.40 |
| FR-SAL-04 | Sales | Confirm quotation | The system shall allow an accepted quotation to be confirmed and become a sales order. | BR-002 | §3.2.2–3.2.3, PDF pp.36, 41 |
| FR-SAL-05 | Sales | Provide order details to warehouse | The confirmed order details shall be available to Warehouse Staff for fulfillment. | BR-002, BR-005 | §3.2.2, PDF p.36 |
| FR-SAL-06 | Sales | Fulfill delivery | Warehouse Staff shall be able to pick and deliver products for the confirmed customer order. | BR-002, BR-005 | §3.2.2, PDF p.36 |
| FR-SAL-07 | Sales | Create/send customer invoice | Sales Staff shall be able to create and send an invoice to the customer. | BR-002, BR-009 | §3.2.2, PDF p.36 |
| FR-SAL-08 | Sales | Record customer payment | Accounting shall be able to receive/record customer payment and retain payment history. | BR-002, BR-009 | §3.2.2, PDF p.36 |
| FR-SAL-09 | Sales | Cancel quotation | The system shall allow a quotation to be cancelled when the customer does not agree to purchase. | BR-002 | §3.2.3.2, PDF p.45 |
| FR-SAL-10 | Sales | Cancel confirmed order delivery | The documented sales exception flow shall allow cancellation of the delivery/order state after a confirmed customer order is cancelled. | BR-002, BR-005 | §3.2.3.2, PDF pp.46–47 |
| FR-PUR-01 | Purchase | Create RFQ | Purchasing Staff shall be able to create a new RFQ for a supplier. | BR-003 | §3.3.2, PDF p.48 |
| FR-PUR-02 | Purchase | Maintain RFQ/PO details | The RFQ/PO shall capture supplier, product information, quantity, price, order deadline, expected receipt date, destination, and currency where documented. | BR-003, BR-014 | §3.3.2.2, PDF pp.49–50 |
| FR-PUR-03 | Purchase | Send RFQ | Purchasing Staff shall be able to send the RFQ to the supplier. | BR-003 | §3.3.2, PDF p.48 |
| FR-PUR-04 | Purchase | Confirm or cancel purchase order | Purchasing Staff shall be able to confirm the order after supplier response or cancel it when not proceeding. | BR-003 | §3.3.2, PDF p.48 |
| FR-PUR-05 | Purchase | Send purchase order | Purchasing Staff shall be able to create/send the purchase order to the supplier. | BR-003 | §3.3.2, PDF p.48 |
| FR-PUR-06 | Purchase | Receive supplier goods | Warehouse Staff shall be able to receive goods delivered by the supplier. | BR-003, BR-004 | §3.3.2, PDF p.48 |
| FR-PUR-07 | Purchase | Inspect received goods | Warehouse Staff shall check received quantity and quality. | BR-003, BR-004 | §3.3.2, PDF p.48 |
| FR-PUR-08 | Purchase | Review supplier invoice | Purchasing Staff shall review/confirm the supplier invoice and send it to Accounting. | BR-003, BR-011 | §3.3.2, PDF pp.48–49 |
| FR-PUR-09 | Purchase | Verify supplier invoice | Accounting shall verify supplier invoice information. | BR-003, BR-011 | §3.3.2, PDF p.49 |
| FR-PUR-10 | Purchase | Pay supplier invoice | Accounting shall be able to pay the supplier invoice. | BR-003, BR-011 | §3.3.2, PDF p.49 |
| FR-REC-01 | Inventory - Receipt | Check received quantity/quality | Warehouse Staff shall check quantity and quality before signing receipt confirmation. | BR-004 | §3.4.1.2, PDF p.62 |
| FR-REC-02 | Inventory - Receipt | Create inbound lot | Warehouse Staff shall be able to create an inbound lot number for the received order. | BR-004 | §3.4.1.2, PDF p.62 |
| FR-REC-03 | Inventory - Receipt | Validate receipt | Warehouse Staff shall be able to validate the goods receipt. | BR-004 | §3.4.1.2, PDF p.62 |
| FR-REC-04 | Inventory - Receipt | Produce and sign receipt documentation | The receipt process shall support printing the receipt, related-party sign-off, and attaching scanned supporting documents. | BR-004 | §3.4.1.2, PDF p.62 |
| FR-REC-05 | Inventory - Receipt | Store receipt fields | The receipt shall hold source party, operation type, destination, scheduled date, deadline, source document, operations, additional info, and notes as documented. | BR-004, BR-014 | §3.4.1.2.2, PDF pp.62–63 |
| FR-OUT-01 | Inventory - Outbound | Review delivery order | Warehouse Staff shall review the stock-issue/delivery request. | BR-005 | §3.4.2.2, PDF p.67 |
| FR-OUT-02 | Inventory - Outbound | Check stock availability | Warehouse Staff/Manager shall check the quantity available for products in the sales order. | BR-005 | §3.4.2.2, PDF p.67 |
| FR-OUT-03 | Inventory - Outbound | Validate stock issue | Warehouse Staff shall confirm the stock-issue document and perform the stock issue. | BR-005 | §3.4.2.2, PDF p.67 |
| FR-OUT-04 | Inventory - Outbound | Record outbound lot/shipment | Warehouse Staff shall create an outbound lot and record the transportation/stock issue process. | BR-005 | §3.4.2.2, PDF p.67 |
| FR-OUT-05 | Inventory - Outbound | Attach outbound documents | Warehouse Staff shall be able to scan and attach related documents to the system. | BR-005 | §3.4.2.2, PDF p.68 |
| FR-CNT-01 | Inventory - Stock Count | Request stock count | A requesting department shall be able to request a stock count and create a count document/request. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-CNT-02 | Inventory - Stock Count | Approve stock-count request | A Manager shall review/approve the stock-count request. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-CNT-03 | Inventory - Stock Count | Define count target/location | Warehouse Staff shall identify the item/object and location to count from the approved count document. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-CNT-04 | Inventory - Stock Count | Record physical count | Warehouse Staff shall perform the count and record results on the count document. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-CNT-05 | Inventory - Stock Count | Compare/investigate variance | Warehouse Staff shall compare physical vs system quantity and investigate variances. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-CNT-06 | Inventory - Stock Count | Approve/recount/adjust | The process shall support manager approval of variance, recount when not approved, and stock adjustment after approval by the requesting side. | BR-006 | §3.4.3.2, PDF p.75 |
| FR-TRF-01 | Inventory - Transfer | Notify shortage | Receiving Warehouse Manager shall send a shortage notification/list to the source warehouse manager. | BR-007 | §3.4.4.2, PDF p.78 |
| FR-TRF-02 | Inventory - Transfer | Check source stock | Source Warehouse Manager shall perform stock checking before transfer. | BR-007 | §3.4.4.2, PDF p.78 |
| FR-TRF-03 | Inventory - Transfer | Cancel transfer if no stock | If the source warehouse has no stock, the internal transfer shall be cancelled. | BR-007 | §3.4.4.2, PDF p.78 |
| FR-TRF-04 | Inventory - Transfer | Issue transfer if stock exists | If stock is available, the source warehouse shall provide the product list, pick goods, issue stock, and create the stock-issue record. | BR-007 | §3.4.4.2, PDF pp.78–79 |
| FR-TRF-05 | Inventory - Transfer | Receive and inspect transfer | The receiving warehouse shall receive and inspect transferred goods. | BR-007 | §3.4.4.2, PDF p.79 |
| FR-TRF-06 | Inventory - Transfer | Return or confirm transfer | If transferred goods fail requirements they are returned; if they pass, the receiving warehouse confirms the transfer. | BR-007 | §3.4.4.2, PDF p.79 |
| FR-CRM-01 | CRM | Create opportunity | The system shall allow creation of an opportunity with the documented basic information such as opportunity name, customer company, email, phone, expected revenue, and priority. | BR-008 | §3.5.3, PDF p.83 |
| FR-CRM-02 | CRM | Maintain opportunity details | The opportunity can include assigned salesperson, tags, expected closing date, and internal notes as documented. | BR-008 | §3.5.3, PDF p.83 |
| FR-CRM-03 | CRM | Progress opportunity stages | Users shall be able to move an opportunity through Consulting and Qualified when the documented conditions are met. | BR-008 | §3.5.3, PDF pp.84–85 |
| FR-CRM-04 | CRM | Create quotation from opportunity | Sales Staff shall be able to create a quotation from an opportunity and enter products, quantity, unit price, and discount. | BR-008, BR-002 | §3.5.3, PDF pp.85–86 |
| FR-CRM-05 | CRM | Send opportunity quotation | Users shall be able to email the quotation and have it move to a sent status. | BR-008, BR-002 | §3.5.3, PDF pp.86–87 |
| FR-CRM-06 | CRM | Confirm quotation to order | When the customer agrees, users shall be able to confirm the quotation and create a sales order. | BR-008, BR-002 | §3.5.3, PDF p.87 |
| FR-CRM-07 | CRM | Cancel and restore quotation | When the customer declines, users shall be able to cancel the quotation; the report also documents restoring a cancelled quotation back to quotation status. | BR-008 | §3.5.3, PDF p.88 |
| FR-CRM-08 | CRM | Capture post-sale feedback | The customer-care process shall support receiving customer feedback and recording issues/improvement proposals. | BR-008 | §3.5.2, PDF p.82 |
| FR-AR-01 | Accounting - AR | Review customer order/invoice | Accounting shall check the customer order/invoice information. | BR-009 | §3.6.1.2, PDF pp.89–90 |
| FR-AR-02 | Accounting - AR | Post invoice information | Accounting shall post/record invoice information. | BR-009 | §3.6.1.2, PDF p.90 |
| FR-AR-03 | Accounting - AR | Send/print draft invoice | Accounting shall be able to print or email a draft invoice. | BR-009 | §3.6.1.2, PDF p.90 |
| FR-AR-04 | Accounting - AR | Record customer payment confirmation | Sales Staff shall confirm receipt of customer payment and communicate confirmation to Accounting. | BR-009 | §3.6.1.2, PDF p.90 |
| FR-AR-05 | Accounting - AR | Send paid invoice | Accounting shall be able to send the confirmed/paid invoice to the customer. | BR-009 | §3.6.1.2, PDF p.90 |
| FR-AR-06 | Accounting - AR | Periodic receivables summary | Accounting shall update and summarize receivables by period. | BR-009 | §3.6.1.2, PDF p.90 |
| FR-OD-01 | Accounting - Overdue AR | Monitor unpaid invoices | Accounting shall monitor customer receivables and review unpaid invoice information. | BR-010 | §3.6.2.2, PDF p.99 |
| FR-OD-02 | Accounting - Overdue AR | Send payment reminder | Accounting shall send an email reminder to customers with unpaid invoices. | BR-010 | §3.6.2.2, PDF p.99 |
| FR-OD-03 | Accounting - Overdue AR | Second reminder after 15 days | When an invoice is 15 days late, Accounting shall send another payment reminder email. | BR-010 | §3.6.2.2, PDF p.99 |
| FR-OD-04 | Accounting - Overdue AR | Phone reminder after 30 days | For invoices unpaid for more than 30 days, Accounting shall call the customer to remind payment. | BR-010 | §3.6.2.2, PDF p.99 |
| FR-OD-05 | Accounting - Overdue AR | Confirm overdue payment | After payment is received, Sales Staff shall confirm payment for Accounting. | BR-010 | §3.6.2.2, PDF p.99 |
| FR-AP-01 | Accounting - AP | Reconcile purchase/goods | Accounting shall reconcile the received goods and purchase order. | BR-011 | §3.6.3.2, PDF p.104 |
| FR-AP-02 | Accounting - AP | Post vendor bill | Accounting shall post vendor invoice information. | BR-011 | §3.6.3.2, PDF p.104 |
| FR-AP-03 | Accounting - AP | Pay vendor debt | Accounting shall perform payment of the supplier payable. | BR-011 | §3.6.3.2, PDF p.104 |
| FR-AP-04 | Accounting - AP | Confirm supplier payment | Accounting shall confirm the supplier invoice as paid. | BR-011 | §3.6.3.2, PDF p.104 |
| FR-AP-05 | Accounting - AP | Periodic supplier debt summary | Accounting shall update and summarize supplier debt by period. | BR-011 | §3.6.3.2, PDF p.104 |
| FR-CRF-01 | Accounting - Customer Refund | Validate refund request | Accounting shall verify a customer refund request and reject invalid requests or continue valid requests. | BR-012 | §3.6.4.2, PDF p.113 |
| FR-CRF-02 | Accounting - Customer Refund | Create linked credit note | Accounting shall create a Credit Note linked to the original invoice for a valid refund. | BR-012 | §3.6.4.2, PDF p.113 |
| FR-CRF-03 | Accounting - Customer Refund | Approve refund credit note | Accounting shall review and approve the refund credit note. | BR-012 | §3.6.4.2, PDF p.113 |
| FR-CRF-04 | Accounting - Customer Refund | Record refund payment | Accounting shall record the refund payment in the system. | BR-012 | §3.6.4.2, PDF p.114 |
| FR-CRF-05 | Accounting - Customer Refund | Notify customer | Accounting shall email the customer that the refund has been completed. | BR-012 | §3.6.4.2, PDF p.114 |
| FR-CRF-06 | Accounting - Customer Refund | Update receivables after refund | Accounting shall update and summarize receivables after refund processing. | BR-012 | §3.6.4.2, PDF p.114 |
| FR-SRF-01 | Accounting - Supplier Refund | Review refund basis | Accounting shall check the purchase invoice/order before requesting a supplier refund. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-02 | Accounting - Supplier Refund | Send supplier refund request | Accounting shall send the refund request to the supplier. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-03 | Accounting - Supplier Refund | Capture supplier response | The supplier shall review the invoice/request and respond. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-04 | Accounting - Supplier Refund | Validate supplier response | Accounting shall reject invalid cases or continue valid supplier-refund processing. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-05 | Accounting - Supplier Refund | Create/approve linked credit note | Accounting shall create and approve a Credit Note linked to the original vendor bill. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-06 | Accounting - Supplier Refund | Record supplier refund | Accounting shall record the supplier refund payment in the system. | BR-013 | §3.6.5.2, PDF p.120 |
| FR-SRF-07 | Accounting - Supplier Refund | Update supplier debt after refund | Accounting shall update and summarize supplier debt after refund processing. | BR-013 | §3.6.5.2, PDF p.120 |
