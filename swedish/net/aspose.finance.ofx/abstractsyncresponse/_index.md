---
title: AbstractSyncResponse
second_title: Aspose.Finance för .NET API-referens
description: Abstrakt basklass för synkroniseringssvarsrelaterade klasser
type: docs
weight: 110
url: /sv/net/aspose.finance.ofx/abstractsyncresponse/
---
## AbstractSyncResponse class

Abstrakt basklass för synkroniseringssvarsrelaterade klasser

```csharp
public class AbstractSyncResponse : AbstractResponse
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Ja om token i synkroniseringsbegäran är äldre än den tidigaste posten i serverns historiktabell. I det här fallet har några svar gått förlorade. Nej om token i synkroniseringsbegäran är nyare än eller matchar en token i serverns historiktabell. |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Hämtar eller ställer in den nya synkroniseringstoken. |

### Se även

* class [AbstractResponse](../abstractresponse)
* namnutrymme [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->