# Requirement Traceability Matrix (RTM)

This RTM connects business requirements to functional requirements, user stories, and UAT cases.

| BR | FR | User Story | UAT | Module | Scenario |
|---|---|---|---|---|---|
| BR-002, BR-014 | FR-SAL-01, FR-SAL-02, FR-SAL-03 | US-SAL-01 | UAT-SAL-01 | Sales | Create and email quotation |
| BR-002 | FR-SAL-04 | US-SAL-02 | UAT-SAL-02 | Sales | Confirm quotation to sales order |
| BR-002, BR-005 | FR-SAL-05, FR-SAL-06, FR-OUT-01, FR-OUT-03 | US-SAL-03 | UAT-SAL-03 | Sales/Inventory | Fulfill customer order |
| BR-002 | FR-SAL-09 | US-CRM-03 | UAT-SAL-04 | Sales | Cancel quotation |
| BR-003, BR-014 | FR-PUR-01, FR-PUR-02, FR-PUR-03 | US-PUR-01 | UAT-PUR-01 | Purchase | Create and send RFQ |
| BR-003 | FR-PUR-04, FR-PUR-05 | US-PUR-02 | UAT-PUR-02 | Purchase | Confirm purchase order |
| BR-003, BR-004 | FR-PUR-06, FR-PUR-07, FR-REC-01, FR-REC-03 | US-REC-01 | UAT-REC-01 | Inventory - Receipt | Receive and validate supplier goods |
| BR-005 | FR-OUT-01, FR-OUT-02, FR-OUT-03 | US-SAL-03 | UAT-OUT-01 | Inventory - Outbound | Issue stock for customer delivery |
| BR-006 | FR-CNT-02, FR-CNT-03, FR-CNT-04, FR-CNT-05 | US-CNT-01 | UAT-CNT-01 | Inventory - Stock Count | Record and compare stock count |
| BR-006 | FR-CNT-06 | US-CNT-02 | UAT-CNT-02 | Inventory - Stock Count | Recount after unapproved variance |
| BR-007 | FR-TRF-01, FR-TRF-02, FR-TRF-03 | US-TRF-01 | UAT-TRF-01 | Inventory - Transfer | Cancel transfer when source stock unavailable |
| BR-007 | FR-TRF-04, FR-TRF-05, FR-TRF-06 | US-TRF-01, US-TRF-02 | UAT-TRF-02 | Inventory - Transfer | Complete transfer when source stock exists |
| BR-007 | FR-TRF-05, FR-TRF-06 | US-TRF-02 | UAT-TRF-03 | Inventory - Transfer | Return nonconforming transfer |
| BR-008 | FR-CRM-01, FR-CRM-02, FR-CRM-03 | US-CRM-01 | UAT-CRM-01 | CRM | Create opportunity and move to Consulting |
| BR-008 | FR-CRM-03 | US-CRM-01 | UAT-CRM-02 | CRM | Move opportunity to Qualified |
| BR-008, BR-002 | FR-CRM-04, FR-CRM-05 | US-CRM-02 | UAT-CRM-03 | CRM | Create/send quotation from opportunity |
| BR-008, BR-002 | FR-CRM-06 | US-CRM-03 | UAT-CRM-04 | CRM | Confirm quotation after customer agrees |
| BR-008 | FR-CRM-07 | US-CRM-03 | UAT-CRM-05 | CRM | Cancel/restore quotation after customer declines |
| BR-009 | FR-AR-01, FR-AR-02, FR-AR-03 | US-AR-01 | UAT-AR-01 | Accounting - AR | Post and send customer invoice |
| BR-009 | FR-AR-04, FR-AR-05, FR-AR-06 | US-AR-01 | UAT-AR-02 | Accounting - AR | Confirm customer payment and update receivables |
| BR-010 | FR-OD-01, FR-OD-03 | US-OD-01 | UAT-OD-01 | Accounting - Overdue AR | Second reminder at 15 days overdue |
| BR-010 | FR-OD-01, FR-OD-04 | US-OD-01 | UAT-OD-02 | Accounting - Overdue AR | Phone reminder after more than 30 days |
| BR-011 | FR-AP-01, FR-AP-02, FR-AP-03, FR-AP-04, FR-AP-05 | US-AP-01 | UAT-AP-01 | Accounting - AP | Process supplier payable |
| BR-012 | FR-CRF-01 | US-CRF-01 | UAT-CRF-01 | Accounting - Customer Refund | Reject invalid customer refund |
| BR-012 | FR-CRF-01, FR-CRF-02, FR-CRF-03, FR-CRF-04, FR-CRF-05 | US-CRF-01 | UAT-CRF-02 | Accounting - Customer Refund | Process valid customer refund |
| BR-013 | FR-SRF-01, FR-SRF-02, FR-SRF-03, FR-SRF-04, FR-SRF-05, FR-SRF-06, FR-SRF-07 | US-SRF-01 | UAT-SRF-01 | Accounting - Supplier Refund | Process valid supplier refund |
