---
title: RecurringInterSyncResponse
second_title: Referencia de API de Aspose.Finance para .NET
description: Clase de respuesta de sincronización de transacción interbancaria recurrente.
type: docs
weight: 2560
url: /es/net/aspose.finance.ofx.intertransfer/recurringintersyncresponse/
---
## RecurringInterSyncResponse class

Clase de respuesta de sincronización de transacción interbancaria recurrente.

```csharp
public class RecurringInterSyncResponse : AbstractSyncResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RecurringInterSyncResponse](recurringintersyncresponse)() | Inicializa una nueva instancia de[`RecurringInterSyncResponse`](../recurringintersyncresponse) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/accountfrom) { get; set; } | Obtiene o establece el origen de[`BankAccount`](../../aspose.finance.ofx/bankaccount) o[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) o[`LoanAccount`](../../aspose.finance.ofx/loanaccount) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Sí, si el token en la solicitud de sincronización es anterior a la entrada más antigua en la tabla de historial del servidor. En este caso, se han perdido algunas respuestas. No, si el token en la solicitud de sincronización es más reciente o coincide con un token en el servidor tabla de historial. |
| [OfxExtension](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/ofxextension) { get; set; } | Obtiene o establece el[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [RecurringInterTransactionResponses](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/recurringintertransactionresponses) { get; set; } | Obtiene o establece la colección de[`RecurringInterTransactionResponse`](../recurringintertransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Obtiene o establece el nuevo token de sincronización. |

### Ver también

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* espacio de nombres [Aspose.Finance.Ofx.InterTransfer](../../aspose.finance.ofx.intertransfer)
* asamblea [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->