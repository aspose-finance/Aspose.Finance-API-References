---
title: IntraSyncResponse
second_title: Referencia de API de Aspose.Finance para .NET
description: Clase de respuesta de sincronización de transacciones intrabancarias.
type: docs
weight: 500
url: /es/net/aspose.finance.ofx.bank/intrasyncresponse/
---
## IntraSyncResponse class

Clase de respuesta de sincronización de transacciones intrabancarias.

```csharp
public class IntraSyncResponse : AbstractSyncResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [IntraSyncResponse](intrasyncresponse)() | Inicializa una nueva instancia de[`IntraSyncResponse`](../intrasyncresponse) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.bank/intrasyncresponse/accountfrom) { get; set; } | Obtiene o establece el origen de[`BankAccount`](../../aspose.finance.ofx/bankaccount) o[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) o[`LoanAccount`](../../aspose.finance.ofx/loanaccount) . |
| [IntraTransactionResponses](../../aspose.finance.ofx.bank/intrasyncresponse/intratransactionresponses) { get; set; } | Obtiene o establece la colección de[`IntraTransactionResponse`](../intratransactionresponse) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Sí, si el token en la solicitud de sincronización es anterior a la entrada más antigua en la tabla de historial del servidor. En este caso, se han perdido algunas respuestas. No, si el token en la solicitud de sincronización es más reciente o coincide con un token en el servidor tabla de historial. |
| [OfxExtension](../../aspose.finance.ofx.bank/intrasyncresponse/ofxextension) { get; set; } | Obtiene o establece el[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Obtiene o establece el nuevo token de sincronización. |

### Ver también

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* espacio de nombres [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* asamblea [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->