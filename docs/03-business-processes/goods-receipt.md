# Goods Receipt / Inbound Process

## Actors

- Purchasing Staff
- Warehouse Staff
- Accounting
- Delivery Party

## Process flow

1. RFQ/order activities initiate the inbound flow.
2. Goods are received after supplier confirmation/delivery.
3. Warehouse Staff checks quantity and quality.
4. Warehouse Staff creates an inbound lot number.
5. Warehouse Staff validates the receipt.
6. Receipt documentation can be printed; related parties sign confirmation.
7. Supporting documents are scanned and attached to the system.
8. Accounting handles invoice/payment and retains payment history as documented.

## Documented exceptions / decision paths

- The source assigns the cancellation step in the inbound table to “Sales Staff”, which conflicts with the purchase context; it is preserved as a documented inconsistency rather than silently corrected.

## BPMN

<p align="center">
  <img src="../../diagrams/goods_receipt.png"
       alt="Goods Receipt / Inbound BPMN"
       width="900">
</p>
