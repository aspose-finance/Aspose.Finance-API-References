---
title: BillStatusCodeEnum
second_title: Aspose.Finance für .NET-API-Referenz
description: Rechnungsstatuscode enum.
type: docs
weight: 1470
url: /de/net/aspose.finance.ofx.billerdelivery/billstatuscodeenum/
---
## BillStatusCodeEnum enumeration

Rechnungsstatuscode enum.

```csharp
public enum BillStatusCodeEnum
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| WITHDRAWN | `0` | Der Rechnungssteller oder Publisher möchte nicht mehr, dass diese Rechnung angezeigt wird. |
| UNDELIVERABLE | `1` | Versuche, diese Rechnung dem Verbraucher rechtzeitig zuzustellen, sind gescheitert. Dieser Status wird im Allgemeinen nicht verwendet, wenn einem Verbraucher eine Rechnung vorgelegt wird. Benachrichtigungen, die diesen Status verwenden, decken jedoch viele nützliche Fälle ab. |
| NEW | `2` | Der Server hat die Rechnung weder an den Client noch an den Client-Proxy gesendet. Dies ist der anfängliche Statuscode einer Rechnung. |
| DELIVERED | `3` | Der Server hat die Rechnung entweder an einen Client oder Client-Proxy gesendet. |
| VIEWED | `4` | Der Kunde hat die Rechnung gesehen. Bedeutet den vorherigen Status GELIEFERT. |
| RETIRED | `5` | Der Kunde möchte diese Rechnung nicht mehr sehen. Bedeutet den vorherigen Status GELIEFERT. |

### Siehe auch

* namensraum [Aspose.Finance.Ofx.BillerDelivery](../../aspose.finance.ofx.billerdelivery)
* Montage [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->