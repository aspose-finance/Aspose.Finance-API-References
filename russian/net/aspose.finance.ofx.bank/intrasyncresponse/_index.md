---
title: IntraSyncResponse
second_title: Справочник по API Aspose.Finance для .NET
description: Класс ответа синхронизации внутрибанковских транзакций.
type: docs
weight: 500
url: /ru/net/aspose.finance.ofx.bank/intrasyncresponse/
---
## IntraSyncResponse class

Класс ответа синхронизации внутрибанковских транзакций.

```csharp
public class IntraSyncResponse : AbstractSyncResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [IntraSyncResponse](intrasyncresponse)() | Инициализирует новый экземпляр класса[`IntraSyncResponse`](../intrasyncresponse). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.bank/intrasyncresponse/accountfrom) { get; set; } | Получает или задает из[`BankAccount`](../../aspose.finance.ofx/bankaccount)или[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount)или[`LoanAccount`](../../aspose.finance.ofx/loanaccount). |
| [IntraTransactionResponses](../../aspose.finance.ofx.bank/intrasyncresponse/intratransactionresponses) { get; set; } | Получает или задает коллекцию[`IntraTransactionResponse`](../intratransactionresponse). |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Да, если токен в запросе на синхронизацию старше, чем самая ранняя запись в таблице истории сервера. В этом случае некоторые ответы были потеряны. Нет, если токен в запросе на синхронизацию новее или совпадает с токеном в таблице истории сервера. |
| [OfxExtension](../../aspose.finance.ofx.bank/intrasyncresponse/ofxextension) { get; set; } | Получает или задает[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype). |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Получает или задает новый маркер синхронизации. |

### Смотрите также

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* пространство имен [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
