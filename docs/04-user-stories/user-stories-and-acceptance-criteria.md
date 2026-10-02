# User Stories and Acceptance Criteria

## US-SAL-01 — Sales

**User Story**  
As **Sales Staff**, I want to **create and send a customer quotation**, so that **the customer can review product and commercial information before deciding to buy**.

**Acceptance Criteria**
- AC1: Given a customer quotation request, when Sales Staff creates a quotation, then the quotation can contain the customer and requested products.
- AC2: Given quotation details are prepared, when Sales Staff sends the quotation, then it can be sent to the customer by email.

**Related FR:** FR-SAL-01, FR-SAL-02, FR-SAL-03  

## US-SAL-02 — Sales

**User Story**  
As **Sales Staff**, I want to **confirm an accepted quotation as a sales order**, so that **the accepted customer request can move into fulfillment**.

**Acceptance Criteria**
- AC1: Given the customer has accepted the quotation, when Sales Staff confirms it, then the quotation becomes a sales order.
- AC2: Given a confirmed sales order, then order details are available for warehouse fulfillment.

**Related FR:** FR-SAL-04, FR-SAL-05  

## US-SAL-03 — Sales

**User Story**  
As **Warehouse Staff**, I want to **pick and deliver products for a confirmed sales order**, so that **the customer order can be fulfilled**.

**Acceptance Criteria**
- AC1: Given confirmed order details, when Warehouse Staff processes the order, then products are taken from stock according to the order.
- AC2: When fulfillment is performed, then goods can be delivered to the customer.

**Related FR:** FR-SAL-06, FR-OUT-01, FR-OUT-02, FR-OUT-03  

## US-SAL-04 — Sales/Accounting

**User Story**  
As **Accountant**, I want to **record customer payment**, so that **the business retains payment history for the sale**.

**Acceptance Criteria**
- AC1: Given a customer invoice and received payment, when payment is recorded, then payment history is retained.

**Related FR:** FR-SAL-07, FR-SAL-08, FR-AR-04  

## US-PUR-01 — Purchase

**User Story**  
As **Purchasing Staff**, I want to **create and send an RFQ to a supplier**, so that **the business can request supplier pricing/order information**.

**Acceptance Criteria**
- AC1: Given purchasing needs, when Purchasing Staff creates an RFQ, then supplier and product/order details can be entered as documented.
- AC2: When the RFQ is ready, then it can be sent to the supplier.

**Related FR:** FR-PUR-01, FR-PUR-02, FR-PUR-03  

## US-PUR-02 — Purchase

**User Story**  
As **Purchasing Staff**, I want to **confirm or cancel a supplier order after supplier response**, so that **the purchase can proceed only when the business decides to continue**.

**Acceptance Criteria**
- AC1: Given a supplier response, when the order is accepted, then Purchasing Staff can confirm the order.
- AC2: Given the business does not proceed, then the order/RFQ can be cancelled as documented.

**Related FR:** FR-PUR-04, FR-PUR-05  

## US-REC-01 — Inventory

**User Story**  
As **Warehouse Staff**, I want to **receive and inspect supplier goods**, so that **only checked goods are validated into the receipt flow**.

**Acceptance Criteria**
- AC1: Given supplier goods arrive, when Warehouse Staff receives them, then quantity and quality are checked before confirmation.
- AC2: After checking, Warehouse Staff can create the inbound lot and validate the receipt.

**Related FR:** FR-PUR-06, FR-PUR-07, FR-REC-01, FR-REC-02, FR-REC-03  

## US-CNT-01 — Inventory

**User Story**  
As **Warehouse Staff**, I want to **perform and record a stock count**, so that **physical stock can be compared with system stock**.

**Acceptance Criteria**
- AC1: Given an approved stock-count request, when Warehouse Staff performs the count, then count results are recorded.
- AC2: When physical and system quantities differ, then the variance is investigated.

**Related FR:** FR-CNT-01, FR-CNT-02, FR-CNT-03, FR-CNT-04, FR-CNT-05  

## US-CNT-02 — Inventory

**User Story**  
As **Manager**, I want to **approve or require recount for stock variance**, so that **stock adjustments follow the documented review process**.

**Acceptance Criteria**
- AC1: Given a stock variance, when the Manager does not approve it, then the count is repeated.
- AC2: Given the variance is approved, then the documented flow can proceed to stock adjustment.

**Related FR:** FR-CNT-06  

## US-TRF-01 — Inventory

**User Story**  
As **Source Warehouse Manager**, I want to **transfer stock to another warehouse when stock is available**, so that **the receiving warehouse can replenish shortages**.

**Acceptance Criteria**
- AC1: Given a shortage request, when source stock is checked and unavailable, then the transfer is cancelled.
- AC2: Given source stock is available, then goods can be picked/issued and a transfer record created.

**Related FR:** FR-TRF-01, FR-TRF-02, FR-TRF-03, FR-TRF-04  

## US-TRF-02 — Inventory

