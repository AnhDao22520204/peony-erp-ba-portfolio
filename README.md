# Peony Fashion Store – ERP Business Analysis Portfolio

A Business Analysis case study restructured from an academic ERP project that applies **Odoo 18.0** to the management of a fashion retail business (Peony).

## Business context

Peony is described as a primarily B2C fashion retailer that purchases products from partners/suppliers and sells clothing and accessories to customers. The project applies ERP to centralize and coordinate business information and operations that otherwise span sales, purchasing, inventory, CRM, and accounting.

## Project scope

The report defines five core areas as in scope:

- Sales Management
- Purchase Management
- Inventory / Logistics
- Customer Relationship Management (CRM)
- Accounting & Finance

## Business processes covered

| Area       | Process                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------- |
| Sales      | Quotation → sales order → delivery → invoice → payment                                         |
| Purchasing | RFQ → purchase order → receipt → vendor invoice → payment                                      |
| Inventory  | Goods receipt, goods issue, stock count, internal transfer                                     |
| CRM        | Customer contact, opportunity stages, quotation, Won/Lost-related handling, feedback           |
| Accounting | Customer receivables, overdue receivables, supplier payables, customer refund, supplier refund |

Detailed process files are available under `docs/03-business-processes/`.

## BA deliverables in this repository

- Business context, problem, objectives, scope, and stakeholders
- Business process specifications
- Business Requirements (BR)
- Functional Requirements (FR)
- Business Rules (BRULE)
- User Stories and Acceptance Criteria
- Requirement Traceability Matrix (RTM)
- User Acceptance Test (UAT) cases
- Source-to-artifact mapping and documented gaps
- Excel traceability workbook for recruiter/interviewer review

## Repository structure

```text
peony-erp-ba-portfolio/
├── README.md
├── README.vi.md
├── SOURCE_GROUNDING.md
├── docs/
│   ├── 00-guide/
│   ├── 01-business-overview/
│   ├── 02-requirements/
│   ├── 03-business-processes/
│   ├── 04-user-stories/
│   └── 05-testing/
├── artifacts/
│   └── BA_Traceability.xlsx
├── diagrams/
   └── README.md

```

## Tools / notation represented in the source project

- Odoo 18.0
- BPMN
- ERP modules for Sales, Purchase, Inventory, CRM, and Accounting
