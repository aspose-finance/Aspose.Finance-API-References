---
title: WireSyncResponse
second_title: Aspose.Finance für .NET-API-Referenz
description: Antwortklasse für die Synchronisierung von Überweisungen.
type: docs
weight: 6410
url: /de/net/aspose.finance.ofx.wiretransfer/wiresyncresponse/
---
## WireSyncResponse class

Antwortklasse für die Synchronisierung von Überweisungen.

```csharp
public class WireSyncResponse : AbstractSyncResponse
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WireSyncResponse](wiresyncresponse)() | Initialisiert eine neue Instanz von[`WireSyncResponse`](../wiresyncresponse) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BankAccountFrom](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/bankaccountfrom) { get; set; } | Ermittelt oder setzt die Quelle von[`BankAccount`](../../aspose.finance.ofx/bankaccount) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja, wenn das Token in der Synchronisierungsanforderung älter ist als der früheste Eintrag in der Verlaufstabelle des Servers. In diesem Fall sind einige Antworten verloren gegangen. Nein, wenn das Token in der Synchronisierungsanforderung neuer ist als oder mit einem Token auf dem Server übereinstimmt Verlaufstabelle. |
| [OfxExtension](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/ofxextension) { get; set; } | Ruft ab oder setzt die[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Ruft das neue Synchronisierungstoken ab oder legt es fest. |
| [WireTransactionResponses](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/wiretransactionresponses) { get; set; } | Ruft die Sammlung von ab oder legt sie fest[`WireTransactionResponse`](../wiretransactionresponse) . |

### Siehe auch

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namensraum [Aspose.Finance.Ofx.WireTransfer](../../aspose.finance.ofx.wiretransfer)
* Montage [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->