**User Story**  
As **Receiving Warehouse Manager**, I want to **inspect transferred goods**, so that **nonconforming transfers can be returned and acceptable transfers confirmed**.

**Acceptance Criteria**
- AC1: Given transferred goods arrive, when they are inspected and do not meet requirements, then they are returned.
- AC2: When transferred goods meet requirements, then the receiving warehouse confirms them.

**Related FR:** FR-TRF-05, FR-TRF-06  

## US-CRM-01 — CRM

**User Story**  
As **Sales Staff**, I want to **create and progress a customer opportunity**, so that **customer interest can be tracked through the documented CRM stages**.

**Acceptance Criteria**
- AC1: When a new opportunity is created, then the documented basic opportunity information can be recorded.
- AC2: When customer information is available, the opportunity can move to Consulting.
- AC3: When staff assess the customer as a potential buyer, the opportunity can move to Qualified.

**Related FR:** FR-CRM-01, FR-CRM-02, FR-CRM-03  

## US-CRM-02 — CRM

**User Story**  
As **Sales Staff**, I want to **create and send a quotation from an opportunity**, so that **customer needs captured in CRM can progress toward a sale**.

**Acceptance Criteria**
- AC1: Given a qualified opportunity, when a quotation is created, then product, quantity, unit price, and discount can be entered as documented.
- AC2: When the quotation is emailed, then the quotation can move to a sent status.

**Related FR:** FR-CRM-04, FR-CRM-05  

## US-CRM-03 — CRM

**User Story**  
As **Sales Staff**, I want to **confirm or cancel a quotation based on customer decision**, so that **the opportunity can follow the documented purchase/no-purchase path**.

**Acceptance Criteria**
- AC1: Given the customer agrees, when the quotation is confirmed, then a sales order is created.
- AC2: Given the customer does not agree, then the quotation can be cancelled.
- AC3: Given a cancelled quotation, the report documents an option to restore it to quotation status.

**Related FR:** FR-CRM-06, FR-CRM-07  

## US-AR-01 — Accounting

**User Story**  
As **Accountant**, I want to **manage customer invoice and receivable information**, so that **customer debt and payment status can be tracked**.

**Acceptance Criteria**
- AC1: Given a customer order/invoice, when Accounting reviews it, then invoice information can be posted.
- AC2: The invoice can be printed/emailed in draft form.
- AC3: After customer payment is confirmed, Accounting can send the paid/confirmed invoice and update receivables.

**Related FR:** FR-AR-01, FR-AR-02, FR-AR-03, FR-AR-04, FR-AR-05, FR-AR-06  

## US-OD-01 — Accounting

**User Story**  
As **Accountant**, I want to **follow up overdue customer invoices**, so that **the business can apply the documented collection reminders**.

**Acceptance Criteria**
- AC1: Given an unpaid invoice, Accounting can send an email payment reminder.
- AC2: Given an invoice is 15 days late, Accounting sends a second reminder email.
- AC3: Given an invoice is unpaid for more than 30 days, Accounting calls the customer.

**Related FR:** FR-OD-01, FR-OD-02, FR-OD-03, FR-OD-04  

## US-AP-01 — Accounting

**User Story**  
As **Accountant**, I want to **process supplier payables**, so that **supplier debt can be reconciled, paid, and summarized**.

**Acceptance Criteria**
- AC1: Given a supplier invoice, Accounting reconciles the purchase/goods information and posts the bill.
- AC2: Accounting can pay and confirm the supplier invoice.
- AC3: Supplier debt is updated/summarized by period.

**Related FR:** FR-AP-01, FR-AP-02, FR-AP-03, FR-AP-04, FR-AP-05  

## US-CRF-01 — Accounting

**User Story**  
As **Accountant**, I want to **process a valid customer refund through a Credit Note**, so that **the customer can be refunded while the transaction remains linked to the original invoice**.

**Acceptance Criteria**
- AC1: Given a refund request, when Accounting validates it, invalid requests are rejected and valid requests continue.
- AC2: For a valid request, a Credit Note linked to the original invoice can be created and approved.
- AC3: After refund payment is recorded, a refund notification can be emailed to the customer.

**Related FR:** FR-CRF-01, FR-CRF-02, FR-CRF-03, FR-CRF-04, FR-CRF-05  


## US-SRF-01 — Accounting

**User Story**  
As **Accountant**, I want to **request and record a supplier refund**, so that **the business can recover valid amounts from a supplier and update supplier debt**.

**Acceptance Criteria**
- AC1: Given a refund basis, Accounting sends a refund request to the supplier.
- AC2: When the supplier responds, invalid cases are rejected and valid cases continue.
- AC3: For a valid case, a Credit Note linked to the original vendor bill is created/approved and the refund is recorded.

**Related FR:** FR-SRF-01, FR-SRF-02, FR-SRF-03, FR-SRF-04, FR-SRF-05, FR-SRF-06, FR-SRF-07  

