---
title: RecurringInterSyncResponse
second_title: Справочник по API Aspose.Finance для .NET
description: Класс ответов для синхронизации повторяющихся межбанковских транзакций.
type: docs
weight: 2560
url: /ru/net/aspose.finance.ofx.intertransfer/recurringintersyncresponse/
---
## RecurringInterSyncResponse class

Класс ответов для синхронизации повторяющихся межбанковских транзакций.

```csharp
public class RecurringInterSyncResponse : AbstractSyncResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RecurringInterSyncResponse](recurringintersyncresponse)() | Инициализирует новый экземпляр класса[`RecurringInterSyncResponse`](../recurringintersyncresponse). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/accountfrom) { get; set; } | Получает или задает из[`BankAccount`](../../aspose.finance.ofx/bankaccount)или[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount)или[`LoanAccount`](../../aspose.finance.ofx/loanaccount). |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Да, если токен в запросе на синхронизацию старше, чем самая ранняя запись в таблице истории сервера. В этом случае некоторые ответы были потеряны. Нет, если токен в запросе на синхронизацию новее или совпадает с токеном в таблице истории сервера. |
| [OfxExtension](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/ofxextension) { get; set; } | Получает или задает[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype). |
| [RecurringInterTransactionResponses](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/recurringintertransactionresponses) { get; set; } | Получает или задает коллекцию[`RecurringInterTransactionResponse`](../recurringintertransactionresponse). |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Получает или задает новый маркер синхронизации. |

### Смотрите также

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* пространство имен [Aspose.Finance.Ofx.InterTransfer](../../aspose.finance.ofx.intertransfer)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
