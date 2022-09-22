---
title: BillPaymentStatusCodeEnum
second_title: Aspose.Finance för .NET API-referens
description: Fakturans betalningsstatuskod enum.
type: docs
weight: 1440
url: /sv/net/aspose.finance.ofx.billerdelivery/billpaymentstatuscodeenum/
---
## BillPaymentStatusCodeEnum enumeration

Fakturans betalningsstatuskod enum.

```csharp
public enum BillPaymentStatusCodeEnum
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| PAIDOUTOFBAND | `0` | En betalning har initierats för denna faktura via en mekanism som inte rapporterar status via OFX. Denna status är avsedd att indikera att kunden har betalat fakturautställaren direkt med kontanter eller en check eller har initierat en elektronisk betalning genom en mekanism som inte rapporterar betalningsstatus via OFX. |
| AUTOPAY | `1` | Bokföraren eller tjänsteleverantören kommer att initiera betalningen baserat på en förauktorisation av kunden, vanligtvis en instruktion "good until cancelled" utan något definierat slutdatum. I USA implementeras detta ofta med en återkommande förauktoriserad ACH-debitering, även om vissa bilare erbjuder förauktoriserad automatisk betalning via kreditkort. Exempel inkluderar månatliga avdrag för att täcka ett bolån, regelbundna betalningar från ett checkkonto till ett kreditkort och den automatiska Payment Service (APS) som erbjuds av många verktyg. Som INGEN kan detta vara den initiala betalningsstatusen för räkningen. |
| CANCELLED | `2` | Kunden avbröt betalningen som tidigare var planerad. |
| UNPAYABLE | `3` | Inget av de betalningsinstrument som är tillåtna för denna räkning stöds av betalningsleverantören. Detta är avsett att användas där -sedeln begränsar betalningen till en delmängd av de betalningsinstrument som är tillåtna i posten i Billerkatalogen. Detta kan inträffa om betalningsleverantören eller Biller ändrade sina betalningsinstrumenttyper som stöds efter registrering och kontoaktivering. |
| NONE | `4` | Det finns varken en betalning planerad eller har gjorts mot denna faktura. Detta kan vara den initiala betalningsstatusen för en faktura. |
| SCHEDULED | `5` | En betalning har schemalagts, men ännu inte behandlad mot denna faktura. |
| PROCESSED | `6` | Betalningen har behandlats mot denna faktura och kan inte längre annulleras. |
| POSTED | `7` | Faktureraren har bokfört betalningen mot denna faktura. |

### Se även

* namnutrymme [Aspose.Finance.Ofx.BillerDelivery](../../aspose.finance.ofx.billerdelivery)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->