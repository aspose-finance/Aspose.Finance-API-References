﻿---
title: BillPaymentStatusCodeEnum enumeration
second_title: Aspose.Finance for Python via .NET API References
description: 
type: docs
weight: 410
url: /python-net/aspose.finance.ofx.billerdelivery/billpaymentstatuscodeenum/
is_root: false
---

## BillPaymentStatusCodeEnum enumeration

Bill payment status code enum.



The BillPaymentStatusCodeEnum type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| PAIDOUTOFBAND | A Payment has been initiated for this bill via a mechanism that does not report status via OFX. This status is intended to
| AUTOPAY | The Biller or Service Provider will initiate the payment based on a pre-authorization by the customer, typically a “good until cancelled”
| CANCELLED | The customer cancelled the payment that was previously scheduled. |
| UNPAYABLE | None of the Payment Instruments allowed for this bill are supported by the Payment Provider. This is intended to be used where the
| NONE | There is neither a payment scheduled, nor has one been made against this bill. This may be the initial payment status of a bill. |
| SCHEDULED | A payment has been scheduled, but not yet processed against this bill. |
| PROCESSED | The payment has been processed against this bill, and can no longer be cancelled. |
| POSTED | The biller has posted the payment against this bill. |


### See Also

* module [aspose.finance.ofx.billerdelivery](../)