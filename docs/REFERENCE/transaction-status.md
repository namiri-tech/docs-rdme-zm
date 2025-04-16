---
title: Transaction status
deprecated: false
hidden: false
metadata:
  robots: index
---
## DigiTax Queueing system

DigiTax provides the following:

* Asynchronous functionality that automatically retries Smart Invoice.
* Get notifications on transaction statuses via [Callback URLs](doc:call-back-urls)
* Throttling traffic between the businesses throughput and Smart Invoice.

These functionality is possible due to the DigiTax Queueing system.

> 📘 You don't run the risk of double-entry
>
> Every transaction that interacts with Smart Invoice is first off entered into the DigiTax Queueing system to **mitigate against possible Smart Invoice intermittency and downtime** or slow response rate.

## The different transaction statuses and what they mean

Since transactions are first off entered into the DigiTax Queueing system, we give you the following statuses. This is what they mean.

### Transaction statuses

...