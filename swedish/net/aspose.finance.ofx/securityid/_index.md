---
title: SecurityId
second_title: Aspose.Finance för .NET API-referens
description: Värdepapper måste identifieras konsekvent för att tillåta klientapplikationer att förbereda korrekta investerings rapporter över alla användarinvesteringskonton även vid flera FIer. För närvarande är varken ett värdepappersnamn eller dess symbol standardiserat. Därför använder OFX CUSIPnummer en unik 9 digit alphanumeric identifier för att identifiera värdepapper. CUSIPnummer är tillgängliga för de allra flesta värdepapper som handlas idag inklusive de utan symboler som obligationer. För ett värdepapper som inte har en CUSIP måste ett finansinstitut följa standardproceduren för att tilldela en CUSIP genom att använda sig själv som utfärdare för att undvika konflikt med någon annan CUSIP.
type: docs
weight: 5200
url: /sv/net/aspose.finance.ofx/securityid/
---
## SecurityId class

Värdepapper måste identifieras konsekvent för att tillåta klientapplikationer att förbereda korrekta investerings rapporter över alla användarinvesteringskonton, även vid flera FI:er. För närvarande är varken ett värdepappersnamn eller dess symbol standardiserat. Därför använder OFX CUSIP-nummer (en unik 9) -digit alphanumeric identifier) för att identifiera värdepapper. CUSIP-nummer är tillgängliga för de allra flesta värdepapper som handlas idag, inklusive de utan symboler som obligationer. För ett värdepapper som inte har en CUSIP måste ett finansinstitut följa standardproceduren för att tilldela en CUSIP genom att använda sig själv som utfärdare för att undvika konflikt med någon annan CUSIP.

```csharp
public class SecurityId
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SecurityId](securityid)() | Initierar en ny instans av[`SecurityId`](../securityid) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [UniqueId](../../aspose.finance.ofx/securityid/uniqueid) { get; set; } | Hämtar eller ställer in den unika identifieraren för säkerheten. CUSIP för US FIs. |
| [UniqueIdType](../../aspose.finance.ofx/securityid/uniqueidtype) { get; set; } | Hämtar eller ställer in namnet på standarden som används för att identifiera säkerheten, dvs. "CUSIP" för FIs i USA. |

### Se även

* namnutrymme [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
