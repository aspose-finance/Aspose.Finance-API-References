---
title: AbstractSyncResponse
second_title: Aspose.Finance per .NET API Reference
description: Classe base astratta delle classi relative alla risposta di sincronizzazione
type: docs
weight: 110
url: /it/net/aspose.finance.ofx/abstractsyncresponse/
---
## AbstractSyncResponse class

Classe base astratta delle classi relative alla risposta di sincronizzazione

```csharp
public class AbstractSyncResponse : AbstractResponse
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Sì se il token nella richiesta di sincronizzazione è più vecchio della prima voce nella tabella della cronologia del server. In questo caso, alcune risposte sono andate perse. No se il token nella richiesta di sincronizzazione è più recente o corrisponde a un token nel server tabella della cronologia. |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Ottiene o imposta il nuovo token di sincronizzazione. |

### Guarda anche

* class [AbstractResponse](../abstractresponse)
* spazio dei nomi [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* assemblea [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->