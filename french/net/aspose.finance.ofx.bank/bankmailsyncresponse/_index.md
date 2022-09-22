---
title: BankMailSyncResponse
second_title: Référence de l'API Aspose.Finance pour .NET
description: Classe de réponse de synchronisation de la messagerie bancaire.
type: docs
weight: 340
url: /fr/net/aspose.finance.ofx.bank/bankmailsyncresponse/
---
## BankMailSyncResponse class

Classe de réponse de synchronisation de la messagerie bancaire.

```csharp
public class BankMailSyncResponse : AbstractSyncResponse
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BankMailSyncResponse](bankmailsyncresponse)() | Initialise une nouvelle instance de[`BankMailSyncResponse`](../bankmailsyncresponse) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.bank/bankmailsyncresponse/accountfrom) { get; set; } | Obtient ou définit le de[`BankAccount`](../../aspose.finance.ofx/bankaccount) ou[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount) . |
| [BankMailTransactionResponses](../../aspose.finance.ofx.bank/bankmailsyncresponse/bankmailtransactionresponses) { get; set; } | Obtient ou définit la collection de[`BankMailTransactionResponse`](../bankmailtransactionresponse) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Oui si le jeton de la demande de synchronisation est plus ancien que la première entrée de la table d'historique du serveur. Dans ce cas, certaines réponses ont été perdues. Non si le jeton de la demande de synchronisation est plus récent que ou correspond à un jeton de la table d'historique du serveur. table d'historique. |
| [OfxExtension](../../aspose.finance.ofx.bank/bankmailsyncresponse/ofxextension) { get; set; } | Obtient ou définit le[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Obtient ou définit le nouveau jeton de synchronisation. |

### Voir également

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* espace de noms [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* Assemblée [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->