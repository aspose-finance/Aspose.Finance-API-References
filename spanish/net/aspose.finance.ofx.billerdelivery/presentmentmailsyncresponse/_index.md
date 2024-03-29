---
title: PresentmentMailSyncResponse
second_title: Referencia de API de Aspose.Finance para .NET
description: Clase de respuesta de sincronización de correo de presentación de factura.
type: docs
weight: 1760
url: /es/net/aspose.finance.ofx.billerdelivery/presentmentmailsyncresponse/
---
## PresentmentMailSyncResponse class

Clase de respuesta de sincronización de correo de presentación de factura.

```csharp
public class PresentmentMailSyncResponse : AbstractSyncResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentmentMailSyncResponse](presentmentmailsyncresponse)() | Inicializa una nueva instancia de[`PresentmentMailSyncResponse`](../presentmentmailsyncresponse) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Sí, si el token en la solicitud de sincronización es anterior a la entrada más antigua en la tabla de historial del servidor. En este caso, se han perdido algunas respuestas. No, si el token en la solicitud de sincronización es más reciente o coincide con un token en el servidor tabla de historial. |
| [OfxExtension](../../aspose.finance.ofx.billerdelivery/presentmentmailsyncresponse/ofxextension) { get; set; } | Obtiene o establece el[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [PresentmentAccountFrom](../../aspose.finance.ofx.billerdelivery/presentmentmailsyncresponse/presentmentaccountfrom) { get; set; } | Obtiene o establece el origen de[`PresentmentAccount`](../../aspose.finance.ofx/presentmentaccount) . |
| [PresentmentMailTransactionResponses](../../aspose.finance.ofx.billerdelivery/presentmentmailsyncresponse/presentmentmailtransactionresponses) { get; set; } | Obtiene o establece la colección de[`PresentmentMailTransactionResponse`](../presentmentmailtransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Obtiene o establece el nuevo token de sincronización. |

### Ver también

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* espacio de nombres [Aspose.Finance.Ofx.BillerDelivery](../../aspose.finance.ofx.billerdelivery)
* asamblea [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
