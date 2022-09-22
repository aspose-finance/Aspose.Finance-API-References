---
title: ChangeUserInfoSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Ändra svarsklass för synkronisering av användarinformation.
type: docs
weight: 5570
url: /sv/net/aspose.finance.ofx.signup/changeuserinfosyncresponse/
---
## ChangeUserInfoSyncResponse class

Ändra svarsklass för synkronisering av användarinformation.

```csharp
public class ChangeUserInfoSyncResponse : AbstractSyncResponse
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ChangeUserInfoSyncResponse](changeuserinfosyncresponse)() | Initierar en ny instans av[`ChangeUserInfoSyncResponse`](../changeuserinfosyncresponse) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ChangeUserInfoTransactionResponses](../../aspose.finance.ofx.signup/changeuserinfosyncresponse/changeuserinfotransactionresponses) { get; set; } | Hämtar eller ställer in samlingen av[`ChangeUserInfoTransactionResponse`](../changeuserinfotransactionresponse) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [OfxExtension](../../aspose.finance.ofx.signup/changeuserinfosyncresponse/ofxextension) { get; set; } | Hämtar eller ställer in[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namnutrymme [Aspose.Finance.Ofx.Signup](../../aspose.finance.ofx.signup)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->