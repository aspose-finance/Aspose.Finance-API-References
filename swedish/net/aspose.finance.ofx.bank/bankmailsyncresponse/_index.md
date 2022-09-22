---
title: BankMailSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Svarsklass för bankepostsynkronisering.
type: docs
weight: 340
url: /sv/net/aspose.finance.ofx.bank/bankmailsyncresponse/
---
## BankMailSyncResponse class

Svarsklass för banke-postsynkronisering.

```csharp
public class BankMailSyncResponse : AbstractSyncResponse
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BankMailSyncResponse](bankmailsyncresponse)() | Initierar en ny instans av[`BankMailSyncResponse`](../bankmailsyncresponse) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.bank/bankmailsyncresponse/accountfrom) { get; set; } | Hämtar eller ställer in från av[`BankAccount`](../../aspose.finance.ofx/bankaccount) eller[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) . |
| [BankMailTransactionResponses](../../aspose.finance.ofx.bank/bankmailsyncresponse/bankmailtransactionresponses) { get; set; } | Hämtar eller ställer in samlingen av[`BankMailTransactionResponse`](../bankmailtransactionresponse) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [OfxExtension](../../aspose.finance.ofx.bank/bankmailsyncresponse/ofxextension) { get; set; } | Hämtar eller ställer in[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namnutrymme [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->