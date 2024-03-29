---
title: RecurringIntraSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Svarsklass för återkommande intrabanktransaktionssynkronisering.
type: docs
weight: 600
url: /sv/net/aspose.finance.ofx.bank/recurringintrasyncresponse/
---
## RecurringIntraSyncResponse class

Svarsklass för återkommande intrabanktransaktionssynkronisering.

```csharp
public class RecurringIntraSyncResponse : AbstractSyncResponse
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RecurringIntraSyncResponse](recurringintrasyncresponse)() | Initierar en ny instans av[`RecurringIntraSyncResponse`](../recurringintrasyncresponse) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.bank/recurringintrasyncresponse/accountfrom) { get; set; } | Hämtar eller ställer in från av[`BankAccount`](../../aspose.finance.ofx/bankaccount) eller[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) eller[`LoanAccount`](../../aspose.finance.ofx/loanaccount) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [OfxExtension](../../aspose.finance.ofx.bank/recurringintrasyncresponse/ofxextension) { get; set; } | Hämtar eller ställer in[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [RecurringIntraTransactionResponses](../../aspose.finance.ofx.bank/recurringintrasyncresponse/recurringintratransactionresponses) { get; set; } | Hämtar eller ställer in samlingen av[`RecurringIntraTransactionResponse`](../recurringintratransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namnutrymme [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
