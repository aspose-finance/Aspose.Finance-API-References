---
title: BillStatusCodeEnum
second_title: Aspose.Finance per .NET API Reference
description: Codice stato fattura enum.
type: docs
weight: 1470
url: /it/net/aspose.finance.ofx.billerdelivery/billstatuscodeenum/
---
## BillStatusCodeEnum enumeration

Codice stato fattura enum.

```csharp
public enum BillStatusCodeEnum
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| WITHDRAWN | `0` | L'emittente di fatture o l'editore non desidera più che questa fattura venga visualizzata. |
| UNDELIVERABLE | `1` | I tentativi di consegnare questa fattura al consumatore in modo tempestivo sono falliti. Questo stato non viene generalmente utilizzato quando si presenta una fattura a un consumatore. Tuttavia, le notifiche che utilizzano questo stato coprono molti casi utili. |
| NEW | `2` | Il server non ha inviato la fattura né al client né al proxy client. Questo è il codice di stato iniziale di una fattura. |
| DELIVERED | `3` | Il server ha inviato la fattura a un client oa un proxy client. |
| VIEWED | `4` | Il cliente ha visto la fattura. Implica lo stato precedente di DELIVERED. |
| RETIRED | `5` | Il cliente non desidera più vedere questa fattura. Implica lo stato precedente di DELIVERED. |

### Guarda anche

* spazio dei nomi [Aspose.Finance.Ofx.BillerDelivery](../../aspose.finance.ofx.billerdelivery)
* assemblea [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
