---
title: StopCheckSyncResponse
second_title: Справочник по API Aspose.Finance для .NET
description: Остановить проверку класса ответа синхронизации.
type: docs
weight: 750
url: /ru/net/aspose.finance.ofx.bank/stopchecksyncresponse/
---
## StopCheckSyncResponse class

Остановить проверку класса ответа синхронизации.

```csharp
public class StopCheckSyncResponse : AbstractSyncResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StopCheckSyncResponse](stopchecksyncresponse)() | Инициализирует новый экземпляр[`StopCheckSyncResponse`](../stopchecksyncresponse) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BankAccountFrom](../../aspose.finance.ofx.bank/stopchecksyncresponse/bankaccountfrom) { get; set; } | Получает или задает из[`BankAccount`](../../aspose.finance.ofx/bankaccount) . |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Да, если токен в запросе на синхронизацию старше самой ранней записи в таблице истории сервера. В этом случае некоторые ответы были потеряны. Нет, если токен в запросе на синхронизацию новее или совпадает с токеном в таблице сервера. таблица истории. |
| [OfxExtension](../../aspose.finance.ofx.bank/stopchecksyncresponse/ofxextension) { get; set; } | Получает или задает[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [StopCheckTransactionResponses](../../aspose.finance.ofx.bank/stopchecksyncresponse/stopchecktransactionresponses) { get; set; } | Получает или задает коллекцию[`StopCheckTransactionResponse`](../stopchecktransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Получает или задает новый маркер синхронизации. |

### Смотрите также

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* пространство имен [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
