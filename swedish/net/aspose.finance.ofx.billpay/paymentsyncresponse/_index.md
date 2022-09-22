---
title: PaymentSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Svarsklass för betalningssynkronisering.
type: docs
weight: 1250
url: /sv/net/aspose.finance.ofx.billpay/paymentsyncresponse/
---
## PaymentSyncResponse class

Svarsklass för betalningssynkronisering.

```csharp
public class PaymentSyncResponse : AbstractSyncResponse
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PaymentSyncResponse](paymentsyncresponse)() | Initierar en ny instans av[`PaymentSyncResponse`](../paymentsyncresponse) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BankAccountFrom](../../aspose.finance.ofx.billpay/paymentsyncresponse/bankaccountfrom) { get; set; } | Hämtar eller ställer in från av[`BankAccount`](../../aspose.finance.ofx/bankaccount) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [OfxExtension](../../aspose.finance.ofx.billpay/paymentsyncresponse/ofxextension) { get; set; } | Hämtar eller ställer in[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [PaymentTransactionResponses](../../aspose.finance.ofx.billpay/paymentsyncresponse/paymenttransactionresponses) { get; set; } | Hämtar eller ställer in samlingen av[`PaymentTransactionResponse`](../paymenttransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namnutrymme [Aspose.Finance.Ofx.BillPay](../../aspose.finance.ofx.billpay)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->