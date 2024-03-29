---
title: PayeeSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Svarsklass för betalningsmottagarelista synkronisering.
type: docs
weight: 1020
url: /sv/net/aspose.finance.ofx.billpay/payeesyncresponse/
---
## PayeeSyncResponse class

Svarsklass för betalningsmottagarelista synkronisering.

```csharp
public class PayeeSyncResponse : AbstractSyncResponse
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PayeeSyncResponse](payeesyncresponse)() | Initierar en ny instans av[`PayeeSyncResponse`](../payeesyncresponse) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [OfxExtension](../../aspose.finance.ofx.billpay/payeesyncresponse/ofxextension) { get; set; } | Hämtar eller ställer in[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [PayeeTransactionResponses](../../aspose.finance.ofx.billpay/payeesyncresponse/payeetransactionresponses) { get; set; } | Hämtar eller ställer in samlingen av[`PayeeTransactionResponse`](../payeetransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namnutrymme [Aspose.Finance.Ofx.BillPay](../../aspose.finance.ofx.billpay)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
