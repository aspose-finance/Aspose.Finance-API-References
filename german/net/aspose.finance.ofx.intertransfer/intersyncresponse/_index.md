---
title: InterSyncResponse
second_title: Aspose.Finance für .NET-API-Referenz
description: InterbankTransaktionssynchronisierungsAntwortklasse.
type: docs
weight: 2460
url: /de/net/aspose.finance.ofx.intertransfer/intersyncresponse/
---
## InterSyncResponse class

Interbank-Transaktionssynchronisierungs-Antwortklasse.

```csharp
public class InterSyncResponse : AbstractSyncResponse
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [InterSyncResponse](intersyncresponse)() | Initialisiert eine neue Instanz von[`InterSyncResponse`](../intersyncresponse) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.intertransfer/intersyncresponse/accountfrom) { get; set; } | Ermittelt oder setzt die Quelle von[`BankAccount`](../../aspose.finance.ofx/bankaccount) oder[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) oder[`LoanAccount`](../../aspose.finance.ofx/loanaccount) . |
| [InterTransactionResponses](../../aspose.finance.ofx.intertransfer/intersyncresponse/intertransactionresponses) { get; set; } | Ruft die Sammlung von ab oder legt sie fest[`InterTransactionResponse`](../intertransactionresponse) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja, wenn das Token in der Synchronisierungsanforderung älter ist als der früheste Eintrag in der Verlaufstabelle des Servers. In diesem Fall sind einige Antworten verloren gegangen. Nein, wenn das Token in der Synchronisierungsanforderung neuer ist als oder mit einem Token auf dem Server übereinstimmt Verlaufstabelle. |
| [OfxExtension](../../aspose.finance.ofx.intertransfer/intersyncresponse/ofxextension) { get; set; } | Ruft ab oder setzt die[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Ruft das neue Synchronisierungstoken ab oder legt es fest. |

### Siehe auch

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namensraum [Aspose.Finance.Ofx.InterTransfer](../../aspose.finance.ofx.intertransfer)
* Montage [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
